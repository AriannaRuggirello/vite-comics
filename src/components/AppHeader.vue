<script>
export default {
    name: "AppHeader"
}

</script>

<template>
    <header>
        <div class="container">
            <img src="/dc-logo.png" alt="">
            <div>
                <a href="#">link1</a>
                <a href="#">link1</a>
                <a href="#">link1</a>
                <a href="#">link1</a>

            </div>
        </div>

    </header>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables.scss' as *;
@use '../styles/partials/mixin.scss' as *;
@use '../styles/general.scss' as *;

header {
    padding: 10px 0;

    .container {
        @include content-center;
    }

}
</style>
