---
title: Adobe Experience Platform Agent Orchestrator
description: Meer weten over Adobe Experience Platform Agent Orchestrator?
source-git-commit: 860b0f2414dc006c23fedcd7b0e29727fc0641d4
workflow-type: tm+mt
source-wordcount: '916'
ht-degree: 0%

---

# Adobe Experience Platform Agent Orchestrator

Adobe Experience Platform Agent Orchestrator is de nieuwe agentische laag in Adobe Experience Platform. Experience Platform Agent Orchestrator is ontworpen om de rijke gegevens en de kennis van klanten van het platform te benutten en biedt de kracht om de intelligentie en redenering achter speciaal ontwikkelde Adobe Experience Platform Agents te gebruiken, waardoor ze complexe besluitvormings- en probleemoplossende taken op snelheid en schaal kunnen uitvoeren — allemaal met menselijk toezicht. Wanneer u vragen stelt of hulp via natuurlijke taal in een gespreksinterface zoals AI Medewerker verzoekt, roept Agent Orchestrator automatisch op gespecialiseerde agenten om u de juiste antwoorden te krijgen. Agent Orchestrator herinnert uw gespreksgeschiedenis, toelatend u om op vorige vragen te bouwen natuurlijk zonder herhalende context, en combineert inzichten van veelvoudige agenten om u met duidelijke, verenigde reacties te presenteren.

U kunt complexe end-to-end werkschema&#39;s door een intuïtieve gespreksinterface voltooien zonder het moeten weten welke agenten achter de scènes werken. Het systeem begrijpt uw doelstellingen, leidt tot geleidelijke plannen, en past zijn benadering aan zoals nodig gebaseerd op uw terugkoppelt. U kunt het redeneringspaneel onderzoeken om het geleidelijke denken proces te zien en beter te begrijpen hoe uw verzoeken worden behandeld. Met Agent Orchestrator kunt u complexe workflows aanpakken en strategieën optimaliseren voor verschillende Adobe Experience Cloud-toepassingen.

Lees dit document voor meer informatie over Agent Orchestrator.

## Componenten van Agent Orchestrator {#components}

Agent Orchestrator bestaat uit verschillende belangrijke onderdelen, waaronder de AI Assistant-interface voor gesprekken, een redeneringsmotor voor besluitvorming en planning, gespecialiseerde Adobe Experience Platform-agenten en een kennisbasis die toegang biedt tot relevante informatie.

![ de marketing architectuur van Agent Orchestrator.](./images/agent-orchestrator/agentic-architecture.png)

### AI Assistant-interface voor gesprekken {#ai-assistant}

AI Assistant is een conversatie-ervaring die u kunt gebruiken om uw workflows in Adobe-toepassingen te versnellen. U kunt AI Medewerker gebruiken om productkennis beter te begrijpen, problemen problemen op te lossen, of door informatie te zoeken en operationele inzichten te vinden. AI Assistant ondersteunt Experience Platform, Real-Time Customer Data Platform, Adobe Journey Optimizer en Customer Journey Analytics. Met AI Assistant hebt u toegang tot Experience Platform Agents en andere AI-functies.

Voor meer informatie, lees de [ AI Hulp UI gids ](../ai-assistant/ai-assistant-ui.md).

### Reddingsmotor {#reasoning-engine}

De motor van de Redenen interpreteert uw doelstellingen die op uw natuurlijke taalherinneringen worden gebaseerd, controleert om het even welke grenzen of vereisten, en leidt geleidelijke plannen om u te helpen uw doelstellingen bereiken. In tegenstelling tot eenvoudige vraag-en-antwoordsystemen, kan het zijn plannen aanpassen aangezien de dingen veranderen, en kan teruggaan en verschillende benaderingen proberen indien nodig. De plannen die het creeert worden getoond aan u in de AI Medewerkende conversatie interface, zodat kunt u het proces zien en volgen, evenals tussenkomen indien nodig.

### Adobe Experience Platform Agents {#agents}

