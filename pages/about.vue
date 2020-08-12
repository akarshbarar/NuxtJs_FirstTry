<template>
  <section class="container">
    <h1> About our nuxt</h1>
    <p class="subheading">About subheading</p>

  </section>
</template>

<script>
export default {
      head(){
    return{
      title:"About",
      meta:[
        {
          name:"description",
          contect:"This is about Page "
        },
          {
          name:"keywords",
          contect:"Test,nuxt, "
        },

      ]
    }
  }
}
</script>

<style>

</style>
