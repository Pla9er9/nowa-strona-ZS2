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
    <img src="images/pp.png" alt="politechnika poznańska">

    <img src="images/wsb.png" alt="wyższa szkoła bezpieczeństwa">

    <img src="images/sos.webp" alt="sos">

    <img src="images/skrzynka.png" alt="anonimowa skrzynka alarmowa">

    <img src="images/kalendarz.png" alt="kalendarz">

    <img src="images/esp.png" alt="elektroniczna skrzynka podawcza ePUAP">
</div>

<style>

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
        margin-top: 0px;
        margin-bottom: 25px;
        background-color: #7ae83f;
        color: rgb(255, 255, 255);
        text-align: center;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        width: 120px;
        font-size: 18px;
        padding: 5px;
        font-weight: 900;
        border-radius: 15px;
        box-shadow: 0px 5px 15px rgb(120, 120, 120);
        transition:200ms;
    }

    .stat:hover {
        margin-top: -10px;
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

@media only screen and (max-width: 900px) {
    .stat {
        width: 100px;
        font-size: 14px;
    }
}

@media only screen and (max-width: 599px) {
    #centerImage {
        width: 95%;
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