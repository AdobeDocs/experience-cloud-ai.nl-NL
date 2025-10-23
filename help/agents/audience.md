---
title: Audience-agent
description: Leer hoe u de Audience Agent gebruikt om een publiek te maken, wijzigingen in het publiek weer te geven, dubbele doelgroepen te detecteren en publieksinzichten weer te geven.
source-git-commit: 2c50a4abaf9606e3c7887073053d0cde3ec761e5
workflow-type: tm+mt
source-wordcount: '859'
ht-degree: 0%

---


# Audience-agent

>[!AVAILABILITY]
>
>De Audience Agent is beschikbaar voor alle klanten die toegang hebben tot AI Assistant. U hebt echter de volgende machtigingen nodig om de Audience Agent-functies volledig te kunnen gebruiken.
>
>**Segmenten van de Mening**: Deze toestemming laat u Audience Agent gebruiken om inzichten in het publiek direct in AI Medewerker te bekijken.
>
>**beheert Segmenten**: Aan toestemming laat u Audience Agent gebruiken om nieuw publiek in AI Medewerker direct tot stand te brengen.

In de Audience Agent kunt u inzichten weergeven over het publiek, zoals het detecteren van belangrijke wijzigingen in de publieksgrootte, het detecteren van dubbele doelgroepen, het verkennen van uw publieksinventaris en het ophalen van de grootte van uw publiek.

## Ondersteunde gebruiksgevallen

De Audience Agent in AI Assistant ondersteunt de volgende gebruiksgevallen:

- Gesprek uw publiek
   - Grootte van publiek zoeken voor bestaand publiek
   - Zoek naar soorten publiek op basis van volledige of gedeeltelijke benoemde kenmerken
   - Gedupliceerde doelgroepen detecteren
   - Ontdek XDM gebieden u kunt gebruiken om een publiek te bepalen
- Belangrijke wijzigingen in de grootte van het publiek vaststellen
   - Dit laat u publiek vinden dat plotseling is gegroeid of gekrompen, latend u potentiële marktveranderingen beter kunt analyseren

<!-- - Find your audience size and detect significant changes in audience size
  - This lets you find audiences that have suddenly grown or shrunk, letting you better analyze potential market changes
- Detect duplicate audiences
  - This lets you reduce redundancies with your created audiences
- Find audiences based on full or partial attributes named
  - This lets you more easily navigate through your audience inventory
- Discover XDM fields you can use to define an audience
  - This skill lets you more easily identify the right fields to use in your audience based on context and relevance -->

Audience Agent steunt momenteel niet **&#x200B;**&#x200B;de volgende eigenschappen:

- Kennisgebaseerde publiekscreatie
   - De op kennis-gebaseerde publieksverwezenlijking leidt tot een publiek dat op de bepaalde attributen en de gebeurtenissen wordt gebaseerd
   - Bovendien kunt u de potentiële grootte van het publiek vóór de publieksverwezenlijking schatten. Zo kunt u snel het meest effectieve publiek doorlopen voordat het klaar is om te activeren
   - Deze functie wordt binnenkort ondersteund
- Goal-based publieksverkenning
   - Met doelgerichte publieksverkenning kunt u relevante datasets en profielen detecteren die zijn afgestemd op een zakelijk doel door modellen voor machinaal leren toe te passen, zoals de neiging om te kopen of om te zetten.

Wanneer u Audience Agent gebruikt, moet u bovendien rekening houden met de volgende beperkingen:

- Audience Agent heeft minstens 24 uur nodig om uw gegevens te verwerken
   - Bijvoorbeeld, kunt u **niet** een vraag hebben die gegevens binnen de laatste 24 uren zoekt. Je moet minimaal binnen de laatste 48 uur kijken.
- Audience Agent ondersteunt alleen de volgende soorten publiek:
   - **Op mensen-gebaseerde** publiek dat gebruikend partijsegmentatie wordt geëvalueerd
   - **op rekening-gebaseerde** publiek voor de volgende gebruiksgevallen:
      - Gesprek voor publiek
      - Detectie van publiek dupliceren

## Voorbeeldaanwijzingen

In de volgende voorbeelden worden voorbeeldaanwijzingen en reacties voor de Audience Agent getoond.

### Gesprek voor publiek

Geef me velden weer voor rijke kopers.

