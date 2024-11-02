<template>
  <pv-floatlabel variant="on">
    <pv-inputnumber
        v-model="value3"
        inputId="on_label"
        mode="currency"
        currency="USD"
        locale="en-US"
        class="w-15rem lg:w-25rem"
        inputStyle="background-color: #ffffff; color: #333333; padding: 1rem;"
    />
    <label for="on_label">Ingrese el Precio</label>
  </pv-floatlabel>  <br/> <br/>

  <pv-floatlabel variant="on">
    <pv-inputtext
        id="on_label"
        v-model="value2"
        class="w-15rem lg:w-25rem p-3 pv-text"
    />
    <label for="on_label">On Label</label>
  </pv-floatlabel>
</template>

<script setup>
import { ref } from "vue";
const value3 = ref(null);
const value2 = ref(null);
</script>

<style scoped>
.pv-text {
  background-color: #ffffff;
  color: #333333;
}
</style>
