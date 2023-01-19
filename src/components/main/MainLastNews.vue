<script>

export default {
    name: 'MainLastNews.vue'
}
</script>

<template>
    <main>
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-3">
                    <p class="text-center my-font">
                        PHASELLUS EGET METUS
                    </p>
                    <h3 class="text-center">
                        <strong>All the latest news</strong>
                    </h3>
                    <div class="my-border">
                    </div>
                </div>
            </div>
        </div>

        <div class="container">
            <div class="row justify-content-center">
                <div class="col-4">
                    <img class="my-img" src="../../assets/img/post_feat_img_25-320x202.jpg" alt="phone">
                    <p>
                        <strong>Morvi vitae dui euismod vulputate sollicitutid</strong><br>
                        <span class="my-text">october 11th,2015</span> | <span>two comments</span>
                    </p>
                    <p class="my-text">
                        Donec finibus amet orci eget ultricies. Praesent posuere ante ut erat fringilla, vestibulum placerat metus mattis. Aenean dictum vitae nisl
                    </p>
                </div>

                <div class="col-4">
                    <img class="my-img" src="../../assets/img/post_feat_img_24-320x202.jpg" alt="phone">
                    <p>
                        <strong>Morvi vitae dui euismod vulputate sollicitutid</strong><br>
                        <span class="my-text">october 11th,2015</span> | <span class="comments">comments off</span> 
                    </p>
                    <p class="my-text">
                        Donec finibus amet orci eget ultricies. Praesent posuere ante ut erat fringilla, vestibulum placerat metus mattis. Aenean dictum vitae nisl
                    </p>
                </div>

                <div class="col-4">
                    <img class="my-img" src="../../assets/img/post_feat_img_23-320x202.jpg" alt="phone">
                    <p>
                        <strong>Morvi vitae dui euismod vulputate sollicitutid</strong><br>
                        <span class="my-text">october 11th,2015</span> | <span class="comments">comments 0ff</span>
                    </p>
                    <p class="my-text">
                        Donec finibus amet orci eget ultricies. Praesent posuere ante ut erat fringilla, vestibulum placerat metus mattis. Aenean dictum vitae nisl
                    </p>
                </div>
            </div>
        </div>
    </main>
</template>


<style lang="scss">
@use '../../Style/partials/variables' as *;
    main{
        font-family: 'Fira Sans', sans-serif;
        .my-font{
            font-size: .6rem;
            margin-top: 5rem;
            color: $color-text;
        }
        h3{
            margin-bottom: 2rem;
        }
        .my-border{
            border-bottom: 2px solid $color-orange;
            margin-bottom: 3rem;
            width: 70px;
            margin-left: 40%
        }
        .my-text{
            color: $color-text;
            font-size: .9rem
        }
        .my-img{
            width: 100%;
        }

        .comments{
            color: $color-text;
        }
    }
</style>