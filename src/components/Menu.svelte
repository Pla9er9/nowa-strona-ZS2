<div id="menu">
    <div id="forStudent">
        <a href="/?p=aktualnosci">
            <div class="menuHrefs">
                <img src="/icons/notifications.svg" alt="aktualności">
                <p>Aktualności</p>
            </div>
        </a>

        <a href="/?p=szkola">
            <div class="menuHrefs">
                <img src="/icons/school.svg" alt="szkoła">
                <p>Szkoła</p>
            </div>
        </a>

        <a href="/?p=eszkola">
            <div class="menuHrefs">
                <img src="/icons/laptop.svg" alt="e-Szkoła">
                <p>e-Szkoła</p>
            </div>
        </a>
        
        <a href="/?p=dokumenty">
            <div class="menuHrefs">
                <img src="/icons/doc.svg" alt="dokumenty">
                <p>Dokumenty</p>
            </div>
        </a>
    </div>
    
    <div id="forParents">
        <a href="/?p=biblioteka">
            <div class="menuHrefs">
                <img src="/icons/library.svg" alt="Biblioteka">
                <p>Biblioteka</p>
            </div>
        </a>
        
        <a href="docs/REGULAMIN-BOISKA.pdf">
            <div class="menuHrefs">
                <img src="/icons/football.svg" alt="Boisko">
                <p>Boisko</p>
            </div>
        </a>
        
        <a href="/?p=matura">
            <div class="menuHrefs">
                <img src="/icons/book.svg" alt="Matura 2023
                ">
                <p>Matura 2023
                </p>
            </div>
        </a>
        
        <a href="/?p=projekty">
            <div class="menuHrefs">
                <img src="/icons/projects.svg" alt="Projekty">
                <p>Projekty</p>
            </div>
        </a>
    </div>

    <div id="forTeacher">
        <a href="/?p=kontakt">
            <div class="menuHrefs" >
                <img src="/icons/phone.svg" alt="Kontakt">
                <p>Kontakt</p>
            </div>
        </a>
        
        <a href="/?p=rodo">
            <div class="menuHrefs" >
                <img src="/icons/person.svg" alt="RODO">
                <p>RODO</p>
            </div>
        </a>
        
        <a href="docs/regulamin_monitoringu.pdf" target="_blank" rel="noreferrer">
            <div class="menuHrefs">
                <img src="/icons/cam.svg" alt="Monitoring">
                <p>Monitoring</p>
            </div>
        </a>
        
        <a href="docs/Bip.pdf" target="_blank" rel="noreferrer">
            <div class="menuHrefs">
                <img src="/icons/bip.svg" alt="Bip">
                <p>Bip</p>
            </div>
        </a>
    </div>
</div>

<style>
    #menu {
        display: flex;
        flex-direction: column;
        margin-left: 20px;
    }

    #menu a p {
        font-size: 20px;
        font-weight: 600;
        transition: 0.2s;
        color: #737373;
        margin-left: 15px;
    }

    .menuHrefs {
        display: inline-flex;
        align-items: center;
        width: 200px;
        margin-top: 5px;
        transition: margin 0.5s;
        border: solid 3px none;
        padding-left: 15px;
    }

    #forStudent {
        border-left: #7ed957 solid;
        margin-top: 15px;
        margin-bottom: 15px;
    }

    #forParents{
        border-left: #f6b619 solid;
        margin-bottom: 30px;
    }

    #forTeacher{
        border-left: #1d4d94 solid;
        margin-bottom: 20px;
    }

    .menuHrefs:hover{
        margin-left: 10px;
    }

    .menuHrefs:hover p {
        padding: 3px;
        color: #033e8d !important;
        font-size: 22px !important;
    }

    .menuHrefs img {
        width: 30px;
        height: 30px;
    }

    @media only screen and (max-width: 950px) {
        #menu {
            margin-left: 20px;
        }
        
        .menuHrefs img {
            width: 20px;
            height: 20px;
        }

        #menu a p {
            font-size: 12px;
        }

        .menuHrefs:hover {
            margin-left: 6px;
        }

        .menuHrefs:hover p{
            font-size: 12px !important;
        }
        
    }

</style>