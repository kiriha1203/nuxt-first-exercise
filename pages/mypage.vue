<template>
  <div class="container">
    <p>{{ message }} </p>
    <hr>
    <router-link to="/">Top Page</router-link>
  </div>
</template>

<script>
export default {
  data: function(){
    return{
      message: 'My Page'
    }
  }
}
</script>