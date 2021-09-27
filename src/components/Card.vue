<template>
    <div class="card-comics">
        <img :src="source" :alt="title">
        <h5>{{ title }}</h5>
    </div> 
</template>

<script>
export default {
    props: ["title", "source"]
}
</script>

<style lang="scss">

.card-comics{
    flex-basis: calc(100% / 6);
    padding-top: 45px;

    h5{
        font-weight: 400;
        text-transform: uppercase;
        padding-top: 10px;
    }
}
</style>