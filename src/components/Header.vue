<script setup>
    
</script>

<template>
    <section class="header">
        <div class="icon">
            <ul>
                <li>
                    <a>
                        <font-awesome-icon icon="fa-brands fa-discord" />
                    </a>
                </li>
                <li>
                    <a>
                        <font-awesome-icon icon="fa-brands fa-tiktok" />
                    </a>
                </li>
                <li>
                    <a>
                        <font-awesome-icon icon="fa-brands fa-github" />
                    </a>
                </li>
                <li>
                    <a>
                        <font-awesome-icon icon="fa-brands fa-twitter" />            
                    </a>
                </li>
                <li>
                    <a>
                        <font-awesome-icon icon="fa-brands fa-facebook" />
                    </a>
                </li>
            </ul>
        </div>
        <div class="logo-menu">
            <div class="logo">Logo</div>
            <div class="menu">
                <ul class="nav">
                    <li>About</li>
                    <li>Pages</li>
                    <li>Blog</li>
                    <li>Portfolio</li>
                    <li>Shortcodes</li>
                </ul>
            </div>
        </div>
    </section>
</template>

<style scoped>
    .header {
        width: 100%;
        display: flex;
        flex-wrap: wrap;
    }
    .icon {
        flex-basis: 100%;
        display: flex;
        justify-content: flex-end;
    }
    .logo-menu {
        flex-basis: 100%;
        display: flex;
        justify-content: space-between;
    }
    .logo {
        flex-basis: 30%;
        font-size: 36px;
    }   
    .menu {
        flex-basis: 50%;
    }
    .nav {
        list-style: none;
        display: flex;
        justify-content: space-evenly;
    }
    .nav li {
        font-size: 18px;
    }
    .icon ul {
        display: flex;
        justify-content: space-evenly;
        list-style: none;
        width: 15%;
    }
</style>