<template>
    <div>
        <nav class="navbar navbar-expand-lg">
            <div class="container">
                <!-- <a class="navbar-brand" href="#"></a> -->
                <nuxt-link to="/" class="navbar-brand">Navbar</nuxt-link>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>

                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav mr-auto">
                        <li class="nav-item active">
                            <!-- <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a> -->
                            <nuxt-link to="/contact" class="nav-link" >Contact</nuxt-link>
                        </li>
                        <li class="nav-item">
                        <a class="nav-link" href="#">Blogs</a>
                        </li>
                        <li class="nav-item">
                        <a class="nav-link" href="#">About</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </div>
</template>

<script>
</script>

<style>

</style>
