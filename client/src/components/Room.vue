<template>
  <g>
    <line stroke="black" stroke-width={1}></line>
    <g><text>{{ name }}</text></g>
<!--    <g transform={`translate(${coords[0].x}, ${coords[0].y})`}></g>-->
  </g>
</template>

<script>
export default {
  name: 'Room',
  props: {
    name: {
      type: String,
      default: 'test'
    }
  }
}
</script>

<style scoped>

</style>
