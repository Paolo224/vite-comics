<script>

</script>

<template>

    <section class="DC-comics_nav">
        <div class="container">
            <div class="navs">
                <div class="nav">
                    <ul>

                    </ul>
                    <ul>

                    </ul>
                </div>
                <div class="nav">
                    <ul>

                    </ul>
                </div>
                <div class="nav">
                    <ul>

                    </ul>
                </div>
            </div>
            <div class="DC-img">
                <img src="../assets/img/dc-logo-bg.png" alt="">
            </div>
        </div>
    </section>

</template>

<style  lang="scss">

    section.DC-comics_nav{
        background-image: url(../assets/img/footer-bg.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        height: 300px;
        overflow: hidden;
    }

    div.container{
        width: 80%;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        align-items: center;
        color: white;
        height: 300px;

        div.navs{
            width: 45%;
            border: 2px solid red;
            height: 100%;
            display: flex;

            div.nav{
                width: calc(100% / 3);
                border: 2px solid blue;
            }
        }

        div.DC-img img{
            width: 450px;
        }
    }

</style>