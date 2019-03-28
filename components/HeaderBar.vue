<template>
<div class="header-bar" id="menu">
  <nuxt-link class="header-bar link active" to="/">Главная</nuxt-link>
  <nuxt-link class="header-bar link" to="/okompanii">О компании</nuxt-link>
  <nuxt-link class="header-bar link" to="/statsubagentom">Стать субагентом</nuxt-link>
  <nuxt-link class="header-bar link" to="/uslygi">Услуги</nuxt-link>
  <nuxt-link class="header-bar link" to="/kontakty">Контакты</nuxt-link>
</div>
</template>

<script>
</script>

<style>
* {
  box-sizing: border-box; }

#menu {
  margin-top: 89px; }
  @media screen and (max-width: 1280px) {
    #menu {
      margin-top: 84px; } }
  #menu nuxt-link {
    width: 25%;
    height: 19px;
    font-family: SegoeUI;
    font-size: 12px;
    font-weight: normal;
    font-style: normal;
    font-stretch: normal;
    line-height: 1.36;
    letter-spacing: normal;
    text-align: left;
    color: #c5c5c5;
    margin-right: 3%;
    cursor: pointer; }
    @media screen and (max-width: 1280px) {
      #menu nuxt-link {
        font-family: SegoeUI;
        font-size: 11px;
        font-weight: normal;
        font-style: normal;
        font-stretch: normal;
        line-height: 1.36;
        letter-spacing: normal;
        color: #c5c5c5;
        margin-right: 3%;
        cursor: pointer;
        display: inline-flex;
        flex-wrap: wrap;
        width: auto; } }
  #menu :hover {
    color: #00aeef;
    border-bottom: 1px solid #00aeef;
    padding-bottom: 14px;
    text-decoration: none; }
  #menu .active {
    color: #00aeef;
    border-bottom: 1px solid #00aeef;
    padding-bottom: 14px;
    text-decoration: none; }

#menu:before {
  content: '';
  display: inline-block;
  vertical-align: middle;
  box-sizing: border-box;
  width: 37%;
  margin-right: 60px;
  height: 1px;
  background: #c5c5c5; }
  @media screen and (max-width: 1280px) {
    #menu:before {
      content: '';
      display: inline-block;
      vertical-align: middle;
      box-sizing: border-box;
      width: 100%;
      height: 1px;
      background: #c5c5c5;
      position: relative;
      left: -0px;
      margin-left: -798px;
      display: inline-flex; } }

body {
  background: #1a1a1a;
  margin: 0 auto; }
</style>
