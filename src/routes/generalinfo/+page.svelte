<script>
    import Header from "$lib/Header.svelte";
    import Footer from "$lib/Footer.svelte";
    import Nav from "$lib/Nav.svelte";
</script>

<Header />
<Nav />

<main>
    <h2>General Information / Mōhiohio Whānui</h2>
    <img
        src="/General Information/colin-lloyd-2.jpg"
        alt="view from mid crowd of stage with flames"
    />
    <p>
        Welcome to the ultimate music festival experience! Get ready for a day
        filled with live music, great food, and unforgettable memories.
    </p>
    <img
        src="/General Information/jade-masri.jpg"
        alt="people in the crowd on other peoples shoulders"
    />
    <p>
        Our festival features a diverse lineup of talented musicians from
        different genres, sure to satisfy every taste in music. With multiple
        stages set up throughout the venue, you can easily move from one act to
        the next, discovering new favorites and enjoying classic hits.
    </p>
    <img
        src="/General Information/samuel-regan-asante.jpg"
        alt="purple confetti falling on crowd with stage behind it"
    />
    <p>
        From up-and-coming artists to established headliners, we have curated an
        exciting lineup that will keep you dancing and singing along all day
        long. Our festival is the perfect opportunity to discover new music, see
        your favorite artists live, and make lasting memories with friends and
        family.
    </p>
    <img
        src="/General Information/tijs-van-leur.jpg"
        alt="people in front of stage with orange hue"
    />
    <p>
        But the music is just the beginning. Our festival also boasts an
        impressive selection of food vendors, offering everything from classic
        festival fare to more gourmet options. You won't go hungry with the
        delicious treats and refreshing beverages available throughout the
        venue.
    </p>
</main>
<Footer />

<style>
    p {
        font-family: "Ibarra Real Nova";
        padding: 7px;
    }

    h2 {
        font-family: "griffy";
        font-weight: 400;
        font-style: normal;
        font-size: 4em;
        color: black;
    }
    img {
        width: 700px;
        /* align-items: center; */
        display: flex;
        justify-content: center;
    }
</style>
