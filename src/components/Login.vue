<template>
  <div>
    <div class="content-login">
      <div class="box">
        <span class="span-form">Usuário</span>
        <b-form-input
            id="usuario"
            type="text"
            placeholder="Digite seu usuário"
            required
        />

        <br />

        <span class="span-form">Senha</span>
        <b-form-input
            id="senha"
            type="password"
            placeholder="Digite sua senha"
            required
        />

        <br />

        <b-button variant="primary">Acessar</b-button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Login",

  data() {
    return {
      options: [
        { value: null, text: 'Please select an option' },
        { value: 'a', text: 'This is First option' },
        { value: 'b', text: 'Selected Option' },
        { value: { C: '3PO' }, text: 'This is an option with object value' },
        { value: 'd', text: 'This one is disabled', disabled: true }
      ]
    }
  }
}
</script>

<style scoped>

  .content-login {
    width: 800px;
    padding-left: 500px;
  }

  .span-form {
    padding-right: 1000px;
  }

  .box{
    background-color: #efecec;
    border-radius: 10px;
    padding-top: 20px;
    padding-bottom: 20px;
    padding-left: 20px;
    padding-right: 20px;
  }

</style>