<script lang="ts">
    export let title: string;
    export let image: string;
    export let description: string;

</script>

<div id="new">
    <h1>{title}</h1>
    <div class="post">
        <div style="display: flex;        justify-content: center;">
            <img src="news/{image}" alt="{title}">
            <p>{description}</p>
        </div>
    </div>
</div>


<style>
    .post {
        width: 500px;
        height: max-content;
        margin-bottom: 100px;
        background-color: #f6f6f6;
        border-radius: 15px;
        transition: 1s !important;
    }

    .post:hover p {
        display: block;
        margin-right: 50px;
    }

    .post:hover img {
        margin-right: 50px;
        margin-left: 50px;
    }

    .post:hover {
        width: max-content;
        background-color: #ecddc6;
    }


    #new h1 {
        font-size: 20px;
        color: #646363;
        text-align: center;
    }

    .post img {
        max-width: 450px;
        padding: 20px;
    }

    .post p {
        align-self: flex-center;
        height: 100%;
        width: 340px;
        font-weight: 400;
        display: none;
        word-wrap: normal;
        color: rgb(22, 21, 21);
    }

</style>