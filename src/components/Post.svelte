<script lang="ts">
    export let title: string;
    export let image: string;
    export let description: string;

    var visibility:boolean = false;

    function changeVisibility(){
        visibility = !(visibility)
    }

</script>

<div id="new">
    <h1>{title}</h1>
    <button on:click={() => changeVisibility()}>
        <div class="post">
            <img src="{image}" alt="{title}">
            {#if visibility}
                <p>{description}</p>
            {/if}
        </div>
    </button>
</div>


<style>
    button {
        width: max-content;
        height: max-content;
        background-color: transparent;
        border: none;
    }
    .post {
        width: 500px;
        height: max-content;
        margin-bottom: 100px;
        display: flex;
        flex-direction: column;
        align-items: center;
        background-color: #7b00ff;
        border-radius: 15px;
        transition: 1s ease-in!important;
    }

    .post p {
        height: 100%;
        width: 340px;
        font-weight: 400;
        color: #fff;
        word-wrap: normal;
        text-align: center;
        padding: 8px;
    }

    #new h1 {
        font-size: 20px;
        color: #646363;
        text-align: center;
    }

    .post img {
        max-width: 450px;
        padding: 20px;
        border: solid none;
        border-radius: 10px;
    }

    @media only screen and (max-width: 850px){
        .post {
            width: 300px;
        }
        
        .post img {
            max-width: 270px;
        }
        .post p {
            font-size: 10px;
            width: 200px;
        }
    }

</style>