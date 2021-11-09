<template>
  <section>
      <div class="future-title" >
          <h1>The future</h1>
      </div>
      <div class="future-bloc" >
        <div>
            <h2>Guardian DAO and Community Wallet</h2>
            <p> Holding any Guardian will allow owners access to the DAO, verified via Grape Protocol. The DAO will be able to vote on future project decisions, such as donations, metaverse partnerships, and the use of the Community Wallet. 10% of the mint sales and 10% of all collected royalties will go directly into the community wallet (including extra contributions from the team if needed).</p>
        </div>
        <div>
            <h2>Guardian Gallery</h2>
            <p>
              The Guardian Gallery will allow anyone to view and filter all Guardians of the Soliverse to find your favourite traits and combinations. The Guardians Gallery will also feature a weekly community showcase of our favourite Solana NFT art pieces. In the future, we'll have metaversal integration (the Soliverse) of the Guardian Gallery.
            </p>
        </div>
        <div>
            <h2>The Mercs are coming !</h2>
            <p>The Mercenaries are coming, and it's going to be one hell of a fierce battle. After mint, the team will airdrop 8,888 uniquely generated Mercenaries(1 per Guardian) to Guardian holders. </p>
        </div>
      </div>
  </section>
</template>

<script>
export default {
  name: "Futur",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
 section {
  margin: auto;
  margin-top: 60px;
}

h2{
  font-family: Roboto;
  color: #0c427c;
}

.future-title h1 {
    color: #fff;
    font-family: "Orbitron", sans-serif;
    text-align: center;
    font-size: 30px;
    margin-bottom: 30px;
}

.future-bloc{
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
  height: 100%;
}

.future-bloc div{
  width: 100%;
  background-color: #fff;
  height: 100%;
  text-align: center;
  padding: 20px;
}

.future-bloc div p {
    font-family: Roboto;
    text-align: center;
    text-align: justify;
    margin-top: 50px;
}

@media screen and (max-width: 734px){
  .future-bloc{
  grid-template-columns:  1fr;
  margin-left: 10px;
  margin-right: 10px;
}
}

</style>
