<template>
    <div class="week">
        <h2>Top of the Week</h2>
        <div class="imagee">
            <img src="../assets/Screenshot 2024-03-19 184900.png" alt="">
        </div>
    </div>
</template>



<style>
h2{
    text-align: center;
    margin-top: 2rem;
}
.imagee{
   width: 100%;
   height: 400px;
   display: flex;
   align-items: center;
   justify-content: center;
}
.imagee img{
    width: 80%;
    margin: auto;
}

@media (max-width:499px){
  body{
    overflow-x: none;
  }
  .imagee img{
    width: 100%;
    height: 250px;
    margin: auto;
}
}
</style>