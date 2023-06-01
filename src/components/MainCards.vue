
<script>

export default {
    name: "MainCards",
    props: {
        details: Object,
    }

}

</script>

<template>
    <div class="card">
        <img :src="details.thumb">
        <h3>{{ details.series }}</h3>
    </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables.scss' as *;
@use '../styles/partials/mixin.scss' as *;

.card {
    width: calc(100% / 6);
    color: white;
    text-align: center;


    img {
        width: 200px;
        height: 200px;
        object-fit: contain;
    }


}
</style>
