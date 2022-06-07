<template>
  <div class="hello">
    <div style="margin-top: 20%;">
      <h2 style="text-align: center; font-size: 36px;">Acesso ao sistema</h2>
     <div style="margin-top: 10%;">
      <v-text-field label="Username" type="text" :rules="rules" hide-details="auto"></v-text-field>
      <v-text-field label="Password" type="password"></v-text-field>
      <div style="display: flex; justify-content:flex-end;">
          <span><a href="">Esquece a senha ?</a></span>
      </div>
      <div style="text-align: center; margin-top: 15%;">
        <v-btn depressed color="primary" style="width: 80%;">Login</v-btn>
      </div>
      <div style="margin: 10% 0; text-align: center;">
        <span>Ou pode fazer o login com?</span>
      </div>
      <div style="display:flex; justify-content:center;">
          <img style="width: 50px; border-radius: 100%; margin: 0px 10px;" src="http://store-images.s-microsoft.com/image/apps.26737.9007199266244427.c75d2ced-a383-40dc-babd-1ad2ceb13c86.ed1d047e-03d9-4cd8-a342-c4ade1e58951" alt="">
          <img style="width: 50px; border-radius: 100%; margin: 0px 10px;" src="https://upload.wikimedia.org/wikipedia/commons/4/44/Facebook_Logo.png" alt="">
          <div style="width: 50px; border-radius: 100%; margin: 0px 10px; background-color: red; text-align: center; ">
            <span style="color:white; text-align:center; font-size: 32px; font-family: sans-serif; font-weight: 700;">G</span>
          </div>
      </div>
      <div style="text-align:center; margin-top: 15%;">
        <span>Não tem acesso? <a href="">Clique aqui e cadastre-se</a></span> <br>
      </div>
    </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'LoginPage',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello{
  width: 700px;
  height: 100%;
  padding: 40px;
}

h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
