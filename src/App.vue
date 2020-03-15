<template>
  <div>
    <div id="slogan" class="text-center">
      <h1>
        NameGator
        <span class="fa fa-check"></span>
      </h1>
      <h6 class="text-secondary">Generate names with VueJs, GraphQl and Node</h6>
    </div>
    <div id="main">
      <DomainList></DomainList>
    </div>
  </div>
</template>

<script>
import "bootstrap/dist/css/bootstrap.css";
import "font-awesome/css/font-awesome.css";
import DomainList from "./components/DomainList";

export default {
  name: "App",
  components: {
    DomainList
  }
};
</script>

<style>
#slogan {
  margin-top: 30px;
  margin-bottom: 30px;
}
#main {
  background-color: #f1f1f1;
  margin-top: 30px;
  margin-bottom: 30px;
}
</style>
