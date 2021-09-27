<template>
    <div>
        <main class="bg-main">
            <div class="container-main">
                <h1>--&gt; Content goes here &lt;--</h1>
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

.bg-main{
    background-color: #1c1c1c;
}

.container-main{
    width: $generalWidth;
    margin: $generalMargin;
    display: flex;
    height: 120px;
    align-items: center;
    color: $whiteColor;
    font-family: 'Roboto Condensed', sans-serif;
}

</style>