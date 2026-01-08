---
title: De reis leidt tot het Overzicht van de Vaardigheid van de Agent
description: Leer hoe u Journey Agent gebruikt om marketingreizen te maken via herinneringen voor natuurlijke talen in Journey Optimizer.
solution: Journey Optimizer
product: journey optimizer
role: Admin,User,Developer
feature: AI Assistant
topic: Administration
level: Beginner
source-git-commit: 864002185f3745ca76180af192f616d1e5da0791
workflow-type: tm+mt
source-wordcount: '1068'
ht-degree: 0%

---


# De reis leidt Agent tot: Overzicht van de Vaardigheid en gebruikersgids

## Overzicht

Met de Reis Create Agent kunnen Journey Optimizer-gebruikers marketingreizen maken en configureren met behulp van een natuurlijke taalinterface. Met Reis creëren Agent, kunnen de artsen reizen snel tot stand brengen door hun vereisten in gespreksherinneringen te beschrijven. De agent stroomlijnt de verwezenlijking van de reis, toestaand marketers om zich op strategie eerder dan technische configuratie te concentreren.

>[!AVAILABILITY]
>
>De Reis creeert Agent is beschikbaar voor alle klanten die toegang tot AI Medewerker hebben. Nochtans, zult u de volgende toestemmingen nodig hebben om de Reis te gebruiken creeert de eigenschappen van de Agent:
>
>**beheert Reizen**: Deze toestemming laat u nieuwe reizen direct in AI Medewerker tot stand brengen.
>
>**de Gebeurtenissen van de Reis van de Mening, Gegevensbronnen en Acties**: Deze toestemming zorgt ervoor dat AI Medewerker door de Gebeurtenissen van de Reis en de Acties van de Douane kan zoeken.
>
>**Segmenten van de Mening**: Deze toestemming zorgt ervoor dat AI Medewerker naar publiekssegmenten kan zoeken wanneer het creëren van een Reis.
>
>**beheer Segmenten**: Deze toestemming laat u nieuw publiek direct in AI Medewerker tot stand brengen.

## Gebruiksscenario’s

### Belangrijkste gebruiksgevallen voor de Agent van de Reis creëren

De reis creeert de vaardigheid van de Agent biedt mogelijkheden aan die kunnen worden gebruikt om marketing uitvoering te versnellen:

1. **gebeurtenis-teweeggebrachte reisverwezenlijking**

   - Reizen maken die worden geactiveerd op basis van specifieke klantgebeurtenissen.
   - Ontwerp geautomatiseerde reacties op acties van klanten in real time.
   - Bouw gepersonaliseerde communicatie stromen die op klantengedrag worden gebaseerd.

1. **publiek-gerichte reisverwezenlijking**

   - Reizen maken voor specifieke doelsegmenten.
   - Ontwerp multi-step communicatiereeksen met strategische timing.

1. **zaken-gebeurtenis teweeggebrachte reisverwezenlijking**

   - Reizen maken die activeren op basis van een bepaalde zakelijke gebeurtenis en een bepaald publiek als doel instellen (bijvoorbeeld product terug in voorraad of verandering van gamescore)
   - Bouw gepersonaliseerde communicatie stromen die op klantengedrag worden gebaseerd.

1. **de kwalificatieverwezenlijking van het publiek**

   - U kunt reizen maken die als profielen worden geactiveerd en een definitie voor een publiekssegment invoeren of afsluiten.
   - Bouw gepersonaliseerde communicatie stromen die op klantengedrag worden gebaseerd.

1. **Voorwaardelijke reisstromen**

   - Beslissingsvertakkingen maken op basis van klantkenmerken.
   - Ontwerp gesplitste paden die worden aangepast aan de voorkeuren van de klant.

Voor elk van deze gebruiksgevallen vertaalt de agent de vereisten voor natuurlijke talen in gestructureerde reisconfiguraties.

## In het toepassingsgebied en buiten het bereik

### **In werkingsgebied**

De volgende mogelijkheden worden gesteund door de Agent van de Reis Create:

- **de verwezenlijking van de de taalreis**: Staat gebruikers toe om reisstroom in gesprekstaal te beschrijven.
- **gebeurtenis-Gebaseerde en op publiek-gebaseerde reizen**: Steunt zowel op trekker-gebaseerde als geplande vervoerstypes, ook bedrijfsgebeurtenis en publiekskwalificatie.
- **Voorwaardelijke logica**: De verdeling van het besluit van de handvatten en het vertakken gebaseerd op klantenattributen.
- **Meerkanaals overseinen**: Steunt dupberichten, e-mail, en de kanalen van SMS.
- **Reis die** plant: Vormt begindata en timing voor geplande reizen.

### **uit werkingsgebied**

De volgende functies worden momenteel niet ondersteund:

- **Geavanceerde reisanalyses**
- **Realtime reiswijzigingen**
- **Cross-trip orchestratie**
- **A/B testende configuratie**
- **Complexe gegevenstransformaties**
- **de berichtverwezenlijking van de inhoud**

## Voorbeeldaanwijzingen

### Veelvoorkomende herinneringen voor het maken van reizen

Hier zijn voorbeelden van waardevolle vragen die gebruikers kunnen gebruiken om reizen te maken.

