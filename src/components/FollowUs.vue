<template>
    <div>
        <div class="bg-followUs">
            <div class="followUs-container">
                <button class="btn btn-footer">Sign-up Now!</button>
                <div class="d-flex">
                    <div class="text-follow">
                        <h4>Follow Us</h4>
                        <img src="../assets/img/footer-facebook.png" alt="facebook logo">
                        <img src="../assets/img/footer-twitter.png" alt="facebook logo">
                        <img src="../assets/img/footer-youtube.png" alt="facebook logo">
                        <img src="../assets/img/footer-pinterest.png" alt="facebook logo">
                        <img src="../assets/img/footer-periscope.png" alt="facebook logo">
                    </div>
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


.bg-followUs{
    background-color: #303030;
    height: 100px;
}

.followUs-container{
    width: $generalWidth;
    margin: $generalMargin;
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.d-flex{
    display: flex;
}

.btn-footer{
    background-color: transparent;
    border: 2px solid $primaryDCcolor;
    padding: 15px;
    text-transform: uppercase;
    font-weight: bold;
    color: $whiteColor;

    &:hover{
        cursor: pointer;
        box-shadow: 2px 2px 2px black;
    }
}

.text-follow{
    display: flex;
    align-items: center;
    width: 100%;
    h4{
        text-transform: uppercase;
        color: $primaryDCcolor;
        padding-right: 15px;
    }

    img{
        padding: 0 10px;

        &:hover{
            cursor: pointer;
            filter: brightness(200%);
        }
    }
}

</style>