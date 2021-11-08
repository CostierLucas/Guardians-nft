<template>
 <section>
     <div class="collec-bloc" >
         <div>
             <div data-aos-duration="1500" data-aos="fade-left" class="collec-img">
                 <img src="../assets/group.png" alt="bot guardians">
             </div>
         </div>
         <div data-aos="fade-right" data-aos-duration="1500" class="collec-text">
            <h1>Welcome to the soliverse</h1>
            <br>
            <p>
                 The Guardians of the Soliverse is a collection of <span> 8,888 </span> uniquely generated 3D Guardians protecting the Solana Universe from dreadful mercenaries. Our foremost commitment is delivering value to our community members. In doing so, we have dedicated countless hours to ensuring the artwork and traits are top tier. In addition, there are unique benefits for being a member of the guardians' community.
            </p>
         </div>
     </div>
 </section>
</template>

<script>
export default {
  name: "Collections",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@media screen and (max-width: 734px) {
  .collec-bloc {
    grid-template-columns: 1fr !important;
    grid-auto-rows: auto;
    height: auto !important;
    gap: 0px !important;
  }

  .collec-img img {
    width: 100% !important;
    margin: auto;
    text-align: center;
  }
}

section {
  width: 90%;
  margin: auto;
  height: 600px;
}

.collec-bloc {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  align-items: center;
  height: 100%;
  gap: 30px;
}

.collec-text {
  background: #fff;
  border: 5px solid #0c427c;
  padding: 30px;
}

.collec-text h1 {
  text-transform: uppercase;
  font-family: Orbitron !important;
}

.collec-bloc p,
.collec-bloc h1 {
  font-family: Roboto;
  color: black;
}

.collec-img img {
  width: 500px;
  height: auto;
}

.collec-text {
  margin-top: 60px;
  text-align: center;
}

.collec-text p {
  text-align: justify;
}

.collec-text p span {
  font-weight: bold;
}

.collec-text p,
.collec-text h1 {
  color: black;
}
</style>
