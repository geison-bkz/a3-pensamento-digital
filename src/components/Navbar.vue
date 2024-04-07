<template>
    <div class="container-fluid text-center">
        <div class="row navbar-field">
            <div class="col btn-logo-col"><button class="btn-logo">Logo</button></div>
            <div class="col navbar-col">
                <ul class="navbar-ul">
                    <li><RouterLink to="/">Blog</RouterLink></li>
                    <li><RouterLink to="/about">About us</RouterLink></li>
                </ul>
            </div>
            <div class="col btn-contact-col"><button class="btn-contact">Contac us</button></div>
        </div>
        <div class="row banner">
            <div class="col">1 of 1</div>
        </div>
    </div>
</template>

<script setup>
import { RouterLink } from 'vue-router';
</script>

<style scoped>
.container-fluid {
    padding: 0px 135px;
}

.btn-logo-col {
    margin: 58px 0px 51px 0px;
    padding: 19px 49px 0px 0px;
    text-align: left;
}

.navbar-col {
    margin: auto;
    padding: 0;
}

.navbar-ul {
    display: inline;
    padding: 0;
}

.navbar-ul li {
    list-style: none;
    display: inline-block;
    font-size: 18px;
    font-weight: 600;
    width: 150px;
    text-align: start;
}

.btn-contact-col {
    padding: 0;
    margin: 0;
    text-align: right;
}

.btn-contact {
    margin: 58px 0px 51px;
    padding: 19px 49px;
    border-radius: 52px;
    border: none;
    background: linear-gradient(#2ca6fb, #218ef5);
    font-size: 18px;
    font-weight: 500;
    color: white;
}

.banner {
    background-image: url(./src/assets/images/banner.jpg);
    background-position: center;
    height: 220px;
    border-radius: 41px;
}
</style>
