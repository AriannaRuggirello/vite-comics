<script>
export default {
    name: "AppFooter"
}
</script>

<template>
    <footer>
        <div class="up">
            <div class="container">
                <div>
                    <img src="/buy-comics-digital-comics.png" alt="">
                    <span>digital comics</span>
                </div>

                <div>
                    <img src="/buy-comics-digital-comics.png" alt="">
                    <span>digital comics</span>
                </div>

                <div>
                    <img src="/buy-comics-digital-comics.png" alt="">
                    <span>digital comics</span>
                </div>

                <div>
                    <img src="/buy-comics-digital-comics.png" alt="">
                    <span>digital comics</span>
                </div>

                <div>
                    <img src="/buy-comics-digital-comics.png" alt="">
                    <span>digital comics</span>
                </div>

            </div>

        </div>

        <div class="middle">
            <div class="container">
                <div>
                    <h4>TITOLO</h4>
                    <ul>
                        <li>parola</li>
                        <li>parola</li>
                        <li>parola</li>
                        <li>parola</li>
                        <li>parola</li>
                        <li>parola</li>
                        <li>parola</li>
                    </ul>

                    <h4>TITOLO</h4>
                    <ul>
                        <li>parola</li>
                        <li>parola</li>
                        <li>parola</li>
                    </ul>
                </div>

                <div>
                    <h4>TITOLO</h4>
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
                    </ul>
                </div>

                <div>
                    <h4>TITOLO</h4>
                    <ul>
                        <li>parola</li>
                        <li>parola</li>
                        <li>parola</li>
                        <li>parola</li>
                    </ul>
                </div>
            </div>


        </div>

        <div class="down">
            <div class="container">
                <button>
                    sign up now!
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
    padding: 30px 0;

    img {
        max-width: 50px;
    }

    .up {
        background-color: #0282f9;
        padding: 15px 0;

        .container {
            @include content-center;

            div {
                display: flex;
                align-items: center;

                span {
                    color: white;
                    padding-left: 5px;
                }

            }


        }
    }

    .middle {
        background-color: #232323;
        padding: 10px 0;
        color: white;

        .container {
            display: flex;

            div {
                margin-right: 15px;
            }

        }

        ul {
            list-style: none;
        }
    }

    .down {
        background-color: #303030;
        padding: 20px 0;

        .container {
            @include content-center;

            div {
                display: flex;
                align-items: center;
            }

            button {
                border: #0282f9 1px solid;
                background-color: #303030;
                color: white;
                padding: 10px;
            }

            span {
                color: #0282f9;
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
