<template>
    <div class="container">
        <div class="logo">
            <RouterLink to="#"><img src="./icons/logo_mundo_IA.svg" alt="logo" /></RouterLink>
        </div>
        <nav class="nav">
            <ul class="nav-ul">
                <li>
                    <RouterLink to="#">Services</RouterLink>
                </li>
                <li>
                    <RouterLink to="#">Creative Studio</RouterLink>
                </li>
                <li>
                    <RouterLink to="#">Blog</RouterLink>
                </li>
                <li>
                    <RouterLink to="/about">About us</RouterLink>
                </li>
            </ul>
        </nav>
        <div class="contactus">
            <RouterLink to="#">Contact us</RouterLink>
        </div>
    </div>
</template>

<script setup>
import { RouterLink } from 'vue-router';
</script>

<style lang="css" scoped>
.container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 0px 120px;
    padding: 0;
}

.logo {
    padding: 0;
    margin: 0;
}

.logo a {
    margin: 0;
    padding: 0;
}

.logo a img {
    margin: 0;
    padding: 0;
    height: 200px;
}

.contactus a {
    background-color: #2698f9;
    padding: 20px 40px;
    margin: 0;
    text-decoration: none;
    color: aliceblue;
    font-size: 18px;
    border-radius: 50px;
    box-shadow:
        0 4px 8px 0 rgba(0, 0, 0, 0.2),
        0 6px 20px 0 rgba(0, 0, 0, 0.19);
}

.nav {
    display: flex;
    justify-content: center;
}

.nav-ul {
    list-style-type: none;
    padding: 0;
    margin: 0;
    text-align: justify;
}

.nav-ul li {
    display: inline-block;
}

.nav-ul li a {
    padding: 20px;
    margin: 20px;
    font-size: 18px;
    text-decoration: none;
    color: rgb(138, 138, 138);
}
</style>
