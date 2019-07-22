<template>
  <Appbutton 
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
  </Appbutton>
</template>

<script>
export default {
  name: 'AppButton',
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

.plainButton

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

.button--blue {
    background-color:#409eff
}

.button--plainRed {
    background-color: #fedfdf;
    border: 1px solid #ee6363;
    color: #ee6363;
}
.button--plainBlue{
    background-color: #dfdffe;
    border: 1px solid #409eff;
    color: #409eff;
}
.button--plainGreen{
    background-color: #dffedf;
    border: 1px solid #67c23a;
    color: #67c23a;
}
.button--plainGray{
    background-color: #cacaca;
    border: 1px solid #6d6b6b;
    color: #6d6b6b;
}
.button--plainYellow{
    background-color: #fffec5;
    border: 1px solid #e6a23c;
    color: #e6a23c;
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