<template>
  <div class="ratings">
    <div class="rating-content">
      <div class="overview">
        <div class="overview-left"></div>
        <div class="overview-right"></div>
      </div>
    </div>
  </div>
</template>

<script type="text/ecmascript-6">
  export default {

  };
</script>

<style lang="stylus" rel="stylesheet/stylus">
  .ratings
    position: absolute
    top: 174px
    bottom: 0
    width: 100%
    left: 0
    overflow: hidden
    .overview
      display: flex
      padding: 18px 0
      .overview-left
        flex: 0 0 137px
        width: 137px
      .overview-right
        flex: 1
</style>
