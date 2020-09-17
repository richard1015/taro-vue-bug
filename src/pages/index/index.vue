<template>
  <view class="index">
    <text class="nut-test">{{ msg }}</text>
  </view>
</template>

<script>
import './index.scss'

export default {
  data () {
    return {
      msg: 'Hello world!'
    }
  }
}
</script>

<style lang="scss">
.nut-test{
  margin-top: 30px;
}
</style>
