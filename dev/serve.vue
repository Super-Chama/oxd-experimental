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
    <oxd-sample />
  </div>
</template>
