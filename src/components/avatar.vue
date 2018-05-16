<template>
<div>
    <b-media tag="li">
        <b-img slot="aside" src="http://img5.imgtn.bdimg.com/it/u=2262880700,3115888735&fm=27&gp=0.jpg" width="40" height="40" alt="placeholder" />
        <h6 class="mt-2 mb-1">麦大人&nbsp;<span v-b-popover.hover.top="'简书优秀签约作家'" title=""><img src="@/assets/icons/sign.svg" width="20" height="20" malt="" /></span></h6>
    </b-media>
</div>
</template>

<script>
export default {

}
</script>

<style scoped>
img {
    border-radius: 50%;
}

h6 {
    font-size: 14px;
    font-weight: 400;
    letter-spacing: 1px;
}

</style>
