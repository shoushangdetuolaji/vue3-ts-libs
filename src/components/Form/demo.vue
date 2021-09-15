<template>
  <div class="demo-box">
    <a-form-item>
      <template #label>
        <b>customlabel</b>
      </template>
      <a-input placeholder="请输入姓名" />
    </a-form-item>
  </div>
</template>

<script lang="tsx">
import {defineComponent, ref} from 'vue'
export default defineComponent({
  name: "FormDemo",
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
