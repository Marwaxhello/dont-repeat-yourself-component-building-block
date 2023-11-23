<script>
  let currentVideoIndex = 0;

  const videos = [
    "https://www.youtube.com/embed/yr-rRMElLFg?si=CkdyjnxpUFMqM7se",
    "https://www.youtube.com/embed/KaX4moO99mA?si=-Ga2yVRDq6corNkW",
    "https://www.youtube.com/embed/hMSZTRgLT-o?si=Rgq8e0O4NJSclR8L",
    "https://www.youtube.com/embed/UQa9sK42OOM?si=OreJuspyQvJhee6f",
    "https://www.youtube.com/embed/r51hdmjgJNw?si=XAuYvcJTQC-dabr3",
    "https://www.youtube.com/embed/vC9mJ-GI7xI?si=Eb2FaZ2zhIfLaU59",
  ];

  const videoInfo = [
    {
      title: "Onderzoeken en begrijpen",
      content: `
          De wereld wordt steeds complexer en het maken van tekeningen kan helpen
        bij het begrijpen en overbrengen van ideeën. Visual thinking wordt in
        het bedrijfsleven steeds meer toegepast maar voor de praktijk van het
        hoger onderwijs vormt het nog een uitdaging. Het is nog niet zo gewoon
        om als docent (live) te tekenen tijdens het geven van de les of om als
        student visuele aantekeningen te maken (sketchnotes). <br />
        <br />
        En dit terwijl het aantoonbaar gunstig is om studenten zelf te laten tekenen.
        Zo kunnen ze zich beter concentreren en worden er meerdere zintuigen tegelijk
        geprikkeld. Naast het verhogen van de participatie wordt het ook voor de
        docent een stuk inzichtelijker wie er actief meedoet aan de les en wat er
        van de stof begrepen wordt. De docent kan de sketchnotes tijdens of na de
        les bekijken en daar weer vragen over stellen. <br />
        <br />
        Waar je bij geschreven tekst gemakkelijk een hele zin of woord kunt overschrijven
        zonder daadwerkelijk te begrijpen waar het over gaat, is dat bij het maken
        van visuele aantekeningen veel moeilijker. Andersom hoef je de taal niet
        volledig meester te zijn om toch aan te tonen dat je een bepaalde term wel
        begrijpt. In de kennisclip wordt uitgelegd hoe visual thinking studenten
        de lesstof beter laat begrijpen en hoe de werkvormen op het platform hierbij
        kunnen helpen.
      `,
    },
       {
      title: "Organiseren en plannen",
      content: `
        Een belangrijk onderdeel van studeren is het plannen en organiseren van
        je studie. Veel studenten zeggen dat ze ‘beter hadden moeten plannen’
        als ze een vak of project niet halen. Er zijn talloze digitale tools en
        agenda’s te vinden waarmee studenten een planning kunnen maken maar het
        maken van een ‘analoge’ planning (iets wat zoveel betekent als met pen
        en papier) helpt het best bij het onthouden van de informatie. <br />
         <br />
        Er zitten namelijk een heleboel ‘visuele aanwijzingen’ in deze handeling: zoals de
        vormen van de letters, het tactiele gevoel van pen en papier, de
        plaatsing van jouw woorden op het papier en details, zoals gevouwen
        hoekjes en de kleur van de inkt.Je brein absorbeert als het ware al deze informatie die later als een
        trigger fungeert: je kan de informatie exacter terughalen uit je
        geheugen. In de kennisclip wordt uitgelegd hoe visual thinking studenten
        kan helpen te organiseren en plannen en hoe de werkvormen op het
        platform hierop aansluiten.
      `,
    },
      {
      title: "Leren over anderen",
      content: `
        Als mensheid zijn we gewend om samen te werken. De meesten van ons doen
        dat op hun werk en als ze als zelfstandige werken, zullen ze op andere
        manieren met andere mensen te maken krijgen. Ook in het hbo wordt er
        door zowel docenten als studenten veel samengewerkt. Studenten worden op
        die manier voorbereid op hun werkzame leven. <br />
        <br />
        Docenten werken meestal ook in teams met andere docenten én op een
        bepaalde manier ook met hun studenten. Juist in een tijd waarin het
        onderwijs minder klassikaal wordt en docenten van een ‘alwetende’ rol
        naar een meer coachende en gelijkwaardige rol gaan, is samenwerking erg
        belangrijk. <br />
        <br />
        Er zijn allerlei manieren om samenwerking goed te laten verlopen maar in
        het hbo wordt nog weinig visueel samengewerkt. En dat terwijl visueel
        werken kan helpen om mensen in een team meer over elkaar te weten te
        laten komen en de neuzen dezelfde kant op te krijgen. In de kennisclip
        wordt uitgelegd hoe visual thinking het leerproces van een groep kan
        ondersteunen en wanneer welke visuele werkvormen van toepassing kunnen
        zijn.
      `,
    },
    {
      title: "Leren over jezelf en reflecteren",
      content: `
        Het hoger onderwijs wordt de komende jaren flexibeler en docenten zullen
        steeds meer feedback en begeleiding op maat gaan geven. Deze individuele
        manier van coaching en ‘vraag-gestuurd’ onderwijs vraagt om een andere
        houding van zowel de coach als de student. Waar de docent minder aan
        kennisoverdracht gaat doen en zich meer als een coach zal opstellen, zal
        de student juist meer initiatief moeten nemen.<br />
        <br />
        Daarnaast komt er meer focus te liggen op het persoonlijke verhaal en
        (zelf)reflectie van de student. Zeker bij opleidingen waar persoonlijke
        ‘kwaliteiten’ ook een grote rol spelen. Veel studenten vinden het
        schrijven van een reflectie vervelend. Ook houden ze het vaak
        oppervlakkig en/of laten het door Chat GPT schrijven. Visualisaties
        kunnen heel krachtig zijn en ervoor zorgen dat een reflectie, en het
        gesprek dat daarop volgt, minder oppervlakkig blijft. <br />
        <br />
        In visual thinking wordt veel gebruik gemaakt van beeldende metaforen om dingen
        begrijpelijker en beter invoelbaar te maken. Door iets wat je niet kent te vergelijken met wat je wel kent, begrijp
        je het en kan je beter over het onderwerp nadenken. Door studenten
        gebruik te laten maken van metaforen geef je ze een manier om zichzelf
        uit te drukken. Daarnaast geeft het de begeleider/docent/coach een
        ingang voor een gesprek. In de kennisclip wordt uitgelegd hoe visual
        thinking en het gebruik van metaforen kunnen helpen om studenten te
        laten reflecteren . Ook de werkvormen op het platform kunnen hierbij
        helpen.
      `,
    },
     {
      title: "Communiceren en presenteren",
      content: `
       Als hbo-student moet je regelmatig een presentatie geven of een idee
        overbrengen. Als docent doe je eigenlijk niet anders. Meestal worden
        hier powerpoints voor gebruikt. Powerpoint-presentaties zijn op zich
        prima maar ze hebben wel een paar nadelen:  
        
        <ul>
        <li>Ze vragen om het gebruik van veel tekst</li>
        <li>Ze zijn lineair</li>
        <li>
          Ze blijven niet in beeld dus je vergeet makkelijk wat er besproken is
        </li>
        <li>Ze zijn saai en spreken niet tot de verbeelding</li>
      </ul>

        Visual thinking kan helpen bij het tot de kern komen van een verhaal
        waardoor je het ook krachtiger, en misschien zelfs in één plaat, kan
        overbrengen. In de kennisclip wordt uitgelegd hoe je dat doet. Met
        behulp van een paar handige tips maak je een presentatie visueler en
        daarmee interessanter. Ook de werkvormen op het platform kunnen hierbij
        helpen.
      `,
    },
        {
      title: "Creatief denken",
      content: `
       Op bijna alle hbo-opleidingen moeten dingen ‘bedacht worden’. Veel
       studenten vinden dit een lastig onderdeel van hun studie. Ze hebben
       moeite met het bedenken van iets nieuws en origineels, laat staan dat ze
       dat willen uittekenen. Ze ‘durven’ nog niet te tekenen en beweren dat ze
       het niet kunnen. <br />
       <br />
       Meestal bedoelen mensen dan dat ze niet een ‘mooie’ of ‘realistische’
       tekening kunnen maken. Alleen is het maken van een mooie tekening iets
       anders dan effectief communiceren. Om creatief te leren denken, hoef je
       niet ‘mooi’ te kunnen tekenen. Het gaat namelijk niet om het resultaat
       (het ‘artefact’) maar om het proces. 
       John Berger, een kunstcriticus en schrijver beschrijft het tekenen als
       het oversteken van een rivier: Iedere pennestreek die je op papier zet
       is een stap richting de overkant. <br />
       <br />
        Het proces van schetsen kan als het ware gezien worden als een
        ‘conversatie’ tussen de gedachten en de schets. De schets ontstaat
        vanuit je huidige kennis: je ziet dat iets zo is. Het lezen of
        interpreteren ervan leidt tot nieuwe kennis: je ziet dat iets ook anders
        kan zijn. En dit is juist zo belangrijk bij het creëren van nieuwe
        dingen. <br />
        <br />
        Bovendien kan het heel nuttig zijn om op een totaal andere manier naar
        een onderwerp te kijken en er zelfs voor zorgen dat je het opeens veel
        beter begrijpt! In de kennisclip wordt uitgelegd hoe je tekenen kan
        gebruiken om creatiever te denken. Ook de werkvormen op het platform
        kunnen hierbij helpen.
      `,
    },
 
  ];

  function playPrevious() {
    if (currentVideoIndex > 0) {
      currentVideoIndex -= 1;
    }
  }

  function playNext() {
    if (currentVideoIndex < videos.length - 1) {
      currentVideoIndex += 1;
    }
  }

