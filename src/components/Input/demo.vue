<template>
  <div class="demo-box">
    <p>text: {{ text }}</p>
    <a-input
      v-model="text"
      readonly="true"
      placeholder="请输入"/>
  </div>
</template>

<script lang="tsx">
import {defineComponent, ref} from 'vue';
import AInput from './index'

export default defineComponent({
  name: "InputDemo",
  components: { AInput },
  setup(props, { emit }) {
    const text = ref('')
    return {
      text
    }
  }
})
</script>

<style lange="scss">

</style>
