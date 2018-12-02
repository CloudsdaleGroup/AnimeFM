<template>
    <header class="main-header">
        <nav class="main-nav">
            <ul class="nav-links">
                <li><nuxt-link to="/"      tag="a" class="nav-links">Home</nuxt-link></li>
                <li><nuxt-link to="/popup" tag="a" class="nav-links">Popup</nuxt-link></li>
                <li><nuxt-link to="/about" tag="a" class="nav-links">About</nuxt-link></li>
                <li><nuxt-link to="/contact" tag="a" class="nav-links">Contact</nuxt-link></li>
            </ul>
        </nav>
    </header>
</template>

<style scoped>
    .main-header {
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        background: #022d30;
        height: 4.5rem;
    }
    .nav-links {
        list-style: none;
        margin: 0;
        padding: 0;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100%;
    }
    .main-nav {
        height: 100%;
    }
    .nav-links {
        height: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        margin: 0 1rem
    }
    .nav-links a {
        display: block;
        text-decoration: none;
        color: white;
    }
    .nav-links a:hover,
    .nav-links a:active,
    .nav-links.nuxt-link-active a {
        color: #06c4d1
    }
</style>
