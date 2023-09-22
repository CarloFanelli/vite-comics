<template>
    <div class="footer_bottom">
        <div class="content">
            <div class="container d-flex justify-content-between align-items-center">

                <div class="my_btn">
                    <a href="#">
                        <h5 class="text-uppercase">sign-up now!</h5>
                    </a>
                </div>

                <div class="social d-flex">
                    <h4 class="text-uppercase px-2">Follow Us</h4>
                    <div class="social_icons">
                        <img class="px-2" src="../assets/img/footer-facebook.png" alt="Facebook">
                        <img class="px-2" src="../assets/img/footer-twitter.png" alt="twitter">
                        <img class="px-2" src="../assets/img/footer-youtube.png" alt="youtube">
                        <img class="px-2" src="../assets/img/footer-pinterest.png" alt="pinterest">
                        <img class="px-2" src="../assets/img/footer-periscope.png" alt="">
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'AppFooterBottom',
}
</script>

<style lang="scss" scoped>
@use '../assets/scss/partials/variabiles' as *;

.footer_bottom {
    z-index: 1;
    position: relative;

    background: $dc__dark;

    .content {

        max-width: 1280px;
        margin: 0 auto;
        padding: 2rem;

        .my_btn {
            border: 3px solid $dc__evidence;
            padding: 1rem;

            & a {
                text-decoration: none;

                & h5 {

                    color: white;
                    text-transform: uppercase;
                    margin: 0;

                }
            }
        }

        .social {
            color: $dc__evidence;
        }
    }
}
</style>