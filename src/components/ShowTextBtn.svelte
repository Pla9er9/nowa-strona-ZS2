<script lang="ts">
    export var title:string = ""
    export var description:string = ""
    function changeDisplay(){
        textDisplay = !(textDisplay)
    }
    var textDisplay = false
</script>

<button on:click={changeDisplay}>{title}</button>
{#if textDisplay}
    <p>{@html description}</p>
{/if}

<style>
        button {
        width: 800px;
        height: 80px;
        border: solid 1px rgb(0, 92, 128);
        background-color: #4a55ff;
        color:#f6f6f6;
        margin-bottom: 50px;
        border-radius: 30px;
        transition: 0.5s;
        font-size: 25px;
    }

    button:hover {
        width: 650px;
        background-color: rgb(1, 97, 214);
    }

    button:active {
        background-color: rgb(0, 81, 255);
        transition: none;
    }
    p {
        color: rgb(74, 72, 72);
        font-size: 1.2em;
        margin-bottom: 50px;
        font-weight: 600;
        border-left: solid 4px #ffc710;
        padding-left: 30px;
        max-width: 800px;
        word-wrap:break-word;
    }

    @media only screen and (max-width: 1289px){
        button {
            width: 400px;
            height: 50px;
        }
        button:hover {
            width: 300px;
        }
    }

    @media only screen and (max-width: 491px){
        button {
            width: 70%;
            height: 50px;
            font-size: 15px;
        }
        button:hover {
            width: 260px;
        }
        p {
            max-width: 250px;
            font-size: 15px;
        }
    }
</style>