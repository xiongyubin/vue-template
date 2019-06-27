<template>
  <div>
    <slot :qqq="testList"></slot>
  </div>
</template>

<script>
export default {
  data () {
    return {
      testList: ['q', 'w', 'e']
    }
  }
}
</script>

<style>

</style>
