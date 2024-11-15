_link naar issue in onze projectboard: [https://github.com/lisavanmansom/dry-drop-and-heal](https://github.com/orgs/fdnd-agency/projects/37/views/1?pane=issue&itemId=86761979&issue=fdnd-agency%7Cdrop-and-heal%7C59)_

# Component Building Block

Ontwerp en bouw voor de opdrachtgever een robuust, goed werkend component, waarin de belangen van de eindgebruiker centraal staan.

# Inventarisatie van componenten

### Alisa
Elk van de pagina's uit de introductie kunnen worden verdeeld in 4 componenten: 

**1. Header en  2. Voortgangsbalk**

Het bovenste gedeelte dat "Introductie algemeen" of "Introductie rouwtaken" weergeeft, kan als een herbruikbaar component worden gemaakt. Dit component kan de titel en voortgangsbalk bevatten, die dynamisch aangepast kan worden aan de hand van pagina (misschien een pagina nummer doorgeven bij gebruiken van component). 
De voortgangsbalk, die de huidige plek in de introductie laat zien, kan ook als apart component worden opgezet. 

![Image](https://github.com/user-attachments/assets/28bed088-b8a6-4019-926e-8ae2e5530636)

**3. Navigatiebuttons**

De buttons om heen en weer te navigeren kunnen als een apart component worden gemaakt. 

![Image](https://github.com/user-attachments/assets/1d91f7e0-9062-4f88-8170-d896c2cd41d6)

**4. Inhoud component**

Het tekstgedeelte onder elke sectie zoals "Privacy," "Tools," en "Rouwtaken" zou ook een component kunnen zijn. 

**5. Rouwtaak Illustratie (animatie)**

De abstracte illustraties die varieëren per pagina van de Introducitie rouwtaken, kan als een afbeelding-component worden opgezet. 

![Image](https://github.com/user-attachments/assets/e577b811-ffaf-462c-8265-03b1819efa90)

**Morphological chart**

Ik heb verschillende opties van componenten voor introductie verkent d.m.v. een morphological chart. 

- **Dynamische header**: header past zich aan de schermgrootte door mediaqueries en is op dit manier toehankelijk. 
- **Balk met huidige voortgang**: dit laat de gebruikers duiderilijk zien in welke fase of taak ze zich bevinden en hoeveel er nog te gaan is.
- **Geanimeerde illustratie (SVG) mbv css**: meer levendig, ruststellend, geeft de website een dynamisch gevoel. 
- **Dynamische typografie**: zorgt voor optimale leesbaarheid en past zich zonder veel afleiding aan de gebruiker of het apparaat aan.
- **Aria-elementen samen met JavaScript-animaties**: combineren van aria-elementen met links voor basisfunctionaliteit en voeg aria-attributen toe voor opmaak, dit is belangrijk voor PE. De JavaScript toevoegen om een overgangsanimatie te maken, waardoor de navigatie meer visueel aantrekkelijk is. Dit werkt dus zonder JavaScript, maar voegt mooie animatie toe als JavaScript beschikbaar is.

![Image](https://github.com/user-attachments/assets/65669faf-f483-4098-9bc6-e723743ba36a)


### Lisa
Mijn page bestaat uit 3 componenten:
1. Form
2. Input
3. Link

![Image](https://github.com/user-attachments/assets/6e682de9-c7c4-4bf3-a586-9faa9540c860)

morphological chart

Ik heb de opties van de form verkent d.m.v. een morphological chart. De uitkomst is: radio / _blank / post.

- **Ik heb gekozen voor radio omdat:** er zijn meerdere opties / antwoorden maar je kan er maar 1 selecteren
- **Ik heb gekozen voor post omdat:** de informatie moet uiteindelijk op een server / database komen te staan. Door gebruik te maken van een Post wordt er informatie opgestuurd.
- **Ik heb gekozen voor _blank omdat:** de gebruiker door moet worden gestuurd naar en volgende pagina met meer informatie. Deze keuze heeft ook te maken met PE en performance. Als het op dezelfde pagina zou blijven dan is de performance lager en is het geheel minder toegankelijk.

![Image](https://github.com/user-attachments/assets/9c168447-e022-40c8-8ba7-eb0b91c7da9f)


### Tristan
1. Heading
2. Form met input element en button

![component-breakdown](https://github.com/user-attachments/assets/62039abb-2ac7-494e-8ad8-b855c82c475f)


### Yassir - componenten 
1. Header
2. Gradient
3. Card
4. Footer


![Image](https://github.com/user-attachments/assets/564c4277-6da2-4783-b551-142ca1cb55b8)

