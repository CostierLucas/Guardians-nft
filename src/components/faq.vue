<template>
 <section>
    <h1>FAQ</h1>
    <div>
      <div class="accordion">
        <div class="contentBx">
          <div class="label"><h3> How much does a guardian cost to mint ? </h3></div>
          <div class="content">
            <p>0.6 SOL presale and 0.9 SOL official mint </p>
          </div>
        </div>
      </div>
      <div class="accordion">
        <div class="contentBx">
          <div class="label"><h3> How many guardians can I mint during initial sale? </h3> </div>
          <div class="content">
            <p>One per transaction.</p>
          </div>
        </div>
      </div>
      <div class="accordion">
        <div class="contentBx">
          <div class="label"><h3>When did collection launch ? </h3></div>
          <div class="content">
            <p>The guardians of the soliverse are coming soon...</p>
          </div>
        </div>
      </div>
      <div class="accordion">
        <div class="contentBx">
          <div class="label"> <h3>When will my guardian be revealed ?</h3></div>
          <div class="content">
            <p>It would take 1 minute after mint.</p>
          </div>
        </div>
      </div>
      <div class="accordion">
        <div class="contentBx">
          <div class="label"> <h3> What about rarity ?</h3></div>
          <div class="content">
            <p>It’s easy, we will give you our rarity ranking, there over 2 million features and only 8888 guardians. Each one is rare but there are most rare features.</p>
          </div>
        </div>
      </div>
    </div>
    <div class="accordion">
        <div class="contentBx">
          <div class="label"> <h3>Which wallets are supported ?</h3></div>
          <div class="content">
            <p>- Phantom, Slope, Solflare and Sollet.</p>
          </div>
        </div>
      </div> 
    <div class="accordion">
        <div class="contentBx">
          <div class="label"> <h3>What if I have a question that hasn’t been answered here ? </h3></div>
          <div class="content">
            <p>Feel free to ask any of our Discord Moderators.</p>
          </div>
        </div>
      </div>
 </section>
</template>

<script>
export default {
  name: "faq",
  mounted() {
    const accordion = document.getElementsByClassName("contentBx");
    var i;
    for (i = 0; i < accordion.length; i++) {
      accordion[i].addEventListener("click", function () {
        this.classList.toggle("active");
      });
    }
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
section {
  margin-top: 100px;
}

h1 {
  font-family: Orbitron;
  color: #fff;
  text-align: center;
  margin-bottom: 30px;
}

.accordion {
  max-width: 800px;
  margin: auto;
}

.accordion .contentBx {
  position: relative;
  margin: 10px 20px;
}

.accordion .contentBx .label {
  position: relative;
  padding: 10px;
  background: #fff;
  font-family: Roboto;
  color: #000;
  cursor: pointer;
}

.accordion .contentBx .label::before {
  content: "+";
  position: absolute;
  top: 50%;
  right: 2%;
  transform: translateY(-50%);
  font-size: 1.5em;
}

.accordion .contentBx.active .label::before {
  content: "-";
}

.accordion .contentBx .content {
  position: relative;
  background: #fff;
  height: 0;
  overflow: hidden;
  transition: 0.5s;
  overflow-y: auto;
}

.accordion .contentBx.active .content {
  height: 80px;
  padding: 10px;
  font-family: Roboto;
}
</style>
