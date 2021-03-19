# Privacy ontwerpeisen


## Versie en suggesties

Versie 1.0, 15 december 2020, Stabiele versie.

Deze versie van het veiligheidskader is stabiel, suggesties voor wijziging, opmerkingen en aanverwante kunnen in het volgende document aangebracht worden: [Privacy by design - ontwerpeisen Sociale Netwerk Standaard - development versie](https://docs.google.com/document/d/1pBTFgYbyHdUIfAusVIkOTTndL6GudWnrSntns3Q_WsA/edit?usp=sharing). Voel je vrij om in die versie wijzigingen voor te stellen of opmerkingen te plaatsen.

## Introductie
Binnen GIDS Open Standaarden zijn er 3 thema's op privacy gebied geïdentificeerd die aandacht behoeven: 

1. Regie in het zorgproces vertalen naar regie over de data: op welke manier kunnen we zorgen dat de op te bouwen netwerk standaard ook de eigen regie bij de zorgprocessen op de grond versterkt?
2. Data in (juridisch) heterogene omgevingen: op welke manier kunnen we er voor zorgen dat er geen problemen ontstaan tussen data uit verschillende contexten en met verschillende juridische status? 
3. Privacy by Design: hoe kunnen we tot een ontwerpproces komen dat recht doet aan de verschillende aspecten van privacy en dat het mogelijk maakt om met de verschillende betrokken partijen tot een goed ontwerp te komen? 

De onderstaande privacy ontwerpeisen voor de Sociale Netwerk Standaard (SNS) zijn een volgende stap en een vertaling van alle uitgangspunten in het voorafgaande proces naar heldere regels waaraan de standaard moet voldoen. Voor achtergrondinformatie en naslagwerk GIDS Open Standaarden ‘privacy by design’, zie onderaan.

## Privacy ontwerpeisen Sociale Netwerk Standaard (SNS) 

### 1. Relatie Centraal 

Veel van wat er rond gezondheid gebeurt, kan begrepen worden als een combinatie van anderen die over jou oordelen en van een bepaald beeld van jezelf opbouwen, zie ook presentatie "[Zelfbeschikking](https://drive.google.com/file/d/1mjQoOU9swQIu_hg4XtUlobUHCq_raEUJ/view?usp=sharing)". Dat is een proces wat binnen elke relatie opnieuw gebeurt en wat uniek is voor elke relatie binnen alle zorgprocessen. De SNS moet dan ook op eenzelfde manier de relaties centraal zetten. De sociale interacties rond gezondheid, zowel professioneel als informeel, zijn zeer complex en divers. 

Om een dergelijk complex systeem te automatiseren, is het goed om op zoek te gaan naar een kleine eenheid waar al die verschillende interacties uit opgebouwd zijn en die als uitgangspunt te nemen bij het opstellen van de SNS. Relaties vervullen ook die rol: het is een een eenheid die behapbaar en modelleerbaar is en die tegelijkertijd de basis vormt voor alle interacties. Door complexe werkelijkheid strikt op te knippen in relaties, wordt 'ie behapbaar. 

Juridisch gezien is het ook belangrijk om te denken vanuit relaties: persoonsgegevens moeten altijd een duidelijke verantwoordelijke hebben en afhankelijk van je rol heb je verschillende rechten en plichten. Die rechten en plichten zijn tussen de verschillende rollen binnen en buiten de zorg conflicterend. Als het altijd duidelijk is bij welke relatie bepaalde data hoort en wie er verantwoordelijk voor is, kan voorkomen worden dat het systeem juridische spaghetti wordt.

<table>
  <tr>
   <td><strong>Ontwerpeis</strong>
   </td>
  </tr>
  <tr>
   <td>1.1 Van data is altijd duidelijk bij welke relatie het hoort.
   </td>
  </tr>
  <tr>
   <td>1.2. Data die van de de ene naar de andere relatie gebracht wordt moet altijd aan die andere relatie relatie aangepast worden door middel van een of meerdere van de volgende processen: selecteren, samenvatten, annoteren, vertalen.
   </td>
  </tr>
  <tr>
   <td>1.3. Elke partij in een relatie heeft een eigen pseudoniem dat uniek is voor die relatie zodat, zonder aanvullende gegevens, de relaties niet op elkaar te herleiden zijn. Het is het besluit van de gebruiker om relaties aan elkaar kenbaar te maken of niet. De keuze daarvoor is een belangrijk aspect voor het vormgeven van de eigen regie. De AVG eist dat dergelijke (cruciale) privacy aspecten in het ontwerp van het systeem ingebakken zitten (Privacy by Design). Vandaar dat het ook een juridische eis is om dit op een technisch niveau al niet herleidbaar te maken.
   </td>
  </tr>
  <tr>
   <td>1.4. Relaties zijn altijd te verbreken basaal voor de eigen regie.
   </td>
  </tr>
  <tr>
   <td>1.5. Het protocol is agnostisch of de relaties tussen mensen onderling, mensen en machines of tussen machines onderling zijn. De rol van apps (machines), komt in verschillende klantreizen naar voren. Dit levert in privacy opzicht een eigen dynamiek op, zie: "<a href="https://drive.google.com/file/d/1Q5iR98C4YoyQulDPBS5m_8gOVR3Z152_/view?usp=sharing">Big Data the e-health bubble and its fix" TILTing Perspectives</a>. Een van de manieren om de privacy te waarborgen als de persoonsgegevens door machines verwerkt worden, is om ze aan hetzelfde regime te onderwerpen als de relaties tussen mensen.
   </td>
  </tr>
  <tr>
   <td>Uitwerking:<strong> </strong>Architectuur voor de <a href="https://drive.google.com/file/d/1yOG20v8FaCiUProXRX6owja7pIzJ9mCY/view?usp=sharing">De Nieuwe GGZ</a> en <a href="https://drive.google.com/file/d/1ODtHvJZ3qpsFO4AAeNq3T_oPQPWCUQcG/view?usp=sharing">informatiemodel</a> & <a href="https://drive.google.com/file/d/1Aa671ZM8mBTW5gvyzel8P5o9_faLrWw9/view?usp=sharing">toelichting</a>.
   </td>
  </tr>
</table>


### 2. Opbouw van relaties en vertrouwen 

De basis voor dit thema is gelegd in het paper "[Opt-in, opt-out and bail-out: Privacy in new approaches to mental healthcare" (Amsterdam Privacy Conference 24 October 2015)](https://drive.google.com/file/d/18HfAjZsjKb-NJQuZU5vj99BYGWxrJBIW/view?usp=sharing). Elke relatie is anders en kent een eigen dynamiek. Die dynamiek, het vertrouwen in de andere partij en de uitgewisselde gegevens gaan hand in hand en zijn een dynamisch geheel. De keuzes voor het wel of niet delen van bepaalde gegevens moeten deze dynamiek dan ook volgen. Tegelijkertijd moeten de keuzes begrijpelijk en overzichtelijk zijn: het is natuurlijk om voor een relatie te kiezen, wat je wel of niet deelt volgt daar uit. Dat maakt het mogelijk om per soort relatie een set van 'veilige defaults' te definiëren, als het ware templates die dienen als standaard keuzes voor een bepaald type relatie. 

Afhankelijk van de situatie kunnen mensen altijd er voor kiezen om (beide kanten op) daar van af te wijken. Met de [privacy game](https://drive.google.com/drive/folders/1pBVrrvQ9LemrWQhU26FWHJ8EwD3oqk3m?usp=sharing) wordt dit uitgangspunt verder getoetst en uitgewerkt. Belangrijke resultaten van de privacy game zijn dat inderdaad de relatie belangrijker is dan de data, dat wederkerigheid een belangrijke factor is en dat de standaard ruimte moet bieden voor ontwikkeling van de relatie en de daarbij behorende veranderende behoefte aan het delen van gegeven. 

<table>
  <tr>
   <td><strong>Ontwerpeis</strong>
   </td>
  </tr>
  <tr>
   <td>2.1 Bij het aangaan van een relatie kunnen de partijen kiezen of en wat ze initieel kenbaar maken over zichzelf.
   </td>
  </tr>
  <tr>
   <td>2.2 Het is mogelijk om voor een bepaalde context (rollen, omgevingen) templates, een set van ‘veilige defaults’ van data om te delen voor beide partijen, te definiëren.
   </td>
  </tr>
  <tr>
   <td>2.3 De templates voor een relatie kunnen per partij verschillen.
   </td>
  </tr>
  <tr>
   <td>2.4. Elke partij kan naar eigen inzicht afwijken van de templates. 
   </td>
  </tr>
  <tr>
   <td>2.5. Partijen kunnen op elk moment besluiten om meer informatie over zichzelf te delen of om toegang te geven tot bepaalde datastromen.
   </td>
  </tr>
  <tr>
   <td>2.6. Toegang tot datastromen kan op elk moment weer gestopt worden.Daarnaast is het een eis vanuit de AVG dat toestemming altijd weer in te trekken is.
   </td>
  </tr>
  <tr>
   <td>2.7. Partijen kunnen er voor kiezen om informatie of toegang tot datastromen alleen te verlenen als de andere partij dat ook doet.
   </td>
  </tr>
  <tr>
   <td>2.8. Partijen kunnen verzoeken om bepaalde informatie of datastromen, die verzoeken kunnen door de andere partij gehonoreerd of afgewezen worden.
   </td>
  </tr>
  <tr>
   <td>Uitwerking: GIDS Open Standaarden <a href="https://drive.google.com/drive/folders/1r5wIo-JLAaKEhcVGeo20VDfNgmCVUFhY?usp=sharing">Design en Use Cases</a>.
   </td>
  </tr>
</table>


### 3. Zeggenschap over data 

Zeker in de zorg is de zeggenschap over persoonsgegevens complex. In principe heeft het data subject zeggenschap over over diens gegevens, maar er zijn letterlijk tientallen wetten en regels die daar uitzonderingen op maken. In de praktijk betekent dit dat de zeggenschap over de persoonsgegevens per relatie sterk kan verschillen. Daarbij geldt ook dat gedeelde gegevens niet meer 'ontdeeld' kunnen worden: Voor het verwijderen (en de zeggenschap over andere aspecten, zoals doorgifte van data) ben je afhankelijk van de andere partij en de regels waar die zich aan moet houden. Het is dus belangrijk om dit helder te communiceren zodat de partijen in een relatie over en weer weten wat ze van elkaar kunnen verwachten. Uit de[ AVG](https://autoriteitpersoonsgegevens.nl/nl/onderwerpen/avg-europese-privacywetgeving) volgt dat mededelingen hierover juridisch bindend zijn.

<table>
  <tr>
   <td><strong>Ontwerpeis</strong>
   </td>
  </tr>
  <tr>
   <td>3.1. Beiden partijen hebben toegang tot de data die binnen die relatie gedeeld of gecreëerd is.
   </td>
  </tr>
  <tr>
   <td>3.2. Het protocol maakt expliciet dat beide partijen toegang hebben tot binnen een relatie gedeelde data en dat software die het protocol implementeert voor de gebruikers zichtbaar moet maken dat de gedeelde data toegankelijk is voor de andere partij.
   </td>
  </tr>
  <tr>
   <td>3.3. Een partij kan binnen een relatie een privacy-policy publiceren over de omgang met die data.
   </td>
  </tr>
  <tr>
   <td>3.4. De privacy-policy is machine leesbaar. Dit maakt het voor systemen die SNS implementeren mogelijk om deze informatie zinnig te verwerken in hun context.
   </td>
  </tr>
  <tr>
   <td>3.5. De privacy-policy bevat informatie over welke data bewaard wordt, de bewaartermijnen, het gebruik van de data, doorgifte van de data aan andere partijen (waarbij eventueel condities aangegeven kunnen worden, zoals ‘opsporingsbevel’) en over het afhandelen van inzage, correctie en verwijderingsverzoeken.
   </td>
  </tr>
  <tr>
   <td>3.6. Uit de formulering van het protocol is duidelijk dat de gepubliceerde privacy-policy juridisch bindend is voor de partij die hem publiceert.
   </td>
  </tr>
  <tr>
   <td>Uitwerking: Architectuur voor de <a href="https://drive.google.com/file/d/1yOG20v8FaCiUProXRX6owja7pIzJ9mCY/view?usp=sharing">De Nieuwe GGZ</a> en <a href="https://drive.google.com/file/d/1ODtHvJZ3qpsFO4AAeNq3T_oPQPWCUQcG/view?usp=sharing">informatiemodel</a> & <a href="https://drive.google.com/file/d/1Aa671ZM8mBTW5gvyzel8P5o9_faLrWw9/view?usp=sharing">toelichting</a>. Er zijn verschillende initiatieven om machine leesbare privacy policies te ontwikkelen. Veelbelovend voorbeeld: <a href="https://www.w3.org/community/dpvcg/">W3C werkgroep "Data Privacy Vocabularies and Controls"</a><strong>.</strong>
   </td>
  </tr>
</table>


### 4. Content 

Een van de dingen die uit de presentatie "[Zelfbeschikking](https://drive.google.com/file/d/1mjQoOU9swQIu_hg4XtUlobUHCq_raEUJ/view?usp=sharing)" volgt, is dat persoonsgegevens verschillende statussen kan hebben: het kan een verhaal zijn dat je over jezelf creëert, het kan ook een verhaal zijn dat iemand anders over je creëert. Het kunnen gegevens zijn die er op gericht zijn om aan anderen door te geven, het kunnen gegevens waarvan het van belang is dat je kan aantonen dat het door iemand anders geverifieerd is.

<table>
  <tr>
   <td><strong>Ontwerpeis</strong>
   </td>
  </tr>
  <tr>
   <td>4.1. Binnen een relatie kunnen eigenschappen van beide partijen (attributen) kenbaar gemaakt worden, kan er een ‘conversatie’ plaatsvinden (een dialogische interactie), kunnen er data-requests gedaan worden en kan een partij zich abonneren om datastromen van de andere partij. (Push berichten, Pull-requests, PubSub).
   </td>
  </tr>
  <tr>
   <td>4.2. Conversaties bestaan uit berichten.
   </td>
  </tr>
  <tr>
   <td>4.3. Data elementen kunnen bestaan uit gestructureerde data (FHIR, medical imaging formats?) of uit ongestructureerde data (tekst, media).
   </td>
  </tr>
  <tr>
   <td>4.4. Elke partij in een relatie besluit zelf welke attributen over zichzelf kenbaar gemaakt worden.
   </td>
  </tr>
  <tr>
   <td>4.5. Eigenschappen (Attributen) kunnen geverifieerd zijn door een derde partij of zelfverklaard zijn.
   </td>
  </tr>
  <tr>
   <td>4.6. Het is bij attributen altijd duidelijk of ze door een derde partij geverifieerd zijn of zelf verklaard.
   </td>
  </tr>
  <tr>
   <td>4.7. Verifiërende partijen kunnen zelf geverifieerd zijn.
   </td>
  </tr>
  <tr>
   <td>4.8. Er is de mogelijkheid om een vertrouwde partij verificaties uit te laten geven.
   </td>
  </tr>
  <tr>
   <td>4.9. Er is een structuur om verificaties weer in te kunnen trekken.
   </td>
  </tr>
  <tr>
   <td>Uitwerking: Architectuur voor de <a href="https://drive.google.com/file/d/1yOG20v8FaCiUProXRX6owja7pIzJ9mCY/view?usp=sharing">De Nieuwe GGZ</a> en <a href="https://drive.google.com/file/d/1ODtHvJZ3qpsFO4AAeNq3T_oPQPWCUQcG/view?usp=sharing">informatiemodel</a> & <a href="https://drive.google.com/file/d/1Aa671ZM8mBTW5gvyzel8P5o9_faLrWw9/view?usp=sharing">toelichting</a>. GIDS Open Standaarden <a href="https://drive.google.com/drive/folders/1r5wIo-JLAaKEhcVGeo20VDfNgmCVUFhY?usp=sharing">Design en Use Cases</a>. Voorbeelden van "Working code" zijn IRMA en de publieke eID-middelen.
   </td>
  </tr>
</table>


### 5. Zoeken & gevonden worden 

De aanzet van dit thema is te vinden in informatiemodel & toelichting. De kern is dat je verschillende rollen c.q. contexten kan hebben waarop je vindbaar wil kunnen zijn of waarop je wil zoeken maar dat je niet per se wil dat die aan elkaar te linken zijn. De eisen moeten echter nog verder uitgewerkt worden, vooral op het punt van het creëren van een natuurlijke gebruikersinteractie. Ook zijn de functionele eisen op dit punt, buiten de privacy om, nog niet duidelijk. 

<table>
  <tr>
   <td><strong>Ontwerpeis</strong>
   </td>
  </tr>
  <tr>
   <td>5.1. De gebruikers kunnen zelf bepalen of en op welke eigenschappen ze vindbaar zijn.
   </td>
  </tr>
  <tr>
   <td>5.2. De gebruikers kunnen op meerdere van elkaar onafhankelijke ‘vindbaar heden’ publiceren met elk een eigen combinatie van eigenschappen (bijvoorbeeld voor verschillende rollen).
   </td>
  </tr>
  <tr>
   <td>5.3. Separate vindbaar heden zijn niet op elkaar te herleiden.
   </td>
  </tr>
  <tr>
   <td>5.4. Vanuit contexten (zoals bepaalde applicaties of rollen) kunnen templates voor ‘vindbaar heden’ voorgegeven worden. Gebruikers kunnen altijd van de templates afwijken.
   </td>
  </tr>
  <tr>
   <td>5.5. Er kan gezocht worden op combinaties van eigenschappen.
   </td>
  </tr>
  <tr>
   <td>Uitwerking: Architectuur voor de <a href="https://drive.google.com/file/d/1yOG20v8FaCiUProXRX6owja7pIzJ9mCY/view?usp=sharing">De Nieuwe GGZ</a> en <a href="https://drive.google.com/file/d/1ODtHvJZ3qpsFO4AAeNq3T_oPQPWCUQcG/view?usp=sharing">informatiemodel</a> & <a href="https://drive.google.com/file/d/1Aa671ZM8mBTW5gvyzel8P5o9_faLrWw9/view?usp=sharing">toelichting</a>.
   </td>
  </tr>
</table>


### 6. Userinterface & interaction design 

Regie is alleen mogelijk als er een userinterface en een bijbehorend interactie design is die mensen helpt om vrije keuzes te maken. Ook helpt het als de verschillende applicaties die de SNS implementeren een vergelijkbare beeldtaal en workflow hanteren, zodat gebruikers de interactie herkennen en niet steeds opnieuw moeten ontdekken. Waar nodig moet de SNS dit afdwingen, waar mogelijk ondersteunen.

<table>
  <tr>
   <td><strong>Ontwerpeis</strong>
   </td>
  </tr>
  <tr>
   <td>6.1. Gebruikers interacties en userinterface elementen die onontbeerlijk zijn voor een goede werking van het protocol worden in de protocol definitie dwingend voorgeschreven.
   </td>
  </tr>
  <tr>
   <td>6.2. Het protocol wordt vergezeld van best practices voor de interactie en de interface zodat de beeldtaal en gebruikspatronen herkenbaar worden.
   </td>
  </tr>
  <tr>
   <td>Uitwerking: GIDS Open Standaarden <a href="https://drive.google.com/drive/folders/1r5wIo-JLAaKEhcVGeo20VDfNgmCVUFhY?usp=sharing">Design en Use Cases</a>.
   </td>
  </tr>
</table>


### 7. Technische eisen 

Vanuit verschillende hoeken zijn er privacy gerichte eisen die direct gevolgen hebben voor technische keuzes die gemaakt worden.

<table>
  <tr>
   <td><strong>Ontwerpeis</strong>
   </td>
  </tr>
  <tr>
   <td>7.1. Decentrale architectuur.
   </td>
  </tr>
  <tr>
   <td>7.2. Centrale structuren (als beoordelings services, indexes van servers, certificate authorities, beoordelings aggregators, spamlijsten) zijn vrij te kiezen en het is mogelijk om een alternatieve structuur op te zetten.
   </td>
  </tr>
  <tr>
   <td>7.3. Zeker bij gevoelige zorgdata is een standaard die uitgaat van een centrale partij die overzicht kan hebben over wie er participeert of welke activiteiten er plaatsvinden een groot privacy probleem. De SNS moet dus zo ontworpen zijn dat er geen centrale plaats is waar overzicht over de activiteiten of mensen kan ontstaan (Privacy by Design). SamenBeter streeft inhoudelijke neutraliteit na: wil niet zelf of via een andere toezichthoudende partij bepalen wat goede zorg is. Dat kan via bijvoorbeeld ratingsystemen door de gebruikers zelf bepaald worden. Voor de SNS heeft dat tot gevolg dat het wel services als ratingsystemen moet ondersteunen, maar de standaard zo opgebouwd moet zijn dat het niet mogelijk is dat een partij het netwerk controleert.
   </td>
  </tr>
  <tr>
   <td>7.4. Alle verbindingen zijn versleuteld. Basale Privacy by Design / beveiligingseis.
   </td>
  </tr>
  <tr>
   <td>7.5. Indien er gegevens langs niet vertrouwde services gaan, de mogelijkheid om dat deel te versleutelen door encryptie bij punten er voor en er na. Afhankelijk van de netwerktopologie kan het zijn dat informatie langs nodes of services gaan die aan lagere eisen wat betreft veiligheid en vertrouwen voldoen dan wat de soort data vraagt. De bruikbaarheid van de SNS neemt zeer toe als die een voorziening heeft om in zulke gevallen de verstuurde gegevens te versleutelen.
   </td>
  </tr>
  <tr>
   <td>7.6. De SNS maakt het mogelijk om eenvoudig de toegepaste cryptografische algoritme & protocol te wijzigen.Cryptografische protocollen en algoritmes zijn het onderwerp van een constante wapenwedloop tussen beveiligers en aanvallers. Daardoor komen er regelmatig nieuwe versies en blijken regelmatig bepaalde protocollen en algoritmes niet meer veilig te zijn. De duurzaamheid van de SNS neemt sterk toe als de standaard mechanismen kent om meerdere protocollen en algoritmes te ondersteunen. 
   </td>
  </tr>
  <tr>
   <td>7.7. Authenticatie die passend is bij de soort relatie die ondersteund wordt. De wet- en regelgeving rond het eID stelsel en uitspraken van de Autoriteit Persoonsgegevens schrijven voor dat, afhankelijk van de gevoeligheid van de data, een passend beveiligingsniveau voor het inloggen gekozen moet worden.
   </td>
  </tr>
  <tr>
   <td>Uitwerking: <a href="https://drive.google.com/file/d/1ODtHvJZ3qpsFO4AAeNq3T_oPQPWCUQcG/view?usp=sharing">informatiemodel</a> & <a href="https://drive.google.com/file/d/1Aa671ZM8mBTW5gvyzel8P5o9_faLrWw9/view?usp=sharing">toelichting</a>
   </td>
  </tr>
</table>


## GIDS Open Standaarden ‘privacy by design’

### Achtergrondinformatie en naslagwerk

De eerste aanzet voor [GIDS Open standaarden](https://www.gidsopenstandaarden.org/) ‘privacy by design’ is gemaakt in 2014. Aanleiding waren de ontwikkeling van “[Koppeltaal GGZ](https://www.koppeltaal.nl/)”. Het komen tot een technische standaard voor het toegankelijk maken van eHealth en blended care voor behandelaars en cliënten. En de [architectuur voor “De Nieuwe GGZ”](https://drive.google.com/file/d/1yOG20v8FaCiUProXRX6owja7pIzJ9mCY/view?usp=sharing), een meer inhoudelijke stroming dat als doel had om state of the art eHealth op grote schaal toe te passen in de GGZ. 

Los van alle schaalbaarheids- en governance problemen, die op technisch niveau van begin af aan meegenomen moesten worden, was er ook een grote vraag op de achtergrond: hoe zorgen we dat in zo een systeem de cliënten de regie kunnen blijven houden? Dat is het begin geworden van een onderzoekstraject naar de privacy van grote genetwerkte eHealth systemen. 

Publicatie: "[Big Data the e-health bubble and its fix](https://drive.google.com/file/d/1Q5iR98C4YoyQulDPBS5m_8gOVR3Z152_/view?usp=sharing)" (TILTing Perspectives, 23 april 2015).

Door het geheel te benaderen als een netwerk van een groot aantal diverse losse relaties, in plaats van gestructureerde data stromen, ontstaat er een benadering die zowel hanteerbaar is als in staat is om met de complexiteit van het geheel mee te bewegen. 

Presentatie: “[Zelfbeschikking](https://drive.google.com/file/d/1mjQoOU9swQIu_hg4XtUlobUHCq_raEUJ/view?usp=sharing)” (bijeenkomst De Nieuwe GGZ 2015).

Een filosofische onderbouwing hoe zelfbeschikking ontstaat in de ruimte tussen "geïdentificeerd worden als" en "jezelf identificeren met". Juist door controle over dat proces en de mogelijkheid om ook zaken onbelicht te laten, er niet mee naar voren te treden, ontstaat eigen regie. De visie van ervaringsdeskundige Jasper Wagteveld is daarin ook heel verhelderend, hij stelt simpelweg: "als je geen zeggenschap hebt over je eigen gegevens, heb je ook geen eigen regie". 

Publicatie: "[Opt-in, opt-out and bail-out: Privacy in new approaches to mental healthcare](https://drive.google.com/file/d/18HfAjZsjKb-NJQuZU5vj99BYGWxrJBIW/view?usp=sharing)" (Amsterdam Privacy Conference 24 October 2015). 

Relaties vormen ook een logische eenheid voor het maken van privacy keuzes. Dit is een van de bronnen geworden voor het '[Beter met Elkaar](https://drive.google.com/file/d/1jOu51nZecCgwDrcF8iCtootjzLBg2MSi/view?usp=sharing)' rapport in 2016, waarin de drie thema's op privacy gebied geïdentificeerd zijn die aandacht behoeven: 

1. Regie in het zorgproces vertalen naar regie over de data ([tekst](https://drive.google.com/file/d/1FiNw5UIV5Z9ZzwcALlixosxH_MVusOgu/view?usp=sharing) & [infographic](https://drive.google.com/file/d/1g8HKaqzRxUfSetT5T1OlIgmODJqh011-/view?usp=sharing) deel I): op welke manier kunnen we zorgen dat de op te bouwen netwerk standaard ook de eigen regie bij de zorgprocessen op de grond versterkt?
2. Data in (juridisch) heterogene omgevingen ([tekst](https://drive.google.com/file/d/1n18lgJoJj0XNEiYxEg7Gh4fDSHM_C5Uc/view?usp=sharing) & [infographic](https://drive.google.com/file/d/1JGiulWp9iPsms6g2D94SyFlcviEMjNjH/view?usp=sharing) deel II): op welke manier kunnen we er voor zorgen dat er geen problemen ontstaan tussen data uit verschillende contexten en met verschillende juridische status? 
3. Privacy by Design: hoe kunnen we tot een ontwerpproces komen dat recht doet aan de verschillende aspecten van privacy en dat het mogelijk maakt om met de verschillende betrokken partijen tot een goed ontwerp te komen? 

Dit is verder uitgewerkt in een [informatiemodel](https://drive.google.com/file/d/1ODtHvJZ3qpsFO4AAeNq3T_oPQPWCUQcG/view?usp=sharing) & [toelichting](https://drive.google.com/file/d/1Aa671ZM8mBTW5gvyzel8P5o9_faLrWw9/view?usp=sharing). Daarnaast zijn er al een aantal ontwerpen gemaakt om tastbaar te maken hoe de uitgangspunten in de praktijk werken. In 2018 zijn de ideeën hierover gebruikt als uitgangspunt voor een privacy game. 

Publicatie: "[Gaming as an agile tool for privacy by design in e-health](https://drive.google.com/file/d/1lPT1n7DwX7ipyxWMICsqnKdcsww5Fxk3/view?usp=sharing)" (Amsterdam Privacy Conference 2018). 

Een simulatie waarin de ideeën in de praktijk getoetst kunnen worden en wat feedback oplevert voor een agile ontwikkelproces. Daarnaast is er geëxperimenteerd met een methode om tot privacy by design te komen voor de onderliggende technische structuren.

Publicatie: “[Privacy by design in complex collaborative systems](https://drive.google.com/file/d/1Glh8_2mrYiQ-xYs5yIDMyaH3TbYOuZlF/view?usp=sharing)” (Amsterdam Privacy Conference 2018) . 

Deze methodiek leek nog niet helemaal goed passend te zijn bij de werkwijze van GIDS Open Standaarden. De bovenstaande privacy ontwerpeisen voor de Sociale Netwerk Standaard (SNS) zijn de volgende stap in het ontwikkelproces. Ze zijn een vertaling van alle uitgangspunten in het voorafgaande proces naar heldere regels waaraan de standaard moet voldoen en zijn bedoeld als een van de uitgangspunten voor GIDS Open Standaarden.

(c) 2020 Winfried Tilanus CC-SA-BY 4.0.
