<template>
  <div>
    Hello world!
  </div>
  <Counter
    :year="2022"
    :month="0"
    :date="4"
    :hour="0"
    :minute="0"
    :second="0"
    :millisecond="0"
  />
</template>
<script>
import Counter from "./components/Counter";
export default {
  components: {
    Counter,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
