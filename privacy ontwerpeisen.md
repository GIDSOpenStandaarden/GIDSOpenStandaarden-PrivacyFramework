Binnen GIDS Open Standaarden zijn er 3 thema's op privacy gebied geïdentificeerd die aandacht behoeven: 

1. Regie in het zorgproces vertalen naar regie over de data: op welke manier kunnen we zorgen dat de op te bouwen netwerk standaard ook de eigen regie bij de zorgprocessen op de grond versterkt?
2. Data in (juridisch) heterogene omgevingen: op welke manier kunnen we er voor zorgen dat er geen problemen ontstaan tussen data uit verschillende contexten en met verschillende juridische status? 
3. Privacy by Design: hoe kunnen we tot een ontwerpproces komen dat recht doet aan de verschillende aspecten van privacy en dat het mogelijk maakt om met de verschillende betrokken partijen tot een goed ontwerp te komen? 

## Ontwerpeisen Sociale Netwerk Standaard (SNS) 

### 1. Relatie Centraal 
Veel van wat er rond gezondheid gebeurt, kan begrepen worden als een combinatie van anderen die over jou oordelen en van een bepaald beeld van jezelf opbouwen, zie ook de presentatie "[Zelfbeschikking](https://drive.google.com/file/d/1mjQoOU9swQIu_hg4XtUlobUHCq_raEUJ/view?usp=sharing)". Dat is een proces wat binnen elke relatie opnieuw gebeurt en wat uniek is voor elke relatie binnen alle zorgprocessen. De SNS moet dan ook op eenzelfde manier de relaties centraal zetten. De sociale interacties rond gezondheid, zowel professioneel als informeel, zijn zeer complex en divers. 

Om een dergelijk complex systeem te automatiseren, is het goed om op zoek te gaan naar een kleine eenheid waar al die verschillende interacties uit opgebouwd zijn en die als uitgangspunt te nemen bij het opstellen van de SNS. Relaties vervullen ook die rol: het is een een eenheid die behapbaar en modelleerbaar is en die tegelijkertijd de basis vormt voor alle interacties. Door complexe werkelijkheid strikt op te knippen in relaties, wordt 'ie behapbaar. 

Juridisch gezien is het ook belangrijk om te denken vanuit relaties: persoonsgegevens moeten altijd een duidelijke verantwoordelijke hebben en afhankelijk van je rol heb je verschillende rechten en plichten. Die rechten en plichten zijn tussen de verschillende rollen binnen en buiten de zorg conflicterend. Als het altijd duidelijk is bij welke relatie bepaalde data hoort en wie er verantwoordelijk voor is, kan voorkomen worden dat het systeem juridische spaghetti wordt.

