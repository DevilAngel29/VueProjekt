<template>
  <div class="my-form">
      <form class="ui form">
<div class="fields">
    <div class="four wide field">
<label >Jmeno</label>
<input type="text" name="jmeno" placeholder="Jmeno" />
    </div>

     <div class="four wide field">
<label >Prijmeni</label>
<input type="text" name="prijmeni" placeholder="Prijmeni" />
    </div>

     <div class="six wide field">
<label >Adresa</label>
<input type="adresa" name="adresa" placeholder="Adresa" />
    </div>

    <div class="two wide field">
<button class="ui primary button submit-button">Save</button>
    </div>
</div>
      </form>
  </div>
</template>

<script>
export default {
    name: "MyForm"
};
</script>

<style scoped>
</style>
