<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld'
}
</script>
<script setup>
defineProps({
  msg: String
})

</script>

<style scoped lang="less">

</style>
