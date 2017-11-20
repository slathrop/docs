<template lang="pug">
  v-app(toolbar footer)
    main
      v-container(fluid).pa-0
        v-slide-x-transition(mode="out-in")
          router-view
</template>

<script>
  export default {
    name: 'home-layout',

    props: ['fullPath'],

    serverCacheKey: props => props.fullPath,
  }
</script>
