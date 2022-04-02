<template>
    <div class="returns-container">
        <h1>KUA CAPITAL STRATEGIST RETURNS</h1>
        <div class="sub-title">
            Opportunities come infrequently. When it rains gold, put out the bucket, not the thimble.
        </div>

        <div class="strategists-container">
            <div class="strategist">
                <div class="strategist-image"></div>
                <div class="strategist-description">
                    <span><i>DISTRESSED VALUE ASSETS</i></span>
                    <div class="exposure">
                        <span>EXPOSURE: 28%</span><br />
                        <span>RETURNS (YOY): 28%</span> 
                    </div>
                </div>
            </div>
            <div class="strategist">
                <div class="strategist-image"></div>
                <div class="cover"></div>
                <div class="strategist-description">
                    <span><i>EMERGING TRENDS PORTFOLIO</i></span>
                    <div class="exposure">
                        <span>EXPOSURE: 26%</span><br />
                        <span>RETURNS (YOY): 20%</span> 
                    </div>
                </div>
            </div>
            <div class="strategist">
                <div class="strategist-image"></div>
                <div class="strategist-description">
                    <span><i>DEFENSIVE INVESTING PORTFOLIO</i></span>
                    <div class="exposure">
                        <span>EXPOSURE: 10%</span><br />
                        <span>RETURNS (YOY): 13%</span> 
                    </div>
                </div>
            </div>
            <div class="strategist">
                <div class="strategist-image"></div>
                <div class="cover"></div>
                <div class="strategist-description">
                    <span><i>RISK PREMIUM PORTFOLIO</i></span>
                    <div class="exposure">
                        <span>EXPOSURE: 5%</span><br />
                        <span>RETURNS (YOY): 12.36%</span> 
                    </div>
                </div>
            </div>
            <div class="strategist">
                <div class="strategist-image"></div>
                <div class="strategist-description">
                    <span><i>INDUSTRIAL SECTOR ROTATION PORTFOLIO</i></span>
                    <div class="exposure">
                        <span>EXPOSURE: 5%</span><br />
                        <span>RETURNS (YOY): 7.53%</span> 
                    </div>
                </div>
            </div>
            <div class="strategist">
                <div class="strategist-image"></div>
                <div class="cover"></div>
                <div class="strategist-description">
                    <span><i>ALL WEATHER PORTFOLIO</i></span>
                    <div class="exposure">
                        <span>EXPOSURE: 10%</span><br />
                        <span>RETURNS (YOY): 2.05%</span> 
                    </div>
                </div>
            </div>
            <div class="strategist">
                <div class="strategist-image"></div>
                <div class="strategist-description">
                    <span><i>MULTIPLE CURRENCIES PORTFOLIO</i></span>
                    <div class="exposure">
                        <span>EXPOSURE: 16%</span><br />
                        <span>RETURNS (YOY): 11%</span> 
                    </div>
                </div>
            </div>
        </div>

        <div class="learn-more-button">LEARN MORE</div>
    </div>
</template>

<script>
export default {
    name: "StrategistReturns"
}

</script>

<style scoped>

.returns-container{
    background-color: rgb(42, 152, 213);
    width: 100%;
    height: 910px;
}

h1 {
    position: relative;
    text-align: left;
    left: 10%;
    top: 60px;
    font-size: 33pt;
}

.sub-title{
    position:relative;
    left: -5.5%;
    top: 60px;
    color: rgb(42, 152, 213);
    background-color: white;
    display: inline-block;      
    font-size: 25pt;
    padding: 12px;
    font-weight: thin;
    align-items: center;
}

.strategists-container{
    width: 100%;
    position: relative;
    top: 82px;
    display: flex;
}

.strategist{
    width: 15%;
    height: 580px;
    background-color: white; 
    margin: 7px;   
}

