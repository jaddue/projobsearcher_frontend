<template>
  <div id="app">
    <ProjobsHeader></ProjobsHeader>
    <ProjobsInput></ProjobsInput>
    <ProjobsFooter></ProjobsFooter>
  </div>
</template>

<script>
import ProjobsHeader from './components/ProjobsHeader.vue'
import ProjobsInput from './components/ProjobsInput.vue'
import ProjobsFooter from './components/ProjobsFooter.vue'
export default {
  components:{
  //컴포넌트 태그명 : 컴포넌트 내용
  'ProjobsHeader': ProjobsHeader,
  'ProjobsInput': ProjobsInput,
  'ProjobsFooter': ProjobsFooter,
  }
}
</script>

<style>
  body {
    text-align:center;
    background-color:#f6f6f6;
  }

  input {
    border-style:groove;
    width:200px;
  }
  button {
    border-style: groove;
  }
  .shadow {
    box-shadow: 5px 10px 10px rgba(0,0,0,0.03);
  }
</style>
