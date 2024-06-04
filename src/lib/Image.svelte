<script>
    export let src;
    export let caption;
    export let alt;
</script>

<figure>
    <img {src} {alt} title={caption} />
    <figurecaption>"Photo taken by caption" {caption}</figurecaption>
</figure>

<style>
</style>
