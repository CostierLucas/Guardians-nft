<template>
 <section>
     <div class="collec-bloc" >
         <div>
             <div data-aos-duration="1500" data-aos="fade-left" class="collec-img">
                 <img src="../assets/group.png" alt="bot guardians">
             </div>
         </div>
         <div data-aos="fade-right" data-aos-duration="1500" class="collec-text">
            <h1>Who are they ?</h1>
            <br>
            <p>
                 The guardians of the universe are robots that travel through a world called 
                 "blockchain" in order to conquer the universe. They are <span> 8,888 </span> and each of them is unique.
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
@import url("https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Orbitron:wght@400;500;700&display=swap");

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
  margin-top: 100px;
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
