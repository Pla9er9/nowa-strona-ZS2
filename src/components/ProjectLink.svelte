<div class="projectLink">
    <slot></slot>
</div>

<style>
    .projectLink {
        display: flex;
        align-items: center;
        justify-content: center;
        background-color: #4a55ff;
        width: 400px;
        height: 50px;
        border-radius: 15px;
    }

    @media only screen and (max-width: 520px) {
        .projectLink {
            width: 250px;
        }
    }

</style>