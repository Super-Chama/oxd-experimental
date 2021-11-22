<script lang="ts">
import { defineComponent } from "vue";
// Uncomment import and local "components" registration if library is not registered globally.
// import { OxdExperimentalSample } from '@/entry.esm';

export default defineComponent({
  name: "ServeDev",
  // components: {
  //  OxdExperimentalSample,
  // }
});
</script>

<template>
  <div id="app">
    <oxd-alert
      :show="true"
      type="success"
      message="Are you sure you want to continue?"
    >
    </oxd-alert>
    <oxd-icon name="trash" />
    <oxd-icon type="svg" name="admin" />
    <oxd-text tag="h1">Nunito is a well balanced sans serif typeface</oxd-text>
    <oxd-text tag="h2">Nunito is a well balanced sans serif typeface</oxd-text>
    <oxd-text tag="h3">Nunito is a well balanced sans serif typeface</oxd-text>
    <oxd-text tag="h4">Nunito is a well balanced sans serif typeface</oxd-text>
    <oxd-text tag="h5">Nunito is a well balanced sans serif typeface</oxd-text>
    <oxd-text tag="h6">Nunito is a well balanced sans serif typeface</oxd-text>
    <oxd-text>Nunito is a well balanced sans serif typeface</oxd-text>
  </div>
</template>
