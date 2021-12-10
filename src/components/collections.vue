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
                The Guardians of the Soliverse is a collection of <span> 3,333 </span> uniquely generated 3D Guardians protecting the Solana Universe from dreadful mercenaries. Our foremost commitment is delivering value to our community members. In doing so, we have dedicated countless hours to ensuring the artwork and traits are top tier. In addition, there are unique benefits for being a member of the guardians' community.
            </p>
         </div>
     </div>
 </section>
  <section>
     <div class="collec-bloc" >
        <div data-aos="fade-right" data-aos-duration="1500" class="collec-text bloc-sol">
            <h1>Delivering Value to Believers	</h1>
            <br>
            <p>
              Guardians' holders will have access to an exclusive Metaverse on the Solana network, airdrops, a unique social club, collaborations, and other valuable benefits. In addition to delivering value to our community, one of our core values is to enrich the entire Solana community. For this reason, 10% of the total funds from mint would be used to sweep the floors on Solana NFT projects voted on by our community.
            </p>
         </div>
         <div class="img-sol" >
             <div data-aos-duration="1500" data-aos="fade-left" class="collec-img">
                 <img src="../assets/sol.jpeg" alt="bot guardians">
             </div>
         </div>
     </div>
 </section>
   <section>
     <div class="collec-bloc" >
        <div>
             <div data-aos-duration="1500" data-aos="fade-left" class="collec-img">
                 <img src="../assets/universe.jpg" alt="bot guardians">
             </div>
         </div>
        <div data-aos="fade-right" data-aos-duration="1500" class="collec-text">
            <h1>The Soliverse</h1>
            <br>
            <p>
              The Soliverse is a Virtual Solana Universe that would be made available after mint, where guardians and mercs could meet each other, hang out and chill. In the Soliverse, there will be exclusive giveaways, game nights with prizes, a tight-knit community, quality Crypto and NFT discussion, community events, and more exclusive benefits. Soliverse membership protocol will be announced. Future metaversal integration of the Guardians Gallery and voting from the Guardians DAO are part of the plan and will be announced shortly.
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

  .bloc-sol{
  order: 2 !important;
  }

  .img-sol{
    margin-left: 0px !important;
    order: 1 !important;
  }
}

section {
  width: 90%;
  margin: auto;
  margin-top: 100px;
  margin-bottom: 100px;
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

.collec-img{
  margin: auto;
}

.collec-img img {
  width: 500px;
  margin-top: 50px;
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

.collec-text h1{
  color: #0c427c;
}

.collec-text p{
  color: black;
}

.bloc-sol{
  order: 1;
}

.img-sol{
  order: 2;
  margin-left: 100px;
}

</style>
