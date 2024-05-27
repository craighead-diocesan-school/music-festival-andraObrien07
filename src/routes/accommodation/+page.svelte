<script>
    import Header from "$lib/Header.svelte";
    import Footer from "$lib/Footer.svelte";
    import Nav from "$lib/Nav.svelte";
</script>

<Header />
<Nav />

<main>
    <h2>Accommodation / Whare Noho</h2>

    <div class="AcomoMain">
        <img
            src="/Accommodation/danny-howe-2.jpg"
            alt="behind crowd with white confetti falling"
        />

        <p>
            Experience the ultimate music festival adventure with our tent
            accommodation packages! With our comfortable and convenient tents,
            you can immerse yourself in the festival atmosphere and stay close
            to all the action.
        </p>
        <p>
            Our tents are spacious and come equipped with everything you need
            for a comfortable stay. With comfortable beds, pillows, and
            blankets, you can get a good night's sleep and wake up feeling
            refreshed and ready for another day of music and fun.
        </p>
        <img
            src="/Accommodation/hanny-naibaho.jpg"
            alt="behind crowd view of stage and pruple lights"
        />
        <p>
            Located within the festival grounds, our tents are just a short walk
            away from all the stages and attractions. You won't have to worry
            about transportation or navigating crowds to get to the festival –
            you'll be right in the heart of it all.
        </p>
        <p>
            Our tents also come with a range of amenities to make your stay even
            more comfortable. You'll have access to clean restroom facilities,
            hot showers, and charging stations for your devices. We also have a
            dedicated staff available to assist with any needs or questions you
            may have during your stay.
        </p>

        <img
            src="/Accommodation/krists-luhaers.jpg"
            alt="person dancing in front of tents"
        />
        <p>
            But the best part of our tent accommodation packages is the
            community. You'll be surrounded by other festival-goers who are just
            as excited as you are to be a part of the experience. You'll make
            new friends, share stories, and create memories that will last a
            lifetime.
        </p>
        <p>
            Don't miss out on this opportunity to enhance your music festival
            experience. Book your tent accommodation package today and get ready
            for an unforgettable adventure. We can't wait to see you there!
        </p>
        <img
            src="/Accommodation/vonecia-carswell.jpg"
            alt="people dancing and talking with eachother"
        />
    </div>
</main>
<Footer />

<style>
    p {
        font-family: "Ibarra Real Nova";
        text-align: center;
        color: black;
    }

    h2 {
        font-family: "griffy";
        font-weight: 400;
        font-style: normal;
        font-size: 4em;
        color: black;
        align-items: center;
        display: flex;
        justify-content: center;
        margin-top: 50px;
        margin-bottom: 28px;
    }

    img {
        width: 700px;
        /* justify-content: center;
        display: flex; */
    }

    .AcomoMain {
        width: 900px;
        margin: auto;
        align-items: center;
    }
</style>
