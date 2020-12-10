<template>
  <div id="root">
    <div v-for="(item,index) of list" :key='index'>{{item}}</div>
  </div>
</template>

<script>
export default {
  name: 'List',
  data () {
    return {
      list: ['a', 'b', 'c']
    }
  }
}
</script>

<style scoped>

</style>
