<template>
    <div class="nav">
        <nuxt-link class="nav-item" to="/">Home &nbsp;</nuxt-link>
        <nuxt-link class="nav-item" to="/blog">Blog posts &nbsp;</nuxt-link>
        <nuxt-link class="nav-item" to="/contact">Contact &nbsp;</nuxt-link>
        <!-- <nuxt-link to="/lorem">Lorem &nbsp;</nuxt-link> -->
    </div>
</template>

<style>
.nav {
    /* background-color: black; */
    color: #2daf72da;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    font-size: 30px;
    width: 100%;
    text-align: center;
}

.nav-item:link {
    text-decoration: none;
    color: #2daf72da;
}
.nav-item:visited {
    text-decoration: none;
    color: #2daf72da;
}
.nav-item:hover {
    text-decoration: none;
    color: #2daf72da;
}

.nav-item:active {
    text-decoration: none;
    color: #2daf72da;
}

</style>