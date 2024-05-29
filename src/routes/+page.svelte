<script>
  import Header from "$lib/Header.svelte";
  import Footer from "$lib/Footer.svelte";
  import Nav from "$lib/Nav.svelte";
</script>

<Header />
<Nav />
<main>
  <div class="SunMain">
    <img src="/Home:SunBurst/tony-pham.jpg" alt="color explosion at festival" />
    <p>
      Welcome to the ultimate music festival experience! Get ready for a day
      filled with live music, great food, and unforgettable memories.
    </p>
    <p class="Maori">
      Nau mai ki te wā tuki puoro mutunga kore! Kia rite mō tētahi rā ki tonu i
      te puoro ora, ngā kai reka, me ngā maharatanga mutungakore
    </p>
    <img
      src="/Home:SunBurst/james-genchi.jpg "
      alt=" People at festival with confetti"
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

    <img
      src="/Home:SunBurst/aranxa-esteve.jpg"
      alt="People sitting on hill at festival"
    />
  </div>
</main>

<Footer />

<style>
  p {
    font-family: "Ibarra Real Nova";
    color: #612a9e;
    text-align: center;
    width: 800px;
    /* padding-bottom: 25px; */
    padding-top: 25px;
  }
  .Maori {
    padding-top: 2px;
    padding-bottom: 25px;
  }

  main {
    padding-top: 50px;
  }

  img {
    width: 900px;
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
  }
</style>
