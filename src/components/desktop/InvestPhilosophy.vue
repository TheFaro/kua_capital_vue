<template>
    <div class="invest-container">
        <div class="title">
            <h1>INVESTMENT PHILOSOPHY & PROCESS</h1>
        </div>
        <div class="sub-title">
            You must add value to yourself to be relevant.
        </div>

        <div class="items">
            <div class="item">
                <div class="item-image-container"><div class="item-image"></div></div>
                <div class="item-text">
                    We have removed the guess work with our systematic data driven proprietary models for top/down, bottom/up market research.
                </div>
            </div>
            <div class="item">
                <div class="item-image-container"><div class="item-image"></div></div>
                <div class="item-text">
                    Our portfolio consturction process emphasizes on wealth preservation through systematic risk quantification and management.
                </div>
            </div>
            <div class="item">
                <div class="item-image-container"><div class="item-image"></div></div>
                <div class="item-text">
                    We keep our investors fully informed monthly about the status of the market, expectation and mitigation measures, especially in the case of irrational market fear.
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default{
    name: "InvestmentPhilosophy"
}
</script>

<style scoped>
.invest-container{
    width: 100%;
    height: 550px;
    background-color: rgb(5, 56, 86);
}

h1 {
    position: relative;
    left: 10%;
    top: 60px;
    font-size: 33pt;
    text-align: left;
}

.sub-title{
    position:relative;
    left: -21.5%;
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
}

.item{
    margin: 12px;
    align-items: center;
}

.item-image-container{
    background-color: white;
    width: 140px;
    height: 140px;
    border-radius: 70px;
    align-items: center;
    margin: auto;
}

.item-image{
    background-color: white;
    background-image: url('../../assets/logo1.png');
    background-repeat: no-repeat;
    background-size: cover;
    width: 120px;
    height: 120px;
    border-radius: 60px;
    margin: auto;
    position: relative; top: 7%;
    vertical-align: 40px;
}

.item-text{
    background-color: white;
    padding: 12px;
    margin: 15px;
    border-radius: 20px; 
    color: rgb(5, 56, 86);
    font-size: 18pt;
}
</style>