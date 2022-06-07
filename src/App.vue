<template>
  <v-app>
    <div style="display: flex; justify-content:space-between">
      <LoginPageOutro class="teste"/>
      <LoginPage/>
    </div>
  </v-app>
</template>

<script>
import LoginPage from './components/LoginPage.vue';
import LoginPageOutro from './components/LoginPageOutro.vue';

export default {
  name: 'App',
  components: {
    LoginPage,
    LoginPageOutro
  },

  data: () => ({
    //
  }),
};
</script>

<style>


@media (max-width: 500px){
  .teste{
    display: none;
  }
}
</style>
