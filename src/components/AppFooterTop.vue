<template>
    <div class="footer_top">
        <div class="content">

            <div class="container">
                <div class="row">
                    <div class="col-5">
                        <div class="row">
                            <div class="col-4 px-1 py-2">
                                <div class="footer_nav">
                                    <h4 class="text-uppercase">dc comics</h4>
                                    <ul>
                                        <li>Characters</li>
                                        <li>Comics</li>
                                        <li>Movies</li>
                                        <li>TV</li>
                                        <li>Games</li>
                                        <li>Videos</li>
                                        <li>News</li>
                                    </ul>
                                </div>
                                <div class="footer_nav">
                                    <h4 class="text-uppercase">shop</h4>
                                    <ul>
                                        <li>Shop DC</li>
                                        <li>Shop DC Collectibles</li>
                                    </ul>
                                </div>
                            </div>
                            <div class="col-4 px-1 py-2">
                                <div class="footer_nav">
                                    <h4 class="text-uppercase">dc</h4>
                                    <ul>
                                        <li>Terms Of Use</li>
                                        <li>Privacy Policy (New)</li>
                                        <li>Ad Choices</li>
                                        <li>Advertising</li>
                                        <li>Jobs</li>
                                        <li>Subscription</li>
                                        <li>Talent Workshop</li>
                                        <li>CPSC Certificates</li>
                                        <li>Ratings</li>
                                        <li>Shop Help</li>
                                        <li>Contact Us</li>
                                    </ul>
                                </div>
                            </div>
                            <div class="col-4 px-1 py-2">
                                <div class="footer_nav">
                                    <h4 class="text-uppercase">sites</h4>
                                    <ul>
                                        <li>DC</li>
                                        <li>MAD Magazine</li>
                                        <li>DC Kids</li>
                                        <li>DC Universe</li>
                                        <li>DC Power Visa</li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-7 position-relative d-flex align-items-center justify-content-center">
                        <img class="logo_abs position-absolute" src="../assets/img/dc-logo-bg.png" alt="">
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'AppFooterTop'
}
</script>

<style lang="scss" scoped>
.footer_top {
    margin: 0 auto;

    .content {
        max-width: 1280px;
        margin: 0 auto;
        padding: 3rem 2rem;

        .logo_abs {
            z-index: 0;
        }
    }

    background: url('../assets/img/footer-bg.jpg');
    color: white;

    .footer_nav {
        & ul {
            color: #787978;
            padding: 0;
            text-align: start;
            list-style: none;
            font-size: 0.9rem;
        }
    }
}
</style>