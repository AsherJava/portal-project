<template>
    <div id="main" class="app-main">
        <router-view></router-view>
    </div>
</template>

<script>

export default {
  data() {
    return {};
  },
    created(){
    },
  mounted() {},
  beforeDestroy() {},
  methods: {}
};
</script>

<style>
html,
body {
  width: 100%;
  height: 100%;
  background: #f0f0f0;
  /* overflow: hidden; */
}

.app-main {
  width: 100%;
  height: 100%;
}

.br button {
  margin-right: 5px;
}

.operation button {
  margin-right: 5px;
}

.ivu-btn-text:focus {
  box-shadow: none !important;
}

.ivu-poptip {
  width: 100%;
  display: block !important;
}

.ivu-poptip-rel {
  display: block !important;
}

.ivu-tooltip {
    display: block !important;
}

.ivu-tooltip-rel {
    display: block !important;
}
</style>
