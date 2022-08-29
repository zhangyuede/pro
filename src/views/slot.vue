/*
 * @Author: zhangyue
 * @Date: 2022-08-29 15:06:42
 * @Last Modified by: zhangyue
 * @Last Modified time: 2022-08-29 15:39:57
 */
<template>
  <div>
    <slot name="header"></slot>
    <slot name="default"></slot>
    <slot name="footer"></slot>
  </div>
</template>

<script>
export default {
  data () {
    return {
    }
  },
  components () {
  },
  created () {
  },
  mountend () {
  },
  methods: {
  },
  watch: {
  }
}
</script>

<style  scoped>

</style>
