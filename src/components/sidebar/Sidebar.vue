<template>
  <div class="vx-sidebar" onselectstart="return false;">
    <slot></slot>
  </div>
</template>

<script>
import { tab } from 'utils/mixins'
export default {
  componentName: 'Sidebar',
  mixins: [tab]
}
</script>
