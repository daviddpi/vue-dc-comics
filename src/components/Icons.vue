<template>
    <div>
        <div class="bg-icons">
            <div class="container-icons">
                <div class="icon-img">
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="DC Icons">
                    <h4>Digital Comics</h4>
                </div>

                <div class="icon-img">
                    <img src="../assets/img/buy-comics-merchandise.png" alt="DC Icons">
                    <h4>Dc Merchandise</h4>
                </div>

                <div class="icon-img">
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="DC Icons">
                    <h4>Subscription</h4>
                </div>

                <div class="icon-img">
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="DC Icons">
                    <h4>Comic Shop Locator</h4>
                </div>

                <div class="icon-img">
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="DC Icons">
                    <h4>Dc Power Visa</h4>
                </div>

            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style  lang="scss" scoped>
@import '../style/general.scss';

.bg-icons{
    background-color: $primaryDCcolor;
}

.container-icons{
    width: $generalWidth;
    margin: $generalMargin;
    display: flex;
    justify-content: space-between;
    height: 150px;
    align-items: center;
    color: $whiteColor;
    padding: 0 40px;
}

.icon-img{
    display: flex;
    align-items: center;
    img{
        width: 50px;
    }

    h4{
        font-weight: 400;
        padding-left: 15px;
        text-transform: uppercase;
        font-size: 0.8rem;
    }

    &:hover{
        cursor: pointer;
    }
}

</style>