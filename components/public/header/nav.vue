<template>
  <div class="m-nav">
    <ul class="nav">
      <li class="list">
        <nuxt-link to="/my">我的美团</nuxt-link>
        <dl>
          <dd><nuxt-link to="/order">我的订单</nuxt-link></dd>
          <dd><nuxt-link to="/order">我的收藏</nuxt-link></dd>
          <dd><nuxt-link to="/order">我的抵用券</nuxt-link></dd>
          <dd><nuxt-link to="/order">我的订单</nuxt-link></dd>
        </dl>
      </li>
      <li>
        <nuxt-link to="/order">手机App</nuxt-link>
      </li>
      <li class="list bd">
        <nuxt-link to="/center">商家中心</nuxt-link>
        <dl>
          <dd><nuxt-link to="/userCenter">登录商家中心</nuxt-link></dd>
          <dd><nuxt-link to="/order">我想合作</nuxt-link></dd>
          <dd><nuxt-link to="/order">免费手机开店</nuxt-link></dd>
          <dd><nuxt-link to="/order">商家中心请开票</nuxt-link></dd>
        </dl>
      </li>
      <li class="list site">
        <nuxt-link to="/site">网站导航</nuxt-link>
        <div class="subContainer">
          <dl class="hotel">
            <dt>酒店旅游</dt>
            <dd>机票</dd>
            <dd>机票</dd>
            <dd>机票</dd>
            <dd>机票</dd>
            <dd>机票</dd>
            <dd>机票</dd>
            <dd>机票</dd>
            <dd>机票</dd>
            <dd>机票</dd>
          </dl>
          <dl class="food">
            <dt>吃美食</dt>
            <dd>烤鱼</dd>
            <dd>烤鱼</dd>
            <dd>烤鱼</dd>
            <dd>烤鱼</dd>
          </dl>
          <dl class="movie">
            <dl>看电影</dl>
            <dd>热电影</dd>
            <dd>热电影</dd>
            <dd>热电影</dd>
            <dd>热电影</dd>
            <dd>热电影</dd>
            <dd>热电影</dd>
            <dd>热电影</dd>
          </dl>
          <dl class="app">
            <dt>手机运用</dt>
            <dd>哈哈哈</dd>
          </dl>
        </div>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
}
</script>

<style lang="scss">

</style>
