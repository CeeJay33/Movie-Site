<template>
   <NavBar />
   <CurrentPage />
   <MoviesPage />
   <div>
    
   </div>
</template>

<script>

import NavBar from './NavBar.vue';
import CurrentPage from './CurrentPage.vue';
import MoviesPage from './MoviesPage.vue';
export default {
    name: "HomePage",
    components: 
    { NavBar, CurrentPage, MoviesPage },
};
</script>

<style>
body{
   background-color: #18181b; 
    overflow-x: none;
}

</style>
