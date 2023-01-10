<script>

</script>

<template>
    <main>
        <section class="jumbo">
            <img src="../assets/img/jumbotron.jpg" alt="Jumbotron">
        </section>
        <section class="black-content">
            <div class="series">
                current series
            </div>
            <h3>
            
            </h3>
        </section>
    </main>

</template>

<style  lang="scss">

    section.jumbo{
        height: 350px;
        overflow: hidden;

        img{
            width: 100%;
        }
    }

    section.black-content{
        height: 100px;
        background-color: black;
        color: white;
        display: flex;
        align-items: center;
        position: relative;

        div.series{
            position: absolute;
            background-color: #0c7cec;
            text-transform: uppercase;
            color: white;
            bottom: 100%;
            left: 18%;
            padding: 0.7rem 1.2rem;
            font-weight: 600;
            transform: translate(0, 50%);
            font-size: 1.2rem;
        }

        h3{
            width: 80%;
            margin: 0 auto;
        }
    }

</style>