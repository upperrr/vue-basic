<template>
  <div>
    {{rawHtml}}
  </div>
  <div>
    {{rawHtml2}}
  </div>
  <h1 v-html="rawHtml2"></h1>
</template>

<script>
export default {
  setup () {
    

    return {
      rawHtml: '이것은 텍스트입니다',
      rawHtml2: '<span style="color: red">이것은 발간색 이어야 함</span>',

    }
  },
}
</script>

<style lang="scss" scoped>

</style>