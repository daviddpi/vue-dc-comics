<template>
    <div>
        <header class="bg-header">
            <div class="conteiner-header">
                <img src="../assets/img/dc-logo.png" alt="Logo DC">
                <nav>
                    <ul>
                        <li>
                            <a href="#">Characters</a>
                        </li>

                        <li>
                            <a href="#" class="active">Comics</a>
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
                            <a href="#">Collectibles</a>
                        </li>

                        <li>
                            <a href="#">Videos</a>
                        </li>

                        <li>
                            <a href="#">Fans</a>
                        </li>

                        <li>
                            <a href="#">News</a>
                        </li>

                        <li>
                            <a href="#">Shop</a>
                        </li>
                    </ul>
                </nav>
            </div>
        </header>
    </div>
</template>

<script>
export default {
    
}
</script>

<style  lang="scss" scoped>
@import '../style/general.scss';

.bg-header{
    width: 100%;
    background-color: $whiteColor;
}

.conteiner-header{
    width: $generalWidth;
    margin: $generalMargin;
    padding-top: 30px;
    height: 100%;
    display: flex;
    justify-content: space-between;

    img{
        height: 100px;
    }
}

ul{
    list-style: none;
    display: flex;
    align-items: center;
    height: 100%;

    li{
        padding: 0px 10px;
    }

    li a{
        text-decoration: none;
        color: black;
        text-transform: uppercase;
        font-family: 'Roboto Condensed', sans-serif;
        font-weight: 700;       
    }
}

.active{ 
    color: $primaryDCcolor;
    border-bottom: 5px solid $primaryDCcolor;
    padding-bottom: 65%;
}

</style>