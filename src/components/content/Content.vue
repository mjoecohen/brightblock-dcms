<template>
<section class="page">
  <div class="columns">
    <div class="column is-one-fifth">
      <side-bar />
    </div>
    <div class="column">
      <router-view></router-view>
    </div>
  </div>
</section>
</template>

<script>
import SideBar from '@/components/SideBar'

export default {
  data: () => ({
  }),
  components: {
    SideBar
  }
}
</script>
