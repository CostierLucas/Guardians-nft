<template>
 <section>
    <div class="roadmap-title" >
        <h1>ROADMAP</h1>
    </div>
     <div class="roadmap" >
         <div data-aos="fade-up">
           <h1>01 - Pre-launch</h1>
           <p>
             Secure secondary market listings.
            <br>
            Secure howrare.is.
            <br>
            Robust multi-channel marketing campaign.
            <br>
            Team AMAs.
            <br>
            Create honorary Guardians for legends in the Solana ecosystem.
           </p>
         </div>
         <div data-aos="fade-up">
           <h1>02 – Ready to Rumble</h1>
           <p>
             Mint 8,888 Guardians.
             <br>
             Guardian Gallery Launch.
             <br>
             Sweep floor on community voted project.
             <br>
             Creation of Community DAO wallet.
             <br>
             Airdrop token for buyers.
          </p>
         </div>
         <div data-aos="fade-up">
          <h1>03 – Locked & Loaded</h1>
           <p>
             Airdrop 8,888 Mercenaries to Guardian holders.
          </p>
         </div>
         <div data-aos="fade-up">
            <h1>04 - The fight continues</h1>
            <p>
              Game Play to Earn , Guardians vs Mercenaries 👀
            </p>
         </div>
     </div>
     <div>
        <h2>
          We only promise things we can do, everything you read above will be done. #GuardianMentality  
        </h2>
     </div>
 </section>
</template>

<script>
export default {
  name: "Roadmap",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@media screen and (max-width: 734px) {
  section {
    width: 90% !important;
  }
}

section {
  width: 60%;
  margin: auto;
}

.roadmap-title {
  margin: auto;
}

.roadmap-title h1 {
  color: #fff;
  font-family: "Orbitron", sans-serif;
  text-align: center;
  font-size: 30px;
  margin-bottom: 30px;
}

h2 {
  color: #fff;
  font-family: Roboto;
  text-align: center;
  margin-top: 20px;
  
}

.roadmap {
  display: grid;
  grid-template-columns: 1fr;
  gap: 20px;
  height: 100%;
  align-items: center;
}

.roadmap div {
  background: #fff;
  border-radius: 10px;
  padding: 20px;
}

.roadmap div h1 {
  font-family: Roboto;
  text-align: center;
  color: #0c427c;
}
.roadmap div p {
  margin-top: 20px;
  font-family: Roboto;
  text-align: center;
  font-style: italic;
}
</style>