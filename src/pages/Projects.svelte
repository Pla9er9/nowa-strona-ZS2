<script lang="ts">
    import ProjectLink from '../components/ProjectLink.svelte'
</script>
<div class="linkContainer">
    <ProjectLink>
        <a href="https://docs.google.com/presentation/d/1tmsn-KAHN4t1Viu85N7U8tAGpu6rIGg-JPlMXxb8Ipk/edit#slide=id.g12f89e00f0f_2_0">E-Twinning – j.angielski</a>
    </ProjectLink>
    <br><br>
    <ProjectLink>
        <a href="https://view.genial.ly/604a5b3e0dacf60d939cf9a7?fbclid=IwAR0_n6z1IbdS0D0P1MmGE_1o3NHkpKKhISmn1mjiE6vLAw5AbK6k_RUZYfY">E-Twinning – j.niemiecki</a>
    </ProjectLink>  
</div>

<br>
<div class="linkContainer">
    <ProjectLink>
        <a href="https://view.genial.ly/604a5b3e0dacf60d939cf9a7?fbclid=IwAR0_n6z1IbdS0D0P1MmGE_1o3NHkpKKhISmn1mjiE6vLAw5AbK6k_RUZYfY">Projekty ETwinning W J.Niem.</a>
    </ProjectLink>
</div>

<div class="linkContainer">
    <ProjectLink>
        <a href="https://zsp2wagrowiec.pl/cms/wp-content/uploads/2022/02/Szkola-Wodorowa.docx">Szkoła wodorowa</a>
    </ProjectLink>
</div>

<div class="linkContainer">
    <ProjectLink>
        <a href="https://padlet.com/osmolenska/1bvphhkj5brdnt5f?fbclid=IwAR13cvORrLW5pO9sYh-I6fI-1QLLmglcGUj3NH4bDy2wnRy4nC8eA9ILyko">Super hotelarze</a>
    </ProjectLink>
</div>

<div class="linkContainer">
    <ProjectLink>
        <a href="Matematyczno-Przyrodniczy">Matematyczno-Przyrodniczy Projekt z UE</a>
    </ProjectLink>
</div>

<h2>Projekt z UE</h2>
<img src="https://zsp2wagrowiec.pl/cms/wp-content/uploads/2021/09/x2021-09-03_21h14_00-1024x723.png.pagespeed.ic.DjvCtKLRf-.webp" alt="projekt z ue">

<div id="projectUeLinks">
    <a href="https://zsp2wagrowiec.pl/cms/wp-content/uploads/2021/09/REGULAMIN_kolor.pdf">Terminy22</a>

    <a href="https://zsp2wagrowiec.pl/cms/wp-content/uploads/2022/04/godziny-zajec.docx">Terminy</a>

    <a href="https://zsp2wagrowiec.pl/cms/wp-content/uploads/2022/10/godziny-zajec-1b.docx">Regulamin</a>
</div>

<style>
    a {
        font-size: 1.3em;
        color: #fff;
    }

    .linkContainer {
        border-left: solid 4px #ffc710;
        padding-left: 20px;
        margin-bottom: 50px;
    }
    img {
        border-left: solid 3px #4a55ff;
        border-right: solid 3px #4a55ff;
        border-radius: 15px;
        margin-bottom: 30px;
    }

    #projectUeLinks {
        display: flex;
        justify-content: space-between;
        width: 350px;
        margin-bottom: 50px;
    }
    #projectUeLinks a{
        color: #4a55ff;
    }

    @media only screen and (max-width: 1550px) {
        img {
            width: 600px;
        }
    }

    @media only screen and (max-width: 680px) {
        img {
            width: 90%;
        }
    }

    @media only screen and (max-width: 520px) {
        a {
            font-size: 1em;
            padding: 8px;
        }
    }

</style>