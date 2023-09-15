<template>
    <div class="body-content">
        <div class="section-1">
            <div class="image-wrapper" >
                <img id="person-1" src="~/assets/images/person-1.png"/>
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
                                    Work with other student athletes to increase visability. When you share and like other players videos it will increase your visability as a player. This is the team work aspect to Surface 1.
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
                                    Resources and tools for you to get better as a student Athelte. Access to training classes, tutor sessions, etc
                                </p>
                            </div>
                        </div>
                    </div>
                    <div class="blank-space">

                    </div>
                </div>
            </div>
            <div class="image-wrapper" >
                <!-- <img id="person-2" src="~/assets/images/person-2.png"/> -->
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
            max-width: 717px;
            .description-label {
                color: #000;
                font-size: 20px;
                font-style: normal;
                font-weight: 400;
                line-height: 28px; /* 140% */
            }
        }

        // CONTENT WRAPPER --------------------------------------------------------------
        .content-wrapper {
            .sub-wrapper {
                display: flex;
                &:first-child {
                    .head-label {
                        margin-top: 24px;
                        margin-bottom: 59px;
                    }
                }
                .blank-space {
                    width: 52.5%;
                }
                .content {
                    display: flex;
                    flex-direction: column;
                    width: 47.5%;
                }
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

        // Sepecific Section Style --------------------------------------------------
        .section-1 {
            position: relative;
            .sub-wrapper {
                &:first-child {
                    .description-label {
                        margin-top: 31px;
                        margin-bottom: 56px;
                    }
                }
                &:nth-child(2) {
                    background: #F5F4F9;
                    padding: 53px 0px 56px;
                    .description-label {
                        margin-top: 21px;
                        margin-bottom: 0px;
                    }
                }
                &:last-child {
                    background: #5E3DB3;
                    padding: 80px 0px 98px;
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
                img {
                    &#person-1 {
                        width: 678px;
                        position: absolute;
                        top: 35px;
                        right: 155px;
                    }
                }
            }
        }
        
        .section-2 {
            position: relative;
            .sub-wrapper {
                &:first-child {
                    .description-label {
                        margin-top: 31px;
                        margin-bottom: 56px;
                    }
                }
                &:nth-child(2) {
                    background: #F5F4F9;
                    padding: 53px 0px 56px;
                    .description-label {
                        margin-top: 21px;
                        margin-bottom: 0px;
                    }
                }
                &:last-child {
                    background: #5E3DB3;
                    padding: 80px 0px 98px;
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
                right: 0;
                width: 52.5%;
                img {
                    &#person-1 {
                        width: 678px;
                        position: absolute;
                        top: 35px;
                        right: 155px;
                    }
                }
            }
        }
    }
    
    @media (min-width: 768px) { // tablet
    }
    @media (min-width: 1200px) { // desktop
        
    }
    
</style>