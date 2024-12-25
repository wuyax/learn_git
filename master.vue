<template>
  <div class="master">
    <h1>Master</h1>
    <router-view></router-view>
  </div>
</template>
<script>
// https://cn.vuejs.org/v2/style-guide/#组件-实例的选项的顺序-推荐
export default {
  name: 'master',
  components: {},
  model: {},
  props: {},
  data() {
    return {
      user: 'zhangwuji'
    }
  },
  computed: {},
  watch: {},
  created() {},
  mounted() {},
  beforeDestroy() {},
  methods: {}
}
</script>
<style lang="scss" scoped>
</style>
