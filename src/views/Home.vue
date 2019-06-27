<template>
  <div class="home">
    <hello-world>
      <template v-slot="{qqq: a}">
        {{a}}
      </template>
    </hello-world>
  </div>
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  created () {
  },
  components: {
    HelloWorld
  }
}
</script>
