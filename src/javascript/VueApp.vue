<template>
  <p>{{ message }}</p>
</template>

<script>
export default {
  data: () => {
    console.log('Vue.jsがインストールされました。');
    return{
      message:'やぁ！これがveuですよ～！',
    };
  },
};
</script>

<style scoped>
  p {
    color:green;
  }
</style>
