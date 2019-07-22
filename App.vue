<template>
  <center>
  <div>
    <br><br> <hr><hr><br>
    <h1>마음에 드는 버튼 스타일을 골라보세요.</h1>
    <br><hr><hr><br><br><br>
    <hr>
    <h2>이곳은 사각형의 버튼들을 모아놓은 공간입니다.</h2>
    <hr><br>

    <h3>1. 사각형의 큰버튼들입니다.</h3>
    <br><br><br>
    <AppButton :rounded="false" color="default" size="large">Default</AppButton> &nbsp;
    <AppButton :rounded="false" color="blue" size="large">Primary</AppButton> &nbsp;
    <AppButton :rounded="false" color="green" size="large">Success</AppButton> &nbsp;
    <AppButton :rounded="false" color="gray" size="large">Info</AppButton> &nbsp;
    <AppButton :rounded="false" color="yellow" size="large">Warning</AppButton> &nbsp;
    <AppButton :rounded="false" color="red" size="large">Danger</AppButton>
    <br><br><br><br>
    <h3>사각형의 중간버튼들입니다.</h3>
    <br><br><br>
    <AppButton :rounded="false" color="default" size="medium">Default</AppButton> &nbsp;
    <AppButton :rounded="false" color="blue" size="medium">Primary</AppButton> &nbsp;
    <AppButton :rounded="false" color="green" size="medium">Success</AppButton> &nbsp;
    <AppButton :rounded="false" color="gray" size="medium">Info</AppButton> &nbsp;
    <AppButton :rounded="false" color="yellow" size="medium">Warning</AppButton> &nbsp;
    <AppButton :rounded="false" color="red" size="medium">Danger</AppButton>
    <br><br><br><br>
    <h3>사각형의 작은버튼들입니다.</h3>
    <br><br><br>
    <AppButton :rounded="false" color="default" size="small">Default</AppButton> &nbsp;
    <AppButton :rounded="false" color="blue" size="small">Primary</AppButton> &nbsp;
    <AppButton :rounded="false" color="green" size="small">Success</AppButton> &nbsp;
    <AppButton :rounded="false" color="gray" size="small">Info</AppButton> &nbsp;
    <AppButton :rounded="false" color="yellow" size="small">Warning</AppButton> &nbsp;
    <AppButton :rounded="false" color="red" size="small">Danger</AppButton>
    <br><br><br><br>
    <hr>
    <h2>이곳은 둥근모양의 버튼들을 모아놓은 공간입니다.</h2>
    <hr><br>
     <h3>둥근모양의 큰버튼들입니다.</h3>
    <br><br><br>
    <AppButton :rounded="true" color="default" size="large">Default</AppButton> &nbsp;
    <AppButton :rounded="true" color="blue" size="large">Primary</AppButton> &nbsp;
    <AppButton :rounded="true" color="green" size="large">Success</AppButton> &nbsp;
    <AppButton :rounded="true" color="gray" size="large">Info</AppButton> &nbsp;
    <AppButton :rounded="true" color="yellow" size="large">Warning</AppButton> &nbsp;
    <AppButton :rounded="true" color="red" size="large">Danger</AppButton>
    <br><br><br><br>
    <h3>둥근모양의 중간버튼들입니다.</h3>
    <br><br><br>
    <AppButton :rounded="true" color="default" size="medium">Default</AppButton> &nbsp;
    <AppButton :rounded="true" color="blue" size="medium">Primary</AppButton> &nbsp;
    <AppButton :rounded="true" color="green" size="medium">Success</AppButton> &nbsp;
    <AppButton :rounded="true" color="gray" size="medium">Info</AppButton> &nbsp;
    <AppButton :rounded="true" color="yellow" size="medium">Warning</AppButton> &nbsp;
    <AppButton :rounded="true" color="red" size="medium">Danger</AppButton>
    <br><br><br><br>
    <h3>둥근모양의 작은버튼들입니다.</h3>
    <br><br><br>
    <AppButton :rounded="true" color="default" size="small">Default</AppButton> &nbsp;
    <AppButton :rounded="true" color="blue" size="small">Primary</AppButton> &nbsp;
    <AppButton :rounded="true" color="green" size="small">Success</AppButton> &nbsp;
    <AppButton :rounded="true" color="gray" size="small">Info</AppButton> &nbsp;
    <AppButton :rounded="true" color="yellow" size="small">Warning</AppButton> &nbsp;
    <AppButton :rounded="true" color="red" size="small">Danger</AppButton>
    <br><br><br><br>
    <hr>
    <h2>이곳은 플레인 형태의 버튼들을 모아놓은 공간입니다.</h2>
    <hr><br>
    <h3>플레인 형태의 큰버튼들입니다.</h3>
    <br><br><br>
    <AppButton :rounded="false" color="default" size="large">Default</AppButton> &nbsp;
    <AppButton :rounded="false" color="plainBlue" size="large">Primary</AppButton> &nbsp;
    <AppButton :rounded="false" color="plainGreen" size="large">Success</AppButton> &nbsp;
    <AppButton :rounded="false" color="plainGray" size="large">Info</AppButton> &nbsp;
    <AppButton :rounded="false" color="plainYellow" size="large">Warning</AppButton> &nbsp;
    <AppButton :rounded="false" color="plainRed" size="large">Danger</AppButton>
    <br><br><br><br>
    <h3>플레인 형태의 중간버튼들입니다.</h3>
    <br><br><br>
    <AppButton :rounded="false" color="default" size="medium">Default</AppButton> &nbsp;
    <AppButton :rounded="false" color="plainBlue" size="medium">Primary</AppButton> &nbsp;
    <AppButton :rounded="false" color="plainGreen" size="medium">Success</AppButton> &nbsp;
    <AppButton :rounded="false" color="plainGray" size="medium">Info</AppButton> &nbsp;
    <AppButton :rounded="false" color="plainYellow" size="medium">Warning</AppButton> &nbsp;
    <AppButton :rounded="false" color="plainRed" size="medium">Danger</AppButton>
    <br><br><br><br>
    <h3>플레인 형태의 작은버튼들입니다.</h3>
    <br><br><br>
    <AppButton :rounded="false" color="default" size="small">Default</AppButton> &nbsp;
    <AppButton :rounded="false" color="plainBlue" size="small">Primary</AppButton> &nbsp;
    <AppButton :rounded="false" color="plainGreen" size="small">Success</AppButton> &nbsp;
    <AppButton :rounded="false" color="plainGray" size="small">Info</AppButton> &nbsp;
    <AppButton :rounded="false" color="plainYellow" size="small">Warning</AppButton> &nbsp;
    <AppButton :rounded="false" color="plainRed" size="small">Danger</AppButton>
    <br><br><br><br> 
    <h4>여기는 일반 클릭 이벤트 버튼과 disabled 버튼이 공존하는 곳입니다.</h4>
    <br><br><br>
   
  </div>
  <div>
  <button v-on: click="greet">저는 눌리는 버튼입니다.</button> &nbsp; &nbsp;
  <button v-on: click="greet" disabled>저는 눌리지않는 버튼입니다.</button>
  <br><br><hr>
  <hr><br><br><br><br>
  </div>
  </center> 
</template>

<script>

import AppButton from './components/Button.vue'

export default {
  components: {
    AppButton
  },
  name: 'App',
  data () {
    return {
      //
    }
  },

  }


</script> 


<!--
<template>
  <div id="app">
  <button v-on:click="greet">Greet</button>
</div>

</template>

<script>
export default {
  components: {
    button
  },
  
}
new Vue({
  el: '#app',
  data: {
    name: 'Vue.js'
  },
  // 메소드는 `methods` 객체 안에 정의합니다
  methods: {
    greet: function (event) {
      // 메소드 안에서 사용하는 `this` 는 Vue 인스턴스를 가리킵니다
      alert('Hello ' + this.name + '!')
      // `event` 는 네이티브 DOM 이벤트입니다
      if (event) {
        alert(event.target.tagName)
      }
    }
  }
});
</script>

-->