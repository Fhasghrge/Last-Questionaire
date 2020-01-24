<template>
  <div id="login">
    <div id="shuang">
      <div id="avatar">
        <img src="../assets/img/logo.jpg" />
      </div>
      <div id="name">毕业生</div>
    </div>

    <div class="entrance-bottom">
      <div class="entrance-bottom-frame clearfix"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: "login",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#login {
  background-image: url('../assets/img/dtbg.png');
    background-size: 100% 100%;
    background-repeat: no-repeat;
    background-color: #F5FDEC;
    height: 100%;
}
#shuang {
  text-align: center;
  line-height: 1rem;
  font-size: 0.36rem;
  margin: auto;
  padding-top: 20px;
}
#name {
  font-size: 1em;
  font-weight: bold;
  font-family: sans-serif;
}
#avatar > img {
  height: 100px;
  border-radius: 50%;
}
</style>

