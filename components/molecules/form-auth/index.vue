<template>
  <form id="login">
    <Input placeholder="E-mail" />
    <Input placeholder="Senha" type="password" />
    <Button type="submit" label="Entrar" />
  </form>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
#login {
  max-width: 320px;
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;

  section:first-child {
    margin-bottom: 30px;
  }

  button {
    margin-top: 40px;
  }
}
</style>
