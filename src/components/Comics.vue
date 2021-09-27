<template>
    <div>
        <div class="bg-comics"></div>
        <div class="bg-container-comics">
            
            <div class="container-comics">

                <div class="title-comics">
                    <h3>Current Series</h3>
                </div>

                <div class="card-comics" v-for="(item, index) in CardDc" :key="index">
                    <img :src="item.thumb" alt="">
                    <h5>{{ item.series }}</h5>
                </div>        
                
                <button class="btn btn-comics">Load More</button>

            </div>

    
        </div>
    </div>
</template>

<script>
import CardDc from "../data/dc-comics.json"

export default {
    data(){
        return{
            CardDc,
        }
    }
}
</script>

<style  lang="scss" scoped>
@import '../style/general.scss';

.bg-comics{
    height: 400px;
    background-image: url("../assets/img/jumbotron.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    background-position-x: center;
}

.bg-container-comics{
    background-color: #1c1c1c;
}

.container-comics{
    width: $generalWidth;
    margin: $generalMargin;
    display: flex;
    flex-wrap: wrap;
    // height: 500px;
    align-items: center;
    justify-content: center;
    color: $whiteColor;
    font-family: 'Roboto Condensed', sans-serif;
    position: relative;

    img{
        width: 150px;
    }

    .title-comics{
        position: absolute;
        top: 0px;
        left: 0px;
        transform: translate(0,-50%);
        background-color: #0282f9;
        
        h3{
            text-transform: uppercase;
            font-size: 1.5rem;
            padding: 10px 25px;
        }
    }
}

.card-comics{
    flex-basis: calc(100% / 6);
    padding-top: 45px;

    h5{
        font-weight: 400;
        text-transform: uppercase;
        padding-top: 10px;
    }
}

.btn-comics{
    background-color: $primaryDCcolor;
    border: 2px solid $primaryDCcolor;
    padding: 10px 40px;
    margin: 35px;
}


</style>