<template>
  <div class="container">
    <p>{{ message }}</p>
    <hr>
    <router-link to="/mypage">My Page</router-link>
  </div>
</template>

<script>
export default {
  data: function(){
    return{
      message: 'Top Page'
    }
  }
}
</script>

<style>
</style>
