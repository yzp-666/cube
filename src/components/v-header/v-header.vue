<template>
  <div class="v-header">

  </div>
</template>

<script>
  import SupportIco from 'components/support-ico/support-ico.vue'

  export default {
    name: 'v-header',
    props: {
      seller: {
        tyle: Object,
        default () {
          return {}
        }
      }
    },
    components: {
      SupportIco
    }
  }
</script>

<style lang="stylus" scoped>
  @import "~common/stylus/mixin"
  @import "~common/stylus/variable"

</style>
