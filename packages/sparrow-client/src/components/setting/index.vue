<template>
  <div class="setting">
    <Toolbox />
  </div>
</template>
<script>
import Toolbox from './Toolbox';

export default {
  name: 'Setting',
  components: {
    Toolbox
  }
}
</script>
<style lang="scss" scoped>
.setting {
  background: #fff;
  box-sizing: border-box;
  height: 100%;
   &__title {
    padding: 5px 0;
    margin: 0 5px;
    border-bottom: 1px solid #409eff;
    color: #409eff;
    font-size: 16px;
  }
  .CodeMirror{
    width: 245px;
    height: 300px;
  }
}
</style>
