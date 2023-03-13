<script>
    export let title = "Ninja Gaming"
</script>

<div class="title">
    <img src="/controller.jpeg" alt="site logo">
    <h1>{title}</h1>
</div>

<style>
    .title
    {
        display: flex;
    }
    .title img
    {
        margin-top: 25px;
        display: inline-block;
        filter: invert(88%) sepia(18%) saturate(500%) hue-rotate(199deg) brightness(100%) contrast(100%);
        height: 2rem ;
    }
    .title h1
    {
        margin-left: 10px;
    }
</style>