+++ Antwoord

![&#x200B; AI Medewerker toont een lijst die gebieden toont die voor welkome kopers relevant zijn.](./images/audience/affluent-buyers.png)

+++

Welk publiek is in de afgelopen 30 dagen niet geactiveerd of gebruikt in een campagne?

+++ Antwoord

![&#x200B; AI Medewerker toont een lijst die publiek toont dat niet in campagnes in de laatste 30 dagen geactiveerd of gebruikt is.](./images/audience/not-activated.png)

+++

Geef een overzicht van alle soorten publiek die in de afgelopen drie maanden zijn toegewezen aan nieuwe doelen.

+++ Antwoord

![&#x200B; AI Medewerker maakt een lijst van het één publiek dat aan een nieuwe bestemming in de laatste 3 maanden in kaart is gebracht.](./images/audience/new-destination.png)

+++

Welk publiek van de rekening heeft de grootste publieksgrootte en wat is die grootte?

+++ Antwoord

![&#x200B; AI Medewerker toont een lijst die het grootste rekeningspubliek toont.](./images/audience/largest-account-audience.png)

+++

### Gedupliceerde doelgroepen detecteren

Heb ik een publiek met identieke of vergelijkbare beschrijvingen?

+++ Antwoord

![&#x200B; AI Medewerker toont een lijst die de segmentdefinitie en de namen van het publiek met de zelfde segmentdefinities bevat.](./images/audience/similar-descriptions.png)

+++

Identificeer publiek dat de zelfde regels maar verschillende namen heeft.

+++ Antwoord

![&#x200B; AI Medewerker toont een lijst die de namen van publiek bevat dat de zelfde publieksregels deelt.](./images/audience/same-rules-different-names.png)

+++

Toon me alle publiek dat de zelfde regels maar verschillende activeringsbestemmingen heeft.

+++ Antwoord

![&#x200B; AI Medewerker toont aan dat er geen dubbele segmentdefinities aan verschillende bestemmingen zijn.](./images/audience/same-rules-different-destinations.png)

+++

Accountsoorten identificeren die dezelfde regels hebben maar andere namen hebben.

+++ Antwoord

![&#x200B; AI Medewerker toont een lijst die de namen en IDs van rekeningspubliek bevat die de zelfde publieksregels delen.](./images/audience/duplicate-account-audience.png)

+++

### Grootte publiek ophalen

Wat is de huidige grootte van mijn publiek &quot;Gold-star members in California_f153e1&quot;?

+++ Antwoord

![&#x200B; AI Medewerker verklaart de huidige grootte van het publiek dat werd gevraagd over.](./images/audience/current-size.png)

+++

Wat is mijn grootste publiek?

+++ Antwoord

![&#x200B; AI Medewerker geeft informatie over het publiek met de meeste profielen, met inbegrip van naam en publieksidentiteitskaart.](./images/audience/largest-audience.png)

+++

### Belangrijke wijzigingen in de grootte van het publiek vaststellen

Welk publiek is de afgelopen week met meer dan 20% toegenomen?

+++ Antwoord

![&#x200B; AI Medewerker toont een lijst die van de namen van alle publiek een lijst maakt die de vraag aanpassen. Het toont ook de percentageverhoging, de huidige publieksgrootte, evenals de vroegere publieksgrootte.](./images/audience/increase-past-week.png)

+++

Welk publiek is de afgelopen maand met meer dan 10% kleiner geworden?

+++ Antwoord

![&#x200B; AI Medewerker toont een lijst die van de namen van alle publiek een lijst maakt die de vraag aanpassen. Het toont ook de huidige publieksgrootte, de vroegere publieksgrootte, evenals de datum van de oude publieksgrootte.](./images/audience/decrease-month.png)

+++

Wat is mijn snelst groeiende publiek?

+++ Antwoord

![&#x200B; AI Medewerker verklaart de naam van het snelst groeiende publiek, evenals de huidige grootte en het percentage van de groei.](./images/audience/fastest-growing.png)

+++

## Volgende stappen

Nadat u deze handleiding hebt gelezen, hebt u beter inzicht in Audience Agent en de functies die deze ondersteunt. Voor meer informatie over agenten in Adobe Experience Platform, lees het [&#x200B; overzicht van Agent Orchestrator &#x200B;](./agent-orchestrator.md).

