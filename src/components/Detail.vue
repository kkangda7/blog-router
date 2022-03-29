<template>
  <div>
    <h5>{{ 블로그글[$route.params.id].number }} </h5>
    <h5>{{ 블로그글[$route.params.id].title }} </h5>
    <h5>{{ 블로그글[$route.params.id].content }} </h5>
    <h5>{{ 블로그글[$route.params.id].data }} </h5>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  props: {
    블로그글: Array,
  }
}
</script>

<style>

</style>