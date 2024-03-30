<template>
    <div class="Subscribe">
        <div class="Sub_container">
            <div  class="sub_cont">
                <div class="price">
                    <span>Free</span>
                    <h3>0.00</h3>
                    <h4></h4>
                </div>
                <div class="content">
                    <div class="icons">

                    </div>
                    <div class="content_des">
                        <p>Free videos</p>
                        <p>Ads</p>
                        <p>No downloads</p>
                        <p>No subtitle</p>
                    </div>
                </div>
            </div>
            <div  class="sub_cont">
                <div class="price">
                    <span>Standard</span>
                    <h3>4,500.00</h3>
                    <h4>Monthly</h4>
</div>
<div class="content">
    <div class="icons">

</div>
<div class="content_des">
    <p>Free videos</p>
    <p>Ads</p>
    <p>No downloads</p>
    <p>No subtitle</p>
</div>
</div>
</div>
<div  class="sub_cont">
    <div class="price">
        <span>Premium</span>
                    <h3>12,600.00</h3>
                    <h4 class="h4">Annualy</h4>
</div>
<div class="content">
    <div class="icons">

</div>
<div class="content_des">
    <p>Free videos</p>
    <p>Ads</p>
    <p>No downloads</p>
    <p>No subtitle</p>
</div>
</div>
</div>
        </div>
    </div>
</template>


<script>
export default{
    name: "SubScribe",
}

</script>


<style>

body{
    background-color: #18181b;
}

.Subscribe{
    width: 100%;
    height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}

.Sub_container {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 1rem;
}

.Sub_container .sub_cont{
background: rgb(5,155,185);
background: linear-gradient(90deg, rgba(5,155,185,1) 12%, rgba(122,111,255,1) 66%, rgba(164,61,255,1) 100%);  
height: 500px;
width: 250px;
border-radius: 20px;
text-align: center;

}

.sub_cont .price span{
    color: #fff;
    font-size: 30px;
}

.sub_cont .price h3{
    color: #fff;
    font-size: 30px;
}
.sub_cont .price h4{
    color: blue;
    font-size: 25px;
}
.sub_cont .price .h4{
    color: rgb(255, 0, 0);
    font-size: 25px;
}

</style>