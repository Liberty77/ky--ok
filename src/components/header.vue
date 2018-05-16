<template>
<b-container fluid class="container-box">
    <b-row align-v="center" class="text-center">
        <b-col md="1">
            <span class="logo-name ml-5">聚雍</span>
        </b-col>
        <b-col md="4">
            <span>
            <a class="homepage" href=""> <span><img src="@/assets/icons/compass.svg" height="20" alt="" /> 首页</span></a>
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <a class="download-app" href=""> <span><img src="@/assets/icons/download-app.svg" height="20" alt="" />下载App</span></a>
            </span>
        </b-col>
        <b-col md="3">
        </b-col>
        <b-col md="2">
            <span class="login">登录1333</span>
        </b-col>
    </b-row>
</b-container>
</template>

<script>
export default {

}
</script>

<style scoped>
div.container-box {
    background: #fefefe;
    box-shadow: 1px 1px 1px #efefef;
    padding: 8px 0;
}

span.logo-name {
    font-size: 1.8rem;
    font-weight: 600;
    color: peru;
}

a.homepage {
    text-decoration: none;
    font-size: 18px;
    font-weight: 300;
    color: peru;
}

a.download-app {
    text-decoration: none;
    font-size: 18px;
    font-weight: 300;
    height: 60px;
    color: black;
}

span.login {
    font-size: 18px;
    font-weight: 300;
    height: 60px;
    color: peru;
}
</style>
