<script lang="ts">
    export var visibility: boolean = false;
    let display: string = "block"
    display = (visibility ? "block" : "none")
</script>


<div id="leftBox">
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
            display: none;
            border-top-left-radius: 30px;
            border-bottom-left-radius: 30px;
        }
    }

</style>