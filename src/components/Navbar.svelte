<script>
    let navbarText = "Zespół szkół nr 2 im. PPŁK. DR. Stanisława Kulińskiego w"

</script>

<div id="navbar">
    <div id="leftSide">
        <img src="images/zs2logo.png" alt="logo zs2" id="navBarLogo">
        <h2 id="navbarText">Zespół szkół nr 2 im. PPŁK. DR. Stanisława Kulińskiego w <yellow> Wągrowcu<yellow></h2>
    </div>

    <div id="rightSide">
        <div id="hrefs">
            <a href="https://uonetplus.vulcan.net.pl/powiatwagrowiecki/" target="_blank" rel="noreferrer" class="navHrefs" style="background-color: #ff5757;"> Dziennik</a>

            <a href="https://www.facebook.com/profile.php?id=100063451487568" target="_blank" rel="noreferrer" class="navHrefs" style="background-color: #033e8d;">  Facebook</a>
        </div>

        <img src="images/herb.png" alt="logo zs2" width="50px" id="navBarHerb">
    </div>
    <button id="menu">
        <img src="images/menu.svg" alt="menu" width="30px">
    </button>
</div>

<style>
    #navbar{
        position: fixed;
        right: 0;
        display: flex;
        align-items: center;
        top: 0;
        width: 85vw;
        height: 70px;
        background-color: #f6f6f6;
    }

    #navBarLogo {
        margin-left: 30px;
        margin-right: 35px;
        height: 65px;
        width: 70px;
    }

    #navbarText {
        color: #1d4d94;
        font-size: 18px;
    }

    yellow {
        color: #f6b619;
    }


    .navHrefs {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 40px;
        width: 150px;
        color: #fff;
        text-align: center;
        border-radius: 30px;
        margin-right: 30px;
        transition: 0.5s;
    }

    .navHrefs:hover {
        width: 160px;
    }

    #navBarHerb {
        margin-right: 30px;
    }

    #leftSide {
        display: inline-flex;
        width: 100%;
        min-width: 150px;
        margin-left: 20px;
        justify-content:flex-start;
        align-items: center;
    }

    #rightSide {
        display: inline-flex;
        width: 100%;
        align-items: center;
        justify-content:flex-end;
    }

    #hrefs {
        display: inline-flex;
    }

    #menu {
        display: none;
        background-color: #f6f6f6;
        border: none;
        margin-right: 10px;
    }

    @media only screen and (max-width: 1159px) {
        #navbar {
            width: 100vw;
        }

        #leftSide {
            width: 900px;
            margin-left: 0px;
        }

        #rightSide {
            width: 200px;
        }

        #hrefs {
            align-items: center;
            flex-direction: column;
        }

        .navHrefs {
            height: 25px;
            width: 130px;
            margin-top: 5px;
            margin-bottom: 5px;
        }

        #navbarText {
            font-size: 15px;
            width: 250px;
        }
    }

    @media only screen and (max-width: 680px) {
        #rightSide {
            display: none;
        }

        #navbarText {
            font-size: 13px;
        }

        #navBarLogo {
            margin-right: 10px;
            margin-left: 10px;
        }

        #menu {
            display: block;
        }
    }

    @media only screen and (max-width: 300px) {
        #navbarText {
            font-size: 11px;
            width: 120px;
        }
    }


</style>