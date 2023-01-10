<script>
export default{
    data(){
            return {
                navItems : [
                    {
                        text : 'characters',
                        active : false,
                    },
                    {
                        text : 'comics',
                        active : true,
                    },
                    {
                        text : 'movies',
                        active : false,
                    },
                    {
                        text : 'tv',
                        active : false,
                    },
                    {
                        text : 'games',
                        active : false,
                    },
                    {
                        text : 'collectibles',
                        active : false,
                    },
                    {
                        text : 'videos',
                        active : false,
                    },
                    {
                        text : 'fans',
                        active : false,
                    },
                    {
                        text : 'news',
                        active : false,
                    },
                    {
                        text : 'shop',
                        active : false,
                    },
                ],
            }
        }
}
</script>

<template>

    <header class="container">
        <div class="logo">
            <img src="../assets/img/dc-logo.png" alt="">
        </div>
        <nav>
            <ul>
                <li v-for="item in navItems" :class="(navItems.active) ? 'active' : ''">{{ item.text }}</li>
            </ul>
        </nav>
    </header>

</template>

<style lang="scss">
header.container {
    width: 80%;
    margin: 0 auto;
    height: 100px;
    display: flex;
    justify-content: space-between;
}

div.logo {
    display: flex;
    align-items: center;

    img {
        width: 80%;
    }
}

nav {
    display: flex;
    align-items: center;

    ul {
        display: flex;
        padding: 0;

        li {
            padding: .7rem;
            list-style-type: none;
            text-transform: uppercase;
            font-size: .8rem;
            font-weight: 700;
            color: rgb(90, 90, 90);
            border-bottom: 2px solid transparent;

            &.active{
                color: #0c7cec;
                border-bottom: 2px solid #0c7cec;
            }
        }
    }
}
</style>
