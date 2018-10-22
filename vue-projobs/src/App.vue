<template>
  <div id="app">
    <div class="wrap">
      <ProjobsHeader></ProjobsHeader>
      <ProjobsAside></ProjobsAside>
      <ProjobsList></ProjobsList>
      <ProjobsFooter></ProjobsFooter>
    </div>
  </div>
</template>

<script>
import ProjobsHeader from "./components/ProjobsHeader.vue";
import ProjobsAside from "./components/ProjobsAside.vue";
import ProjobsList from "./components/ProjobsList.vue";
import ProjobsFooter from "./components/ProjobsFooter.vue";
export default {
  components: {
    //컴포넌트 태그명 : 컴포넌트 내용
    ProjobsHeader: ProjobsHeader,
    ProjobsAside: ProjobsAside,
    ProjobsList: ProjobsList,
    ProjobsFooter: ProjobsFooter
  }
};
</script>

<style>
ul,
li {
  list-style: none;
}
p,
ul,
li {
  margin: 0;
  padding: 0;
}
body {
  text-align: center;
  background-color: #f6f6f6;
  font-family: "Nanum Gothic", sans-serif;
}

input {
  border-style: groove;
  width: 200px;
}
button {
  border: 1px solid #d1d1d1;
  background: #f8f8f8;
  cursor: pointer;
  padding: 8px 15px;
}
.shadow {
  box-shadow: 5px 10px 10px rgba(0, 0, 0, 0.03);
}

.wrap{
  width:1200px;
  margin:0 auto;
  position:relative;
}
</style>