.strategist:nth-child(1) .strategist-image{
    background-image: url("../../assets/distressed_value.jpg");
    width: 100%;
    height: 360px;
    background-repeat: no-repeat;
    background-size: cover;
}

.strategist:nth-child(1) .strategist-description{
    text-align: left;
    padding: 20px;
}

.strategist:nth-child(2) .strategist-image{
    background-image: url("../../assets/emerging_trends.jpg");
    width: 100%;
    height: 580px;
    background-repeat: no-repeat;
    background-size: cover;
}

.strategist:nth-child(2) .cover{
    background-color: rgba(5, 56, 86, 0.8);
    width: 100%;
    height: 580px;
    position: relative;
    top: -580px;
}


.strategist:nth-child(2) .strategist-description{
    text-align: left;
    padding: 20px;
    position: relative;
    top: -800px;
    color: white;
}

.strategist:nth-child(2) .strategist-description span{
    color: white;
}

.strategist:nth-child(3) .strategist-image{ 
    background-image:url("../../assets/defensive_investing.jpg"); 
    width: 100%; 
    height: 360px;
    background-repeat: no-repeat; 
    background-size: cover; 
}

.strategist:nth-child(3) .strategist-description{
    text-align: left;
    padding: 20px;
}

.strategist:nth-child(4) .strategist-image{
    background-image:url("../../assets/risk_premium.jpg"); 
    width: 100%;
    height: 580px; 
    background-repeat: no-repeat; 
    background-size: cover; 
}

.strategist:nth-child(4) .cover{
    background-color: rgba(5, 56, 86, 0.8);
    width: 100%;
    height: 580px;
    position: relative;
    top: -580px;
}


.strategist:nth-child(4) .strategist-description{
    text-align: left;
    padding: 20px;
    position: relative;
    top: -800px;
    color: white;
}

.strategist:nth-child(4) .strategist-description span{ color: white; }


.strategist:nth-child(5) .strategist-image{
    background-image:url("../../assets/industrial_sector.jpg"); 
    width: 100%;
    height: 360px; 
    background-repeat: no-repeat; 
    background-size: cover; 
}

.strategist:nth-child(5) .strategist-description{
    text-align: left;
    padding: 20px;
}

.strategist:nth-child(6) .strategist-image{
    background-image:url("../../assets/all_weather.jpg"); 
    width: 100%;
    height: 580px; 
    background-repeat: no-repeat; 
    background-size: cover; 
}

.strategist:nth-child(6) .cover{
    background-color: rgba(5, 56, 86, 0.8);
    width: 100%;
    height: 580px;
    position: relative;
    top: -580px;
}


.strategist:nth-child(6) .strategist-description{
    text-align: left;
    padding: 20px;
    position: relative;
    top: -800px;
    color: white;
}

.strategist:nth-child(6) .strategist-description span{ color: white; }


.strategist:nth-child(7) .strategist-image{
    background-image:url("../../assets/multiple_currencies.jpg"); 
    width: 100%;
    height: 360px; 
    background-repeat: no-repeat; 
    background-size: cover; 
}

.strategist:nth-child(7) .strategist-description{
    text-align: left;
    padding: 20px;
}


span{
    font-size: 17pt;
    font-weight: bold;
    color: rgb(5, 56, 86);
}

.exposure{
    margin-top: 15px;
    margin-left: 5px;
}

.exposure > span{
    font-size: 13pt; 
    font-weight: 500;
}

.learn-more-button{
    background-color: white;
    position: relative;
    top: 135px;
    right: -40%;
    display: inline;
    padding: 25px;  
    border-radius: 60px;
    font-size: 25pt;
    font-weight: 600;
    color:rgb(5, 56, 86); 
    text-align: center;
    margin-bottom: 20px;
    border: none;
}

.learn-more-button:hover{
    box-shadow: 0px 0px 25px 12px rgb(5, 56, 86);
    background-color: rgba(5, 56, 86,0.9);
    color: white;
    border: none;
}
</style>