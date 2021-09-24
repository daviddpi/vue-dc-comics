<template>
  <div>
        <main class="bg-icons">
            <div class="container-icons">
                <div class="icon-img">
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="Smatphone DC">
                    <h4>Digital Comics</h4>
                </div>

                <div class="icon-img">
                    <img src="../assets/img/buy-comics-merchandise.png" alt="Merchandise DC">
                    <h4>Digital Comics</h4>
                </div>

                <div class="icon-img">
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="Subscriptions DC">
                    <h4>Digital Comics</h4>
                </div>

                <div class="icon-img">
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="Locator Shop DC">
                    <h4>Digital Comics</h4>
                </div>

                <div class="icon-img">
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="Power DC">
                    <h4>Digital Comics</h4>
                </div>
            </div>
        </main>
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