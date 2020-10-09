<script>
import Vue from 'vue';
import { MrlibrarySample } from '@/entry';

export default Vue.extend({
  name: 'ServeDev',
  components: {
    MrlibrarySample,
  }
});
</script>

<template>
  <div id="app">
    <mrlibrary-sample />
  </div>
</template>
