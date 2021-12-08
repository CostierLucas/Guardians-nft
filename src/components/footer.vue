<template>
    <footer>
        <hr>
        <!-- <img src="../assets/guardians.gif" alt=""> -->
        <h3>Join the guardians ! We need each of you ! </h3>
        <div class="social">
          <div>
            <a href="https://discord.gg/kCtvefWsBu"><img style="width:60px !important" src="https://img.icons8.com/color/96/000000/discord-logo.png"/></a>
          </div>
          <div>
            <a href="https://twitter.com/GOTSNFT"><img style="width:60px !important" src="https://img.icons8.com/color/96/000000/twitter--v1.png"/></a>
          </div>
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
  padding-bottom: 30px;
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
  font-family: Orbitron;
  margin-top: 30px;
  text-align: center;
}

footer p {
  color: #fff;
  margin: auto;
  text-align: center;
}

.copyright {
  margin-top: 30px;
  font-family: Roboto;
}

.social {
  display: flex;
  justify-content: center;
  gap: 30px;
  margin-top: 30px;
}
</style>
