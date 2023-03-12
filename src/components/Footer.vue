<template>
    <footer class="footer">
        <div class="container">
            <h2 class="footer__title">Связаться со мной</h2>
            <div class="footer__box">
                <a href="#" class="footer__link"><img src="@/assets/images/fb.svg" alt=""></a>
                <a href="#" class="footer__link"><img src="@/assets/images/inst.svg" alt=""></a>
                <a href="#" class="footer__link"><img src="@/assets/images/tg.svg" alt=""></a>
                <a href="#" class="footer__link"><img src="@/assets/images/mail.svg" alt=""></a>
                <a href="#" class="footer__link"><img src="@/assets/images/ws.svg" alt=""></a>
            </div>
        </div>
    </footer>
</template>

<script>
    export default {
        
    }
</script>

<style>
    .footer {
        background: #000000;
        padding-top: 47px;
        padding-bottom: 60px;
    }
    .footer__title {
    color: #FFFFFF;
    font-size: 40px;
    line-height: 46px;
    text-align: center;
    }
    .footer__box {
        display: flex;
        gap: 200px;
        margin-top: 30px;
    }
</style>