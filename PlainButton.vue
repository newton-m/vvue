<template>
  <Plainbutton 
    :class="[
        'button',
        'button--' + color,
        'button--' + size,
        'button--' + type,
        {
            'button--rounded':rounded
        },
        {
            'button--disabled':disabled
        }
        ]"
    >
    <slot></slot>
  </Plainbutton>
</template>

<script>
export default {
  name: 'PlainButton',
  props: {
      color: {
          type : String,
          default: "default",
          validator(x) {
              return ["blue", "green", "default", "gray", "yellow", "red"].indexOf(x) !==-1;
          }
      },
      rounded: {
          type: Boolean,
          default: false
          
      },
      disabled: {
          type: Boolean,
          default: false

      },
      
      size: {
          type: String,
          default: "default",
          validator(x) {
              return ["small", "medium", "default"].indexOf(x) !==-1;
          }
      }

  }
  
}
</script>

<style scoped>
.button {
    display: in-line-block;
    outline: 0;
    border: 1px solid rgba(0, 0, 0, 0.5);
    color: #000000;
    font-weight: 500;
    text-align: center;
    vertical-align: middle;
    border-radius: 10px;
    
}


.button--blue {
    background-color: #409eff
}

.button--default {
    background-color: #ffffff
}
.button--green {
    background-color: #67c23a
}
.button--gray {
    background-color: #909399
}
.button--yellow {
    background-color: #e6a23c
}
.button--red {
    background-color: #f56c6c
}

.button--plainRed {
    background-color: #f56c6c
}
.button--plainBlue{
    background-color: rgba(64, 158, 255, 0.5)
}
.button--small {
    padding: 10px 20px;
    font-size : 12px;
}

.button--medium {
    padding: 15px 25px;
    font-size : 14px;
}

.button--large {
    padding: 20px 30px;
    font-size : 14px;
}

.button--rounded {
    border-radius: 60px;
}

.button--disabled {
}

</style>