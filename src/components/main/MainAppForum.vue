<script>

export default {
    name:'mainAppForum.vue'
}
</script>

<template>
    <main>
        <div class="my-grey">
            <div class="container">
                <div class="row justify-content-center">
                    <div class="col-6 ">
                        <p class="my-color-text text-center">
                            AVAD FORUM IS THE PLACE TO BE
                        </p>
                        <p class=" my-p text-center">
                            In quis lectus sed leo elementum faucibus in dapibus dictum.Nulla molestie tortor nec lectus venenatis, sed blandit dui finibus. dolor at, bibendum purus. Donec vehicula nec tortor ac finibus.    
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
        .my-grey{
            background-color: $background-grey;
            width: 100%;
            height: 200px;


            .my-p{
                color: #747474;
            }

            .my-color-text{
                margin-top: 4.5rem;
                color:#616161;
            }
        }
    }
</style>