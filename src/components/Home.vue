<template>

<div class="w100 h100 single-page">
     
    <img class="picture-one" src="../assets/Logo-MTech.svg" alt="">
    <div class="social-media">
        <a class="lh" href="https://www.instagram.com/teammtech/"><img src="../assets/instagram.svg" alt=""></a>
        <a class="lh m10" href="https://"><img src="../assets/github.svg" alt=""></a>
        <a class="lh" href="www.linkedin.com/in"><img src="../assets/linkedin.svg" alt=""></a>
    </div>
    <div class="links">
        <a class="btn-link" href="https://drive.google.com/file/d/1Msh-j1MbIvvMM4FRtzTB7OkqR2cRNm7T/view?usp=sharing">Rookie Book</a>
        <a class="btn-link" href="https://drive.google.com/file/d/1M56YeRA4LGLSXRQ6CR7RV5ahbD9HsRqa/view?usp=sharing">Robot Book</a>
        <a class="btn-link" href="https://drive.google.com/file/d/16ft45Zms0LmNTAcIJ5hv2aEL1RphxISQ/view?usp=sharing">Memories Book</a>
        <a class="btn-link" href="https://drive.google.com/file/d/1qu8vI4MtV2cWTp3hu6K2Pv5fGf35Hy_W/view?usp=sharing">Bussiness Plan</a>
    </div>
    <div class="footer-menu">
        <small>Desenvolvido por @teammtech</small>
    </div>

</div>

</template>

<script>

export default{
    name: 'menuBio'
}

</script>

<style scoped>

@import url('https://fonts.googleapis.com/css2?family=Teko:wght@300..700&display=swap');

*{
    font-family: "Teko", sans-serif;
    margin: 0;
    padding: 0;
    max-width: 100%;
    max-height: 100vh;
    font-weight: 400;
}

.m10{
    margin-left: 10px;
    margin-right: 10px;
}

.h20{
    height: 30%;
}

.w80{
    width: 80%;
}

.h100{
    height: 100%;
}

.w100{
    width: 100%;
}

.picture-one{
    width: 250px;
    height: 120px;
    margin-bottom: 10px;
}

.single-page{
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;   
    background: rgb(12,18,32);
    background: linear-gradient(90deg, rgba(12,18,32,1) 0%, rgba(14,19,66,1) 53%);
}

.links{
    display: flex;
    flex-direction: column;
    width: 264px;
    height: 60%;
    align-items: center;
    justify-content: center;
}

.btn-link{
    display: flex;
    width: 222px;
    height: 49px;
    background-color: cyan;
    margin-bottom: 33px;
    text-decoration: none;
    justify-content: center;
    align-items: center;
    border-radius: 7px;
    color: white;
    box-shadow: 0 0 10px #025576, 0 0 40px #114b62, 0 0 70px #013c53;
    text-shadow: 1px 1px gray;
}

    

.btn-link:hover{
    background-color: darkcyan;
    box-shadow: 0 0 10px #297b9c, 0 0 40px #258db6, 0 0 70px #036389;
    transition-duration: 0.6s;
}

.lh{
    width: 100px;
    height: 100px;
    padding: 10px;
}

.footer-menu{
    color: #a0a8b0;
    font-size: 17px;
    font-style: italic;
    text-shadow: 1vw 1vw 1vw #000, 0 0 3vw #0e68c7, 0 0 3vw #1682db, 0 0 3vw #15cbad;   
}


</style>