<template>
  <div id="app">
    <product-list-one></product-list-one>
    <product-list-two></product-list-two>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      products: [
        {
          name: 'Banana skin,',
          price: 20
        },
        {
          name: 'Shiny Star,',
          price: 40
        },
        {
          name: 'Green Shells,',
          price: 60
        },
        {
          name: 'Red Shells,',
          price: 80
        }
      ]
    }
  }
}
</script>

<style>

</style>
