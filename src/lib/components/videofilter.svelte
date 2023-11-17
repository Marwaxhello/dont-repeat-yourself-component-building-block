<main>
    <section>
    <article class="teksten">
    <h2>Onderzoeken en begrijpen</h2>
  <p>
    De wereld wordt steeds complexer en het maken van tekeningen kan helpen bij
    het begrijpen en overbrengen van ideeën. Visual thinking wordt in het
    bedrijfsleven steeds meer toegepast maar voor de praktijk van het hoger
    onderwijs vormt het nog een uitdaging. Het is nog niet zo gewoon om als
    docent (live) te tekenen tijdens het geven van de les of om als student
    visuele aantekeningen te maken (sketchnotes). <br />
    <br />
    En dit terwijl het aantoonbaar gunstig is om studenten zelf te laten tekenen. Zo kunnen ze zich beter
    concentreren en worden er meerdere zintuigen tegelijk geprikkeld. Naast het
    verhogen van de participatie wordt het ook voor de docent een stuk
    inzichtelijker wie er actief meedoet aan de les en wat er van de stof
    begrepen wordt. De docent kan de sketchnotes tijdens of na de les bekijken
    en daar weer vragen over stellen. <br />
    <br />
    Waar je bij geschreven tekst gemakkelijk een hele zin of woord kunt overschrijven zonder daadwerkelijk te begrijpen
    waar het over gaat, is dat bij het maken van visuele aantekeningen veel
    moeilijker. Andersom hoef je de taal niet volledig meester te zijn om toch
    aan te tonen dat je een bepaalde term wel begrijpt. In de kennisclip wordt
    uitgelegd hoe visual thinking studenten de lesstof beter laat begrijpen en
    hoe de werkvormen op het platform hierbij kunnen helpen.
  </p>
   </article>

  <article class="youtube-vid">

      <button>
        <img
          class="left-arrow"
          src="./arrow.svg"
          alt="Knop met pijl naar volgende video"
        />
      </button>


  <iframe
    width="560"
    height="315"
    src="https://www.youtube.com/embed/yr-rRMElLFg?si=CkdyjnxpUFMqM7se"
    title="YouTube video player"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
    allowfullscreen
  />

      <!-- <article class="beschrijving">
      <h3 class="youtube-video-naam">
        Visual thinking in het hbo: onderzoeken en begrijpen
      </h3>

      <p>
        Deze kennisclip gaat over visual thinking en hoe het kan worden
        toegepast om zowel studenten als docenten in het hbo op een andere
        manier te leren onderzoeken.
      </p>

      <p>
        Deze kennisclips zijn onderdeel van het platform ‘Visual thinking in het
        hbo’. Dit platform staat vanaf 2024 online. Tot die tijd kunnen
        werkvormen opgevraagd worden bij Charley Muhren, docent en onderzoeker
        bij CMD Amsterdam: c.j.muhren@hva.nl.
      </p>

      </article> -->

      <button>
        <img
          class="right-arrow"
          src="./arrow.svg"
          alt="Knop met pijl naar volgende video"
        />
      </button>


  </article>
  </section>
</main>


<style>
   
     :root {

    /* Visual Thinking: Primary Colors: Zie kleuren styleguide of eventueel Figma designs voor gebruik! */

    --vtDarkBlue: #090940;
    --vtLightBlue: #67c5d1;
    --vtYellow: #feb51e;
    --vtRed: #f96c4f;
    --vtWhite: #ffffff;

    /* Visual Thinking: Primary Colors Lichtere versies, ongeveer 80%, 50%, 30% en 10% opacity van de originele kleuren ^
    Zie kleuren styleguide of eventueel Figma designs voor gebruik!  */

    --vtDarkBlue-80: #3a3a66;
    --vtDarkBlue-50: #6b6b8c;
    --vtDarkBlue-30: #9d9db3;
    --vtDarkBlue-10: #ceced9;

    --vtLightBlue-80: #85d1da;
    --vtLightBlue-50: #a4dce3;
    --vtLightBlue-30: #c2e8ed;
    --vtLightBlue-10: #e1f3f6;

    --vtYellow-80: #fec44b;
    --vtYellow-50: #fed378;
    --vtYellow-30: #ffe1a5;
    --vtYellow-10: #fff0d2;

    --vtRed-80: #fa8972;
    --vtRed-50: #fba795;
    --vtRed-30: #fdc4b9;
    --vtRed-10: #fee2dc;

     }


 /* Iframe styling */

  .youtube-vid {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-bottom: 2em;
    margin-top: 4em;
  }

  /* Arrow buttons */
   
  button{
    border: none;
    background-color: white;
  }

  button:hover{
    background-color: #FEB51F;
  }

  .right-arrow {
    margin-left: 1em;
    transform: rotate(270deg);
  }

  .left-arrow {
    margin-right: 1em;
    transform: rotate(90deg);
  }


 /* Kennisclip teksten */

  .teksten{
    text-align: left;
    text-transform: none;
    line-height: 1.5rem;
    margin-left: 3em;
    margin-right: 3em;
  }

/* Headers */

  h1 {
    font-size: 3.157rem;
    font-family: var(--vtPrimaryFont);
    color: var(--vtDarkBlue);
  }

  h2 {
    font-size: 2rem;
    font-family: var(--vtSecondaryFont);
    line-height: 1.5rem;
    color: var(--vtDarkBlue);
  }

  .h1-detail {
    padding-left: 6.7rem;
    max-width: 30rem;
    max-height: 6rem;
  }

  .h2-detail,
  .bold {
    font-size: 1rem;
    font-weight: 400;
    font-family: var(--vtPrimaryFont);
    color: var(--vtSec-DarkBlue);
  }
 
    .bold {
    font-weight: 800;
    text-decoration: underline;
    text-decoration-thickness: 0.2rem;
    text-underline-offset: 0.5rem;
  }

  h3 {
    font-size: 1.2rem;
    font-family: var(--vtSecondaryFont);
    line-height: 1.5rem;
  }

</style>