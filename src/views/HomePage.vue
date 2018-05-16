<template>
<div>
    <div class="page-header">
        <Header></Header>
    </div>
    <div class="page-carousel">
        <Carousel></Carousel>
    </div>
    <div class="content">
        <Article />
        <Article />
        <Article />
        <Article />
        <Article />
        <Article />
        <Article />
        <Article />
        <Article />
    </div>
</div>
</template>

<script>
import Header from '@/components/header'
import Carousel from '@/components/carousel'
import Article from '@/components/article'
export default {
    name: "HomePage",
    data() {
        return {
            msg: "Welcome to Your Vue.js App"
        };
    },
    components: {
        Header,
        Carousel,
        Article
    }

};
</script>

<style scoped>
div.page-header {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    z-index: 999999999;
}

div.page-carousel {
    width: 60%;
    margin-left: 20%;
    margin-top: 5rem;
    text-align: right;
}

div.content {
    width: 60%;
    margin-left: 20%;
    margin-top: 5rem;
    text-align: left;
}
</style>
