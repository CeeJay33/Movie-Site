<template>
  <div>
    <HomePage />
  </div>
</template>

<script>
import HomePage from './components/HomePage.vue';


export default {
  name: 'App',
  components: {
    HomePage
},
};
</script>

<style>
h2{
  color: #fff;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 20px;
}

li{
  color: #fff;
  font-family: Arial, Helvetica, sans-serif;
  cursor: pointer;
}
h3{
  color: #fff;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 17px;
}
</style>
