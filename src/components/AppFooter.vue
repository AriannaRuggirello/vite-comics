<script>
export default {
    name: "AppFooter"
}
</script>

<template>
    <footer>
        <div class="up">
            <div class="container">

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
                    <h2>follow us</h2>
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

    .up {
        background-color: #0282f9;
        height: 70px;
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

        .container {
            @include content-center;

        }

        h2 {
            color: white;
        }
    }

}
</style>
