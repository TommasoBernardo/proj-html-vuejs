<script>
export default {
    name : 'ComponentsHeader.vue',
}
</script>

<template>
    <header class="my-size ">
        <img src="../assets/img/logo.png" alt="logo-avada">
        <nav class="navbar navbar-expand-lg bg-body-tertiary">
            <div class="container-fluid">
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav">
                        <li class="nav-item">
                            <a class="nav-link" aria-current="page" href="#">Home</a>
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
                            <button class="btn btn-outline-dark">
                                <a class="nav-link">Join Us</a>
                            </button>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>

    </header>
</template>


<style lang="scss">
@use '../Style/partials/variables' as *;
@use 'bootstrap/scss/bootstrap.scss' as *;
    header{
        display: flex;
    }
    .my-size{
        width: 100%;
        background-color: $header-color;

        img{
            width: 150px;
            margin-top: .5rem;
            margin-left: 20rem;
        }

        nav{
            margin-left: 10rem;
        }

        a{
            color: $color-white;
        }
    }
</style>