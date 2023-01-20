
<script>
export default {
    
}
</script>
<template>
    <main>
        <div class="pre">
            <div class="container mt-5">
                <div class="row justify-content-center">
                    <div class="col-4">
                        <p class="text-center mb-bottom">
                            <strong class="text-white">
                                READ OUR BLOG
                            </strong>
                        </p>
                    </div>
                </div>
            </div>
        </div>
        <div class="backg">
            <div class="container">
            <div class="row justify-content-center">
                <div class="col-4 mt-5">
                    <p class="text-center mini-title">
                        PHASELLUS EGET METUS
                    </p>
                    <h3 class="text-center">
                        <strong>
                            Forum Sections
                        </strong>
                        <div class="bord"></div>
                    </h3>
                </div>
            </div>
            <div class="row justify-content-center  ">
                    <div class="col-3 position">
                        <div class="white">
                            <div class="circle mt-5 text-center fs-1">
                            <i class= "file fas fa-file my-file"></i>
                            </div>
                            <p class="text-center mt-3">
                                <strong>
                                    News & Community
                                </strong> 
                            </p>
                        </div>
                    </div>
                    <div class="col-3">
                        <div class="white">
                            <div class="circle mt-5 text-center fs-1">
                                <i class=" file fab fa-apple"></i>
                            </div>
                            <p class="text-center mt-3">
                                <strong>
                                    Apple Forum
                                </strong> 
                            </p>
                        </div>
                    </div>
                    <div class="col-3">
                        <div class="white">
                            <div class="circle mt-5 text-center fs-1">
                                <i class='file fab fa-microsoft'></i>
                            </div>
                            <p class="text-center mt-5">
                                <strong>
                                    Microsoft Forum
                                </strong> 
                            </p>
                        </div>
                    </div>
                    <div class="col-3">
                        <div class="white">
                            <div class="circle mt-5 text-center fs-1">
                                <i class='file fab fa-android'></i>
                            </div>
                            <p class="text-center mt-3">
                                <strong>
                                    Android Forum
                                </strong> 
                            </p>
                        </div>
                    </div>
                    <div class="col-3 pt-5">
                        <div class="white">
                            <div class="circle mt-5 text-center fs-1">
                            <i class="file fas fa-coffee"></i>
                            </div>
                            <p class="text-center mt-3">
                                <strong>
                                    General Discussion
                                </strong> 
                            </p>
                        </div>
                    </div>

                    <div class="col-3 pt-5">
                        <div class="white">
                            <div class="circle mt-5 text-center fs-1">
                                <i class="file fa-solid fa-cubes"></i>
                            </div>
                            <p class="text-center mt-3">
                                <strong>
                                    App & Software
                                </strong> 
                            </p>
                        </div>
                    </div>

                    <div class="col-3 pt-5">
                        <div class="white">
                            <div class="circle mt-5 text-center fs-1">
                                <i class="file fa-solid fa-laptop"></i>
                            </div>
                            <p class="text-center mt-3">
                                <strong>
                                    Gadgets & Stuff
                                </strong> 
                            </p>
                        </div>
                    </div>

                    <div class="col-3 pt-5">
                        <div class="white">
                            <div class="circle mt-5 text-center fs-1">
                                <i class="file fa-solid fa-wrench"></i>
                            </div>
                            <p class="text-center mt-3">
                                <strong>
                                    Tutorials & Guides
                                </strong> 
                            </p>
                        </div>
                    </div>
            </div>
            
        </div>
        </div>
        <div class="pre">
            <div class="container mt-5">
                <div class="row justify-content-center">
                    <div class="col-4">
                        <p class="text-center mb-bottom">
                            <strong class="text-white">
                                GO TO OUR FORM <i class="fa-solid fa-arrow-right"></i>
                            </strong>
                        </p>
                    </div>
                </div>
            </div>
        </div>
        
    </main>
</template>

<style lang="scss">
    @use '../../Style/partials/variables' as *;
    main{
        font-family: 'Fira Sans', sans-serif;
        .pre{
        background-color: black;
        height: 100px;
    }
    .mb-bottom{
        margin-top: 10%;
    }
    .backg{
        background-color :#f2f2f2 ;
    }
    .mini-title{
        font-size: .7rem;
        
    }
    .bord{
        border-bottom: 2px solid $color-orange;
        width: 70px;
        margin-left: 10rem;
        margin-top: 1.5rem;
    }
    .white{
        width: 100%;
        height: 250px;
        background-color: $color-white;
        border-top: 2px solid $header-color ;
    }
    .circle{
        width: 100px;
        height: 100px;
        border-radius: 50%;
        background-color: $color-orange;
        margin: 0 auto;

    }
    .file{
        margin-top: 1.6rem;
        color: white;
    }
    .position{
        margin: 0 auto;
    }
    }

</style>