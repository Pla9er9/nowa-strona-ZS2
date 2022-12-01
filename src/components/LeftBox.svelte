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
    <slot></slot>
</div>


<style>
    #leftBox {
        background-color: #f6f6f6;
        margin-top: -8px;
        margin-left: -8px;
        margin-bottom: 100px;
        width: 220px;
        height: 1000px;
        border-top-right-radius:30px;
        border-bottom-right-radius: 30px;
        padding-bottom: 40px;
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
            padding-bottom: 60px;
            border-right: none;
            width: 200px;
            position: absolute;
            margin-top: 60px;
            justify-self: flex-end;
        }
    }

</style>