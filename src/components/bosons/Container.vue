<template>
  <div class="container">
    <slot />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'ContainerPage'
})
</script>

<style lang="scss" scoped>
.container {
  width: 85%;
  max-width: 1150px;
  margin: 0 auto;
}
</style>
