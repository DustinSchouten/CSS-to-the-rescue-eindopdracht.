Link naar project: https://dustinschouten.github.io/CSS-to-the-rescue-eindopdracht./

# CSS-to-the-rescue-eindopdracht. Procesverslag

## Week 1

Voor dit vak heb ik besloten om de magische vuurwerkshow te gaan maken waarbij ik zelfgemaakte vuurpijlen omhoog wil laten vuren die allemaal op een andere manier ontploffen.

Op het moment van schrijven weet ik nog niet met welke CSS-technieken ik als eerste aan de slag ga. Ik denk dat het het beste is als ik daar zelf tijdens het coderen achter ga komen.

Mijn grootste uitdaging is ongetwijfeld het maken van interacties en bewegende elementen zonder gebruik te maken van ID's, classes en JavaScript.

Bij de vuurwerkshow had ik een aantal ideeën bedacht:

- Één daarvan was dat de vuurpijlen niet recht omhoog maar in een vloeiende ronde baan zouden opstijgen.

- Een ander idee is dat je een interactie zou kunnen maken waarmee de gebruiker kon bepalen hoeveel vuurpijlen er tegelijk zouden verschijnen.

- Ook had ik bedacht dat je de kleuren van het vuurwerk kon aanpassen.

Deze ideeën werden afgelopen vrijdag dan ook goedgekeurd.

Hieronder heb ik een eerste schets gemaakt van mijn nog prille vuurwerkshow en de manier waarop ik mijn HTML wil maken:

![](Documentatie/Week_1/Eerste_schets.jpg)

Daarna ben ik aan de slag gegaan met het bouwen van een enkele vuurpijl die recht omhoog kan opstijgen. Zie de screenshot hieronder:

![](Documentatie/Week_1/Screenshot_1.png)

Zoals in mijn eerste schets al te zien is, was ik eerst van plan om met de CSS Pseudo Elements ::before en ::after het rode driehoekje en de stok en aansteeklont te maken. Het probleem echter was dat er maar twee pseudo elements waren voor de drie elementen die ik wilde maken. Daarom ben ik van plan om dit d.m.v. een ul met drie li's op te lossen.

Ook heb ik al nagedacht over de manier waarop de vuurpijlen met een vloeiende curve zouden opstijgen, namelijk d.m.v. een onzichtbare cirkel als div die ik zou ronddraaien met transform:rotate.
Zie mijn breakdown schets hieronder:

![](Documentatie/Week_1/Breakdown_schets.png)

Op de vuurvonkjes na (die komen later in dit procesverslag aan bod) heb ik mijn breakdown schets uitgewerkt en dit werkt goed. Om het idee van de vloeiende baan te laten zien heb ik de div een witte border gegeven.
Zie de screenshot hieronder:

![](Documentatie/Week_1/Screenshot_2.png)

## Week 2
In deze week heb ik me beziggehouden met het helemaal afmaken van mijn vuurpijl. Dat heb ik uitgewerkt volgens mijn breakdown-schets. Het rode driehoekje, het aansteeklontje en de vuurwerkstok.
Zie de screenshot hieronder:

![](Documentatie/Week_2/Screenshot_1.png)

Ook heb ik me beziggehouden met het maken van de vuurvonkjes. Zoals ik in mijn breakdown-schets eerder heb laten zien, heb ik de vuurvonkjes als list-items in een unordered list gegroepeerd.
Het coderen van vuurvonkjes is erg goed gegaan. Ik heb alle vuurvonkjes een aparte keyframe meegegeven waardoor ze allemaal een andere kant opvliegen. Ook heb ik ervoor gezorgd dat je doormiddel van custom properties de kleuren kan aanpassen.
Zie de screenshot hieronder:

![](Documentatie/Week_2/Screenshot_2.png)

Wat ging er soepel en wat was lastig.

Tot nu toe heb ik nog geen nieuwe experimenten gedaan die 'mislukt' zijn. Wel heb ik een hoop nieuwe CSS-technieken geleerd met dit project:
- Ik heb geleerd dat je custom properties ook kan aanpassen door de CSS-regels heen, ipv het enkel definieren bij de :root.
- Ik heb geleerd hoe je de ~ en de + selector kunt toepassen. Ook heb ik de pseudo-class :is voor het eerst gebruikt.
- Wat ik ook niet wist, was dat je labels en radio buttons op een dusdanige manier kon gebruiken dat je hiermee een interactie kan creëeren waardoor je geen JavaScript hoeft te gebruiken.


-misschien: random variabelen

Neem wijzigingen aan je 1e plan op.


Waar liggen je (nieuwe) uitdagingen voor komende week.
- elk vuurvonkje als list met nieuwe vuurvonkjes laten ontploffen
- het geheel zoveel mogelijk responsive maken. Hierbij ga ik de property viewport min proberen toe te passen.