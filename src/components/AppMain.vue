
<script>
export default {
    name: "AppMain",
}


</script>

<template>
    <main>
        <h1> contenuto qui</h1>
    </main>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables.scss' as *;
@use '../styles/partials/mixin.scss' as *;
@use '../styles/general.scss' as *;

main {
    background-color: black;
    height: 100px;
    @include content-center;

    h1 {
        color: white;
    }
}
</style>
