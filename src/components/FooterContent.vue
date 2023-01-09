<script>
export default{
    data(){
            return {
                dcComicsItems : [
                    'Character',
                    'Comics',
                    'Movie',
                    'TV',
                    'Games',
                    'Videos',
                    'News',
                ],
                
                shop : [
                    'Shop DC',
                    'Shop DC Collectibles',
                ],
                
                dc : [
                    'Terms Of Use',
                    'Privacy policy(New)',
                    'Ad Choices',
                    'Advertising',
                    'Jobs',
                    'Subscriptions',
                    'Talent Workshops',
                    'CPSC Certificates',
                    'Ratings',
                    'Shop Help',
                    'Contact Us',
                ],

                sites : [
                    'DC',
                    'MAD Magazine',
                    'DC Kids',
                    'DC Universe',
                    'DC Power Visa',
                ],
            }
        }
}
</script>

<template>

    <section class="DC-comics_nav">
        <div class="DC-container">
            <div class="navs">
                <div class="nav">
                    <p>DC COMICS</p>
                    <ul>
                        <li v-for="item in dcComicsItems">
                            {{ item }}
                        </li>
                    </ul>
                    <p>SHOP</p>
                    <ul>
                        <li v-for="item in shop">{{ item }}</li>
                    </ul>
                </div>
                <div class="nav">
                    <p>DC</p>
                    <ul>
                        <li v-for="item in dc">{{ item }}</li>
                    </ul>
                </div>
                <div class="nav">
                    <p>SITES</p>
                    <ul>
                        <li v-for="item in sites">{{ item }}</li>
                    </ul>
                </div>
            </div>
            <div class="DC-img">
                <img src="../assets/img/dc-logo-bg.png" alt="">
            </div>
        </div>
    </section>

    <section class="contacts-gray">
        <div class="contacts-container">
            <div class="button">
                <button>
                    sign-up now!
                </button>
            </div>
            <div class="contacts">
                <img src="../assets/img/footer-facebook.png" alt="">
                <img src="../assets/img/footer-twitter.png" alt="">
                <img src="../assets/img/footer-youtube.png" alt="">
                <img src="../assets/img/footer-pinterest.png" alt="">
                <img src="../assets/img/footer-periscope.png" alt="">
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

    div.DC-container{
        width: 80%;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        align-items: center;
        color: white;
        height: 300px;

        div.navs{
            width: 45%;
            height: 100%;
            display: flex;

            div.nav{
                width: calc(100% / 3);
                padding: .7rem;

                p{
                    font-weight: 700;
                    margin: .6rem 0;
                }
            }

            ul li{
                list-style-type: none;
                font-size: .8rem;
                color: gray;
                padding: .2rem 0;
            }
        }

        div.DC-img img{
            width: 450px;
        }
    }

    section.contacts-gray{
        background-color: #2f2f2f;
        height: 90px;
    }

    div.contacts-container{
        width: 80%;
        margin: 0 auto;
        height: 100%;
        display: flex;
        justify-content: space-between;
        align-items: center;

        div.button button{
            border: 2px solid #0c7cec;
            text-transform: uppercase;
            color: white;
            padding: .8rem;
            background-color: #2f2f2f;
        }

        p{
            text-transform: uppercase;
            color: #0c7cec;
            font-weight: 700;
            font-size: 1.1rem;
        }

        div.contacts img{
            padding: .5rem;
        }
    }

</style>