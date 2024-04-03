<script setup>
import NavbarTop from '@/components/NavbarTop.vue';
</script>

<template>
    <header>
        <NavbarTop></NavbarTop>
    </header>
    <main>
        <div class="img-blog"></div>
        <div class="input-field">
            <div class="search-bar">
                <button class="btn-search"></button
                ><input class="search" type="text" placeholder="Search.." />
            </div>
        </div>
    </main>
</template>

<style scoped>
main {
    margin: 0;
    width: 100%;
    height: auto;
    display: flex;
    flex-direction: column;
}

.img-blog {
    background-image: url(../assets/images/banner.jpg);
    background-position: center;
    background-size: auto;
    background-repeat: no-repeat;
    margin: 0px 120px;
    height: 300px;
    border-radius: 40px;
    box-shadow:
        0 4px 8px 0 rgba(0, 0, 0, 0.2),
        0 6px 20px 0 rgba(0, 0, 0, 0.19);
}

.input-field {
    margin: -40px 120px;
    height: 90px;
    display: flex;
    justify-content: center;
}

.search-bar {
    background-color: white;
    width: 790px;
    border-radius: 20px;
    display: flex;
    box-shadow:
        0 4px 8px 0 rgba(0, 0, 0, 0.2),
        0 6px 20px 0 rgba(0, 0, 0, 0.19);
}

.btn-search {
    height: 100%;
    width: 10%;
    margin: 0;
    padding: 0;
    border: none;
    border-radius: 20px 0px 0px 20px;
    background-color: white;
}

.search {
    margin: 0;
    padding: 0;
    height: 100%;
    width: 90%;
    font-size: 18px;
    border: none;
    border-radius: 0px 20px 20px 0px;
}
</style>

