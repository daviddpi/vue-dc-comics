<template>
    <div>
        <header class="bg-header">
            <div class="conteiner-header">
                <img src="../assets/img/dc-logo.png" alt="Logo DC">
                <nav>
                    <ul>
                        <li @click="changeNavItem(index)" v-for="(item, index) in navTitle" :key="item" :class="{'active': index == indiceNav}">
                            <a :href="item.link">{{ item.name }}</a>
                        </li>
                    </ul>
                </nav>
            </div>
        </header>
    </div>
</template>

<script>
export default {
    data(){

        return{
            navTitle: [
                {
                    name: "Characters",
                    link: "#",
                },

                {
                    name: "Comics",
                    link: "#",
                },

                {
                    name: "Movies",
                    link: "#",
                },

                {
                    name: "Tv",
                    link: "#",
                },

                {
                    name: "Games",
                    link: "#",
                },

                {
                    name: "Collectibles",
                    link: "#",
                },

                {
                    name: "Videos",
                    link: "#",
                },

                {
                    name: "Fans",
                    link: "#",
                },

                {
                    name: "News",
                    link: "#",
                },

                {
                    name: "Shop",
                    link: "#",
                },

            ],

            indiceNav: 0,
            
        }
    },

    methods:{
        changeNavItem(index){
            this.indiceNav = index;
        }
    }
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
    height: 100%;
    display: flex;
    justify-content: space-between;

    img{
        height: 100px;
        padding: 15px 0px;
    }
}

ul{
    list-style: none;
    display: flex;
    height: 100%;

    li{
        padding: 0px 10px;
        height: 100%;
        display: flex;
        align-items: center;
        border-bottom: 5px solid transparent;

    }

    li a{
        text-decoration: none;
        color: black;
        text-transform: uppercase;
        font-family: 'Roboto Condensed', sans-serif;
        font-weight: 700;
        vertical-align: middle;
    }
}

.active{ 
    a{
        color: $primaryDCcolor;

    }
    border-bottom: 5px solid $primaryDCcolor;
    // padding-bottom: 65%;
}

</style>