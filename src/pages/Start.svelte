<script lang="ts">
</script>

<img src="https://zsp2wagrowiec.pl/cms/wp-content/uploads/2022/03/xcropped-baner-2.1-ukraine.png.pagespeed.ic.g-uPoisrUU.webp" alt="szkoła" id="centerImage"> 


<div id="stats">
    <div class="stat">
        <h2>70</h2>
        <p>Nauczycieli</p>
    </div>

    <div class="stat" style="background-color: #9d32a8;" >
        <h2>579</h2>
        <p>Uczniów</p>
    </div>

    <div class="stat" style="background-color: red;">
        <h2>21</h2>
        <p>Odziałów</p>
    </div>

    <div class="stat" style="background-color: #35b1b5;" >
        <h2>100+</h2>
        <p>Lat kształcenia</p>
    </div>

</div>

<div id="icons">
    <img src="https://zsp2wagrowiec.pl/cms/wp-content/uploads/2022/03/pp-logo.png" alt="politechnika poznańska">

    <img src="https://zsp2wagrowiec.pl/cms/wp-content/uploads/2022/03/Wyzsza-Szkola-Bezpieczenstwa-logo-1024x1024.png" alt="wyższ szkoła bezpieczeństwa">

    <img src="https://zsp2wagrowiec.pl/cms/wp-content/uploads/2022/04/xsos-dtz-page-768x567.jpg.pagespeed.ic.FLpzX4ilsK.webp" alt="sos">

    <img src="https://zsp2wagrowiec.pl/cms/wp-content/uploads/2021/11/skrzynka.png" alt="anonimowa skrzynka alarmowa">

    <img src="https://zsp2wagrowiec.pl/cms/wp-content/uploads/2021/08/x2021-08-25_17h13_34-768x280.png.pagespeed.ic.DFe4Qp-u3P.webp" alt="kalendarz">

    <img src="https://zsp2wagrowiec.pl/cms/wp-content/uploads/2017/12/xskrzynka.png.pagespeed.ic.AXMAbKhbQ8.webp" alt="elektroniczna skrzynka podawcza ePUAP">
</div>

<style>
    * {
        animation: changeVisibility 1s;
    }

    #centerImage {
        width: 70%;
        margin-top: -60px;
        border: solid 0px;
        border-radius: 20px;
    }

    #stats {
        margin-top: 100px;
        width: 90%;
        flex-wrap: wrap;
        display: flex;
        justify-content: space-around;
    }

    .stat {
        margin-bottom: 25px;
        background-color: #7ae83f;
        color: rgb(255, 255, 255);
        text-align: center;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        width: 120px;
        font-size: 20px;
        font-weight: 900;
        border-radius: 15px;
        box-shadow: 0px 5px 5px rgb(120, 120, 120);
    }

    #icons {
        margin-top: 100px;
        margin-bottom: 100px;
        display: flex;
        justify-content: space-around;
        width: 100%;
        height: max-content;
        flex-wrap: wrap;
        border-bottom-left-radius: 25px;
        border-bottom-right-radius: 25px;
    }

    #icons img {
        width: 100px;
        margin: 50px;
    }

    @keyframes changeVisibility {
  from {
    opacity: 0;
  }

  to {
    opacity: 1;
  }
}

@media only screen and (max-width: 900px) {
    .stat {
        width: 100px;
        font-size: 14px;
    }
}

@media only screen and (max-width: 599px) {
    #centerImage {
        width: 90%;
    }
    .stat {
        margin-right: 15px;
        margin-left: 15px;
    }
}

@media only screen and (max-width: 415px) {
    #icons img {
        width: 65px;
        margin: 20px;
    }
}

@media only screen and (max-width: 305px) {
    .stat {
        width: 60px;
        font-size: 10px;
    }
}
</style>