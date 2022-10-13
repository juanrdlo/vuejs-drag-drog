<template>
  <DragDrogComponent accepted="image/jpeg" />
</template>

<script>

import DragDrogComponent from "@/components/DragDrogComponent";

export default {
  name: 'App',
  components: {
    DragDrogComponent
  }
}
</script>

<style lang="sass">
@import 'base.sass'
</style>
