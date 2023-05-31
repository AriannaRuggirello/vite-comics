<script>
export default {
    name: "AppHeader",
    data() {
        return {
            links: [
                {
                    text: 'CHARACTERS',
                    url: '#',
                    active: false

                },

                {
                    text: 'COMICS',
                    url: '#',
                    active: true

                },

                {
                    text: 'MOVIES',
                    url: '#',
                    active: false

                },

                {
                    text: 'GAMES',
                    url: '#',
                    active: false

                },

                {
                    text: 'COLLECTIBLES',
                    url: '#',
                    active: false

                },

                {
                    text: 'VIDEOS',
                    url: '#',
                    active: false

                },

                {
                    text: 'FANS',
                    url: '#',
                    active: false

                },

                {
                    text: 'NEWS',
                    url: '#',
                    active: false

                },

                {
                    text: 'SHOP',
                    url: '#',
                    active: false

                },
            ]
        }
    }
}

</script>

<template>
    <header>
        <div class="container">
            <img src="/dc-logo.png" alt="">
            <div v-for="link in links">
                <a :href="link.url" :class="link.active ? 'active' : ''">{{ link.text }}</a>


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

        div a {
            color: #303030;
            font-weight: bold;
            text-decoration: none;

            &.active,
            &:hover {
                color: #0282f9;
                border-bottom: 2px solid #0282f9;
            }
        }
    }

}
</style>
