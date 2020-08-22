<template>
  <div class="container">
    <div class="auth">
      <h1>Jano</h1>
      <FormAuth />
    </div>
    <div class="cover"></div>
  </div>
</template>

<script>
export default {
  head: {
    title: "Jano | Login"
  }
};
</script>

<style lang="scss" scoped>
.container {
  height: 100vh;
  display: flex;

  > .auth {
    display: flex;
    flex-direction: column;

    align-items: center;
    height: 100%;
    flex: 1;

    > h1 {
      font-size: 80px;
      color: #366858;
      margin: 20% 0 60px 0;
    }
  }

  > .cover {
    width: 100%;
    height: 100%;
    flex: 2;

    background: url("~@/assets/bg-jano.jpg") left center no-repeat;
    background-size: cover;
  }
}
</style>
