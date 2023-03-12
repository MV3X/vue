<template>
    <nav class="nav">
        <div class="container">
            <div class="nav__box">
                <a href="#" class="logo">PROWEB</a>
                <ul class="list">
                    <li v-for="(link,i) in links" :key="i">
                        <a href="#" class="link">{{ link }}</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
    <div class="header__content">
        <div class="container">
            <div class="header__content-box">
                <h1 class="title">Добро пожаловать на мой сайт</h1>
                <a href="#" class="header__link">Позвонить</a>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                links: ['Обо мне','Мои работы','Контакты']
            }
        }
    }
</script>

<style>
    .nav {
        background: #000000;
        padding: 15px;
    }
    .nav__box {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    .logo {
    font-size: 40px;
    line-height: 46px;
    color: #FFFFFF;
    }
    .link {
    font-size: 25px;
    line-height: 29px;
    color: #FFFFFF;
    }
    .list {
        display: flex;
        gap: 80px;
    }
    .header__content {
        background: url(@/assets/images/back.jpg) center top /cover ;
        height: 850px;
    }
    .header__content-box {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        gap: 145px;
        height: 850px;
    }
    .title {
    font-size: 40px;
    line-height: 46px;
    color: #000000;
    }
    .header__link {
    background: #FFFFFF;
    border-radius: 10px;
    padding: 10px 24px;
    font-size: 35px;
    line-height: 40px;
    color: #000000;
    }
</style>