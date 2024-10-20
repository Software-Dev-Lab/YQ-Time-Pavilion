<script setup lang="ts">
</script>

<template>
    <div>
        <header class="Header">
            <nav class="navbar">
                <a href="#home">首页</a>
                <a href="#about">历史长廊</a>
                <a href="#products">历史人物</a>
                <a href="#review">古代遗址</a>
            </nav>

            <div class="icons">
                <a href="#" class="fas fa-heart"></a>
                <a href="#header" class="fas fa-user"></a>

                <a href="#" class="fas fa-search" id="search-icon"></a>
                <a href="#" class="fas fa-cog"></a>
            </div>
        </header>
    </div>
</template>

<style>
:root {
    --pink: #dfb835;
}

header {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    background: #fff;
    padding: 2rem 9%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    z-index: 1000;
    box-shadow: 0 .5rem 1rem rgba(0, 0, 0, .1);
}

header .logo {
    font-size: 3rem;
    color: #333;
    font-weight: bolder;
}

header .logo span {
    color: var(--pink);
}

header .navbar a {
    font-size: 2rem;
    padding: 0 1.5rem;
    color: #666;
}

header .navbar a:hover {
    color: var(--pink);
}

header .icons a {
    font-size: 2.5rem;
    color: #333;
    margin-left: 1.5rem;
}

header .icons a:hover {
    color: var(--pink);
}

header #toggler {
    display: none;
}

header .fa-bars {
    font-size: 3rem;
    color: #333;
    border-radius: .5rem;
    padding: .5rem 1.5rem;
    cursor: pointer;
    border: .1rem solid rgba(0, 0, 0, .3);
    display: none;
}
</style>