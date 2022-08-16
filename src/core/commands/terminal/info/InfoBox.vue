<template>
  <div>关于本站：鱼头浏览器主页</div>

  <div>作者：程序员鱼头</div>
</template>

<script setup lang="ts">
interface InfoBoxProps {
  seconds: string;
}

const props = withDefaults(defineProps<InfoBoxProps>(), {});
</script>

<style scoped></style>
