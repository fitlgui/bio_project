<template>

<div class="w100 h100 single-page">
     
    <img class="picture-one" src="../assets/Logo-MTech.svg" alt="">
    <div class="social-media">
        <a class="lh" href="https://www.instagram.com/teammtech/"><img src="../assets/instagram.svg" alt=""></a>
        <a class="lh m10" href="https://"><img src="../assets/github.svg" alt=""></a>
        <a class="lh" href="www.linkedin.com/in"><img src="../assets/linkedin.svg" alt=""></a>
    </div>
    <div class="links">
        <a class="btn-link" href="../assets/ROOKIE-BOOK-MTECH.pdf">Rookie Book</a>
        <a class="btn-link" href="../assets/ROBOT-BOOK-MTECH.pdf">Robot Book</a>
        <a class="btn-link" href="../assets/MEMORIE-BOOK-MTECH.pdf">Memories Book</a>
        <a class="btn-link" href="../assets/BUSSINESS-PLAN-MTECH.pdf">Bussiness Plan</a>
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
    margin-bottom: 20px;
}

.single-page{
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;   
    background: #2980b9;  /* fallback for old browsers */
    background: -webkit-linear-gradient(to right, #2c3e50, #2980b9);  /* Chrome 10-25, Safari 5.1-6 */
    background: linear-gradient(to right, #2c3e50, #2980b9); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */

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
}
    

.btn-link:hover{
    background-color: darkcyan;
    box-shadow: 0 0 10px #297b9c, 0 0 40px #258db6, 0 0 70px #036389;
    transition-duration: 0.6s;
}

.lh{
    width: 100px;
    height: 100px;
}

.footer-menu{
    color: #a0a8b0;
    font-size: 17px;
    font-style: italic;
    text-shadow: 1vw 1vw 1vw #000, 0 0 3vw #0e68c7, 0 0 3vw #1682db, 0 0 3vw #15cbad;   
}


</style>