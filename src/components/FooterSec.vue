<template>
    <div class="footer">
        <div class="the_section">
            <div class="navs">
                <ul class="links">
                    <li>Series</li>
                    <li>Movie</li>
                    <li>Show</li>
                    <li>Cartoons</li>
                </ul>
            </div>

            <div class="navss">
                <ul class="links">
                    <li>Agreements</li>
                    <li>Advertisments</li>
                    <li>Reference</li>
                    <li>Blog</li>
                    <li>Offer</li>
                    <li>Support</li>
                </ul>
            </div>

            <div class="Stores">
                <div class="app_store">
                    <img src="../assets/recruit-microsoft-store-android-app-hire-app-store-google-play-app-google-button-apple-thumbnail.png" alt="">
                </div>

                <div class="play_store">
                    <img src="../assets/download-on-app-store-png-with-without-wifi-or-data-2000_0.png" alt="">
                </div>
                    
            </div>

        </div>
        <div class="footer_links">
            <div class="outside">
                <span>2023-2024, Movie 18+</span>
            </div>
            <div class="outsid">
                <i class="fa fa-twitter"></i>
                <i class="fa fa-facebook"></i>
                <i class="fa fa-instagram"></i>
                <i class="fa fa-telegram"></i>
            </div>
            <div class="outside">
                <span>Movie.All rights reserved </span>
            </div>
        </div>
    </div>
</template>

<style>
.footer{
    width: 100%;
    display: flex;
    align-items: center;
    flex-direction: column;
    justify-content: space-between;
    padding-top: 4rem;
    background-color: #000;
}

.footer .links{
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 1.5rem;
    padding: 10px 0;
}
.navss li{
    opacity: 0.7;
    font-size: 15px;
}

.Stores{
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 1.2rem;
    margin: 1.5rem 0;
}

.Stores img{
    width: 120px;
    background-color: gray;
    border-radius: 5px;
}

.footer_links{
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 20rem;
    margin: 1.5rem 0;
}

.footer_links span{
    color: #fff;
    opacity: 0.7;
    font-family: Arial, Helvetica, sans-serif;
    font-size: 14px;
}
.footer_links i{
    color: #fff;
    padding: 0 7px;
    cursor: pointer;
}
</style>