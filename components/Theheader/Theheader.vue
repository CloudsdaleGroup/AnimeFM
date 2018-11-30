<template>
    <header class="header">
        <nav class="nav">
            <ul class="links">
                <nuxt-link to="/" tag="li">Home</nuxt-link>
                <nuxt-link to="/popup" tag="li">Popup</nuxt-link>
                <nuxt-link to="/about" tag="li">About</nuxt-link>
            </ul>
        </nav>
    </header>
</template>

<style scoped>
    .header {
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        background: #022d30;
    }
</style>