</script>


<main>
  <section>

    <article class="video-player">
    <h2>{videoInfo[currentVideoIndex].title}</h2>
    <p>{@html videoInfo[currentVideoIndex].content}</p>
    
    <aside>
    <button on:click={playPrevious}>
    <img
    class="left-arrow"
    src="./arrow.svg"
    alt="Knop met pijl naar volgende video"
    />
    </button>

    <iframe class="video-iframe" src={videos[currentVideoIndex]} allowfullscreen />

    <button on:click={playNext}>
     <img
    class="right-arrow"
    src="./arrow.svg"
    alt="Knop met pijl naar volgende video"
    />

    </button>
    </aside>
    
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

    --vtPrimaryFont: "rigid-square", sans-serif;
    --vtSecondaryFont: "yrsa", serif;
  }

  /* Iframe styling */

  .video-iframe {
    margin-bottom: 2em;
    margin-top: 4em;
    width: 560px;
    height: 315px;
  }

.video-iframe iframe {
  width: 100%;
  height: 100%;
  position: absolute;
  top: 0;
  left: 0;
}

@media only screen and (max-width: 480px) {
  /* Adjust styles for screens smaller than 480px (typical mobile sizes, including iPhone 13) */
  .video-iframe {
    margin-bottom: 0.5em;
    margin-top: 1em;
    width: 100%;
  }
}

  aside {
    display: flex;
    justify-content: center;
    align-items: center;
  }

  /* Arrow buttons */

  button {
    border: none;
    background-color: white;
    cursor: pointer;
  }

  button:hover {
    border-radius: 5px;
    
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

  p {
    text-align: left;
    text-transform: none;
    line-height: 1.5rem;
    margin-left: 3em;
    margin-right: 3em;
    font-family: var(--vtPrimaryFont);

  }

  /* Headers */

  h1 {
    font-size: 3.157rem;
    font-family: var(--vtPrimaryFont);
    color: var(--vtDarkBlue);
  }

  h2 {
    font-size: 2rem;
    font-family: var(--vtPrimaryFont);
    line-height: 1.5rem;
    color: var(--vtDarkBlue);
    margin-left: 1.5em;
    margin-right: 1.5em;
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
