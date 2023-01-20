<script>
export default {
    name : 'ComponentsHeader.vue',
}
</script>

<template>
    <header class="my-size ">
        <div class="my-flex">
            
        
        <img class="my-logo" src="../assets/img/logo.png" alt="logo-avada">
        <nav class="navbar navbar-expand-lg bg-body-tertiary">
            <div class="container-fluid">
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav">
                        <li class="nav-item dropdown">
                            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                                Dropdown
                            </a>
                            <ul class="dropdown-menu">
                                <li><a class="dropdown-item" href="#">Action</a></li>
                            </ul>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Apple</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Microsoft</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link">Android</a>
                        </li>
                        <li>
                            <a class="nav-link ">Forums</a>
                        </li>
                        <li>
                            <a class="nav-link">Contact Us</a>
                        </li>
                        <li>
                            <button class="my-button">
                            Join Us
                            </button>
                        </li>

                        <li>
                            <i class="my-color fas fa-search my-search"></i>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </div>
    <div class="my-background">
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <h2 class="text-white">
                        Tech Forum!
                    </h2>
                    <p class="text-white">
                        Discuss all the latest technology news and trends
                    </p>

                    <button class="my-get text-white ">
                        GET AVAD NOW! >
                    </button>
                </div>
            </div>
        </div>
    </div>
    </header>
</template>


<style lang="scss">
@use '../Style/partials/variables' as *;
@use 'bootstrap/scss/bootstrap.scss' as *;
header{
    font-family: 'Fira Sans', sans-serif;
}
    .my-flex{
        display: flex;
        background-color: $header-color;
        position: fixed;
        width: 100%;
    }
    .my-size{
        width: 100%;

        .my-logo{
            width: 150px;
            margin-top: .5rem;
            margin-left: 20rem;
        }

        nav{
            margin-left: 10rem;
            a{
            color: $color-white;
            }
            .my-button{
                color: $color-white;
                border: none;
                margin-top: .5rem;
                background-color: $color-black;
                font-size: 1rem;
                width: 70px;
            }

            .my-search{
                margin-left: 30px;
                margin-top:12px;
            }
        }
        
    }
    .my-background{
        background-image: url(../assets/img/home_slider_bg.jpg);
        background-size: cover;
        width: 100%;
        height: 700px;
        h2{
            font-size: 7rem;
            margin-top: 17%;
            margin-left: 15.5%;
        }

        p{
            margin-top: 1rem;
            margin-left: 17%;
            font-size: 1.2rem;

        }

        button{
            margin-top: 1rem;
            margin-left: 17%;
            border: none;
            background-color: $button-color;
            width: 150px;
            height: 40px;
        }

        .my-color{
            color:white;
        }
    }
</style>