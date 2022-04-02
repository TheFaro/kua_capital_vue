<template>
  <div class="team-container">
    <div class="title">
      <h1>OUR TEAM</h1>
    </div>
    <div class="sub-title">Driven by the pursuit of gradual growth.</div>

    <div class="items">
      <div class="item">
        <div class="item-image samkeliso"></div>
        <div class="item-text-container">
            <div class="item-text name">Samkeliso M. Dlamini    </div>
            <div class="item-text position">Founder and CEO, Investment Strategist</div>
        </div>
      </div>
      <div class="item">
        <div class="item-image likhanyiso"></div>
        <div class="item-text-container">
            <div class="item-text name">Likhanyiso S. Dlamini</div>
            <div class="item-text position">Hedge Fund Risk Manager</div>
        </div>
      </div>
      <div class="item">
        <div class="item-image fanele"></div>
        <div class="item-text-container">
            <div class="item-text name">Fanelesibonge P. Malaza</div>
            <div class="item-text position">Chief Technology Officer</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "OurTeam",
};
</script>

<style scoped>

.team-container{
    width: 100%;
    height: 440px;
    background-color: white;
}

h1{
    text-align: left;
    position: relative;
    left: 10%;
    top: 60px;
    font-size: 33pt;
    color: rgb(42, 152, 213);
}

.sub-title{
    position:relative;
    left: -24%;
    text-align: left;
    top: 70px;
    background-color: rgb(42, 152, 213);
    color: white;
    display: inline;    
    padding: 12px;
    font-size: 25pt;
    font-weight: thin;
}

.items{
    display: flex;
    justify-content: center;
    position: relative;
    top: 120px;
    width: 80%;
    margin: auto;
}

.item{
    display: flex;
    margin: 30px;
    text-align: left;
    align-items: center;
}

.item-image{
    border: #ED1B5B 0.5px solid;
    border-radius: 60px;
    width: 120px;
    height: 120px;
    background-size: cover;
    background-repeat: no-repeat;
}

.samkeliso{
    background-image: url('../../assets/samkeliso.png');
}

.likhanyiso{
    background-image: url('../../assets/user.png');
}

.fanele{
    background-image: url('../../assets/fanele.jpg');
}

.item-text-container{
    margin: 12px;
    width: 70%;
}

.name{
    color: rgb(5, 56, 86);
    font-size: 18pt;
}

.position{
    color: rgb(47, 151, 211);
    font-size: 18pt;
}
</style>