1. **Ontwerpeis:**
    1. Van data is altijd duidelijk bij welke relatie het hoor
    2. Data die van de de ene naar de andere relatie gebracht wordt moet altijd aan die andere relatie relatie aangepast worden door middel van een of meerdere van de volgende processen: selecteren, samenvatten, annoteren, vertalen.
    3. Elke partij in een relatie heeft een eigen pseudoniem dat uniek is voor die relatie zodat, zonder aanvullende gegevens, de relaties niet op elkaar te herleiden zijn. Het is het besluit van de gebruiker om relaties aan elkaar kenbaar te maken of niet. De keuze daarvoor is een belangrijk aspect voor het vormgeven van de eigen regie. De AVG eist dat dergelijke (cruciale) privacy aspecten in het ontwerp van het systeem ingebakken zitten (Privacy by Design). Vandaar dat het ook een juridische eis is om dit op een technisch niveau al niet herleidbaar te maken.
    4. Relaties zijn altijd te verbreken basaal voor de eigen regie.
    5. Het protocol is agnostisch of de relaties tussen mensen onderling, mensen en machines of tussen machines onderling zijn. De rol van apps (machines), komt in verschillende klantreizen naar voren. Dit levert in privacy opzicht een eigen dynamiek op, zie: "[Big Data the e-health bubble and its fix" TILTing Perspectives, 23 april 2015](https://drive.google.com/file/d/1Q5iR98C4YoyQulDPBS5m_8gOVR3Z152_/view?usp=sharing). Een van de manieren om de privacy te waarborgen als de persoonsgegevens door machines verwerkt worden, is om ze aan hetzelfde regime te onderwerpen als de relaties tussen mensen.

**Uitwerking:** Architectuur voor de [De Nieuwe GGZ](https://drive.google.com/file/d/1yOG20v8FaCiUProXRX6owja7pIzJ9mCY/view?usp=sharing) en [informatiemodel & toelichting](https://drive.google.com/file/d/1aXiXJRO77qoqVkE-1PoDjt_roMrvIz9y/view?usp=sharing).


### 2. Opbouw van relaties en vertrouwen 
De basis voor dit thema is gelegd in het paper "[Opt-in, opt-out and bail-out: Privacy in new approaches to mental healthcare" (Amsterdam Privacy Conference 24 October 2015)](https://drive.google.com/file/d/18HfAjZsjKb-NJQuZU5vj99BYGWxrJBIW/view?usp=sharing). Elke relatie is anders en kent een eigen dynamiek. Die dynamiek, het vertrouwen in de andere partij en de uitgewisselde gegevens gaan hand in hand en zijn een dynamisch geheel. De keuzes voor het wel of niet delen van bepaalde gegevens moeten deze dynamiek dan ook volgen. Tegelijkertijd moeten de keuzes begrijpelijk en overzichtelijk zijn: het is natuurlijk om voor een relatie te kiezen, wat je wel of niet deelt volgt daar uit. Dat maakt het mogelijk om per soort relatie een set van 'veilige defaults' te definiëren, als het ware templates die dienen als standaard keuzes voor een bepaald type relatie. 

Afhankelijk van de situatie kunnen mensen altijd er voor kiezen om (beide kanten op) daar van af te wijken. Met de [privacy game](https://drive.google.com/drive/folders/1pBVrrvQ9LemrWQhU26FWHJ8EwD3oqk3m?usp=sharing) worden dit uitgangspunt verder getoetst en uitgewerkt. Belangrijke resultaten van de privacy game zijn dat inderdaad de relatie belangrijker is dan de data, dat wederkerigheid een belangrijke factor is en dat de standaard ruimte moet bieden voor ontwikkeling van de relatie en de daarbij behorende veranderende behoefte aan het delen van gegeven. 


### 3. Zeggenschap over data 
Zeker in de zorg is de zeggenschap over persoonsgegevens complex. In principe heeft het data subject zeggenschap over over diens gegevens, maar er zijn letterlijk tientallen wetten en regels die daar uitzonderingen op maken. In de praktijk betekent dit dat de zeggenschap over de persoonsgegevens per relatie sterk kan verschillen. Daarbij geldt ook dat gedeelde gegevens niet meer 'ontdeeld' kunnen worden: Voor het verwijderen (en de zeggenschap over andere aspecten, zoals doorgifte van data) ben je afhankelijk van de andere partij en de regels waar die zich aan moet houden. Het is dus belangrijk om dit helder te communiceren zodat de partijen in een relatie over en weer weten wat ze van elkaar kunnen verwachten. Uit de[ AVG](https://autoriteitpersoonsgegevens.nl/nl/onderwerpen/avg-europese-privacywetgeving) volgt dat mededelingen hierover juridisch bindend zijn.


### 4. Content 
Een van de dingen die uit de presentatie "[Zelfbeschikking](https://drive.google.com/file/d/1mjQoOU9swQIu_hg4XtUlobUHCq_raEUJ/view?usp=sharing)" volgt, is dat persoonsgegevens verschillende statussen kan hebben: het kan een verhaal zijn dat je over jezelf creëert, het kan ook een verhaal zijn dat iemand anders over je creëert. Het kunnen gegevens zijn die er op gericht zijn om aan anderen door te geven, het kunnen gegevens waarvan het van belang is dat je kan aantonen dat het door iemand anders geverifieerd is.


### 5. Zoeken & gevonden worden 
De aanzet van dit thema is te vinden in informatiemodel & toelichting. De kern is dat je verschillende rollen c.q. contexten kan hebben waarop je vindbaar wil kunnen zijn of waarop je wil zoeken maar dat je niet per se wil dat die aan elkaar te linken zijn. De eisen moeten echter nog verder uitgewerkt worden, vooral op het punt van het creëren van een natuurlijke gebruikersinteractie. Ook zijn de functionele eisen op dit punt, buiten de privacy om, nog niet duidelijk. 


### 6. Userinterface & interaction design 
Regie is alleen mogelijk als er een userinterface en een bijbehorend interactie design is die mensen helpt om vrije keuzes te maken. Ook helpt het als de verschillende applicaties die de SNS implementeren een vergelijkbare beeldtaal en workflow hanteren, zodat gebruikers de interactie herkennen en niet steeds opnieuw moeten ontdekken. Waar nodig moet de SNS dit afdwingen, waar mogelijk ondersteunen.


### 7. Technische eisen 
Vanuit verschillende hoeken zijn er privacy gerichte eisen die direct gevolgen hebben voor technische keuzes die gemaakt worden:

c) 2020 Winfried Tilanus CC-SA-BY 4.0

