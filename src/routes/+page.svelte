<script>
  import Header from "$lib/Header.svelte";
  import Footer from "$lib/Footer.svelte";
  import Nav from "$lib/Nav.svelte";
  import Image from "$lib/Image.svelte";
</script>

<Header />
<Nav />
<main>
  <div class="SunMain">
    <Image
      src="/Home:SunBurst/tony-pham.jpg"
      alt="color explosion at festival"
      title="Photo taken by Tony Pham"
    />
    <p>
      Welcome to the ultimate music festival experience! Get ready for a day
      filled with live music, great food, and unforgettable memories.
    </p>
    <p class="Maori">
      Nau mai ki te wā tuki puoro mutunga kore! Kia rite mō tētahi rā ki tonu i
      te puoro ora, ngā kai reka, me ngā maharatanga mutungakore
    </p>
    <Image
      src="/Home:SunBurst/james-genchi.jpg "
      alt=" People at festival with confetti"
      title="Photo taken by James Genchi"
    />
    <p>
      Tickets are $200 per person, and festival goers must be 15 years of age or
      older.
    </p>

    <p class="Maori">
      He $200 ia tangata ngā tīkiti, ā, me 15 tau te pakeke o te hunga haere ki
      te taiopenga, neke atu rānei.
    </p>

    <p>Tent sites are $15 per night, or $40 with a tent included.</p>

    <p class="Maori">
      Ko ngā wāhi puni he $15 ia pō, $40 rānei mēnā ka tukuna he tēneti.
    </p>

    <Image
      src="/Home:SunBurst/aranxa-esteve.jpg"
      alt="People sitting on hill at festival"
      title="Photo taken by Aranxa Esteve"
    />
  </div>
</main>

<Footer />

<style>
  p {
    font-family: "Ibarra Real Nova";
    color: #7e20eb;
    text-align: center;
    width: 800px;
    /* padding-bottom: 25px; */
    padding-top: 25px;
    font-weight: bolder;
  }
  .Maori {
    padding-top: 2px;
    padding-bottom: 25px;
  }

  main {
    padding-top: 50px;
  }

  .SunMain {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  @media screen and (max-width: 1000px) {
    .SunMain {
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
  }
</style>
