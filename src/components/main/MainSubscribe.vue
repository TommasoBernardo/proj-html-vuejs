
<script>
export default {
    name: 'MainSubscribe',
}
</script>

<template>
    <main>
        <div class="bk-ground">
            <div class="container">
                <div class="row justify-content-center">
                    <div class="col-6 margin-subscribe text-center">
                        <h3 class="center text-white">
                            <strong>Hey! Join to our Community</strong>
                        </h3>
                        <p class="text-center text-white">
                            Nulla molestie tortor nec lectus venenatis, sed blandit dui finibus. Curabitur feugiat vulputate purus ipsums dolores ficilis uns etra. 
                        </p>
                        <button class="text-center text-white button-azull">
                            <strong>SIGN UP <i class="fa-solid fa-greater-than"></i></strong>
                        </button>
                    </div>
                </div>
            </div>
        </div>
        <div class="bg-gray">
            <div class="container">
                <div class="row justify-content-center">
                    <div class="col-6 ">
                        <h3 class="text-center mt-5 mb-5">Subscribe to our Newsletter</h3>
                        <div class="text-center my-mg">
                            <input class="my-form" type="email" placeholder="insert your email">
                            <button class="button-azull">
                                SEND
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </main>
</template>

<style lang="scss">
@use '../../Style/general.scss' as *; 
main{
    font-family: 'Fira Sans', sans-serif;
    .bk-ground{
        background-image: url(../../assets/img/join_now_cta_bg.jpg);
        background-size: contain;
        height: 617px;
        width: 100%;
    }
    .margin-subscribe{
        margin-top: 15rem;
    }

    .center{
        margin-left: 3%;
        font-size: 3rem;
    }
    .button-azull{
        background-color: #27aabe;
        border: none;
        width: 150px;
        height: 40px;
    }
    .bg-gray{
        background-color: #f2f2f2;
        width: 100%;
        height: 200px;
    }
    .my-form{
        width: 300px;
        margin-right: 40px;
    }
}
</style>