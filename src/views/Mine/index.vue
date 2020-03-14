<template>
    <div id="main">
        <!-- 头部 -->
        <Header :title="title"></Header>

        <!-- 登陆部分 -->
        <div id="content">
            <Login></Login>
        </div>
        
        <TabBar></TabBar>
    </div>
</template>

<script>
import Header from '@/components/Header'
import TabBar from '@/components/TabBar'
import Login from '@/components/Login'
export default {
    name: 'Mine',
    data() {
        return {
            title: '我的喵喵'
        }
    },
    components: {
        Header,
        TabBar,
        Login
    }
}
</script>

<style scoped>

</style>