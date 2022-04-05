<template>
  <section class="home">
    <div>
      <h1>Dimas Toriq Pratama Putra</h1>
      <p>This my journey</p>
      <p>as</p>
      <p>Web Developer</p>
    </div>
  </section>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
  },
};
</script>

<style scoped lang='scss'>
.home {
  background-image: url("../assets/img/background-home.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  width: 100%;
  height: calc(100vh + 60px);
  margin-top: -60px;
  padding: 100px 20px;
  display: flex;
  flex-direction: column;
  align-items: flex-end;
  h1 {
    font-size: 40px;
    font-weight: bold;
    color: #fbe7c0;
  }
  p {
    width: 75%;
    font-size: 24px;
    color: white;
    &:nth-child(3) {
      text-align: center;
    }
    &:nth-child(4) {
      text-align: end;
      font-weight: 600;
    }
  }
}
</style>
