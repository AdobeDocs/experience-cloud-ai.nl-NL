---
title: Adobe Marketing Agent for Microsoft 365 Copilot
description: Leer hoe je de Adobe Marketing Agent for Microsoft 365 Copilot kunt gebruiken.
source-git-commit: 5cf5e42c727cd5e48b1b817e150fb9862fc80c82
workflow-type: tm+mt
source-wordcount: '1793'
ht-degree: 0%

---

# Adobe Marketing Agent for [!DNL Microsoft 365 Copilot]

De Adobe Marketing Agent for [!DNL Microsoft 365 Copilot] is een door AI aangedreven gereedschap dat Adobe Experience Platform rechtstreeks verbindt met [!DNL Microsoft 365 Copilot] . Met deze agent kunt u in [!DNL Microsoft 365] -toepassingen, zoals [!DNL Teams] , [!DNL Word] , [!DNL Powerpoint] en [!DNL Excel] , vragen in de natuurlijke taal stellen om direct marketinginzichten van Experience Platform op te halen zonder uw workflow te onderbreken. Dezelfde agent is beschikbaar voor deze apps en uw chathistorie met de Adobe Marketing Agent loopt over—zodat u bijvoorbeeld in [!DNL Copilot] in [!DNL Teams] kunt beginnen te zoeken en het gesprek kunt voortzetten in [!DNL Word] of [!DNL Powerpoint] terwijl u een campagnemorandum samenstelt of een presentatie kunt reviseren.

Met de Adobe Marketing Agent for [!DNL Microsoft 365 Copilot] kunnen marketingmanagers, analytische en inzichten teams en zakelijke belanghebbenden:

- Maak snellere, gegevensgestuurde marketingbeslissingen.
- Verminder tijd besteed schakelen tussen hulpmiddelen.
- Vereenvoudig toegang tot publiek en reisinzichten door teams.

## Hoe de agent werkt

>[!IMPORTANT]
>
>De Adobe Marketing Agent for [!DNL Microsoft 365 Copilot] biedt momenteel ondersteuning voor Experience Platform Operational Insights, Customer Journey Analytics Data Insights, Audience Agent en de Journey Agent.

De Adobe Marketing Agent for [!DNL Microsoft 365 Copilot] biedt een geïntegreerde ervaring tussen Experience Platform- en [!DNL Microsoft 365] -toepassingen:

- Adobe Marketing Agent wordt als een agent weergegeven in [!DNL Microsoft 365 Copilot] , inclusief in [!DNL Teams] , [!DNL Word] , [!DNL Powerpoint] en [!DNL Excel] .
- Meld u aan met uw Adobe-account en selecteer de gegevensomgeving (sandbox, gegevensweergave) die u wilt gebruiken.

### Toegang tot gegevens en machtigingen

De antwoorden u ontvangen wijzen op het **gegevens en toegangsniveau** verbonden aan uw Adobe identiteit-wat u kunt vragen en zien is het zelfde als wat u in Experience Platform en zijn bijbehorende oplossingen gerechtigd bent. Adobe Marketing Agent **erft** die toestemmingen en vereist **** geen afzonderlijke toestemmingenopstelling voor de [!DNL Microsoft 365] integratie. Voor onderliggende mogelijkheden van de Medewerker van Experience Platform AI en andere agenten van Adobe AI, **zijn de toestemmingsvereisten onveranderd** van het gebruiken van die eigenschappen in Experience Platform.

De agent maakt een [!DNL Microsoft 365] -instantie met Experience Platform en de bijbehorende toepassingen (Real-Time CDP, Adobe Journey Optimizer en Customer Journey Analytics). Met deze integratie kunt u vervolgens de Experience Platform AI Assistant en de agents gebruiken om relevante inzichten rechtstreeks op te halen in uw [!DNL Microsoft 365] -instantie. De antwoorden die in uw [!DNL Microsoft 365] -instantie worden gegeven, worden weergegeven als conversatie- en natuurlijke taaltekst, tabellen en gegevensvisualisatie. Daarnaast is ondersteuning voor vervolgvragen en onderzoeken beschikbaar in dezelfde [!DNL Copilot] -chat.

## Hoofdgebruik en voorbeeldscenario&#39;s

