<template>
    <div>
        <nav class="nav justify-content-center bg-primary">
          <a v-for="(nav,index) in navs" :key="index" class="nav-link text-white" href="">{{ nav.name }}</a>
        </nav>
    </div>
</template>

<script>
        export default{
        data(){
            return {
                title:"Submit",
                navs:[
                    {name:"Home",path:"/"},
                    {name:"About",path:"/"},
                    {name:"Content",path:"/"},
                ]
            }
        }
    }
</script>

<style scoped>

</style>