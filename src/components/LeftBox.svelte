<script lang="ts">
    export let visibility: boolean = true;
    $: window.screen.width, () => 
    {    
        if (window.screen.width <= 680)
        {
            visibility = false
            display = "none"
        }
        else 
            visibility = true
    }

    var display: string = "none"

    $: visibility, display = (visibility ? "block" : "none")
</script>


<div id="leftBox" style="--display: {display};">
    <center>
        <a href="https://uonetplus.vulcan.net.pl/powiatwagrowiecki/"><p id="dz">Dziennik</p></a>
        <a href="https://www.facebook.com/profile.php?id=100063451487568"><p id="fb">Facebook</p></a>
    </center>

    <slot></slot>
</div>


<style>
    #leftBox {
        background-color: #f6f6f6;
        margin-top: -8px;
        margin-left: -8px;
        margin-bottom: 100px;
        width: 220px;
        height: max-content;
        border-top-right-radius:30px;
        border-bottom-right-radius: 30px;
        padding-bottom: 40px;
    }

    #fb {
        display: none;
        background-color: #033e8d;
        color: #fff;
        width: 70%;
    }
    
    #dz {
        display: none;
        background-color: #ff5757;
        color: #fff;
        width: 70%;
    }

    @media only screen and (max-width: 1266px) {
        #leftBox {
            margin-top: 80px;
        }
    }

    @media only screen and (max-width: 950px) {
        #leftBox {
            width: 150px;
            height: 600px;
        }
    }
    @media only screen and (max-width: 680px){
        #leftBox{
            right: 0;
            display: var(--display);
            border-radius: 0px;
            border-top-left-radius: 15px;
            border: solid 3px rgb(0, 34, 255);
            padding-bottom: 20px;
            border-right: none;
            width: 200px;
            position: absolute;
            margin-top: 60px;
            height: max-content;
            justify-self: flex-end;
        }
        #fb {
            display: block;
        }
        #dz {
            display: block;
        }
    }

</style>