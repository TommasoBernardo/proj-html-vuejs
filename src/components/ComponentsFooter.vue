
<script>
export default {
    name: 'ComponentsFooter'
}
</script>

<template lang="">
    <footer>
        <div class="container mb-5">
            <div class="row">
                <div class="col-3">
                    <h4 class="mb-3 mt-5 "><strong>AVADA TECH FORMUM</strong></h4>
                    <p class="color-g">
                        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Asperiores, perferendis! Earum, porro, itaque aliquid velit iusto nobis rem esse ut asperiores quos ipsa accusamus fugit?
                    </p>
                </div>
                <div class="col-3">
                    <h4 class="mb-3 mt-5 "><strong>POPULAR TOPICS</strong></h4>
                    <ul>
                        <li><i class="fa-solid fa-greater-than"></i> Lorem, ipsum dolor sit amet consectetur adipisicing. <hr></li>
                        <li><i class="fa-solid fa-greater-than"></i> Lorem ipsum dolor, sit amet consectetur adipisicing. <hr></li>
                        <li><i class="fa-solid fa-greater-than"></i> Lorem ipsum dolor sit amet consectetur adipisicing. <hr></li>
                        <li><i class="fa-solid fa-greater-than"></i> Lorem ipsum dolor sit amet consectetur adipisicing. <hr></li>
                    </ul>
                </div>
                <div class="col-3">
                    <h4 class="mb-3 mt-5 "><strong>RECENT TOPICS</strong></h4>
                    <ul>
                        <li><i class="fa-solid fa-greater-than"></i> Lorem, ipsum dolor sit amet consectetur adipisicing. <hr></li>
                        <li><i class="fa-solid fa-greater-than"></i> Lorem ipsum dolor, sit amet consectetur adipisicing. <hr></li>
                        <li><i class="fa-solid fa-greater-than"></i> Lorem ipsum dolor sit amet consectetur adipisicing. <hr></li>
                        <li><i class="fa-solid fa-greater-than"></i> Lorem ipsum dolor sit amet consectetur adipisicing. <hr></li>
                    </ul>
                </div>
                <div class="col-3">
                    <h4 class="mb-3 mt-5 "><strong>LATEST REPLIES</strong></h4>
                    <ul>
                        <li><i class="fa-solid fa-greater-than"></i> Lorem, ipsum dolor sit amet consectetur adipisicing. <hr></li>
                        <li><i class="fa-solid fa-greater-than"></i> Lorem ipsum dolor, sit amet consectetur adipisicing. <hr></li>
                        <li><i class="fa-solid fa-greater-than"></i> Lorem ipsum dolor sit amet consectetur adipisicing. <hr></li>
                        <li><i class="fa-solid fa-greater-than"></i> Lorem ipsum dolor sit amet consectetur adipisicing. <hr></li>
                    </ul>
                </div>
            </div>
        </div>
        <hr>
        <div class="container">
            <div class="row justify-content-between">
                <div class="col-6">
                    <p class="my-fonts">
                        copyright 2012-2020 | Avada Theme by <span class="my-spans">Theme Fusion</span> | all rights reservered | powered by <span class="my-spans">WordPress</span>
                    </p>
                </div>
                <div class="col-6 d-flex justify-content-end">
                    <div class="m-dimension text-center">
                        <i class="files fa-brands fa-facebook-f"></i>
                    </div>
                    <div class="m-dimension-t text-center">
                        <i class="files fa-brands fa-twitter"></i>
                    </div>
                    <div class="m-dimension-i text-center">
                        <i class="files fa-brands fa-instagram"></i>
                    </div>
                    <div class="m-dimension-y text-center">
                        <i class="files fa-brands fa-youtube"></i>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>


<style lang="scss">
@use '../Style/partials/variables' as *;
    .color-g{
        color: #a3a3a3;
    }
    ul li{
        list-style: none;
        margin-bottom: .5rem;
    }
    .my-fonts{
        font-size: .5rem;
        color:#a3a3a3;
    }
    .my-spans{
        color: black;
    }
    .m-dimension{
        width: 50px;
        height: 50px;
        border-radius: 50%;
        background-color:#3c5998;
        margin-left: 1rem ;
    }
    .m-dimension-t{
        width: 50px;
        height: 50px;
        border-radius: 50%;
        background-color:#54acee;
        margin-left: 1rem ;
    }
    .m-dimension-i{
        width: 50px;
        height: 50px;
        border-radius: 50%;
        background-color:#3f729b;
        margin-left: 1rem ;
    }
    .m-dimension-y{
        width: 50px;
        height: 50px;
        border-radius: 50%;
        background-color:#cd201f;
        margin-left: 1rem ;
    }
    .files{
        text-align: center;
        color: white;
        font-size: 1.5rem;
        margin-top: .8rem;
    }
</style>