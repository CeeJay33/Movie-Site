<template>
   <NavBar />
   <CurrentPage />
   <MoviesPage />
   <TheWeek/>
   <AllDevice/>
   <FooterSec />
   <div>
    
   </div>
</template>

<script>

import NavBar from './NavBar.vue';
import CurrentPage from './CurrentPage.vue';
import MoviesPage from './MoviesPage.vue';
import TheWeek from './TheWeek.vue';
import AllDevice from './AllDevice.vue';
import FooterSec from './FooterSec.vue';
export default {
    name: "HomePage",
    components: 
    { NavBar, CurrentPage, MoviesPage, TheWeek, AllDevice, FooterSec },
};
</script>

<style>
body{
   background-color: #18181b; 
    overflow-x: none;
}

</style>