| Agent | Details | Ondersteunde toepassingen |
| --- | --- | --- |
| [ Audience Agent ](audience.md) | In Audience Agent kunt u inzicht weergeven in het publiek, zoals het detecteren van belangrijke wijzigingen in de publieksgrootte, het detecteren van dubbele doelgroepen, het verkennen van uw publieksoverzicht en het ophalen van de grootte van uw publiek. | <ul><li>Real-Time CDP</li><li>Adobe Journey Optimizer</li></ul> |
| [ Data Insights Agent ](https://experienceleague.adobe.com/nl/docs/analytics-platform/using/cja-overview/cja-b2c-overview/data-analysis-ai) | Data Insights Agent, dat vanuit de AI Assistant in Customer Journey Analytics toegankelijk is, is een generatieve AI-gespreksagent die snel en efficiënt vragen over uw gegevens beantwoordt. In Analysis Workspace worden relevante visualisaties gemaakt aan de hand van componenten uit uw gegevensweergave en met behulp van uw werkelijke gegevens. | Customer Journey Analytics |
| Experimentatieagent | De Experimentation Agent helpt teams sneller te leren door experimentele resultaten te analyseren, de impact te voorspellen en nieuwe experimenten voor te stellen. Het centraliseert verleden en actieve experimenten zodat kunt u voortbouwen op wat u reeds hebt geleerd, vlekkleuningen, en prioriteren wat om daarna te testen. | Adobe Journey Optimizer Experimentation Accelerator |
| [ Journey Agent ](./ajo-agent-analyze.md) | Met Journey Agent kunnen Adobe Journey Optimizer-gebruikers reizen maken, analyseren en optimaliseren met behulp van een natuurlijke taalinterface. Met Journey Agent kunt u snel reizen maken, plannings- of publieksconflicten opsporen en oplossen, prestaties en aflooppunten analyseren en best presterende reizen identificeren die u wilt repliceren voor toekomstige campagnes. Het helpt u gegevensgestuurde beslissingen te maken, de betrokkenheid van klanten te verbeteren en reisorchestratie te stroomlijnen. | Adobe Journey Optimizer |
| [ Agent van de Steun van het Product ](https://experienceleague.adobe.com/nl/docs/experience-platform/ai-assistant/new-features/customer-support) | De Agent van de Steun van het product is zelfbediening het zuiveren en het oplossen van problemenvermogen dat u helpt de eigenschappen en de toepassingen van Adobe Experience Platform problemen oplossen zonder uw werkschema te verlaten. De beheerders van de steun kunnen de kaartjes van de klantensteun met context van uw Hulp van AI tot stand brengen en u kunt kaartupdates controleren door AI Medewerker. | <ul><li>Adobe Experience Platform</li><li>Real-Time CDP</li><li>Adobe Journey Optimizer</li><li>Adobe Journey Optimizer B2B edition</li><li>Customer Journey Analytics</li><li>Adobe Experience Manager</li></ul> |

### Kennisbank {#knowledge-base}

De kennisbank verleent agenten veilige toegang tot de bedrijfsintelligentie van de klant door gestructureerde en ongestructureerde gegevensbronnen, met inbegrip van het productdocumentatie van Adobe, klantenmeta-gegevens over bedrijfsvoorwerpen, en analysegegevens.

## Toegang {#access}

AI Assistant-aanvragen worden geverifieerd met de Adobe Identity Management Services. Autorisaties worden afgedwongen door Adobe Experience Platform Access Control en Customer Journey Analytics Access Control.

Om toegang tot de AI Hulp gespreksinterface te krijgen en één of meerdere Agenten van Experience Platform te gebruiken, moet uw beheerder van Adobe u de relevante toestemmingen in de UI van Toestemmingen of Adobe Admin Console verlenen:

* **Real-Time CDP** en **Adobe Journey Optimizer**: Uw beheerder moet u **toelaten AI Medewerker** toestemming verlenen om u toe te laten om tot Medewerker toegang te hebben AI. Uw beheerder moet u ook de **Operationele toestemmingen van de Mening verlenen** om u toe te staan om operationele inzichten vragen in AI Medewerker te stellen. Beide toestemmingen worden geplaatst door de beheerder in de Toestemmingen UI.

* **Customer Journey Analytics**: Uw beheerder moet u de toestemming verlenen om tot AI Medewerker door [ het Toegangsbeheer van Customer Journey Analytics ](https://experienceleague.adobe.com/nl/docs/analytics-platform/using/technotes/access-control) toegang te hebben. Hierdoor kunt u vragen stellen over productkennis en gegevensinzichten.

>[!NOTE]
>
>Voor Customer Journey Analytics zijn geen vragen over operationele inzichten beschikbaar. Er zijn daarom geen aanvullende machtigingen van toepassing.

* **Adobe Experience Manager**: Uw beheerder moet u de toestemming verlenen om tot AI Medewerker door [ Adobe Admin Console ](https://helpx.adobe.com/nl/enterprise/using/admin-console.html) toegang te hebben.


