<template>
<div class="sidebar">
 <a class="active">Войти&nbsp;&nbsp;&nbsp;&#8594;</a>
 <div class="bar">
   <a>Авиабилеты</a>
   <hr>
   <a>Ж/Д Авиабилеты</a>
   <hr>
   <a>Гостиницы</a>
   <hr>
   <a>Страхование</a>
   <hr>
   <a>Трансфер</a>
   <hr>
   <a>Туризм</a>
 </div>
</div>
</template>

<script>
</script>

<style>
.sidebar {
  position: sticky;
  left: 1712px;
  width: 224px;
  height: 1272px;
  font-family: SegoeUI;
  font-size: 12px;
  font-weight: normal;
  font-style: normal;
  font-stretch: normal;
  line-height: 5.22;
  letter-spacing: normal;
  color: #c5c5c5;
  border-left: 1px solid #c5c5c5;
  margin-top: -100px;
  padding-left: 46px;
  padding-top: 68px; }
  @media screen and (max-width: 1280px) {
    .sidebar {
      position: sticky;
      left: 1103px;
      width: 175px;
      height: 1272px;
      font-family: SegoeUI;
      font-size: 12px;
      font-weight: normal;
      font-style: normal;
      font-stretch: normal;
      line-height: 5.22;
      letter-spacing: normal;
      color: #c5c5c5;
      border-left: 1px solid #c5c5c5;
      margin-top: -104px;
      padding-left: 39px;
      padding-top: 61px; } }
  .sidebar .bar {
    margin-top: 134px;
    vertical-align: right; }
    @media screen and (max-width: 1280px) {
      .sidebar .bar {
        margin-top: 134px;
        flex-direction: column;
        margin-left: -8px; } }
  .sidebar hr {
    margin-left: 0px;
    margin-top: 4px;
    margin-bottom: 4px;
    width: 10px; }
    @media screen and (max-width: 1280px) {
      .sidebar hr {
        margin-left: -0px;
        margin-top: -3px;
        margin-bottom: -3px;
        width: 10px; } }
  .sidebar a {
    padding: -10px; }
    @media screen and (max-width: 1280px) {
      .sidebar a {
        padding: -10px; } }
  .sidebar .active {
    color: #00aeef;
    padding-bottom: 14px;
    text-decoration: none;
    cursor: pointer; }
    @media screen and (max-width: 1280px) {
      .sidebar .active {
        color: #00aeef;
        padding-bottom: 14px;
        text-decoration: none;
        cursor: pointer; } }
</style>