| Hoofdletters gebruiken | Beschrijving |
| --- | --- |
| Operationele inzichten ophalen voor publiek- en klantreizen | Met de Adobe Marketing Agent kunt u eenvoudig operationele inzichten opvragen voor uw publiek en klanten. U kunt bepalen welke doelgroepen het grootst of het meest betrokken zijn, zodat u kunt bepalen waar uw inspanningen moeten worden geconcentreerd. U kunt zien welke klantenreizen momenteel actief zijn en leren hoe zij presteren, die u helpen mogelijkheden voor optimalisering identificeren. De agent laat u ook volgen hoe uw verschillende segmenten in tijd groeien of krimpen, toelatend u om aan veranderingen in uw publieksdynamiek te antwoorden aangezien zij gebeuren. |
| Gegevensvisualisatie gebruiken om klantreizen en -campagnes beter te analyseren | U kunt de reisprestaties en keuzemogelijkheden bekijken, de campagneprestaties in de loop der tijd vergelijken en begrijpen welke aanraakpunten de conversies van de schijf ondersteunen. Daarnaast kunt u visuele rapporten genereren over de prestaties van de campagne en deze vergelijken over kanalen, regio&#39;s of verschillende tijdsperiodes. U kunt ook trends verkennen zonder dat u handmatig query&#39;s of dashboards hoeft te maken. |
| Samenwerking en besluitvorming versterken | Gebruik voorgestelde herinneringen om publiek, campagnes, en Webverkeer te onderzoeken. Profiteer van een natuurlijke-taalinterface voor het gemakkelijker leren van Experience Platform- en Customer Journey Analytics-concepten. Bovendien kunt u tijdens planningsvergaderingen inzichten delen over [!DNL Teams] kanalen of chats. U kunt de Adobe Marketing Agent ook gebruiken om ad-hoc vragen in real time te beantwoorden terwijl het herzien van plannen of decks, die u toestaan om belanghebbenden op de zelfde reeks metriek en definities gericht te houden. |

## Vereisten

Voordat u de Adobe Marketing Agent for [!DNL Microsoft 365 Copilot] kunt gebruiken, moet u eerst controleren of u over het volgende beschikt:

- [!DNL Microsoft 365] with [!DNL Microsoft Teams] or [!DNL Microsoft Copilot Chat] .
- Experience Platform en ten minste één van: Real-Time CDP, Adobe Journey Optimizer en/of Customer Journey Analytics.
- Recht op de Experience Platform Agent Orchestrator en de gemachtigden.
- Toegang tot de Adobe Experience Cloud-account van uw organisatie (aanmelden en productrechten) voor de oplossingen en gegevens die u gebruikt. Neem contact op met de Adobe-beheerder als u geen Adobe-toegang hebt.

## De agent inschakelen voor uw organisatie {#enable-the-agent-for-your-organization}

Eindgebruikers kunnen de Adobe Marketing Agent alleen gebruiken nadat deze beschikbaar is gesteld in uw [!DNL Microsoft 365] -huurder. **Werk met uw [!DNL Microsoft 365] beheerder Copilot** (of gelijkwaardige admin voor de agenten van Copilot in uw organisatie) om toegang toe te laten en de agent toe te wijzen zoals uw organisatie vereist.

De typische resultaten na de installatie van admin omvatten:

- U kunt **[!DNL Agent Store]** openen in [!DNL Teams] , **[!DNL Adobe Marketing Agent]** zoeken in uw lijst met agents en **[!DNL Add]** kiezen om deze aan uw Copilot-agents te koppelen.
- Alternatief, kan uw beheerder Copilot **** de agent aan iedereen in uw organisatie of aan specifieke groepen publiceren zodat hoeven de gebruikers niet om het individueel toe te voegen.

Voor beheerderstappen en beleidsopties in het [!DNL Microsoft 365] admin centrum, zie [ agenten voor Microsoft 365 Copilot ](https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/manage) in de documentatie van Microsoft leiden.

## Aan de slag

