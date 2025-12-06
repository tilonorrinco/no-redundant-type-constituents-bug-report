<template>
  <div class="some-component">
    {{ text }}
  </div>
</template>

<script setup lang="ts">
interface Props {
  text: string;
};

defineProps<Props>()
</script>
