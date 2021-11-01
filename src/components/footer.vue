<template>
    <footer>
        <hr>
        <img src="../assets/guardians.gif" alt="">
        <h3>Join the guardians ! We need each of you ! </h3>
        <div class="social media">
        </div>
        <p class="copyright">&copy; 2021 GOTSNFT</p>
    </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
footer {
  padding-top: 30px;
  display: grid;
  align-items: center;
}

footer hr {
  border: 1px solid white;
  width: 80%;
  margin: auto;
  margin-bottom: 30px;
}

footer img {
  text-align: center;
  margin: auto;
}

footer h3 {
  color: #fff;
  margin: auto;
  font-family: Roboto;
  margin-top: 30px;
}

footer p {
  color: #fff;
  margin: auto;
}

.copyright {
  margin-top: 30px;
  font-family: Roboto;
}
</style>
