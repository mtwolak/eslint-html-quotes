<template>
  <div id="app">
    <CustomComponent num="10" />
  </div>
</template>

<script>

import CustomComponent from './components/CustomComponent'

export default {
  name: 'App',
  components: {
    CustomComponent
  }
}
</script>
