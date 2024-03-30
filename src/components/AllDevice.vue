<template>
    <div class="device">
         <div class="texts">
            <h1>Subscribe and watch TV shows on all devices</h1>
            <p>This app is available for iOS, Andriod, Smart Tv and set-top boxes.</p>
            <button class="btnnn">Try 30 days for free</button>
        </div>
         <div class="imaage">
            <img src="../assets/1000_F_169063774_I8VuotGlqfMFJwCH4kU9sXjdTu2z86rH-removebg-preview.png" alt="">
         </div>
    </div>
</template>


<style>
.texts p{
    font-family: Arial, Helvetica, sans-serif;
    color: #fff;
    padding-top: 1rem;
    margin-left: 4rem;
}
h1{
    font-family: Arial, Helvetica, sans-serif;
    font-weight: 500;
    font-stretch: semi-expanded;
    color: #fff;
    margin-left: 4rem;
}

.device{
    width: 100%;
    height: 390px;
    margin-top: 3.5rem;
    background: rgb(5,155,185);
background: linear-gradient(90deg, rgb(50, 45, 103) 12%, rgb(55, 51, 111) 66%, rgba(164,61,255,1) 100%);  
    display: flex;
    align-items: center;
    justify-content: space-around;
    background-color: linear-gradient(rgba(0, 0, 0, 0.9), rgba(0, 0, 0.9));
}

.btnnn{
    margin-top: 2rem;
    margin-left: 4rem;
    padding: 9px 16px;
    border: none;
    color: #fff;
    border-radius: 10px;
    cursor: pointer;
    background: rgb(5,155,185);
background: linear-gradient(90deg, rgba(122,111,255,1) 12%, rgba(122,111,255,1) 66%, rgba(164,61,255,1) 100%);  
  }  

  @media (max-width:499px){
  body{
    overflow-x: none;
  }
  .device{
    width: 100%;
    padding: 20px 0;
    height: 100%;
    margin-top: 3.5rem;
    display: flex;
    align-items: center;
    justify-content: space-around;
    flex-direction: column;
}
.texts p{
    font-family: Arial, Helvetica, sans-serif;
    color: #fff;
    padding-top: 1rem;
    margin-left: 1rem;
}
h1{
    font-family: Arial, Helvetica, sans-serif;
    font-weight: 500;
    font-stretch: semi-expanded;
    color: #fff;
    margin-left: 1rem;
}
.btnnn{
    margin-top: 2rem;
    margin-left: 1rem;
    padding: 9px 16px;
    cursor: pointer;
  }  
  .imaage img{
    width: 100%;
  }
}
</style>