### Vrachtvragen die door gebeurtenissen worden geactiveerd

**reis van het bezoek van de Opslag:**

&quot;Maak een reis die begint wanneer een gebruiker mijn winkellocatie betreedt. Stuur een pushmelding om gebruikers naar de winkel te ontvangen. Wacht twee dagen en controleer of de gebruiker een geldig e-mailadres heeft. Als de gebruiker een geldig e-mailadres heeft, stuurt u een e-mailenquête naar zijn ervaringen met winkels. Als de gebruiker geen geldig e-mailadres heeft, verzendt u een pushmelding om te vragen of de gebruiker zich kan registreren.&quot;

**reis na aankoop:**

&quot;Maak een reis die begint wanneer een klant online een aankoop doet. Stuur een pushmelding om ze te bedanken voor hun aankoop. Controleer vervolgens of ze loyaliteitsleden zijn. Als de gebruiker een loyaliteitbeloningslid is, verzend een tweede dupmelding met een 10% kortingscode. Als de gebruiker geen loyaliteitsbeloningslid is, verzendt een duw die hen uitnodigt om zich voor het loyaliteitsprogramma aan te melden. Wacht 2 dagen en verzend een vervolgduw met een onderzoek over hun aankoopervaring.&quot;

**gebeurtenis-gebaseerde bevordering:**

&quot;Maak een rit die wordt geactiveerd wanneer de gamescore 50 bereikt. Stuur een SMS-bericht naar loyaliteitsbonnen die zeggen dat ze in aanmerking komen voor een gratis pizza-segment van de sponsor van de partner.&quot;

### Doelgerichte reisherinneringen voor het publiek

**seizoenscampagne:**

&quot;Ik wil een reis maken die gericht is op een publiek van de dag. Ik wil een e-mail sturen waarin dit publiek wordt gewaarschuwd voor mijn aanstaande vakantieverkoop die een verscheidenheid aan hangende basiszaken omvat. Wacht 3 dagen na het verzenden van het eerste e-mailbericht en verzend een tweede e-mailbericht met een coupon van 15% voor gratis verzending. Wacht 1 week en verzend dan een 3de e-mailbericht om onze nieuwe slaapzak en tentinzameling te tonen. Plan de reis om 12/20 te beginnen.&quot;

**Waardering van de Loyalty:**

&quot;Bouw een reis van de loyaliteitswaardering voor SUV-eigenaren, met inbegrip van een dank u duw bericht met een vrije aanbieding van het carwash en een herinnering van de follow-up dupmelding als de eerste bericht niet binnen 1 dag met elkaar in wisselwerking staat.&quot;

### Open-end herinneringen

Voor gebruikers die beginnen zonder een specifieke reis in mening:

- &quot;Ik wil een reis maken&quot;
- &quot;Help me een reis te maken&quot;
- &quot;Maak me een reis&quot;

De agent zal begeleiding en voorbeelden verstrekken om u te helpen uw reisvereisten bepalen.

## Best practices

### Aankondiging van aanbevolen procedures

Om de doeltreffendheid van Reis te maximaliseren creeer Agent, volg deze beste praktijken:

1. **ben Specifiek**: Verstrek duidelijke details over uw reisdoelstellingen, doelpubliek, en gewenste acties. Neem informatie op over kanalen, timing en voorwaarden.
1. **specificeer Tijdopnemer**: wijs duidelijk wachttijden tussen acties en wanneer de reis zou moeten beginnen.
1. **bepaalt Voorwaarden**: Wanneer het gebruiken van voorwaardelijke logica, verklaar de criteria voor elke takweg.
1. **omvat Kanalen**: Specificeer welke communicatiekanalen u (duw, e-mail, SMS) wilt gebruiken.
1. **Verwijzing die** plant: Voor geplande reizen, verstrek de gewenste begindatum en de tijd.
1. **de Acties van de Douane**: Als u douaneacties in uw werkschema gebruikt moet u specificeren dat u een douaneactie samen met de nauwkeurige naam van de douaneactie gebruikt. Voorbeeld:
Wanneer een gebruiker mijn opslagplaats ingaat verzend een welkomstbericht gebruikend douaneactie ExternalPush. Wacht twee dagen en verzend dan een vervolgbericht gebruikend douaneactie ExternalEmail met een onderzoek op hun bezoek.
1. **bevestigt Uitdrukkingen**: Zorg ervoor om het even welke uitdrukkingen te controleren en te bevestigen die Journey Agent creeert om ervoor te zorgen dat de correcte gebieden en de waarden worden gebruikt.

### Beste werkwijzen instellen

- **bepaalt Duidelijke Doelstellingen**: Alvorens reizen te creëren, bepaal duidelijke doelstellingen (verbeterend behoud, aandrijvende omzettingen, verhogend engagement).
- **Bereid publiek voor**: Zorg ervoor uw doelpubliek reeds wordt gecreeerd en behoorlijk gesegmenteerd.
- **Inhoud van het Bericht van het Plan**: Heb uw overseinenstrategie die vóór reisverwezenlijking wordt bepaald.
- **overweeg de Ervaring van de Klant**: De reisstromen van het ontwerp die klantenvoorkeur respecteren en overmededeling vermijden.

