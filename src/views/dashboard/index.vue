<template>
  <div class="dashboard-container">
    <div class="dashboard-text">{{ title }}</div>
  </div>
</template>

<script>
export default {
  name: 'Dashboard',
  data() {
    return {
      title: '首页展示统计区域~正在开发中……'
    }
  }
}
</script>

<style lang="scss" scoped>
.dashboard {
  &-container {
    margin: 30px;
  }
  &-text {
    font-size: 30px;
    line-height: 46px;
  }
}
</style>
