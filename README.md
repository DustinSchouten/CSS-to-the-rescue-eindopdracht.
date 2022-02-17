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


de vuurvonkjes. Zoals ik in mijn breakdown-schets eerder heb laten zien, heb ik de vuurvonkjes als list-items in een unordered list gegroepeerd. 

![](Documentatie/Week_2/Screenshot_1.png)


Laat je voortgang zien ('praatje met plaatjes').

Wat ging er soepel en wat was lastig.

Welke experimenten heb je gedaan die die 'mislukt' zijn.

Heb je nieuwe inzichten hoe je de kracht CSS kunt benutten (of juist niet).

-ja: custom properties toepassen (zowel root als per element) gebruikt voor werken met delays bij animaties
-misschien: random variabelen
-ja labels en checkboxes voor interactie

Neem wijzigingen aan je 1e plan op.

Waar liggen je (nieuwe) uitdagingen voor komende week.
- elk vuurvonkje als list met nieuwe vuurvonkjes laten ontploffen
- checkboxes voor interactie maken