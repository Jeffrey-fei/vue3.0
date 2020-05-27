<template>
  <div class="page"></div>
</template>

<script type="text/ecmascript-6">
export default {
name: 'TabBar',
 data() {
 return {

 }
 },
 components: {

 },
beforeRouteEnter (to, from, next) {
if (to.meta.title) {
document.title = to.meta.title
}
next()
},
beforeRouteLeave (to, from, next) {
next()
},
created () {
},
methods: {
}
}
</script>

<style scoped lang="less"></style>
