<template>
  <div>
    <div class="tab"><router-link to="/sliddelete">滑动删除组件</router-link></div>
    <div class="tab"><router-link to="/hint">透明提示组件</router-link></div>
    <div class="tab"><router-link to="/loading">加载状态组件</router-link></div>
    <div class="tab"><router-link to="/fixedtitle">表头固定组件</router-link></div>
    <div class="tab"><router-link to="/fixedtitle">页面置顶组件</router-link></div>
    <div class="tab"><router-link to="/arrows">箭头组件</router-link></div>
  </div>
</template>

<script>
export default {
  name: 'el-index',
  data () {
    return {};
  }
};
</script>

<style lang="scss" scoped>
  .tab {
    text-align: center;
    padding: 10px;
    margin: 5px 0;
    background-color: #F2F2F2;
    a {
      color: #7e8c8d;
    }
  }
</style>
