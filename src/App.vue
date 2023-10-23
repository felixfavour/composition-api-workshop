<template>
  <div id="app">
    <ShoppingList />
    <ShoppingListComposition />
  </div>
</template>

<script>
import ShoppingList from './components/ShoppingList.vue';
import ShoppingListComposition from './components/ShoppingListComposition.vue';

export default {
  name: 'App',
  components: {
    ShoppingList,
    ShoppingListComposition
}
}
</script>

<style>
</style>