Nadat uw organisatie de agent (zie [ toelaat de agent voor uw organisatie ](#enable-the-agent-for-your-organization)) heeft toegelaten, navigeer aan [!DNL Microsoft 365 Copilot] in de toepassing van uw keus en gebruik de linkernavigatie om **[!DNL All Agents]** te selecteren.

![ Microsoft 365 de linkernavigatie van de Kopilot met Alle Geselecteerde Agenten.](../agents/images/ama/all-agents.png)

Zoek de kaart voor [!DNL Adobe Marketing Agent] of gebruik de zoekbalk om handmatig naar de agent te zoeken. Zodra u de agent hebt, selecteer de kaart.

![ de kaart of het onderzoeksresultaat van Adobe Marketing Agent in de agentengalerie.](../agents/images/ama/select-ama.png)

Gebruik het pop-up venster om meer over de agent te leren. Wanneer u klaar bent, selecteert u **[!DNL Add]** .

![ de details pop-up van Adobe Marketing Agent met Add benadrukte knoop.](../agents/images/ama/add-ama.png)

Het dashboard van [!DNL Microsoft 365 Copilot] wordt bijgewerkt met de markering [!DNL Adobe Marketing Agent] nu op de hoofdpagina.

![ Microsoft 365 de homepage van Copilot die Adobe Marketing Agent op het belangrijkste dashboard toont.](../agents/images/ama/home.png)

### Aanmelden en uw context instellen

Vervolgens vraagt u de agent zich aan te melden en de stappen te volgen die nodig zijn om uw account te verifiëren. Tijdens deze stap, zult u een numerieke code moeten kopiëren die de agent terugkeert en dan binnen aan uw organisatie van Adobe ondertekent. Als u login niet kunt voltooien of u hebt geen toegang tot de oplossingen van Adobe voor uw organisatie, contacteer uw **beheerder van Adobe**.

![ Adobe teken-binnen stap die een numerieke code tonen om met uw organisatie van Adobe voor authentiek te verklaren.](../agents/images/ama/sign-in.png)

Wanneer succesvol, gebruik contextsetter om de documentatiebron, zandbak, en gegevensmening te vestigen die u voor uw vragen zult gebruiken.

![ de setter UI van de Context om documentbron, zandbak, en gegevensmening voor vragen te kiezen.](../agents/images/ama/context.png)

### Gebruik de agent om operationele inzichten terug te winnen

Nadat u zich hebt aangemeld, kunt u de aanwijzingen op de hoofdpagina gebruiken om aan de slag te gaan. U kunt ook profiteren van een startprompt die zich kan vertakken naar het analyseren van marketingsoorten, het evalueren van de campagneresultaten en het controleren van campagnetreizen. Selecteer bijvoorbeeld **[!DNL Review campaign performance]** en vervolgens **[!DNL Analyze engagement - Show web visitors for top 10 products last week]** .

![ de herinneringen van de Aanzet op de pagina van het agentenhuis, met inbegrip van de campagneprestaties van het Overzicht en analyseer betrokkenheidsopties.](../agents/images/ama/starter-guide.png)

Sta voor een paar ogenblikken voor de agent toe om te berekenen en dan antwoordt de agent met een visualiseerde vertegenwoordiging van uw gegevens. U kunt het weergegeven staafdiagram gebruiken of **[!DNL View data]** selecteren om de gegevens in tabellen weer te geven.

![ de reactie van de Agent met een staafdiagram visualiserend Webbezoekers voor hoogste producten en de optie van de Gegevens van de Mening.](../agents/images/ama/response.png)

![ Zelfde inzichten die als gegevenslijst na het selecteren van de gegevens van de Mening worden getoond.](../agents/images/ama/tables.png)

U kunt verder onderzoeken door follow-upvragen te selecteren die de agent aanbeveelt. Alternatief, kunt u roteren en verschillende starterherinneringen proberen, de informatiebronnen verifiëren die de agent van verwijzingen voorziet, of terugkoppelen verstrekken gebruikend het terugkoppelt mechanisme.

![ stelde vervolgvragen onder de reactie van de agent voor verder onderzoek voor.](../agents/images/ama/follow-up.png)

Voor meer informatie over de AI Hulpeigenschappen UI, lees de gids op [ gebruikend de Medewerker AI ](../ai-assistant/ai-assistant-ui.md).

## Beveiliging, privacy en verantwoordelijke AI

**de behandeling en het bestuur van gegevens**

De Adobe Marketing Agent vertrouwt op dezelfde besturingselementen en governance die van toepassing zijn op Experience Platform en [!DNL Microsoft 365] . Uw organisatie behoudt de eigendom van en de controle over de gegevens. De inzichten die door de agent zijn teruggekeerd zijn scoped aan de toestemmingen en de gegevensaanspraken van elke gebruiker Adobe; geen extra toestemmingsmodel wordt geïntroduceerd voor het [!DNL Microsoft 365] oppervlak voorbij wat reeds in Experience Platform en verwante agenten van Adobe AI van toepassing is.

**Verantwoordelijk gebruik AI**

De agent is bedoeld om alleen-lezen inzichten te retourneren en wijzigt uw klantgegevens in Experience Platform niet. U zou om het even welke geproduceerde samenvattingen en analyses moeten herzien alvorens u hen gebruikt om bedrijfsbesluiten te nemen.

**Gesteunde talen en werkingsgebied**

De eerste release is beschikbaar als een Engelstalige ervaring. Capabilities zijn beperkt tot alleen-lezen inzichten; de agent maakt of werkt geen marketingelementen of -configuraties bij.

## Bijlage

Lees het volgende voor meer informatie over de Adobe Marketing Agent for [!DNL Microsoft 365 Copilot] .

### Adobe Marketing Agent [!DNL Microsoft 365 Copilot] -beheerstappen

Om agenten van een externe leverancier (derdeontwikkelaars of de Commerciële Marketplace van Microsoft) op te zetten, moet u eerst uw huurdersmontages externe apps toestaan en dan hen beheren door de Geïntegreerde Apps of sectie van Agenten van het admin centrum.

#### Externe agenten in huurdersmontages toelaten

Alvorens u externe agenten kunt opstellen, moet het beleid van uw organisatie hen toestaan.

- Login aan het [ Microsoft 365 admin centrum ](https://admin.microsoft.com/).
- Ga naar **Agenten** > **Montages** > **de toegang van de Gebruiker**.
- Onder **Toegestane agententypes,** verzekert **apps en agenten toestaat die door externe uitgevers** worden gebouwd wordt geselecteerd.

>[!IMPORTANT]
>
>Als dit plaatsen gehandicapt is, zullen de externe agenten niet in de [ Winkel van de Agent ](https://devblogs.microsoft.com/microsoft365dev/introducing-the-agent-store-build-publish-and-discover-agents-in-microsoft-365-copilot/) voor uw gebruikers verschijnen.

#### Verkrijg en keur de agent goed

Typisch, kunt u externe agenten in [[!DNL Microsoft Commercial Marketplace] vinden ](https://appsource.microsoft.com/).

- **van de Marketplace**: Vind de agent u wilt en **selecteert krijgt het nu**. Dit zal u vaak terug naar uw admin centrum **Geïntegreerde Apps** pagina opnieuw richten.
- **Toestemmingen van het Overzicht**: In de [ Geïntegreerde Apps ](https://learn.microsoft.com/en-us/microsoft-365/admin/manage/manage-deployment-of-add-ins?view=o365-worldwide) lijst, selecteer de externe agent.
- Herzie de **Gegevens &amp; hulpmiddelen** en **Veiligheid &amp; naleving** lusjes om te zien welke gegevens de externe leverancier toegang zal hebben.
- Selecteer **goedkeuren** of **activeer** om het in de inventaris van uw organisatie te bewegen.

#### Distribueren naar bepaalde gebruikers

Zodra goedgekeurd, kunt u precies controleren wie de agent in hun Copilot sidebar ziet.

- In het [[!DNL Microsoft 365]  admin centrum ](https://admin.microsoft.com/), navigeer aan **Agenten** > **Alle agenten**.
- Selecteer de externe agent in de lijst.
- Selecteer **opstellen** (of **geef Toewijzing** uit).
- Kies **Specifieke gebruikers/groepen** en onderzoek naar de individuen of [!DNL Entra ID] groepen die het zouden moeten hebben.
- Selecteer **Voltooi plaatsing**. Dit &quot;duwt&quot;de agent aan die gebruikers zodat verschijnt het automatisch in hun interface Copilot.

#### Updates beheren

Externe providers werken hun agents vaak bij. Volg onderstaande aanbevolen procedures om deze updates te beheren:

- Controleer [[!DNL Agent Registry] ](https://learn.microsoft.com/en-us/microsoft-365/admin/manage/agent-registry?view=o365-worldwide) periodiek.
- Als een update nieuwe toestemmingen vereist, kan de agent een status van **in afwachting van Update** tonen.
- U moet manueel **Updates** goedkeuren alvorens de nieuwe versie aan uw toegewezen gebruikers wordt opgesteld.