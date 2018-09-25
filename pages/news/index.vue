<template>
    <div>
        <p>{{$route.params.newsID}}</p>
        <ul>
            <li><a href="/">Home</a></li>
            <li><nuxt-link :to="{name:'news-id',params:{id:123,title:'Hello'}}">1</nuxt-link></li>
            <li><nuxt-link :to="{name:'news-id',params:{id:456}}">2</nuxt-link></li>
        </ul>
    </div>
</template>

<script>
    export default {
        transition:'test'
    }
</script>

<style scoped>

</style>