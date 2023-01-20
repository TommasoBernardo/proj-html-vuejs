
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
        <div class="container-fluid backg">
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
        height: 600px;
    }
    .mini-title{
        font-size: .7rem;
        
    }
    .bord{
        border-bottom: 2px solid $color-orange;
        width: 70px;
        margin-left: 13rem;
        margin-top: 1.5rem;
    }
    }

</style>