<template>
  <div class="container">
    <div>
      <logo />
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  },
  data () {
    return {

    }
  },
  mounted () {
    this.$axios.get('https://api2test.haoyishu.org/lesson/v2/live_stream_list/430803?userId=430803&timestamp=1594728124&nonce=3e0gm3r5xu&signature=94f47db8334ff0446473b884baee7d03872347f1').then((res) => {

    })
  }
}
</script>

<style>

</style>
