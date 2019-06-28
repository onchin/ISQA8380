<template>
    <div class="about">
        <h1>This is {{ their_name }}'s To Do list developed in Vue.Js to learn Vue.Js</h1>
        <p>Lorem ipsum dolor sit amet, consectetur......</p>
    </div>
</template>

<script>
export default {
  name: 'Skills',
  data() {
    return {
      their_name: this.$route.params.name
    } 
  }
}
</script>





