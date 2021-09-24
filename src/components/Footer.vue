<template>
    <footer class="bg-footer">
        <div class="container-footer">
            <div class="container-nav-footer">
                <div class="columns">
                    <!-- Dc Comics Nav -->
                    <nav>
                        <h4>Dc Comics</h4>
                        <ul>
                            <li>
                                <a href="#">Characters</a>
                            </li>
                            <li>
                                <a href="#">Comics</a>
                            </li>
                            <li>
                                <a href="#">Movies</a>
                            </li>
                            <li>
                                <a href="#">Tv</a>
                            </li>
                            <li>
                                <a href="#">Games</a>
                            </li>
                            <li>
                                <a href="#">Videos</a>
                            </li>
                            <li>
                                <a href="#">News</a>
                            </li>                
                        </ul>
                    </nav>

                    <!-- Shop Nav -->
                    <nav>
                        <h4>Shop</h4>
                        <ul>
                            <li>
                                <a href="#">Shop Dc</a>
                            </li>
                            <li>
                                <a href="#">Shop Dc Collectibles</a>
                            </li>  
                        </ul>
                    </nav>
                </div>

                <div class="colums">

                    <!-- Dc Nav -->
                    <nav>
                        <h4>Dc</h4>
                        <ul>
                            <li>
                                <a href="#">Term Of Use</a>
                            </li>
                            <li>
                                <a href="#">Privacy policy (New)</a>
                            </li>
                            <li>
                                <a href="#">Ad Choices</a>
                            </li>
                            <li>
                                <a href="#">Advertising</a>
                            </li>
                            <li>
                                <a href="#">Jobs</a>
                            </li>
                            <li>
                                <a href="#">Subscriptions</a>
                            </li>
                            <li>
                                <a href="#">Talent Workshops</a>
                            </li>
                            <li>
                                <a href="#">CPSC Certificates</a>
                            </li>
                            <li>
                                <a href="#">Ratings</a>
                            </li>
                            <li>
                                <a href="#">Shop Help</a>
                            </li>
                            <li>
                                <a href="#">Contact Us</a>
                            </li>
                        </ul>
                    </nav>
                </div>

                <div class="columns">
                    <!-- Sites Nav -->
                    <nav>
                        <h4>Sites</h4>
                        <ul>
                            <li>
                                <a href="#">DC</a>
                            </li>
                            <li>
                                <a href="#">MAD Magazine</a>
                            </li>
                            <li>
                                <a href="#">DC kinds</a>
                            </li>  
                            <li>
                                <a href="#">DC Universe</a>
                            </li>  
                            <li>
                                <a href="#">DC Power Visa</a>
                            </li>
                        </ul>
                    </nav>
                </div>
            </div>
        </div>
    </footer>    
</template>

<script>
export default {

}
</script>

<style  lang="scss" scoped>
@import '../style/general.scss';

.bg-footer{
    background-image: url('../assets/img/footer-bg.jpg');
    height: 450px;
}

.container-footer{
    width: $generalWidth;
    margin: $generalMargin;
    background-image: url('../assets/img/dc-logo-bg.png');
    background-repeat: no-repeat;
    background-position: right;
    height: 100%;
    font-family: 'Roboto Condensed', sans-serif;
}

.container-nav-footer{
    padding: 40px 0;
    width: 45%;
    display: flex;
    justify-content: space-between;
}

nav{
    padding-bottom: 20px;
    h4{
        color: $whiteColor;
        text-transform: uppercase;
        padding-bottom: 15px;
        font-size: 1.5rem;
    }

    ul{
      
      li{
            list-style: none;
            padding-bottom: 5px;

          a{
                text-decoration: none;
                color: grey;
                font-family: sans-serif;

                &:hover{
                    text-decoration: underline;
                }
            }
        }
    }
}

</style>