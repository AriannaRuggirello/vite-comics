
<script>
export default {
    name: "AppMain",
}


</script>

<template>
    <main>
        <div class="hero">

        </div>
        <div class="container">

        </div>

    </main>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables.scss' as *;
@use '../styles/partials/mixin.scss' as *;
@use '../styles/general.scss' as *;

main {

    .hero {
        height: 300px;
        background-image: url("/jumbotron.jpg");
        background-size: cover
    }

    .container {
        @include content-center;



    }
}
</style>
