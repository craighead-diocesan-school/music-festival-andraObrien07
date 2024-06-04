<script>
    export let src;
    export let caption;
    export let alt;
</script>

<figure>
    <img {src} {alt} {caption} />
    <!-- <figurecaption> {caption}</figurecaption> -->
</figure>

<style>
    img {
        width: 900px;
    }
</style>
