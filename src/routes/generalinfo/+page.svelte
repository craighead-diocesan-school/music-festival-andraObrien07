<script>
    import Header from "$lib/Header.svelte";
    import Footer from "$lib/Footer.svelte";
    import Nav from "$lib/Nav.svelte";
    import Image from "$lib/Image.svelte";
</script>

<Header />
<Nav />

<main>
    <h2>General Information / Mōhiohio Whānui</h2>
    <div class="GinfoMain">
        <Image
            src="/General Information/jade-masri.jpg"
            alt="people in the crowd on other peoples shoulders"
            title="Photo taken by Jade Masri"
        />
        <p>
            Welcome to the ultimate music festival experience! Get ready for a
            day filled with live music, great food, and unforgettable memories.
        </p>
        <Image
            src="/General Information/tijs-van-leur.jpg"
            alt="people in front of stage with orange hue"
            title="Photo taken by Tijs Van Leur"
        />
        <p>
            Our festival features a diverse lineup of talented musicians from
            different genres, sure to satisfy every taste in music. With
            multiple stages set up throughout the venue, you can easily move
            from one act to the next, discovering new favorites and enjoying
            classic hits.
        </p>

        <Image
            src="/General Information/colin-lloyd-2.jpg"
            alt="view from mid crowd of stage with flames"
            title="Photo taken by Colin Lloyd"
        />
        <p>
            From up-and-coming artists to established headliners, we have
            curated an exciting lineup that will keep you dancing and singing
            along all day long. Our festival is the perfect opportunity to
            discover new music, see your favorite artists live, and make lasting
            memories with friends and family.
        </p>

        <Image
            src="/General Information/samuel-regan-asante.jpg"
            alt="purple confetti falling on crowd with stage behind it"
            title="Photo take by Samuel Regan Asante"
        />
        <p>
            But the music is just the beginning. Our festival also boasts an
            impressive selection of food vendors, offering everything from
            classic festival fare to more gourmet options. You won't go hungry
            with the delicious treats and refreshing beverages available
            throughout the venue.
        </p>
    </div>
</main>
<Footer />

<style>
    p {
        font-family: "Ibarra Real Nova";
        width: 800px;
        color: #7e20eb;
        text-align: center;
        padding-bottom: 25px;
        padding-top: 25px;
        font-weight: bolder;
    }

    h2 {
        font-family: "griffy";
        font-weight: 400;
        font-style: normal;
        font-size: 4em;
        color: black;
        display: flex;
        justify-content: center;
        margin-top: 50px;
        margin-bottom: 5px;
    }

    .GinfoMain {
        display: flex;
        flex-direction: column;
        align-items: center;
    }
    @media screen and (max-width: 1000px) {
        .GinfoMain {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin-left: 7px;
            margin-right: 7px;
        }

        p {
            font-family: "Ibarra Real Nova";

            text-align: center;
            width: 350px;
            font-size: 12px;
            padding-top: 10px;
        }
        h2 {
            font-size: 1.65em;
            margin-top: 20px;
            margin-bottom: 5px;
            text-align: center;
        }
    }
</style>
