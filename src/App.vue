<template>
<div id="app">
  <div class="ui fixed inverted menu vue-color">
<div class="ui container">
  <a href="#" class="header item">Database VUE</a>
</div>
  </div>

<div class="ui main container">
  <MyForm />
  <ZakaznikList />
</div>
</div>
</template>

<script>
import MyForm from "./components/MyForm";
import ZakaznikList from "./components/ZakaznikList";

export default {
  name: 'App',
  components: {
    MyForm,
    ZakaznikList
    }
};
</script>

<style>
.vue-color {
  background: #f44336 !important;
}

.main.container {
  margin-top: 60px;
}

.submit-button {
  margin-top: 24px !important;
  float: right;
}
</style>
