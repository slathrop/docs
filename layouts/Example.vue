<template lang="pug">
  router-view
</template>

<script>
  export default {
    props: ['fullPath'],

    serverCacheKey: props => props.fullPath
  }
</script>
