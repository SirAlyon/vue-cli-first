<template>
    <div class="hero">
        <img src="https://c8p9p3e5.rocketcdn.me/wp-content/uploads/2022/04/twitter-elon-musk-meme.jpg" alt="">
    </div>
</template>

<script>

export default {
    name: 'MyHero'
}
</script>

<style scoped lang="scss">
    img{
        max-width: 100%;
        border-radius: 20px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.629);
    }

    .hero{
        width: 1000px;
        margin: 1rem auto;
        display: block;
        justify-content: center;
    }
</style>
