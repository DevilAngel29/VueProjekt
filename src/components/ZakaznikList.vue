<template>
  <div class="zakaznik-list">
<div class="data">
    <table class="ui celled table">
<thead>
    <tr>
        <th style="width: 50px; text-align: center;">#</th>
        <th>Jmeno</th>
        <th>Adresa</th>
        <th style="width: 148px;">Action</th>
    </tr>
</thead>
<tbody>
    <NovyZakaznik />
</tbody>
    </table>
</div>
</div>
</template>

<script>
import NovyZakaznik from "./NovyZakaznik";
export default {
    name: "ZakaznikList",
    components: {
        NovyZakaznik
    }
};
</script>

<style scoped>
</style>
