<script>
export default {
    props: [
        'comicsThumb',
        'comicsPrice',
        'comicsSeries',
        'comicsType'
    ],

    data() {
        return {

        }
    },
}

</script>

<template>
    <div class="comic">
        <img class="" :src="comicsThumb" :alt="comicsSeries">
        <!-- <p>
            {{ comicsSeries }}
        </p> -->
    </div>
</template>

<style lang="scss">
div.comic {
    width: calc((100% / 6) - .8rem);
    height: 166px;
    overflow: hidden;
    margin: .4rem 0.4rem;

    img {
        width: 100%;
    }
}
</style>