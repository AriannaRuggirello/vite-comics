<script>
export default {
    name: "AppFooter",
    data() {
        return {
            upIcons: [
                {
                    title: 'DIGITAL COMICS',
                    image: "/buy-comics-digital-comics.png"

                },

                {
                    title: 'DC MERCHANDISE',
                    image: "/buy-comics-merchandise.png"

                },

                {
                    title: 'SUBSCRIPTION',
                    image: "/buy-comics-subscriptions.png"

                },

                {
                    title: 'COMIC SHOP LOCATOR',
                    image: "/buy-comics-shop-locator.png"

                },

                {
                    title: 'DC POWER VISA',
                    image: "/buy-dc-power-visa.svg"

                },
            ],
        }
    }

}
</script>

<template>
    <footer>
        <div class="up">
            <div class="container">
                <div v-for="upIcon in upIcons">
                    <img :src="upIcon.image" alt="">
                    <span>{{ upIcon.title }}</span>
                </div>

            </div>

        </div>

        <div class="middle">
            <div class="container">
                <div class="content-left">
                    <div>
                        <h4>DC COMICS</h4>
                        <ul>
                            <li>parola</li>
                            <li>parola</li>
                            <li>parola</li>
                            <li>parola</li>
                            <li>parola</li>
                            <li>parola</li>
                            <li>parola</li>
                        </ul>

                        <h4>SHOP</h4>
                        <ul>
                            <li>parola</li>
                            <li>parola</li>
                        </ul>
                    </div>

                    <div>
                        <h4>DC</h4>
                        <ul>
                            <li>parola</li>
                            <li>parola</li>
                            <li>parola</li>
                            <li>parola</li>
                            <li>parola</li>
                            <li>parola</li>
                            <li>parola</li>
                            <li>parola</li>
                            <li>parola</li>
                            <li>parola</li>
                            <li>parola</li>

                        </ul>
                    </div>

                    <div>
                        <h4>SITES</h4>
                        <ul>
                            <li>parola</li>
                            <li>parola</li>
                            <li>parola</li>
                            <li>parola</li>
                            <li>parola</li>

                        </ul>
                    </div>
                </div>

                <div class="content-right">
                    <img src="/dc-logo-bg.png" alt="">
                </div>

            </div>


        </div>

        <div class="down">
            <div class="container">
                <button>
                    SIGN-UP NOW!
                </button>

                <div class="icons">
                    <span>FOLLOW US!</span>
                    <img src="footer-facebook.png" alt="">
                    <img src="footer-periscope.png" alt="">
                    <img src="footer-pinterest.png" alt="">
                    <img src="footer-twitter.png" alt="">
                    <img src="footer-youtube.png" alt="">


                </div>
            </div>

        </div>
    </footer>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables.scss' as *;
@use '../styles/partials/mixin.scss' as *;
@use '../styles/general.scss' as *;

footer {


    .up {
        background-color: $primary-color;
        padding: 15px 0;

        .container {
            @include content-center;

            div {
                display: flex;
                align-items: center;

                img {
                    width: 40px;
                }

                span {
                    color: white;
                    padding-left: 5px;
                }



            }


        }
    }

    .middle {
        max-height: 350px;
        background-image: url(/footer-bg.jpg);
        color: white;

        .container {
            display: flex;
            justify-content: space-between;

            .content-left {
                display: flex;
                padding-top: 40px;

                div {
                    margin-right: 30px;
                }
            }

            .content-right {
                img {
                    height: 450px;
                    position: relative;
                    top: -30px;
                    right: 25%;
                }
            }



        }

        ul {
            list-style: none;
            padding-bottom: 10px;
            color: gray;
        }
    }

    .down {
        position: relative;
        background-color: #303030;
        padding: 20px 0;

        .container {
            @include content-center;

            div {
                display: flex;
                align-items: center;
            }

            button {
                border: $primary-color 3px solid;
                background-color: #303030;
                color: white;
                padding: 10px;
            }

            span {
                color: $primary-color;
                font-weight: bold;
            }

            .icons {

                img,
                span {
                    margin-right: 15px;
                }

            }


        }


    }

}
</style>
