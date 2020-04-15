<template>
  <div>{{ num }}</div>
</template>

<script>
export default {
  name: 'CustomComponent',
  props: {
    num: {
      type: Number,
      required: true,
      default: 5
    }
  }
}
</script>
