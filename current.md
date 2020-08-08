---
title: Versionsinformation om Adobe Experience Cloud
description: Versionsinformation om Adobe Experience Cloud
doc-type: release notes
last-update: August 2020
author: mfrei
translation-type: tm+mt
source-git-commit: dab2c3fb8b9920f079195693a584f7c48b813e23
workflow-type: tm+mt
source-wordcount: '6017'
ht-degree: 41%

---


# Tidig åtkomst - Adobe Experience Cloud versionsinformation - augusti 2020

![Banderoll](/assets/experience-cloud-banner-3.png)

Den här sidan beskriver nya funktioner, korrigeringar och viktiga meddelanden i [!DNL Adobe Experience Cloud]. Här finns också ny dokumentation, kurser och videokurser som hjälper dig att få ut mesta möjliga av Experience Cloud.

>[!IMPORTANT]
>
>Den här sidan innehåller innehåll som släppts i förväg och omfattas av ändringar före den planerade releasen.

>[!NOTE]
>
>Prenumerera på [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) om du vill få meddelanden via e-post om kommande versioner.

**Releasedatum: 13 augusti 2020**

Datum för produktreleaser kan variera. Leta ofta efter uppdateringar.

Senaste uppdatering: **7 augusti 2020**

* [Adobe – systemstatus](#status)
* [Experience Cloud-gränssnitt](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Analytics](#analytics) och [Customer Journey Analytics](#cust-journey)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/sv-SE/target/using/release-notes/target-release-notes.html)
* [!DNL Magento](#magento)
* [!DNL Marketo Engage](#marketo)
* [!DNL Primetime](https://docs.adobe.com/content/help/sv-SE/primetime/release-notes/home.html)

Behöver du hjälp? Besök [Adobe Experience League](https://experienceleague.adobe.com/#home) för att hitta produkt- och teknisk dokumentation, kurser, videokurser, snabbsvar, communityinsikter och lärarledd utbildning.

## ![Ikon för](/assets/adobe.png) Adobe – systemstatus {#status}

[!UICONTROL Adobe System Status] ger detaljerad information, statusuppdateringar och e-postmeddelanden om Adobe-molnprodukter och -tjänster, driftstopp, avbrott och underhållshändelser. Kolla in det på [status.adobe.com](https://status.adobe.com/).

Information om den senaste versionen finns i [21 maj 2020](c-legacy-releases/2020/05212020.md#status) .

## ![Ikonen i](/assets/ec_appicon_24.png) Experience Cloud-gränssnittet {#ecloud}

I Julens [tidigare versionsinformation](c-legacy-releases/2020/07162020.md#ecloud) finns den senaste versionsinformationen om det uppdaterade gränssnittet och den enhetliga produktdomänen.

## ![Ikon för](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Versionsinformation för [!DNL Experience Platform] inklusive [!DNL Experience Platform Launch,] [!UICONTROL Offers], [!UICONTROL People], [!UICONTROL Places], [!UICONTROL Mobile Services], och säkerhetsbulletiner.

Latest release date: **July 15, 2020**

[Versionsinformationen för Experience Platform](https://docs.adobe.com/content/help/sv-SE/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md) innehåller den senaste informationen om Experience Platform.

## ![Ikon](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Med Adobe Experience Platform kan ni orkestrera enskilda kundresor i stor skala över olika upplevelsekanaler genom att intelligent förutse varje enskild individs behov i realtid, oavsett vart resan bär.

### Nya kurser och självstudiekurser i Campaign

Nya videofilmer, självstudiekurser och kurser som publicerats den senaste månaden.

| Publicerad | Namn | Beskrivning |
| ----------- | ---------- | ---------- |  
| 10 juli 2020 | [Rapportera händelser för kundresa till Adobe Experience Platform](https://docs.adobe.com/content/help/en/journey-orchestration-learn/tutorials/reporting-step-events-to-adobe-experience-platform.html) | Lär dig vilka steg som ska tas på kundresan och vilka datasteg som ska skapas automatiskt på Experience Platform och hur du utforskar dessa. |

### Ytterligare resurser för resesamordning

[Dokumentation](https://docs.adobe.com/content/help/sv-SE/journeys/using/journey-orchestration-home.html) – [Versionsinformation](https://docs.adobe.com/content/help/sv-SE/journeys/using/release-notes/release-notes.html) – [Instruktionsvideor](https://docs.adobe.com/content/help/sv-SE/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html)

## ![Ikon](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

* [Nya funktioner i Adobe Analytics](#aa-features)
* [Nya funktioner i Customer Journey Analytics](#cust-journey)
* [Nya funktioner i Media Analytics](#media-aa)
* [Korrigeringar i Adobe Analytics](#aa-fixes)
* [Viktiga meddelanden för Analytics-administratörer](#aa-notices)
* [AppMeasurement](#appm)

### Nya funktioner i Adobe Analytics {#aa-features}

| Funktion | [Allmän tillgänglighet](https://docs.adobe.com/content/help/sv-SE/analytics/landing/an-releases.html) – Måldatum | Beskrivning |
| -----------| ---------- |-------|
| Förbättringar av datainsamling i Kina | 13 aug 2020 | Bland förbättringarna finns: Stöd för Experience Cloud ID-tjänst. Stöd för SSL från första part. och stöd för vidarebefordran på serversidan. Kontakta din säljare på Adobe om du vill ha mer information. |
| [!UICONTROL Cross-Device Analytics]: Tillgänglighet i EMEA och APAC | 31 augusti 2020 | [Enhetsövergripande analyser](https://docs.adobe.com/content/help/en/analytics/components/cda/overview.html) och privata diagram kommer att vara tillgängliga för kunder i EMEA och APAC. |
| Förbättring av fältbaserad stygn i [!UICONTROL Cross-Device Analytics] (tillgänglig i Nord- och Sydamerika och EMEA) | 17 augusti 2020 | Denna förenklade implementering för nya [!UICONTROL Cross-Device Analytics] kunder ger dig möjlighet att sy ihop baserat på ett användar-ID som lagras i ett analysfält (prop eller eVar) i stället för att använda enhetsdiagram (co-op eller private). Förbättringen eliminerar kravet på att implementera ECID och eliminerar kravet på att implementera ID-synkronisering för CDA. (ECID- och ID-synkronisering krävs fortfarande för vissa andra funktioner.) |

### Nya funktioner i Customer Journey Analytics {#cust-journey}

| Funktion | [Allmän tillgänglighet](https://docs.adobe.com/content/help/sv-SE/analytics/landing/an-releases.html) – Måldatum | Beskrivning |
| -----------| ---------- |-----|
| [!UICONTROL Identity Map] alternativ för person-ID | 26 juni 2020 | [!UICONTROL Identity Map] är en kartdatastruktur som gör att du kan överföra nyckelvärdepar som en del av skapandet av en anslutning i [!UICONTROL Customer Journey Analytics]. Nycklarna är ID-namnutrymmen och värdet är den struktur som innehåller identitetsvärdet. [Läs mer...](https://docs.adobe.com/content/help/sv-SE/analytics-platform/using/cja-connections/create-connection.html#use-identity-map-as-a-person-id) |

### Nya funktioner i [!UICONTROL Media Analytics] {#media-aa}

Releasedatum: **16 juli 2020**

| Funktion | [Allmän tillgänglighet](https://docs.adobe.com/content/help/sv-SE/analytics/landing/an-releases.html) – Måldatum | Beskrivning |
| -----------| ---------- | ---------- |
| [Enheter och plattformar som stöds](https://docs.adobe.com/content/help/sv-SE/media-analytics/using/supported-devices.html) | 18 juni 2020 | I [!UICONTROL Media Launch Extension] AEP SDK finns nu stöd för följande OTT-enheter:<ul><li>Apple TV (tvOS)</li><li>Fire TV (Fire OS)</li><li>Android TV</li></ul> |
| [Enheter och plattformar som stöds](https://docs.adobe.com/content/help/sv-SE/media-analytics/using/supported-devices.html) | 18 juni 2020 | Media Launch Extension med AEP SDK har nu stöd för följande OTT-enheter:<ul><li>Apple TV (tvOS)</li><li>Fire TV (Fire OS)</li><li>Android TV</li></ul> |
| [Spårning av spelarens tillstånd](https://docs.adobe.com/content/help/sv-SE/media-analytics/using/player-state-tracking/player-state-overview.html) | 29 maj 2020 | [!UICONTROL Media Analytics]-kunder kan samla in tittarinteraktioner under uppspelning med en standarduppsättning lösningsvariabler för helskärmsvisning, undertexter, ljud av, bild-i-bild och i fokus. Du kan också skapa anpassade spelarlägen. [!UICONTROL Player State Tracking] variabler är nu tillgängliga för rapportering i [!UICONTROL Analysis Workspace]. Den här funktionen kräver något av följande: <ul><li>Media [!DNL JavaScript] SDK 3.0 eller senare</li><li>För användning med [!DNL Adobe Experience Platform] (AEP) SDK:</li><li>[!UICONTROL Media Analytics Extension] (för webb): [!UICONTROL Adobe Media Analytics] (3.x SDK) för ljud och video v1.0 eller senare</li><li>[!UICONTROL Media Analytics Extension] (för mobil): [!UICONTROL Adobe Media Analytics for Audio] och video v2.0 eller senare</li><li>[!UICONTROL Media Collection]</li></ul> |

### Korrigeringar i Adobe Analytics {#aa-fixes}

* Ett problem har korrigerats där rapporterings-API inte returnerade aktuella mätvärden. (AN-225617)
* Korrigerade ett problem som förhindrade [!UICONTROL Classification Rules] att data klassificerades för [!UICONTROL Marketing Channel Details]. (AN-224832)
* Korrigerade ett problem som orsakade ett _fel om saknade komponenter_ när nya projekt skapades i en [!UICONTROL Virtual Report Suite].(AN-226808)
* Korrigerade ett problem som orsakade ett _fel om saknade komponenter_ när en Virtual Report Suite valdes. (AN-228257)
* Ett problem som gjorde att nya mål och kalenderhändelser inte kunde skapas har korrigerats. [!UICONTROL Reports & Analytics] (AN-224872, AN-224890, AN-224914, AN-226661)
* Korrigerade ett problem som orsakade saknade aktiviteter i A4T-panelen i [!UICONTROL Workspace]. (AN-224606)
* Korrigerade ett problem med dubblerade träffar i [!UICONTROL Data Feeds]. (AN-226308)
* Ett problem har korrigerats där beräknade värden med deltagarattribuering inte returnerade korrekta värden. (AN-224642, AN-225190)
* Korrigerade ett problem med segmentdata som delats från [!DNL Analytics] till det [!DNL Audience Manager] att det tog mer än tre dagar att visas i [!DNL Audience Manager].(AN-226649)
* Korrigerade ett problem med att inte kunna använda länken i [!UICONTROL Analyze Further] [!UICONTROL Intelligent Alerts] e-postmeddelanden. (AN-226823)
* Korrigerade ett problem med att inte kunna skapa segment i en [!UICONTROL virtual report suite]. (AN-227039)
* Ett problem har korrigerats som innebar att intelligenta aviseringar inte kunde redigeras. (AN-227162)

#### Övriga korrigeringar i Adobe Analytics

AN-219351; AN-220960; AN-223788; AN-224630; AN-224948; AN-225618; AN-226261; AN-226828; AN-226845; AN-226937; AN-226961; AN-227070; AN-227079; AN-227521; AN-227610; AN-228203; AN-228451; AN-228466; AN-228538

### Viktiga meddelanden för [!DNL Analytics]-administratörer {#aa-notices}

| Meddelande | Datum tillagt eller uppdaterat | Beskrivning |
| -----------| ---------- | ---------- |
| Adobe Data Connectors upphör | 13 juli 2020 | Adobe [!UICONTROL Data Connectors] are powered by legacy technology that is no longer viable or supported. Vi har en ny standard i [Adobe Exchange Partner Program](https://partners.adobe.com/exchangeprogram/experiencecloud), som bör implementeras för alla integreringar som ska användas och stödjas framöver. Det officiella slutdatumet är ännu inte fastställt, men vi räknar med att det blir under kommande 12–18 månader (mitten/slutet av 2021). [Läs mer...](https://docs.adobe.com/content/help/sv-SE/analytics/import/dataconnectors/data-connectors-eol.html) |
| Mappning av rapportsvit till IMS-organisation | Juli 2020 | Mappningsverktyget för rapportsviter upphör i november 2020. Den här funktionen hanterar integreringar som Advertising Analytics och Experience Cloud-segmentpublicering i Adobe Analytics. En rapportsvit måste mappas till en IMS-organisation för att dessa och andra tjänster ska fungera. Nyare rapportsviter mappas automatiskt när de skapas. Äldre rapportsviter måste emellertid mappas manuellt till en IMS-organisation. See [Map report suites to an organization](https://docs.adobe.com/content/help/sv-SE/core-services/interface/about-core-services/report-suite-mapping.html) in the Experience Cloud interface (Core Services) user guide to make sure all report suites belong to an IMS org. |
| Migrering till den enhetliga produktdomänen | Datum för ikraftträdande: 28 maj 2020 | Övergången till en enhetlig produktdomän för Adobe Analytics, som började i januari 2020, slutfördes den 28 maj 2020. Adobe Analytics utelämnar alla `omniture.com`-domänreferenser från arkitekturen, men det är viktigt att vitlista `omniture.com` som en cookie från tredje part. När den fullständiga arkitekturmigreringen (snart) är klar kommer vi att meddela dig via release-notiserna och detta tillåtelseliststeg kommer inte längre att behövas. [Här](https://helpx.adobe.com/se/analytics/kb/adobe-ip-addresses.html) är en fullständig lista över rekommenderade IP-adresser och domäner som du bör vitlista.<br>Om din organisation blockerar cookies från tredje part kan du kontakta kundtjänst för att få tillgång till Adobe Analytics igen. |
| Ny startsida för Adobe Analytics | Startdatum: 18 juni 2020 | Den 18 juni 2020 ändras standardlandningssidan för Adobe Analytics från [!UICONTROL Reports] till [!UICONTROL Workspace]. Den här ändringen sker för användare som inte tidigare har angett en anpassad landningssida. |
| Tredjepartsteknologi | 12 mars 2020 (giltighetsdatum) | Adobe Analytics har börjat utnyttja teknik från tredje part för funktionshantering och produktsupport. Följande URL:er ska läggas till alla nödvändiga nätverksbrandväggstillstånd för att säkerställa fullständig åtkomst till funktionen:<ul><li>Gainsight: https://esp.aptrinsic.com</li><li>LaunchDarkly: https://app.launchdarkly.com</li></ul> |
| Förbättrad redundans för [!UICONTROL Analysis Workspace] tillgänglighet | 21 maj 2020 | Vi lägger till ett sekundärt CDN (Content Delivery Network) för förbättrad redundans och säkerställa tillgänglighet till [!UICONTROL Analysis Workspace]. Följande URL:er ska läggas till alla nödvändiga nätverks brandväggstillståndslistor:<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul> |
| Ändra hur [!UICONTROL Entries/Exits] beräknas i [!UICONTROL Workspace] | 7 april 2020 | Från och med mars 2020, har vi ändrat hur värdet _Inga_ interagerar med [!UICONTROL Entries/Exits] i [!UICONTROL Analysis Workspace]. Eftersom du nu kan aktivera och inaktivera _Inga_ i [!UICONTROL Analysis Workspace] använder vi värdet _Inga_ efter första eller sista besökssidan i stället för före (för eVars). Anta till exempel att den första träffen för ett besök inte har ett värde för eVars, men att den andra träffen har det. I [!UICONTROL Reports & Analytics] visas den första träffen som _Ospecificerat_ för första besökssidan, men i [!UICONTROL Analysis Workspace] visas det som ett värde för den andra träffen. |
| **[!UICONTROL Dashboard Archive]** tas bort | 27 mars 2020 | Inställningen **[!UICONTROL View Archive]** under **[!UICONTROL Manage Dashboards]** i [!UICONTROL Reports & Analytics] är inte tillgänglig från och med oktober 2020. |
| Äldre Analytics-API:er upphör | 9 januari 2020 | I november 2020 kommer följande äldre API-tjänster för Analytics att ha nått slutet av sina livscykler och avslutas. Aktuella integreringar som byggts med dessa tjänster kommer att sluta fungera. <ul><li>1.3 API:er för Analytics</li><li>1.4 API:er för SOAP Analytics</li><li>Äldre OAuth-autentisering (OAuth och JWT)</li></ul>Vi har tagit fram [vanliga frågor och svar om upphörande av äldre API:er](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) som kan hjälpa dig att få svar på frågor och ge vägledning om hur du går vidare. API-integrationer som använder dessa tjänster kan migrera till [1.4 Analytics REST-API:er](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) eller [2.0 Analytics API:er](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Äldre OAuth-konton kan migrera till ett [Adobe IO](https://console.adobe.io/home?mv=email) Analytics-integreringskonto som kan användas för att få tillgång till både 1.4 Analytics API:er och 2.0 Analytics API:er. |
| San Jose FTP-hantering upphör för London och Singapore | Juli 2020 | För kunder i London och Singapore stöder vi inte längre datahantering mellan London eller Singapore och datacentret [ftp.omniture.com](ftp://ftp.omniture.com/) i San Jose.<br/><ul><li>I London använder du [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>I Singapore använder du [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Ad Hoc Analysis upphör | 6 aug 2018 | Adobe har meddelat att man avser att dra tillbaka Ad Hoc Analysis. Ett slutdatum meddelas så snart det är tillgängligt. Mer information finns i [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

#### AppMeasurement

Uppdaterad information om de senaste AppMeasurement-versionerna finns i [versionsinformationen för AppMeasurement för JavaScript](https://docs.adobe.com/content/help/sv-SE/analytics/implementation/appmeasurement-updates.html).

#### Nya kurser och självstudiekurser i Analytics {#tutorials-analytics}

Nya kurser, självstudiekurser och artiklar i Analytics och Customer Journey Analytics.

| Publicerad | Namn | Lösning | Beskrivning |
| ----------- | ----------- | ---------- | ---------- |  
| 30 juli 2020 | [Begränsa åtkomst till Report Suite i Admin Console](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/administration/user-management/limit-report-suite-access-in-the-admin-console.html) | Självstudiekurs | Lär dig hur du använder [!UICONTROL Admin Console] för att säkerställa att användare bara kan komma åt de rapportsviter som är nödvändiga för deras roll. |
| 24 juli 2020 | [Lägga till en administratör i Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/administration/user-management/adding-an-administrator-to-adobe-analytics.html) | Självstudiekurs | Lär dig hur du lägger till en användare som administratör i Adobe [!UICONTROL Admin Console]. |
| 17 juli 2020 | [Panelen Quick Insights i Analysis Workspace](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/using-panels/quick-insights-panel-in-analysis-workspace.html) | Självstudiekurs | Quick Insights ger vägledning till icke-analytiker och nya användare av Analysis Workspace så att de snabbt och enkelt kan lära sig att svara på affärsfrågor. |
| 17 juli 2020 | [Analyser för målpanelen (A4T) i Analysis Workspace](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/integrations/target/analytics-for-target-a4t-panel-in-analysis-workspace.html) | Självstudiekurs | The [!UICONTROL Analytics for Target] (A4T) panel lets you analyze your Adobe Target activities and experiences, with lift and confidence, in Analysis Workspace. |
| 6 juli 2020 | [Skapa Advertising Cloud Dashboards med Adobe Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/integrations/ad-cloud/create-advertising-cloud-dashboards-with-adobe-analytics.html?lang=en#tutorials) | Självstudiekurs | Tekniker för att skapa en Advertising Cloud-kontrollpanel för övervakning av livekampanjer. |
| 6 juli 2020 | [Skapa anpassade analysvärden med Advertising Cloud Data](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/integrations/ad-cloud/create-analytics-custom-metrics-with-advertising-cloud-data.html?lang=en#tutorials) | Självstudiekurs | Användbara anpassade mätvärden för att skapa när du använder Advertising Cloud-data i Adobe Analytics. |
| 6 juli 2020 | [Skapa profiler för Analytics-webbplatsresor](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/integrations/ad-cloud/create-analytics-site-journey-profiles.html?lang=en#tutorials) | Självstudiekurs | Så här använder du Adobe Analytics för att skapa stabila pooler för återmarknadsföring av webbplatser för Advertising Cloud. |
| 6 juli 2020 | [Skapa analyssegment för aktivering och rapportering](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/integrations/ad-cloud/create-analytics-segments-for-activation-and-reporting.html?lang=en#tutorials) | Självstudiekurs | Använda Advertising Cloud-dimensioner för att skapa segment för tydligare rapportering och analys. |
| 6 juli 2020 | [Skapa en kampanjanalys före start med Adobe Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/integrations/ad-cloud/reporting-with-advertising-cloud-marketing-channels.html?lang=en#tutorials) | Självstudiekurs | Så här använder du Adobe Analytics för att lägga grunden till en mediekampanj som betalas av Advertising Cloud. |
| 6 juli 2020 | [Projektdelning i Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/curate-and-share-projects/project-sharing-in-analysis-workspace.html?lang=en#tutorials) | Självstudiekurs | Projektdelning är ett sätt att demokratisera data och insikter från Analysis Workspace till användare i organisationen. Du kan placera mottagare i en av tre projektroller, beroende på vilken projektupplevelse du vill att de ska ha - Redigera, Duplicera och Visa. |
| 26 juni 2020 | [Anpassade summeringsfönster i Attribution IQ](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/attribution-iq/custom-lookback-windows-in-attribution-iq.html?lang=en#tutorials) | Självstudiekurs | Med anpassade summeringsfönster kan du expandera attribueringsfönstret utanför rapporteringsintervallet (upp till högst 90 dagar) och använda för varje konvertering i rapporteringsintervallet. |
| 26 juni 2020 | [Visa projekt i Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/curate-and-share-projects/view-only-projects-in-analysis-workspace.html?lang=en#tutorials) | Självstudiekurs | Workspace projects can be shared to users as _Can view_ only. When a _View_ recipient opens the shared project, they receive a more restrictive project experience, with no left rail and limited interactions. |
| 26 juni 2020 | [Algoritmisk modell i Attribution IQ](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/attribution-iq/algorithmic-model-in-attribution-iq.html?lang=en#tutorials) | Självstudiekurs | I [!UICONTROL Algorithmic Attribution]-modellen i Analysis Workspace används statistiska tekniker för att dynamiskt fastställa den optimala kreditfördelningen för det valda mätvärdet. |

#### Hjälpresurser för Analytics

* [Adobe Analytics självstudiekurser](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Adobe Analytics – produktdokumentation](https://docs.adobe.com/content/help/sv-SE/analytics/landing/home.html)

## ![Ikonen](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Nya funktioner, korrigeringar, dokumentation och självstudiekurser för Audience Manager.

Releasedatum: **13 augusti 2020**

### Nya funktioner och korrigeringar i Adobe Audience Manager

* [Prediktiva målgrupper](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/algorithmic-models/predictive-audiences/predictive-audiences.html) har nu stöd för val av en [!UICONTROL Profile Merge Rule] per modell när en modell skapas. (AAM-55178)
* Startdatum och slutdatum för målmappning visas nu på varje segmentsida. (AAM-40056)
* Ett problem har korrigerats där värdet [!UICONTROL Device Type] för ett trait automatiskt ställdes in på [!UICONTROL Cross-Device] när ett nytt trait skapades. (AAM-55368)
* Korrigerade ett problem där [!UICONTROL Audience Marketplace] programmet inte kunde läsas in. (AAM-55549)
* Du kan nu ta bort mappningen av segment från [!DNL Google] mål när [!DNL Google UserList] parametern inte kan hämtas. (AAM-42655)
* Ett problem har korrigerats där tillägg av flera segment till ett mål inte alltid skulle fungera korrekt. (AAM-55651)
* Ett problem har korrigerats där användare som fick en högre [!DNL Profile Merge Rules] gräns inte kunde se [!UICONTROL Add New Rule] knappen. (AAM-55700)
* Korrigerade ett fel där [!UICONTROL 30 Day Overlapped Unique Users] titeln saknades i [!UICONTROL Data Feed Report Metrics]. (AAM-55801)
* Livstidsmått tas nu inte med i [!UICONTROL Destination] vyn när målet är konfigurerat att exportera [!DNL UUID]s. (AAM-54196)
* Ett problem där användare inte kunde visa [!DNL Tableau] rapporter har korrigerats. (AAM-55868)
* Ett problem där användare fick ett fel när de skapade en ny [!UICONTROL Predictive Audiences] modell har korrigerats. (AAM-55921)
* Flera tillgänglighetsförbättringar i hela gränssnittet. (AAM-49062, AAM-49063, AAM-49365).

### Nya självstudiekurser för Audience Manager {#tutorials-aam}

| Publicerad | Namn | Lösning | Beskrivning |
| ----------- | ----------- | ---------- | ---------- |
| 7 augusti 2020 | [Spara pengar och optimera kundupplevelsen genom att utelämna annonser till konverterare](https://experienceleague.adobe.com/?recommended=AudienceManager-A-1-2020.1) | Självstudiekurs | I den här kursen får du lära dig alla koncept du kan gå från början till slut genom att spara pengar och optimera kundupplevelsen genom att ta bort befintliga kunder från era målgruppskampanjer. Detta inkluderar att bygga egenskaper och segment, lägga till rätt regler för profilsammanslagning, lägga till segment till mål och till och med beräkna avkastningen när du använder det här användningsexemplet. |
| 7 augusti 2020 | [Välja rätt profilkopplingsregel](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/profile-merge/choosing-the-right-profile-merge-rule.html) | Självstudiekurs | I den här videon får du se tre av de vanligaste användningsexemplen för [!UICONTROL Profile Merge Rules]och hur de kan hjälpa er marknadsföring. |
| 5 augusti 2020 | [Skapa en segmenttaxonomi](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/creating-a-segment-taxonomy.html) | Självstudiekurs | När du skapar ett segment i Audience Manager lagras de i en mappbaserad struktur eller i en _taxonomi_. Lär dig några tips om hur du skapar och hanterar segmenttaxonomin. |
| 4 augusti 2020 | [Hämta API-autentiseringsuppgifter i Adobe I/O](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/api/retrieve-api-credentials-in-adobe-io.html) | Självstudiekurs | Istället för att kontakta Adobe Consulting eller kundtjänst för att få inloggningsuppgifter för att använda REST API, kan du bara gå till `Adobe.io` en webbläsare och hämta eller registrera dina egna inloggningsuppgifter. |
| 31 juli 2020 | [Använda senaste och frekventa i segment](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/using-recency-and-frequency-in-segments.html) | Självstudiekurs | Använd [!UICONTROL Recency] och [!UICONTROL Frequency] ge segmentparametrarna för hur många gånger en besökare måste kvalificera sig för ett visst yrke under en viss tidsperiod. Perfekt när det gäller innehållets affinitet och användning av frekvensbegränsning med mera. |
| 22 juli 2020 | [Grunderna i att skapa segment](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/the-basics-of-creating-segments.html) | Självstudiekurs | Gå igenom fälten i användargränssnittet för att skapa ett segment i Audience Manager. |
| 22 juli 2020 | [Praktisk segmentdefinition och skapande](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/practical-segment-definition-and-creation.html) | Självstudiekurs | I den här videon får du hjälp med att definiera segment och sedan dela upp dem efter de egenskaper och signaler som du behöver för att skapa dem. |
| 17 juli 2020 | [Utelämna annonser till konverterare](https://video.tv.adobe.com/v/36658?captions=swe) | Självstudiekurs | Spara pengar och optimera kundupplevelsen genom att undertrycka annonser till konverterare. |
| 15 juli 2020 | [Mäta avkastningen i ett fall där kunden inte kan använda produkten](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/value-realization/measuring-roi-in-a-customer-suppression-use-case.html) | Självstudiekurs | Lär dig att använda några formler för att fastställa era kampanjkostnadsbesparingar genom att undertrycka annonser för befintliga kunder. |
| 10 juli 2020 | [Skapa ett segment för att utelämna annonser till kunder](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/building-a-segment-to-suppress-ads-to-customers.html) | Självstudiekurs | I den här videon diskuteras alternativ för att skapa segment som ska exkluderas från dem som redan har konverterat till kundstatus. |

## ![Ikonen för](/assets/aem.png) Adobe Experience Manager {#aem}

Nya funktioner, korrigeringar och uppdateringar i Adobe Experience Manager (AEM). Adobe rekommenderar att kunder med lokala distributioner driftsätter de senaste korrigeringarna för bättre stabilitet, säkerhet och prestanda.

### **Produktreleaser**

* **AEM som molntjänst**

   Vad är nytt i AEM som Cloud Service? Bland nyheterna finns följande:

   * AEM Commerce är nu tillgänglig i Cloud Service. Se [Komma igång med AEM Commerce som Cloud Service.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/commerce/getting-started.html)
   * Kopplingar till förbättringarna i Adobe Target och Adobe Analytics omfattar förbättringar av användargränssnittet, ersättning av klassiskt användargränssnitt och integrering av Adobe Launch. Se [Integrera Adobe Analytics](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/sites/integrations/integrating-adobe-analytics.html) och [Integrera Adobe Target.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/sites/integrations/integrating-adobe-target.html)
   * Tjänsten Asset Compute är en skalbar och utbyggbar tjänst för att bearbeta resurser. Administratörer kan konfigurera Experience Manager att anropa anpassad arbetare som skapats med tjänsten Resursberäkning. Utvecklare kan använda tjänsten för att skapa specialarbetare som klarar komplexa användningsfall. Den här webbtjänsten kan generera miniatyrbilder för olika filtyper, bildåtergivning av hög kvalitet från filformat i Adobe, koda videor (framtida), extrahera metadata, extrahera full text som prekursor för indexering och köra en resurs via alla tillgängliga Sensei-tjänster. Se [Använda resursmikrotjänster och bearbetningsprofiler.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/manage/asset-microservices-configure-and-use.html)
   * Flera förbättringar för arbetsflödesmodeller och Dynamic Media i AEM som Cloud Service.
   * Version 2.11.0 av [AEM Core Components](https://docs.adobe.com/content/help/sv-SE/experience-manager-core-components/using/introduction.html) finns nu som en del av AEM Sites, inklusive följande:
      * Introduktion till en ny [PDF Viewer-komponent.](https://aemcomponents.dev/content/core-components-examples/library/page-authoring/pdf-viewer.html)
      * AMP-stöd (Accelerated Mobile Pages) för kärnkomponenter. Det hjälper till att skapa snabbare kundupplevelser genom att göra sidövergången omedelbart när du kommer in på webbplatsen från ett Google-sökresultat för mobiler, vilket förbättrar användarengagemanget och SEO. Se [AMP-stöd för kärnkomponenterna.](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/data-layer/overview.html)
      * Kompatibilitet med version 1.0.2 av [Adobe-klientdatalagret](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/data-layer/overview.html).
   * Flera förbättringar av användargränssnittet i Cloud Manager.
   * Molnhanterarens pipelines har nu stöd för kundspecifika variabler och hemligheter. Se [Förvandlingsvariabler.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/getting-access/creating-aem-application-project.html#pipeline-variables)
   * [Loggar kan vidarebefordras till Splunk-konton](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/developing/logging.html#splunk-logs), vilket gör att organisationer kan utnyttja sin [!DNL Splunk] investering.
   * Du kan tilldela [en statisk, dedikerad IP-adress](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/developing/development-guidelines.html#dedicated-egress-ip-address) för utgående trafik som programmeras i Java-kod, vilket kan vara användbart för vissa integreringar.
   * Cloud Readiness Analyzer v1.0.2 har släppts. Se [Installera CRA på AEM 6.1.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/cloud-readiness-analyzer/using-cloud-readiness-analyzer.html#installing-on-aem61)
   * Se den [fullständiga versionsinformationen för AEM som en Cloud Service.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html?mkt_tok=eyJpIjoiWm1SallqTmtOekF6WldZMCIsInQiOiJoTTZ3Qm9LNVRXc1lsbjExdlpNMGdQNFE2UGM5ejZob1EwZXlPZHp2MEZJa1BPTHhybHBYcUxFWTgwVjNFajlzYU1Fb1NoVXRwMTc3U2IrbHZKeTVSOG02MUErbWpIb1pjNU8zYkdTbW5MZHVIRUUyNk9vUU9SckdOeUJmbXlObSJ9)

### Självhjälp

* **AEM Forms**

   * AEM Forms-tillägg i paket finns nu tillgängliga för [AEM programvarudistribution](https://experience.adobe.com/#/downloads/content/software-distribution/en/aem.html?2_group.propertyvalues.property=.%2Fjcr%3Acontent%2Fmetadata%2FDc%3Asolution&amp;2_group.propertyvalues.operation=equals&amp;2_group.propertyvalues.0_values=target-solution%3AAEM%2Fforms&amp;orderby=%40jcr%3Acontent%2Fjcr%3AlastModified&amp;order.sort=desc&amp;layout=layout=layout list&amp;p.offset=0&amp;p.limit=24). Du hittar direktlänkar för paket med de utgåvor som stöds i artikeln om [AEM Forms-utgåvor](https://helpx.adobe.com/se/aem-forms/kb/aem-forms-releases.html) .
   * Använd [referenswebbplatsen](https://docs.adobe.com/content/help/en/experience-manager-65/forms/getting-started/aem-forms-reference-collaterals/forms-gov-reference-site-user-demo.html) för att lära dig hela arbetsflödet i tjänsten Automated Forms Conversion.
   * Javadocs finns för AEM [6.5.5.0](https://helpx.adobe.com/experience-manager/6-5/forms/javadocs/index.html) och AEM [6.4.8.1](https://helpx.adobe.com/experience-manager/6-4/forms/javadocs/index.html) .
   * [Importera betrodda certifikat](https://docs.adobe.com/content/help/en/experience-manager-65/forms/manage-administer-aem-forms/hardening-aem-forms-environment/hardening-aem-forms-jee-environment.html#configuring-ssl) till JVM samtidigt som du stärker en AEM Forms i JEE-miljö.
   * Förbättrad installationsdokumentation för [PDF Generator.](https://docs.adobe.com/content/help/en/experience-manager-65/forms/install-aem-forms/osgi-installation/install-configure-document-services.html)

* **Core Components**

   Core Components version 2.11.0 har stöd för AMP och finns nu tillsammans med [redigeringsdokumentation](https://docs.adobe.com/content/help/sv-SE/experience-manager-core-components/using/introduction.html) och [utvecklarinformation samt projektnedladdning på GitHub.](https://github.com/adobe/aem-core-wcm-components)

### **Community**

* **Det senaste AEM innehållet om Experience League**

   Detta är den officiella källan till digitalt upplevelsetekniskt innehåll som producerats av Adobe. Se hela listan [här.](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/list-of-latest-adobe-experience-manager-content-on-experience/qaq-p/373396)

### Nya Experience Manager-kurser och självstudiekurser

Nya videofilmer, självstudiekurser och kurser som publicerats den senaste månaden.

| Publicerad | Namn | Typ | Beskrivning |
| -----------| ---------- | ---------- | ---------- |
| 7 augusti 2020 | [Komma igång med hantering av flera webbplatser för företagsanvändare](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.sites.msm) | Kurs | Lär dig skapa en stabil grund för implementeringen av AEM Assets genom att konfigurera kärnproblemen, från att skapa en grundläggande innehållsarkitektur och taxonomi till att anpassa metadata och materialbearbetning. |
| 7 augusti 2020 | [Konfigurera AEM Assets för administratörer](https://experienceleague.adobe.com/?recommended=ExperienceManager-A-1-2020.1.assets) | Självstudiekurs | Beskrivning |
| 19 juli 2020 | [Använda verktyget Innehållsöverföring](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/migration/content-transfer-tool.html) | Självstudiekurs | Verktyget [!UICONTROL Content Transfer] är det rekommenderade sättet att migrera innehåll från en lokal eller AMS-värdbaserad version av Experience Manager till en [!UICONTROL AEM as a Cloud Service] miljö. |
| 21 juli 2020 | [Skapa en Live Copy](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/create-live-copy.html) | Självstudiekurs | Lär dig hur du skapar en webbplats [!UICONTROL Live Copy] från en [!UICONTROL Blueprint] med hjälp av [!UICONTROL Create Live Copy] guiden. |
| 21 juli 2020 | [Live Copy Console](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/live-copy-overview-console.html) | Självstudiekurs | Lär dig hur du visar eller hanterar arv på en webbplats eller utför utrullningsåtgärder med hjälp av konsolen Live Copy Overview. |
| 21 juli 2020 | [Översättningsprojekt](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/manage-translation-projects.html) | Självstudiekurs | Lär dig hur du skapar, redigerar och hanterar ett översättningsprojekt för dina [!UICONTROL Language Copy]behov. |
| 21 juli 2020 | [Översättningsjobb](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/manage-translation-projects.html) | Självstudiekurs | Lär dig hur du lägger till ett översättningsjobb i ett befintligt översättningsprojekt. |
| 21 juli 2020 | [Uppdaterar språkkopia med startprogram](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/updating-language-copy.html) | Självstudiekurs | Lär dig hur du uppdaterar, granskar och godkänner ändringar i ett dokument [!UICONTROL Language Copy] med hjälp av Launches. |
| 21 juli 2020 | [Översikt över hantering av flera webbplatser](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/language-copy-overview.html) | Självstudiekurs | Få en översikt över hur du skapar en flerspråkig webbplats med [!UICONTROL Language Copy] i [!UICONTROL AEM Sites]. |
| 21 juli 2020 | [Live Copy och Blueprint](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/live-copy-and-blueprint.html) | Självstudiekurs | Förstå relationen mellan en [!UICONTROL Live Copy] och dess [!UICONTROL Blueprint] i [!UICONTROL AEM Sites]. |
| 21 juli 2020 | [Hantera Live Copy-arv på en sida](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/manage-page-inheritance-live-copy.html) | Självstudiekurs | Lär dig hur du hanterar arv mellan en [!UICONTROL Live Copy] och dess [!UICONTROL Blueprint] på sidnivå. |
| 21 juli 2020 | [Hantera Live Copy-arv för en komponent](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/manage-component-inheritance-live-copy.html) | Självstudiekurs | Lär dig hur du hanterar arv mellan en [!UICONTROL Live Copy] och dess [!UICONTROL Blueprint] på komponentnivå. |
| 21 juli 2020 | [Skapa en språkkopia](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/manage-component-inheritance-live-copy.html) | Självstudiekurs | Beskrivning. |
| 21 juli 2020 | [Skapa en språkkopia](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/create-launguage-copy.html) | Självstudiekurs | Lär dig hur du skapar en [!UICONTROL Language Copy] för din AEM webbplats med [!UICONTROL Create Language Copy wizard]. |
| 21 juli 2020 | [Skapa ett flerspråkigt översättningsprojekt](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/create-multinational-translational-project.html) | Självstudiekurs | Lär dig hur du skapar, redigerar och hanterar ett flerspråkigt översättningsprojekt för din [!UICONTROL Language Copy] från AEM projektkonsol. |
| 21 juli 2020 | [Skapa en landsplats](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/create-new-site.html) | Självstudiekurs | Lär dig hur du skapar en landsplats från en befintlig [!UICONTROL Language Copies] med hjälp av [!UICONTROL Create Site] guiden. |
| 21 juli 2020 | [Skapa en sida för språkkopia](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/create-new-page-language-copy.html) | Självstudiekurs | Lär dig hur du skapar en sida i en befintlig [!UICONTROL Language Copy]och sedan översätter du innehållet till en annan [!UICONTROL Language Copy]. |
| 21 juli 2020 | [Status för översättningsjobb](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/translation-job-status.html) | Självstudiekurs | Förstå de olika statusvärden som är associerade med ett översättningsjobb eller ett objekt i jobbet. |
| 21 juli 2020 | [Introduktion till hantering av flera webbplatser](https://video.tv.adobe.com/v/36686?captions=swe) | Självstudiekurs | Introduktion till kursen Getting Started with Multi-Site Management för företagsanvändare. |
| 21 juli 2020 | [Skapa adaptiva formulärfragment](https://video.tv.adobe.com/v/37325?captions=swe) | Självstudiekurs | Med adaptiva formulär kan du enkelt skapa formulärsegment som en panel eller en grupp fält endast en gång och återanvända dem i anpassade formulär. Dessa återanvändbara och fristående segment kallas adaptiva formulärfragment. |
| 21 juli 2020 | [AEM](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/inbox-customization/introduction.html) | Självstudiekurs | [!UICONTROL AEM Inbox] konsoliderar meddelanden och uppgifter från olika AEM, inklusive Forms-arbetsflöden. |
| 21 juli 2020 | [Felsöka AEM SDK:s lokala snabbstart med hjälp av loggar](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/logs.html) | Självstudiekurs | Loggar fungerar som en frontlinje för felsökning AEM program, men är beroende av korrekt inloggning i det distribuerade AEM. |
| 21 juli 2020 | [Introduktion till SPA Editor](https://video.tv.adobe.com/v/37705?quality=12&learn=on&captions=swe) | Självstudiekurs | En introduktion till Getting started with AEM SPA Editor for developers. |
| 2020 | [Baslinjebehörigheter](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/baseline-permissions.html) | Självstudiekurs | Hantering av användaråtkomst i resursmappar är en viktig aspekt när det gäller styrning och säkerställer att processerna stöds på rätt sätt. |
| 21 juli 2020 | [Starta arbetsflöden automatiskt](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/auto-start-workflows.html) | Självstudiekurs | Autostart-arbetsflöden utökar materialbearbetningen i AEM som en Cloud Service genom att automatiskt anropa ett anpassat arbetsflöde vid överföring eller ombearbetning. |
| 21 juli 2020 | [Felsöka AEM SDK:s lokala snabbstart med hjälp av loggar](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/logs.html) | Självstudiekurs | Loggar fungerar som en frontlinje för felsökning AEM program, men är beroende av korrekt inloggning i det distribuerade AEM. |
| 21 juli 2020 | [Skapa adaptiv formulärmall](https://video.tv.adobe.com/v/37324?captions=swe) | Självstudiekurs | När författare använder mallen för att skapa ett anpassat formulär ärver det nya formuläret strukturen och komponenterna som du har angett i mallen. |
| 21 juli 2020 | [Skapa grupperad datakälla för Apache Sling-anslutning](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/prefill-fdm-db/create-form-data-model.html) | Självstudiekurs | Det första steget för att skapa en RDBMS-baserad formulärdatamodell är att konfigurera Apache Sling Connection Pooled DataSource. |
| 21 juli 2020 | [Fylla i anpassningsbara formulär i förväg med hjälp av formulärdatamodell](https://video.tv.adobe.com/v/36387?captions=swe) | Självstudiekurs | Introduktion till förifyllda formulär med formulärdatamodellen. |
| 21 juli 2020 | [Skapa ditt första adaptiva formulär](https://video.tv.adobe.com/v/37701?captions=swe) | Självstudiekurs | I den här videon får du lära dig hur du skapar ditt första adaptiva formulär. |

### Versionsinformation för Experience Manager

All versionsinformation för Experience Manager finns på följande sidor:

* [Versionsinformation för AEM som en molntjänst](https://docs.adobe.com/content/help/sv-SE/experience-manager-cloud-service/release-notes/home.html)
* [Versionsinformation för AEM Cloud Manager](https://docs.adobe.com/content/help/sv-SE/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Versionsinformation för konverteringstjänsten för automatiserade formulär](https://docs.adobe.com/content/help/sv-SE/aem-forms-automated-conversion-service/using/release-notes.html)
* [Versionsinformation för AEM 6.5 Service Pack](https://docs.adobe.com/content/help/sv-SE/experience-manager-65/release-notes/service-pack/sp-release-notes.translate.html)
* [Versionsinformation för AEM 6.4 Cumulative Fix Pack](https://docs.adobe.com/content/help/sv-SE/experience-manager-64/release-notes/cfp-release-notes.translate.html)
* [Versionsinformation för AEM Assets Dynamic Media](https://docs.adobe.com/content/help/sv-SE/dynamic-media-developer-resources/release-notes/s7rn2017.translate.html)
* [Versionsinformation för varumärkesportalen i AEM](https://docs.adobe.com/content/help/sv-SE/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)
* [Versionsinformation för AEM-datorprogrammet](https://docs.adobe.com/content/help/sv-SE/experience-manager-desktop-app/using/release-notes.html)
* [Versionsinformation för AEM Dispatcher](https://docs.adobe.com/content/help/sv-SE/experience-manager-dispatcher/using/getting-started/release-notes.html)
* [Versionsinformation för Adobe Primetime](https://docs.adobe.com/content/help/sv-SE/primetime/release-notes/home.html)
* [Versionsinformation för Livefyre](https://docs.adobe.com/content/help/sv-SE/livefyre/using/release-notes/c-rn.html)

### Ytterligare hjälpresurser för AEM

* [Användarhandböcker för AEM som en molntjänst](https://docs.adobe.com/content/help/sv-SE/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 – startsida för utbildning och support](https://helpx.adobe.com/se/support/experience-manager/6-5.html)
* [AEM 6.4 – startsida för utbildning och support](https://helpx.adobe.com/se/support/experience-manager/6-4.html)
* [AEM 6.3 – startsida för utbildning och support](https://helpx.adobe.com/se/support/experience-manager/6-3.html)
* [AEM 6.2 – startsida för utbildning och support](https://helpx.adobe.com/se/support/experience-manager/6-2.html)
* [Användarhandbok för Cloud Manager](https://docs.adobe.com/content/help/sv-SE/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
* [Äldre versioner av AEM-dokumentation](https://helpx.adobe.com/se/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic – startsida för hjälp](https://docs.adobe.com/content/help/sv-SE/dynamic-media-classic/using/home.html)

## ![Ikon](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign är ett intuitivt och automatiserat sätt att leverera personliga meddelanden i alla marknadsföringskanaler, både online och offline. Nu kan ni förutse vad era kunder vill ha med upplevelser som bestäms av deras vanor och önskemål.

### Nya produktversioner

Versionsinformation för Campaign Classic, Campaign Standard och Kontrollpanelen.

#### Campaign Classic

* 20.2.1 - [Läs mer](https://docs.adobe.com/content/help/sv-SE/campaign-classic/using/release-notes/latest-release.html#release-20-2-2-build-9180)

### Nya kurser och självstudiekurser i Campaign

Nya videofilmer, självstudiekurser och kurser som publicerats den senaste månaden.

| Publicerad | Namn | Lösning | Beskrivning |
| ----------- | ----------- | ---------- | ---------- |  
| 10 juli 2020 | [Kontrollpanelen - Hantering av GPG-nyckel - Dekryptera data](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/gpg-key-management/decrypting-data.html) | Campaign Classic | Läs mer om hur du skapar en offentlig nyckel samt importerar och installerar den på en instans i Campaign för att dekryptera inkommande data. |
| 10 juli 2020 | [Kontrollpanelen - Hantering av GPG-nyckel - Använda en GPG-nyckel för att kryptera data](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/gpg-key-management/using-a-gpg-key-to-encrypt-data.html) | Campaign Classic | Läs mer om hur du exporterar data med en GPG-nyckel som installeras på kontrollpanelen. |
| 10 juli 2020 | [Kontrollpanelen - Generera och installera GPG-nycklar för datakryptering](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/gpg-key-management/generating-and-installing-gpg-keys-for-data-encryption.html) | Campaign Classic | Lär dig hur du genererar ett offentligt/privat GPG-nyckelpar och installerar den offentliga nyckeln på Kontrollpanelen för att kunna kryptera data innan du skickar dem från din instans. |
| 21 juli 2020 | [Hantera marknadsföringskampanjer](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/managing-marketing-campaigns.html) | Campaign Classic | Förstå nyckelbegreppen i Adobe Campaign som hjälper er att effektivt planera, genomföra och mäta flerkanalskampanjer. |
| 22 juli 2020 | [Skapa en marknadsföringsplan, program och kampanjer](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/creating-a-marketing-plan-programs-and-campaigns.html) | Campaign Classic | Lär dig hur du skapar en marknadsföringsplan, ett program och en kampanj, anger egenskaper för en kampanj och hur du använder schemat. Videon vägleder dig genom en övning som du kan följa med i. |
| 23 juli 2020 | [Skapa och hantera profiler](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/profile-management/create-and-manage-profiles.html) | Campaign Classic | Förstå begreppet profiler i Adobe Campaign Classic. Lär dig hur du får åtkomst till profildata, sorterar och filtrerar profiler och skapar och hanterar profiler manuellt. |
| 28 juli 2020 | [Anpassa e-postmeddelanden med villkorsstyrt innehåll](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/email-channel/personalizing-emails-create-a-multi-lingual-newsletter-using-conditional-content.html) | Campaign Classic | Lär dig hur du lägger till villkorligt innehåll i en leverans med ett exempel på ett flerspråkigt nyhetsbrev. |
| 28 juli 2020 | [Anpassa e-postmeddelanden med personaliseringsfält](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/email-channel/personalizing-emails-using-personalization-fields.html) | Campaign Classic | Lär dig hur du lägger till ett anpassningsfält på ämnesraden och innehållet i en e-postleverans. |
| 28 juli 2020 | [Målinriktade profiler i ett arbetsflöde](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/targeting-profiles-in-a-workflow.html) | Campaign Classic | Förstå användningen av kampanjarbetsflöden och lär dig hur du skapar ett arbetsflöde och målprofiler i ett arbetsflöde med filtervillkor. |
| 31 juli 2020 | [Generera en beskrivande analysrapport](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/reporting/generating-a-descriptive-analysis-report.html) | Campaign Classic | Lär dig hur du skapar en beskrivande analysrapport. |
| 9 juli 2020 | [Kontrollpanelen - Hantering av GPG-nyckel - Använda en GPG-nyckel för att kryptera data](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/gpg-key-management/using-a-gpg-key-to-encrypt-data.html) | Campaign Standard | Läs mer om hur du exporterar data med en GPG-nyckel som installeras på kontrollpanelen. |
| 9 juli 2020 | [Kontrollpanelen - Hantering av GPG-nyckel - Dekryptera data](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/gpg-key-management/decrypting-data.html) | Campaign Standard | Läs mer om hur du skapar en offentlig nyckel samt importerar och installerar den på en instans i Campaign för att dekryptera inkommande data. |
| 9 juli 2020 | [Kontrollpanelen - Hantering av GPG-nyckel - Generera och installera GPG-nycklar för datakryptering](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/gpg-key-management/generating-and-installing-gpg-keys-for-data-encryption.html) | Campaign Standard | Läs mer om hur du skapar och installerar ett offentligt/privat nyckelpar på en angiven instans i Campaign för att kryptera utgående data. |

### Hjälpresurser

* Adobe Campaign Standard: [Hjälpcenter](https://docs.adobe.com/content/help/sv-SE/campaign-standard/using/campaign-standard-home.html) – [Versionsinformation](https://docs.adobe.com/content/help/sv-SE/campaign-standard/using/release-notes/release-notes.html) – [Instruktionsvideor](https://docs.adobe.com/content/help/sv-SE/campaign-standard-learn/tutorials/overview.html) – [Versionsplanering](https://docs.adobe.com/content/help/sv-SE/campaign-standard/using/release-notes/release-planning.html) – [Senaste dokumentationsuppdateringar](https://docs.adobe.com/content/help/sv-SE/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Hjälpcenter](https://docs.adobe.com/content/help/sv-SE/campaign-classic/using/campaign-classic-home.html) – [Versionsinformation](https://docs.adobe.com/content/help/sv-SE/campaign-classic/using/release-notes/latest-release.html) – [Instruktionsvideor](https://docs.adobe.com/content/help/sv-SE/campaign-classic-learn/tutorials/overview.html) – [Senaste dokumentationsuppdateringar](https://docs.adobe.com/content/help/sv-SE/campaign-classic/using/documentation-updates.html)
* Kontrollpanelen för Adobe Campaign: [Dokumentation](https://docs.adobe.com/content/help/sv-SE/control-panel/using/control-panel-home.html) – [Versionsinformation](https://docs.adobe.com/content/help/sv-SE/control-panel/using/release-notes.html) - Instruktionsvideor för [Campaign Standard](https://docs.adobe.com/content/help/sv-SE/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.translate.html) / [Campaign Classic](https://docs.adobe.com/content/help/sv-SE/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html)

## ![Ikon](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Versionsinformation för Adobe Advertising Cloud.

### Nya funktioner i [!UICONTROL Advertising Cloud Search] {#adcloud-search}

**8 augusti** -versionen

| Funktion | Beskrivning |
| -----------| ---------- |
| [!UICONTROL Portfolios] | Positionsgränser på Portfolio-nivå är inte längre tillgängliga i portföljinställningarna. Eventuella tidigare placeringsbegränsningar har tagits bort. |
| [!UICONTROL Constraints] | Positionsbaserade begränsningar och begränsningsvillkor stöds inte längre:<br/><ul><li>Min pos och Max pos-begränsningar är inte längre tillgängliga och har tagits bort från alla tidigare skapade begränsningar för bud- och positionsbegränsningar och Impression-delning.</li><li>Befintliga bud- och positionsbegränsningar som innehöll positionsbegränsningar men inga anbudsbegränsningar pausades. De finns fortfarande i användargränssnittet och i rapporter.</li><li>Bid- och positionsbegränsningarna döptes om till Bid-begränsningar.</li><li>Alla positionsbaserade villkor (med medelposition, viktad genomsnittlig position eller senaste kända pos-mått) i någon typ av begränsning togs bort.</li></ul><br/>**Obs!**Positionsdata fylls i så länge de är tillgängliga från sökmotorerna. Microsoft Ads upphör i september 2020. |  |
| [!UICONTROL Campaigns] | (Google Ads-kampanjer) Advertising Cloud Search har nu stöd för annonsanpassare i responsiva sökannonser (RSA). Tidigare stöddes de i alla annonstyper utom RSA. |

## ![Ikon](/assets/magento.png) [!DNL Magento] {#magento}

Versionsinformation om Magento finns i:

* [Magento Commerce 2.3.5](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-5-open-source.html)
* [Magento Open Source 2.3.5](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-5-open-source.html)

## ![Ikon](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] är ett komplett program för lead-hantering för B2B-marknadsförare som vill transformera kundupplevelser genom engagemang under alla faser av komplexa inköpsresor.

### Uppdateringar om Core Marketo Engage

Den senaste informationen finns i [!DNL Marketo] [versionsinformationen](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+July+%2720).

### Kommande funktioner

Följande funktioner släpps under kvartalet:

| Funktion | Beskrivning |
|------|---------|
| [!DNL Bizible] | <ul><li>Ny kontobaserad segmentering</li><li>Spara instrumentpanelsspecifika filter</li><li>Exportera Bizible-instrumentpaneler som PDF-filer</li></ul> |
| Sales Connect | Uppdateringar/förbättringar av kompositionsfönster och kommandocentral |

### Meddelanden

**Marketo Engage Success Center:** Startar i februari 2020. Success Center är ett hjälpcenter i produkten som gör att du kan söka i produktdokumentation och communityn, starta instruktionsguider, komma åt hjälpavsnitt och mycket annat. Obs! Den här funktionen lanseras som en betaversion i ANZ och lanseras i Nordamerika senare under kvartalet.

### Utgånget

* **Resurs-API &quot;_method&quot;-parameter:** Efter september 2020 accepterar inte längre Assets API-slutpunkter `_method` för att skicka frågeparametrar i en POST-brödtext som kringgår begränsningar av URI-längd.
* **Stöd för Internet Explorer har tagits bort:** Från och med juliversionen den 31 juli 2020 stöds inte längre gränssnittet Marketo Engage i Internet Explorer.

Kumulativ och historisk versionsinformation finns i [Marketos versionsinformation](https://docs.marketo.com/x/CgA6Ag).
