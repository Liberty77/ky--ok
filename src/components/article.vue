<template>
<div class="mt-4">
    <avatar />
    <b-media right-align vertical-align="center">
        <b-img slot="aside" src="http://h.hiphotos.baidu.com/image/pic/item/63d0f703918fa0ecf70575602a9759ee3c6ddb99.jpg" width="160" height="120" alt="placeholder" />
        <h5 class="mt-2 mb-1">游戏对于我们而言到底是什么？-《头号玩家》</h5>
        <p class="mt-2">这是一部好评如潮的电影，也是游戏迷们的盛宴。 《头号玩家》中数之不尽的彩蛋和游戏形象让游戏迷们雀跃不已，精美画面和震撼镜头则是让非游戏迷们惊艳。但这些都不足以让它成为一部伟大...</p>
    </b-media>
    <div class="line-bottom mt-5"></div>
</div>
</template>

<script>

import avatar from "./avatar";

export default {
    name: "Article",
    components: {
        avatar
    }
}
</script>

<style scoped>

img {
    border-radius: 8px;
}


h5 {
    font-size: 18px;
    color: black;
    font-weight: 600;
}

P {
    font-size: 14px;
    color: black;
    font-weight: 400;
    line-height: 160%;
}

.line-bottom {
    background-color: #eee;
    height: 1px;
}
</style>
