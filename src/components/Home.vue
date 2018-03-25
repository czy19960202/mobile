<template>
  <!-- p -->
  <div>
      <h1>我是主页</h1>
      <nav>
          <router-link to="/home/login">登录</router-link>
          <router-link to="/home/reg">注册</router-link>
      </nav>
      <div>
          <router-view></router-view>
      </div>
      <div>{{hint}}</div>
  </div>
</template>

<script>
export default {
    name: 'Home',
    data(){
        return {
            hint:'Welcome to my Homepage'
        }
    }
}
</script>

