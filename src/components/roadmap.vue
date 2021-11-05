<template>
 <section>
    <div class="roadmap-title" >
        <h1>ROADMAP</h1>
    </div>
     <div class="roadmap" >
         <div data-aos="fade-up">
           <h1>15% Sold</h1>
           <p>15 item airdrop</p>
         </div>
         <div data-aos="fade-up">
           <h1>45% Sold</h1>
           <p>We will offer 2 floors to 45 owners and we will distribute 5000$ to the community through raffles, challenges, etc.. </p>
         </div>
         <div data-aos="fade-up">
          <h1>75% Sold</h1>
           <p>After 1 month, the follower with the highest level on discord = 10k</p>
         </div>
         <div data-aos="fade-up">
            <h1>100% Sold</h1>
            <p> You have all already played counter strike, halo, etc.. I miss it and I think you do too so we are already preparing a P2E game... We will inform you every time we make a progress. <strong> IT'S A BIG PROJECT !! </strong> </p>
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
}
.roadmap div p {
  margin-top: 20px;
  font-family: Roboto;
  text-align: center;
  font-style: italic;
}
</style>