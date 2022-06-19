<template>
  <div id="app">
    <product-list-one></product-list-one>
    <product-list-two></product-list-two>
  </div>
</template>

<script>
import ProductListOneVue from './components/ProductListOne.vue';
import ProductListTwoVue from './components/ProductListTwo.vue';

export default {
  components : {
    'product-list-one' : ProductListOneVue,
    'product-list-two' : ProductListTwoVue
  },
  name: 'app',
  data () {
    return {

    }
  }
}
</script>

<style>

</style>
