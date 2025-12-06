<template>
  <div class="app">
    
  </div>
</template>

<script setup lang="ts">
import SomeComponent from './SomeComponent.vue';

type SomeComponentType = typeof SomeComponent;
// eslint-disable-next-line @typescript-eslint/no-unused-vars
type ExtendedSomeComponentType = SomeComponentType & { hello: 'world' };
// why @typescript-eslint/no-redundant-type-constituents error here?
</script>

