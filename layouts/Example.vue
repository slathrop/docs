<template lang="pug">
  router-view
</template>

<script>
  export default {
    name: 'example-layout',

    props: ['fullPath'],

    serverCacheKey: props => props.fullPath
  }
</script>
