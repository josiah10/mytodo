<template>
<div class="contain">
  <h2>#todo</h2>
  <div class="main">
    <div class="header">
      <div class="all">All</div>
      <div class="active">Active</div>
      <div class="complete">Completed</div>
    </div>
    <div class="line"></div>
    <div class="components">
        <All/>
    </div>
  </div>
</div>
</template>

<script>
import All from "./components/All";

export default {
  name: 'App',
  components: {
    All,
  }
}
</script>

<style>
.contain{
}
  h2 {
    margin: 32px auto;
    font-weight: 700;
    font-size: 36px;
    line-height: 42px;
    text-align: center;
    letter-spacing: -0.045em;
    color: #333333;
  }
  .main{
    margin: 0 auto;
  }
  .header{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: row;
    margin-left: 220px;
    margin-bottom: -1px;
  }
  .all,.active,.complete{
    margin-right: 165px;
    padding: 15px;
    border-bottom-left-radius: 2px;
    border-bottom-right-radius: 2px;
    border-bottom: 3px solid #2F80ED;;
  }
  .line{
    width: 608px;
    margin: 0 515px 25px;
    text-align: center;
    border: 1px solid #BDBDBD;

  }
</style>
