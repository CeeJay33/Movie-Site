<template>
    <div class="section">
     <div class="navigation">
        <div class="nav">
        <div class="nav_section">
        <img src="" alt="">
        </div>
        <div class="nav_section">
        <ul>
            <li>Serials</li>
            <li>Movies</li>
            <li>Show</li>
            <li>Cartoons</li>
        </ul>
        </div>
        </div>
     </div>
     <div class="navigation">
        <div class="nav2">
        <div class="nav2_section">
        <img src="../assets/search-svgrepo-com.svg"  alt="">
        </div>
        <div class="nav2_section">
        <button class="btn">Try 30 days for free</button>
        </div>
        <div class="nav2_section">
        <button class="btnn">Sign In</button>
        </div>
        </div>
</div>

    </div>
</template>
  
  <script>
  export default {
    name: "NavBar"
  }
  </script>
  
  <style>

  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    text-decoration: none;
    list-style: none;
  }
  
  body{
    /* background-color: #18181b; */
  }

  .section{
    display: flex;
    align-items: center;
    justify-content: space-around;
     background-color: #18181b;
     padding: 1rem 0;
  }

.nav{
    display: flex;
    align-items: center;
    justify-content: space-between;
  }

  .nav_section ul{
    display: flex;
    gap: 2rem;
    color: #fff;
  }
  

  .nav2{
    display: flex;
    gap: 1rem;
  }

  .nav2_section .btn{
    padding: 9px 16px;
    border: none;
    color: #fff;
    border-radius: 10px;
    cursor: pointer;
    background: rgb(5,155,185);
background: linear-gradient(90deg, rgba(5,155,185,1) 12%, rgba(122,111,255,1) 66%, rgba(164,61,255,1) 100%);  }
  
.nav2_section .btnn{
    padding: 8px 17px;
    cursor: pointer;
    border-radius: 10px;
    color: #fff;
    background-color: transparent;
    border: 1px solid #fff;
}
  
.nav2_section img{
    width: 30px;
    cursor: pointer;
}
  </style>
                                                                                     