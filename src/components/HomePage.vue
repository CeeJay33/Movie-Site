<template>
   <NavBar />
   <CurrentPage />
   <div>
    
   </div>
</template>

<script>

import NavBar from './NavBar.vue';
import CurrentPage from './CurrentPage.vue';
export default {
    name: "HomePage",
    components: 
    { NavBar, CurrentPage },
};
</script>

<style>
body{
   background-color: #18181b; 
}

</style>
