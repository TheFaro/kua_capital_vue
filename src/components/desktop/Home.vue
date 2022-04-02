<template>
    <div class="background-div">
        <div class="background-banner"></div>
        <div class="logo-menu-container">
            <div class="logo-container"><div class="logo"></div></div>
        </div>

        <div class="incoporated-container">
            <div class="alternating-texts">
                <div class="nametag">Kua Capital is a data driven investment hedge fund. We employ proprietary models to capture returns.</div>
                <div class="nametag">Our legacy investment strategies are non correlated and capitalize on Macro themes, Volatility, Distressed Assets, Risk Premium, Sector Rotation, Value and Growth.</div>
                <p class="nametag">Our mission is to protect wealth and a gradual organic of assets, leveraging compound interest.</p>
                <p class="nametag">Our Foundation is INTEGRITY<br />Our Strength is our PEOPLE<br />Our Style is TEAMWORK<br />Our Goal is EXCELLENCE.</p>
                <p class="nametag">We have skin in the game. We own a larger percentage of all the portfolio's.</p>
            </div>
            <div class="incoporated-text">
                <span>Incoporated in ESwatini but with footprints in Africa and globally, at Kua Capital our core market approach is systematic, with a business owner mindset, with zero tolerance to stock price addiction.</span>
            </div>
        </div>
    </div>
</template>

<script>

export default{
    name: "HomeView",
};
</script>

<style scroped>

.background-div{
    height: 1268px;
}

.background-banner{
    width: 100%;
    height: 1268px;
    background-image: url("../../assets/banner.png");
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
}

.logo-container{
    color: black;
    background-color: rgb(42, 152, 213);
    width: 400px;
    hegith: 120px;
    position: absolute;
    top: 2%;
}

.logo{
    background-size: cover;
    background-image: url('../../assets/banner_logo.png');
    background-repeat: no-repeat; 
    height: 120px;
    width: 520px;
    transform: scale(0.6);
    position: relative;
    left: -15%;
}

.incoporated-container{
    width: 100%;
    position: absolute;
    top: 50%;
    display: flex;
    align-items: center;
}

.incoporated-text{
    width: 32%; 
    background-color: rgb(5, 56, 86);
    background-size: cover;
    font-size: 30pt;
    font-weight: 500;
    align-items: center;
    display: flex;
    justify-content: center;
    position: absolute;
    right: 0;
    padding: 18px;
}

.alternating-texts{
    position: absolute;
    left: 0;
    display: flex;
    align-items: center;
}

.nametag{
    width: 220px;
    height: 200px;
    display: flex;
    margin: 3px;
    background-color: grey;
    font-size: 15pt;
    font-weight: 400;
    align-items: center;
    padding: 12px;
}

@keyframes fade{
    0%, 50%{
        opacity: 0;
    }

    100%{
        opacity: 1;
    }
}
</style>