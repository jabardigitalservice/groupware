<template>
  <ResponsiveComponentLoader
    v-bind="$attrs"
    v-on="$listeners"
    for-desktop="LogbookList/table.vue"
    for-mobile="LogbookList/card-list.vue" />
</template>

<script>
import ResponsiveComponentLoader from '../ResponsiveComponentLoader'
export default {
  components: {
    ResponsiveComponentLoader
  }
}
</script>
