<template>
  <footer class="footer">
    <h3>Vue app made by Bruno Figueiredo</h3>
    <div class="nav">
      <a href="https://edzijlstra.nl/bruno/Portfolio/Portfolio/" target="_blank">Portfolio</a>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
.footer {
  background: #333;
  color: #fff;
  text-align: center;
  padding: 10px;
  position: relative;
  width: 100%;
}

.footer a {
  color: #fff;
  padding-right: 5px;
  text-decoration: none;
}
</style>