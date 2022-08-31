<template>
    <div class='footer'>
        <a href="https://st.music.163.com/official-terms/service" target="_blank">服务条款</a>
        |
        <a href="https://st.music.163.com/official-terms/privacy" target="_blank">隐私政策</a>
        |
        <a href="https://music.163.com/st/staticdeal/complaints.html" target="_blank">版权投诉</a>
        |
        <a href="https://mp.music.163.com/600948c936c13f4d09752e73/contact-us-web/index.html?source=Music-Main-Station" target="_blank">联系我们</a>
    </div>
</template>

<script>
export default {
    components: {},
    data () {
        // 这里存放数据
        return {
        }
    },
    // 监听属性 类似于data概念
    computed: {},
    // 方法集合
    methods: {
    }
}
</script>
<style scoped lang="less">
.footer {
    height: 80px;
    line-height: 80px;
    background: red;
    color: #60606d;
    display: flex;
    justify-content: center;
    justify-items: center;
    align-content: center;
    align-items: center;
    a {
        padding: 0 10px;
        color: #fff;
    }
}
</style>
