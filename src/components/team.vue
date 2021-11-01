<template>
 <section>
     <div class="team">
         <div data-aos="fade-left" data-aos-duration="1500" >
             <img src="../assets/designer.png" alt="Team dev">
             <h3>Felipe</h3>
             <p>Graphic designer, he built this magnificent collection of nft. </p>
         </div>
        <div data-aos="fade-up" data-aos-duration="1500">
             <img src="../assets/dev.png" alt="Team dev">
             <h3>Lucas</h3>
             <p>Developer, he made the website and everything necessary for the mint.</p>
         </div>
        <div data-aos="fade-right" data-aos-duration="1500" >
             <img src="../assets/cm.png" alt="Team dev">
             <h3>Peete</h3>
             <p>The community manager. He and 9 other people manage the social media and the interaction with you. </p>
         </div>
     </div>
 </section>
</template>

<script>
export default {
  name: "Team",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@media screen and (max-width: 734px) {
  .team {
    grid-template-columns: 1fr !important;
  }
}

@import url("https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap");

section {
  width: 90%;
  margin: auto;
  padding-top: 100px;
}

.team {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  align-items: center;
  gap: 30px;
  height: 80%;
}

.team div {
  width: 100%;
  background-color: #fff;
}

.team div img {
  width: 100%;
  height: auto;
}

.team div h3 {
  font-family: Roboto;
  color: #000;
  text-align: center;
  padding: 10px;
}

.team div p {
  text-align: center;
  font-family: Roboto;
  color: #000;
  padding: 10px;
}
</style>