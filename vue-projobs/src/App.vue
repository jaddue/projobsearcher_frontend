<template>
  <div id="app">
    <ProjobsHeader></ProjobsHeader>
    <ProjobsSelect></ProjobsSelect>
    <ProjobsList></ProjobsList>
    <ProjobsFooter></ProjobsFooter>
  </div>
</template>

<script>
import ProjobsHeader from './components/ProjobsHeader.vue'
import ProjobsSelect from './components/ProjobsSelect.vue'
import ProjobsList from './components/ProjobsList.vue'
import ProjobsFooter from './components/ProjobsFooter.vue'
export default {
  components:{
  //컴포넌트 태그명 : 컴포넌트 내용
  'ProjobsHeader': ProjobsHeader,
  'ProjobsSelect': ProjobsSelect,
  'ProjobsList': ProjobsList,
  'ProjobsFooter': ProjobsFooter,
  }
}
</script>

<style>
ul, li {list-style: none;}
p, ul, li {margin:0; padding:0;}
  body {
    text-align:center;
    background-color:#f6f6f6;
    
  }

  input {
    border-style:groove;
    width:200px;
  }
  button {
    border:1px solid #d1d1d1;
    background:#f8f8f8;
    cursor: pointer;
    font-family: 'Nanum Gothic', sans-serif;
    padding:8px 15px;
  }
  .shadow {
    box-shadow: 5px 10px 10px rgba(0,0,0,0.03);
  }
</style>
