<script>
     export let src;
    export let caption;
    export let alt;
</script>
<figure>
    <img
    src={src}
    alt={alt}
    title={caption}
    <figcaption>"Photo taken by caption" {caption}</figcaption>

</figure>