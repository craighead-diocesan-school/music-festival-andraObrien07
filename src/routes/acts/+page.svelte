<script>
    import Header from "$lib/Header.svelte";
    import Footer from "$lib/Footer.svelte";
    import Nav from "$lib/Nav.svelte";
</script>

<Header />
<Nav />

<main>
    <h2>Acts / Wāhanga</h2>
    <div class=" ActsMain">
        <img
            src="/Acts/danny-howe.jpg"
            alt="back stage view of band playing with sun streaming in"
        />
        <p>
            The music festival boasts an exciting lineup of talented musicians
            from a variety of genres, promising a diverse and entertaining
            experience for all attendees.
        </p>
        <p>
            On the main stage, the headliners are a mix of established and
            up-and-coming acts, guaranteed to draw in large crowds. The first
            headliner is a popular rock band, known for their high-energy
            performances and catchy hooks. They will be followed by a
            chart-topping pop artist, whose upbeat and infectious hits are sure
            to get the crowd dancing and singing along. The final headliner is a
            legendary hip-hop artist, whose iconic rhymes and charismatic stage
            presence will bring the festival to a thrilling close.
        </p>

        <img
            src="/Acts/maxwell-collins.jpg"
            alt="backstage view of someone singing with crowd watching"
        />
        <p>
            On the second stage, indie bands and singer-songwriters showcase
            their unique styles and sounds. The performers on this stage are
            often the most buzzed-about acts of the festival, with a loyal and
            passionate following. From dreamy shoegaze bands to alternative rock
            acts, the second stage offers a more intimate and personal
            experience for music lovers looking to discover new artists.
        </p>
        <p>
            The third stage is dedicated to up-and-coming artists from different
            genres, providing a platform for emerging talent to showcase their
            skills and gain exposure. This stage is a great opportunity for
            attendees to discover new artists and support the next generation of
            musicians.
        </p>
        <img
            src="/Acts/colin-lloyd.jpg"
            alt="close up of a DJ with a microphone on stage"
        />
        <p>
            Throughout the festival, DJs and electronic acts keep the energy up
            between sets, playing a mix of classic and contemporary dance tracks
            that will keep the crowd moving and grooving.
        </p>
        <p>
            Overall, the music festival offers a diverse and exciting lineup
            that caters to different tastes and styles. From established
            headliners to emerging talent, the festival promises a memorable and
            thrilling musical experience for all attendees.
        </p>

        <img
            src="/Acts/aditya-chinchure.jpg"
            alt="behind crowd with rainbow lights and white confetti falling"
        />
    </div>
</main>
<Footer />

<style>
    p {
        font-family: "Ibarra Real Nova";
        color: #612a9e;
        width: 800px;
        text-align: center;
        padding-bottom: 25px;
        padding-top: 25px;
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
        margin-bottom: 20px;
    }
    img {
        width: 900px;
    }

    .ActsMain {
        display: flex;
        flex-direction: column;
        align-items: center;
    }

    @media screen and (max-width: 1000px) {
        .ActsMain {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin-left: 7px;
            margin-right: 7px;
        }

        img {
            width: 500px;
        }
        p {
            font-family: "Ibarra Real Nova";
            color: #612a9e;
            text-align: center;
            width: 400px;

            padding-top: 10px;
        }
        h2 {
            font-size: 2em;
            margin-top: 20px;
            margin-bottom: 5px;
        }
    }
</style>
