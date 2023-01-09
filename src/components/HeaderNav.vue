<script>

</script>

<template>

    <header class="container">
        <div class="logo">
            <img src="../assets/img/dc-logo.png" alt="">
        </div>
        <nav>
            <ul>
                <li>characters</li>
                <li class="active">comics</li>
                <li>movies</li>
                <li>tv</li>
                <li>games</li>
                <li>collectibles</li>
                <li>videos</li>
                <li>fans</li>
                <li>news</li>
                <li>shop</li>
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
        }
    }
}
</style>
