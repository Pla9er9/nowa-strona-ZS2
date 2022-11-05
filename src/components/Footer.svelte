<div id="footer">
    <p>Copyright © 2022 Zespół Szkół nr 2 w Wągrowcu</p>
</div>

<style>
    #footer {
        position: fixed;
        display:flex;
        align-items:center;
        left: 0;
        bottom: 0;
        width: 100%;
        height:40px;
        background-color: #033e8d;
        color: #f6f6f6;
        padding: 0px;
        text-indent: 30px;
        transition: 0.2s ease;
    }

    #footer:hover {
        border-top-left-radius: 5px;
        border-top-right-radius: 5px;
        height: 45px;
        background: linear-gradient(to right, #033e8d,#057bfa);
    }

    @media only screen and (max-width: 390px) {
    #footer {
        text-align: center;
        font-size: 14px;
  }
}

</style>