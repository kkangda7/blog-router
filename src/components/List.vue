<template>
  <div>
    <h5 @click="$router.push('/detail/0')">{{ 블로그글[0].title }}</h5>
    <p>{{ 블로그글[0].date }}</p>
  </div>
  <div>
    <router-link to="/detail/1">{{ 블로그글[1].title }}</router-link>
    <p>{{ 블로그글[1].date }}</p>
  </div>
  <div>
    <router-link to="/detail/2">{{ 블로그글[2].title }}</router-link>
    <p>{{ 블로그글[2].date }}</p>
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