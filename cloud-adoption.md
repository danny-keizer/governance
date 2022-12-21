# Azure Cloud Adoption Framework

### 1. Filmpje

Dit filmpje geeft uitleg over het Microsoft Cloud Adoption Framework voor Azure.

https://www.microsoft.com/nl-nl/videoplayer/embed/RE4tyzr?postJsllMsg=true&autoCaptions=nl-nl

### 2. Definitie

Het Microsoft Cloud Adoption Framework voor Azure is een governance framework dat it-professionals en besluitvormers de tools geeft om hun migratie naar de cloud te ondersteunen. Het gaat hier om een verzameling van best practices, documentatie en hulpprogramma's waarmee de organisatie de kans op succes kan vergroten.


### 3. Toepassing

De levenscyclus van het framework word toegepast in 7 verschillende stappen, waarvan 4 gaan over cloud adoptie en 3 over het beheersen van de cloud omgeving.

1. Strategie, Zakelijke rechtvaardiging en verwachte acceptatieresultaten definiëren.

Voor organisaties die overwegen om over te stappen naar de cloud zijn er een aantal voordelen te benoemen, de cloud kent en aantal fundamentele voordelen.
Het gaat hier om;

- Grotere flexibiliteit, services in de cloud zijn ontwikkelt met mobiliteit en schaalbaarheid van IT assets in gedachte.

- Lagere kosten, public clouds zoals Azure bieden hun diensten aan op basis van operational expenditure, waardoor een grote investering vooraf niet nodig is, maken ook grote kostenbesparingen mogelijk middels gereserveerde infrastrctuur.

- Een versnelde time to market, doormiddel van DevOps , infrastrucure as code en Automation tools kunnen goed doordachte en uitstekend beveiligde omgevingen binnen relatief weinig tijd worden geimplementeerd.

- Eenvoudiger uitbreiden in nieuwe markten, je kunt zelf kiezen in welke regio jouw infrastructuur draait.

Door de onderstaande stappen te volgen word de waarde van cloud adoptie duidelijk voor zowel het management van de organisatie, als andere stakeholders.

- Documenteer de motivaties voor cloud adoptie
- Documenteer bedrijfsresultaten
- Evalueer de financiele voordelen
- Creer inzicht in de technische voordelen

2. Maak een plan

Op basis van de vorige stap worden concrete doelstellingen gemaakt. Vervolgens moet worden overwogen hoe deze doelstellingen kunnen worden behaald.
Doe nu het volgende om een plan op te stellen;

- Inventariseer digitale activa, het kan hier gaan om netwerkapparaten servers, container clusters en SaaS paketten. Zo bepaal je welke onderelen naar de cloud moeten worden gemigreerd.

- Creer een plan ter ondersteuning van de migratie,  maak resources vrij binnen de organisatie om dit te realiseren.

- Bereid je voor op eventuele hiaten, door fouttolerant te bouwen, een back-out plan op te stellen en disaster recovery te overwegen doe je dit zo goed mogelijk.

- Migreer gefaseerd, zo voorkom je dat de gehele infrastructuur onbeschikbaar is indien de migratie faalt, en heb je minder resources nodig. 

3. Voorbereiding

De volgende stap is om de nieuwe cloud omgeving zodanig in te richten dat een migratie kan worden gefaciliteerd. Doe nu het volgende;

- Creer een operationeel model, bepaal hoe de organisatie gebruik zal maken van cloud technologieen en hoe deze haar zullen ondersteunen.

- Bereid een Azure-landing zone voor, dit is je uiteindelijke doelarchitecuur waar workloads naar kunnen worden gemigreerd.

- Maak je doelarchitectuur op basis van drie fasen "start,uitlijnen,verbeteren", dat wil zeggen: dat wil zeggen vergelijk jouw conceputele doelarchitectuur met de best practices en verbeter continue.

- Bepaal of jouw architectuur voldoet aan de richtlijnen, door de behoeftes van de organisatie te overwegen. 

4. Migreren

Wanneer de omgeving gereed is voor migratie volgt men de onderstaande strategie;

- Migreer de eerste workload, door eerst een pilot uit te voeren kan de migratie pipeline veilig worden getest.

- Ontdek migratiescenario's ter voorbereiding op bredere migratie, houd rekening met de verschillende randvoorwaarde voor de migratie van verschillende infra/services

- Controleer of je aan de best practices voldoet

- Verbeter je migratie proces iteratief, stroomlijn het proces met elke fase van de migratie.


5. Beveiligen



[![Foo](https://learn.microsoft.com/nl-nl/azure/cloud-adoption-framework/secure/media/secure-methodology-popout.png#lightbox)

Zie de bovenstaande plaat over business alignment en security disciplines.
Hierin word de relatie tussen deze twee principes gelegd.

Het beveiligen van de cloud omgeving is niet enkel een kwestie van operationele security toepassen (Access Control, Security Operations, Asset Protection) maar vereist ook dat de organisatie voldoende inzicht heeft in wat er binnen hun omgeving gebeurt. Door Risk Insights te verzamelen kunnen potentiele gevaren worden geadresseerd voordat zij schade kunnen aanrichten. Denk dan bijvoordbeeld aan intrusion detection en monitoring oplossingen.

Business Resillience gaat over de mate waarin de infrastructuur kan worden hersteld na een aanval of de uitval van een gedeelde van de infrastructuur.

7. Governance (zie hoofdstuk 4)

### 4. Compleetheid governance conepten

Het Cloud Adoption Framework kent als laatste stap "governance".
Hieronder valt het governance beleid dat de organisatie zelf gebruikt.
Alle behandelde governance concepten vallen hier dus onder, indien de organisatie hier zelf aandacht aan kiest te besteden.
Alle andere stappen van het framework hebben betrekking op de adoptie van de cloud .

### 5. Voordelen en nadelen 

De voordelen van het Cloud Adoption Framework zijn benoemd onder hoofdstuk 3.1. 
Het nadeel van het gebruik van dit framework is dat deze ten opzichte van andere frameworks erg is gericht op de Azure cloud, en zodoende minder breed inzetbaar is dan meer algemene frameworks.

### 6. Cloud Providers

Het Microsoft Cloud Adoption Framework voor Azure word uiteraard toegepast door Microsoft zelf binnen hun Azure cloud. De werkwijze die bij dit framework past sluit naadloos aan op de tools die binnen Azure worden aangeboden.

Andere Cloud providers zoals AWS en GCP hebben hun eigen richtlijnen, methodieken en best practices die zijn toegespitst op de services die zij bieden, hoewel veel aspecten overeenkomen. Denk hierbij bijvoorbeeld aan de richtlijnen rondom redundantie en en retentie van data.

Dit framework valt daarom in een andere categorie dan de algemenere vendor-agnostische frameworks welke door standaardenorganisaties worden bijgehouden.

### 7. Bronnen

https://learn.microsoft.com/nl-nl/azure/cloud-adoption-framework/overview

https://learn.microsoft.com/nl-nl/azure/cloud-adoption-framework/strategy/

https://learn.microsoft.com/nl-nl/azure/cloud-adoption-framework/plan/

https://learn.microsoft.com/nl-nl/azure/cloud-adoption-framework/migrate/

https://learn.microsoft.com/nl-nl/azure/cloud-adoption-framework/secure/

https://learn.microsoft.com/nl-nl/azure/cloud-adoption-framework/manage/

https://learn.microsoft.com/nl-nl/azure/cloud-adoption-framework/govern/