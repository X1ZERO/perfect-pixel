<template>
    <div class="body-content">
        <div class="section-1">
            <div class="image-wrapper" >
                <div class="image-container">
                    <img id="person-1" src="~/assets/images/person-1.png"/>
                    <img id="plus-1" src="~/assets/images/plus-primary.svg"/>
                    <img id="plus-2" src="~/assets/images/plus-secondary.svg"/>
                    <img id="line-1" src="~/assets/images/path-45.svg"/>
                    <img id="line-2" src="~/assets/images/path-45.svg"/>
                </div>
            </div>
            <div class="content-wrapper">
                <div class="sub-wrapper">
                    <div class="blank-space">

                    </div>
                    <div class="content">
                        <div>
                            <h1 class="head-label">
                                ATHLETS
                            </h1>
                        </div>
                        <div>
                            <div class="bullet-wrapper">
                                <span class="num-bullet">01</span>
                                <h2 class="sub-head-label">CONNECTION</h2>
                            </div>
                        </div>
                        <div>
                            <div class="description-wrapper">
                                <p class="description-label">
                                    Connect with coaches directly, you can ping coaches to view profile.
                                </p>
                            </div>
                        </div>
                    </div>
                    
                </div>
                <div class="sub-wrapper">
                    <div class="blank-space">

                    </div>
                    <div class="content">
                        <div>
                            <div class="bullet-wrapper">
                                <span class="num-bullet">02</span>
                                <h2 class="sub-head-label">COLLABORATION</h2>
                            </div>
                        </div>
                        <div>
                            <div class="description-wrapper">
                                <p class="description-label">
                                    Work with other student athletes to increase visability. When you share and like other players videos it will increase your visability as a player. This is the team work aspect to Surface 1.
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="sub-wrapper">
                    <div class="blank-space">

                    </div>
                    <div class="content">
                        <div>
                            <div class="bullet-wrapper">
                                <span class="num-bullet">03</span>
                                <h2 class="sub-head-label">GROWTH</h2>
                            </div>
                        </div>
                        <div>
                            <div class="description-wrapper">
                                <p class="description-label">
                                    Resources and tools for you to get better as a student Athelte. Access to training classes, tutor sessions, etc
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="section-2">
            <div class="content-wrapper">
                <div class="sub-wrapper">
                    <div class="content">
                        <div>
                            <h1 class="head-label">
                                PLAYERS
                            </h1>
                        </div>
                        <div>
                            <div class="bullet-wrapper">
                                <span class="num-bullet">01</span>
                                <h2 class="sub-head-label">CONNECTION</h2>
                            </div>
                        </div>
                        <div>
                            <div class="description-wrapper">
                                <p class="description-label">
                                    Connect with talented athlete directly, you can watch their skills through video showreels directly from Surface 1.
                                </p>
                            </div>
                        </div>
                    </div>
                    <div class="blank-space">

                    </div>
                </div>
                <div class="sub-wrapper">
                    <div class="content">
                        <div>
                            <div class="bullet-wrapper">
                                <span class="num-bullet">02</span>
                                <h2 class="sub-head-label">COLLABORATION</h2>
                            </div>
                        </div>
                        <div>
                            <div class="description-wrapper">
                                <p class="description-label">
                                    Work with recruiter to increase your chances of finding talented athlete.
                                </p>
                            </div>
                        </div>
                    </div>
                    <div class="blank-space">

                    </div>
                </div>
                <div class="sub-wrapper">
                    <div class="content">
                        <div>
                            <div class="bullet-wrapper">
                                <span class="num-bullet">03</span>
                                <h2 class="sub-head-label">GROWTH</h2>
                            </div>
                        </div>
                        <div>
                            <div class="description-wrapper">
                                <p class="description-label">
                                    Save your time, recruit proper athlets for your team.
                                </p>
                            </div>
                        </div>
                    </div>
                    <div class="blank-space">

                    </div>
                </div>
            </div>
            <div class="image-wrapper" >
                <div class="image-container">
                    <img id="person-2" src="~/assets/images/person-2.png"/>
                    <img id="plus-1" src="~/assets/images/plus-primary.svg"/>
                    <img id="plus-2" src="~/assets/images/plus-secondary.svg"/>
                    <img id="plus-3" src="~/assets/images/plus-primary.svg"/>
                    <img id="line-1" src="~/assets/images/path-45.svg"/>
                    <img id="line-2" src="~/assets/images/path-45.svg"/>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>

