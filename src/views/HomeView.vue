<template>
  <div class="home">
    <List></List>
  </div>
</template>

<script>
// @ is an alias to /src
import List from '@/components/List.vue'

export default {
  name: 'HomeView',
  components: {
    List
  }
}
</script>

<style lang="scss" scoped>

</style>
