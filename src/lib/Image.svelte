<script>
    export let src;
    export let title;
    export let alt;
</script>

<figure>
    <img {src} {alt} {title} />
</figure>

<style>
    img {
        width: 900px;
    }

    @media screen and (max-width: 1000px) {
        img {
            width: 500px;
        }
    }
</style>
