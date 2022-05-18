<template>
    <nav class="navbar navbar-expand-lg bg-light">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Navbar</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                <router-link to="/" class="button">
                    <li class="nav-item active">
                        <a class="nav-link" aria-current="page">Home</a>
                    </li>
                </router-link>
                 <router-link to="/about" class="button">
                    <li class="nav-item">
                        <a class="nav-link" aria-current="page">About</a>
                    </li>
                </router-link>
            </ul>
            <form class="d-flex" role="search">
                <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                <button class="btn btn-outline-success" type="submit">Search</button>
            </form>
            </div>
        </div>
    </nav>
</template>

<script>
</script>

<style>
li .active{
    background-color: aqua;
}
a{
    text-decoration: none;
}
</style>