<style lang="scss">
    body {
        margin: 0px;
    }

    .body-content {
        * {
            font-family: Roboto;
        }
        overflow-x: hidden;
        // LABEL ----------------------------------------------------------------
        .head-label {
            color: #E7E7E7;
            font-size: 90px;
            font-style: normal;
            font-weight: 400;
            line-height: normal;
        }
        .sub-head-label {
            color: #C2C2C2;            
            font-size: 36px;
            font-style: normal;
            font-weight: 400;
            line-height: normal;
            letter-spacing: 1.5px;
            margin: 0px;
        }
        .description-wrapper {
            .description-label {
                color: #000;
                font-style: normal;
                font-weight: 400;
                line-height: 28px; /* 140% */
            }
        }

        // BULLET ----------------------------------------------------------------
        .bullet-wrapper {
            display: flex;
            gap: 10px;
            .num-bullet {
                color: #000;
                font-size: 18px;
                font-style: normal;
                font-weight: 400;
                line-height: normal;
                letter-spacing: 1.5px;
                position: relative;
                align-self: start;
                margin-top: 5px;
                &::after {
                    content: "";
                    border-radius: 2.5px;
                    background: #603EBE;
                    width: 22px;
                    height: 5px;
                    position: absolute;
                    bottom: 0px;
                    left: 0px;
                    bottom: -8px;
                }
            }
        }
    }
    
    @media (min-width: 768px) and (max-width: 1199px) { // tablet
        // Sepecific Section Style --------------------------------------------------
        .description-label {
            font-size: 18px;
        }
        .section-1 {
            position: relative;
            .sub-wrapper {
                display: flex;
                .blank-space {
                    width: 37.9%;
                }
                .content {
                    display: flex;
                    flex-direction: column;
                    width: 62.1%;
                }
                &:first-child {
                    .head-label {
                        margin-top: 81px;
                        margin-bottom: 42px;
                    }
                    .description-label {
                        width: 457px;
                        margin-top: 21px;
                        margin-bottom: 30px;
                    }
                }
                &:nth-child(2) {
                    background: #F5F4F9;
                    padding: 30px 0px;
                    .description-label {
                        width: 446.195px;
                        margin-top: 21px;
                        margin-bottom: 0px;
                    }
                }
                &:last-child {
                    background: #5E3DB3;
                    padding: 30px 0px 58px;
                    .num-bullet {
                        &::after {
                            background: #FFF;
                        }
                    }
                    .description-label {
                        width: 446.195px;
                        color: #FFF;
                        margin-top: 21px;
                        margin-bottom: 0px;
                    }
                }
            }
             // Image Section
             .image-wrapper {
                position: absolute;
                top: 0;
                left: 0;
                width: 37.9%;
                height: 100%;
                .image-container {
                    position: absolute;
                    width: 498px;
                    top: 121px;
                    right: -46.3px;
                }
                img {
                    position: absolute;
                    &#person-1 {
                        width: 498px;
                        top: 0;
                        left: 0;
                        z-index: 1;
                    }
                    &#plus-1 {
                        top: -10px;
                        right: 271px;
                        width: 15px;
                        height: 15px;
                    }
                    &#plus-2 {
                        top: -19px;
                        right: 293px;
                        width: 15px;
                        height: 15px;
                    }
                    &#line-1 {
                        top: 18.98px;
                        right: 98.8px;
                        width: 209.292px;
                        height: 233.717px;
                    }
                    &#line-2 {
                        display: none;
                    }
                }
            }
        }
        
        .section-2 {
            position: relative;
            .sub-wrapper {
                display: flex;
                .blank-space {
                    width: 45.9%;
                }
                .content {
                    display: flex;
                    flex-direction: column;
                    /* width: 54.1%; */
                    max-width: 382.5px;
                    margin-left: auto;
                }
                &:first-child {
                    .head-label {
                        margin-top: 52px;
                        margin-bottom: 34px;
                    }
                    .description-label {
                        margin-top: 21px;
                        margin-bottom: 10px;                    
                        width: 432px;
                    }
                }
                &:nth-child(2) {
                    background: #F5F4F9;
                    padding: 51px 0px 65px;
                    .description-label {
                        margin-top: 21px;
                        margin-bottom: 0px;
                        width: 432px;
                    }
                }
                &:last-child {
                    background: #090C35;
                    padding: 44px 0px 72px;
                    .num-bullet {
                        color: #8F6BE8;
                        &::after {
                            background: #FFF;
                        }
                    }
                    .description-label {
                        color: #FFF;
                        margin-top: 21px;
                        margin-bottom: 0px;
                        width: 455px;
                    }
                }
            }
             // Image Section
            .image-wrapper {
                position: absolute;
                top: 0;
                right: 0;
                width: 45.9%;
                height: 100%;
                .image-container {
                    position: absolute;
                    width: 691px;
                    top: 33px;
                    left: -84px;
                }
                img {
                    position: absolute;
                    &#person-2 {
                        width: 691px;
                        top: 0;
                        left: 0;
                        z-index: 1;
                    }
                    &#plus-1 {
                        top: 72px;
                        left: 202px;
                        width: 15px;
                        height: 15px;
                    }
                    &#plus-2 {
                        top: 89px;
                        left: 224px;
                        width: 15px;
                        height: 15px;
                    }
                    &#plus-3 {
                        display: none;
                    }
                    &#line-1 {
                        top: 263.89px;
                        left: 159px;
                        width: 178.877px;
                        height: 207.224px;
                    }
                    &#line-2 {
                        display: none;
                    }
                }
            }
        }
    }
    @media (min-width: 1200px) { // desktop
        .description-wrapper {
            width: 713px;
            .description-label {
                font-size: 20px;
            }
        }
        // Sepecific Section Style --------------------------------------------------
        .section-1 {
            position: relative;
            .sub-wrapper {
                display: flex;
                .blank-space {
                    width: 52.5%;
                }
                .content {
                    display: flex;
                    flex-direction: column;
                    width: 47.5%;
                }
                &:first-child {
                    .head-label {
                        margin-top: 24px;
                        margin-bottom: 59px;
                    }
                    .description-label {
                        margin-top: 31px;
                        margin-bottom: 56px;
                    }
                }
                &:nth-child(2) {
                    background: #F5F4F9;
                    padding: 52px 0px 56px;
                    .description-label {
                        margin-top: 21px;
                        margin-bottom: 0px;
                    }
                }
                &:last-child {
                    background: #5E3DB3;
                    padding: 87px 0px 90px;
                    .num-bullet {
                        &::after {
                            background: #FFF;
                        }
                    }
                    .description-label {
                        color: #FFF;
                        margin-top: 21px;
                        margin-bottom: 0px;
                    }
                }
            }
             // Image Section
            .image-wrapper {
                position: absolute;
                top: 0;
                left: 0;
                width: 52.5%;
                height: 100%;
                .image-container {
                    position: absolute;
                    width: 678px;
                    top: 35px;
                    right: 155px;
                }
                img {
                    position: absolute;
                    &#person-1 {
                        width: 678px;
                        top: 0;
                        left: 0;
                    }
                    &#plus-1 {
                        display: none;
                    }
                    &#plus-2 {
                        display: none;
                    }
                    &#plus-3 {
                        display: none;
                    }
                    &#line-1 {
                        display: none;
                    }
                    &#line-2 {
                        display: none;
                    }
                }
            }
        }
        
        .section-2 {
            position: relative;
            .sub-wrapper {
                display: flex;
                .blank-space {
                    width: 45.9%;
                }
                .content {
                    display: flex;
                    flex-direction: column;
                    width: 54.1%;
                    max-width: 725px;
                    margin-left: auto;
                }
                &:first-child {
                    .head-label {
                        margin-top: 124px;
                        margin-bottom: 68px;
                    }
                    .description-label {
                        margin-top: 21px;
                        margin-bottom: 69px;
                        width: 571px;
                    }
                }
                &:nth-child(2) {
                    background: #F5F4F9;
                    padding: 52px 0px 102px;
                    .description-label {
                        margin-top: 21px;
                        margin-bottom: 0px;
                    }
                }
                &:last-child {
                    background: #090C35;
                    padding: 80px 0px 78px;
                    .num-bullet {
                        color: #8F6BE8;
                        &::after {
                            background: #FFF;
                        }
                    }
                    .description-label {
                        color: #FFF;
                        margin-top: 21px;
                        margin-bottom: 0px;
                    }
                }
            }
             // Image Section
            .image-wrapper {
                position: absolute;
                top: 0;
                right: 0;
                width: 52.5%;
                height: 100%;
                .image-container {
                    position: absolute;
                    width: 991px;
                    top: 0px;
                    //left: -125px;
                    left: -115px;
                }
                img {
                    position: absolute;
                    &#person-2 {
                        width: 991px;
                        top: 0;
                        left: 0;
                        z-index: 1;
                    }
                    &#plus-1 {
                        top: 131px;
                        left: 294px;
                        width: 15px;
                        height: 15px;
                    }
                    &#plus-2 {
                        top: 148px;
                        left: 316px;
                        width: 15px;
                        height: 15px;
                    }
                    &#plus-3 {
                        top: 401px;
                        right: 202px;
                        width: 15px;
                        height: 15px;
                    }
                    &#line-1 {
                        top: 457.84px;
                        left: 185.13px;
                        width: 262.516px;
                        height: 304.117px;
                    }
                    &#line-2 {
                        top: 81px;
                        right: 64.48px;
                        width: 265.625px;
                        height: 311.16px;
                    }
                }
            }
        }
    }
    
</style>