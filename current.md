---
title: Versionsinformation om Adobe Experience Cloud
description: Mall för versionsinformation om Experience Cloud
doc-type: release notes
last-update: March 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 3a66c0ee04a336a702ea9ff502a0f2ce6c5b2109

---


# Versionsinformation om Adobe Experience Cloud - april 2020

![Banderoll](/assets/experience-cloud-banner-3.png)

Nya funktioner och korrigeringar i [!DNL Adobe Experience Cloud].

>[!NOTE]
>
>Prenumerera på [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) om du vill få meddelanden via e-post om kommande versioner. Ny information som publiceras efter publiceringen markeras med publiceringsdatumet.

**Releasedatum: April 2020**

(Vissa releasedatum kan variera.)

* [Systemstatus för Adobe](#status)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics) **(Uppdaterat 16 april)**
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (länkar till målets hjälpsida)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (länkar till Primetimes hjälpsida)

Söker du hjälp hem? Se [Adobe Experience Cloud-dokumentation](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html).

## ![Ikon](/assets/adobe.png) för Adobe-systemstatus {#status}

[!UICONTROL Adobes systemstatus] innehåller detaljerad information, statusuppdateringar och e-postmeddelanden om Adobe-molnprodukter och -tjänster, driftstopp, avbrott och underhållshändelser. Kolla in den på [status.adobe.com](https://status.adobe.com/).

**Nyheter**

* Med ditt Adobe-ID kan du prenumerera på händelsemeddelanden med större detaljrikedom, ända ned till produkterbjudandet och tilläggsnivån. Dessutom rekommenderar självprenumerationsprocessen i vår senaste version nu ett urval av produkter och tjänster baserat på dina produkträttigheter. Detta bör effektivisera prenumerationsprocessen genom att minska antalet beslut eller klick som krävs för att skapa prenumerationer och, viktigast av allt, leverera mer relevanta meddelanden i inkorgen. Kom igång på [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nya funktioner och förbättringar som är tillgängliga idag**

| Funktion | Beskrivning |
| -----------| ---------- |
| Personaliserade prenumerationer baserade på berättiganden | <ul><li>Förvalda prenumerationsrekommendationer baserade på användarens DX-rättigheter.</li><li>Rekommenderade prenumerationer markeras högst upp i produktlistan för snabb visualisering.</li><li>Mottagna e-postmeddelanden är relevanta för användarens produkträttigheter.</li></ul> |
| Enklare hantering av prenumerationer | <ul><li>**[!UICONTROL Hantera prenumerationer]** har en ny användarupplevelse för att hantera både produkt- och eventprenumerationer.</li><li>Nytt alternativ för att visa och redigera prenumerationer på produkter och evenemang separat.</li><li>Med alternativet **[!UICONTROL Ta bort]** kan du avbryta prenumerationen på en produkt eller ett evenemang.</li><li>Alternativet **[!UICONTROL Avbeställ alla]** med ett klick är tillgängligt för produktprenumerationer.</li><li>UX-stöd finns för webb-/mobilsurfplattor och lokalisering på 19 språk.</li></ul> |

## ![Ikon](/assets/ec_appicon_24.png) i Experience Cloud-gränssnittet {#ecloud}

Nya funktioner och korrigeringar i Experience Cloud-gränssnittet:

* Experience Cloud [!UICONTROL Feed] -sidan har tagits bort. (EXC-8505)
* Inloggningssidan för Experience Cloud uppdaterades för att återspegla nya varumärkeselement. (EXC-10747)

Produktdokumentation finns i [hjälpen](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html)för Experience Cloud-gränssnittet.

### Enhetlig produktdomän

Adobe uppdaterar domänen och gränssnittshuvudet för att göra upplevelsen enhetlig och bättre i alla Experience Cloud-program. Dessa förbättringar är utformade för att förenkla din upplevelse på små men viktiga sätt. Dessa förbättringar kommer inte att ändra dina aktuella arbetsflöden.

Bland uppdateringarna finns:

* Nya program-URL:er: `experience.adobe.com/<application name>`:
   * Alla produkter kommer så småningom att använda det här URL-mönstret. Leta efter nya URL:er som ska gälla hela månaden.
   * Stöd för webbläsare: De webbläsare som stöds är [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari]och [!DNL Opera] (de senaste versionerna). **Obs!** Trots att Experience Cloud-gränssnittet har stöd för dessa webbläsare kanske inte enskilda program har stöd för alla webbläsare. ( [Analytics](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html) stöder till exempel inte [!DNL Opera]och [Target](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html) stöder inte [!DNL Safari].)
   * ([!DNL Safari] endast) Domänändringen kan orsaka cookie-problem i [!DNL Safari]. Om du avmarkerar _Förhindra spårning_ av webbplatser i [!DNL Safari] Sekretessinställningar aktiveras cookies i domäner (och alla upplevelser på olika webbplatser), och Experience Cloud kan fungera i den nya domänen.
* Enklare att växla mellan olika organisationer eller till olika applikationer.
* Förbättrad produkthjälp: Experience [!UICONTROL League] är integrerat i produkten så att en hjälpsökning även innehåller resultat från communityforum och videoinnehåll. Den här ändringen förenklar åtkomsten till mer innehåll och hjälper er att få ut mesta möjliga av Experience Cloud. Klicka dessutom på **[!UICONTROL Hjälp]** > **[!UICONTROL Feedback]** för att rapportera problem eller dela med dig av dina idéer till Adobe.

## ![Icon](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Versionsinformation om [!DNL Experience Platform,] bland annat [!DNL Experience Platform Launch,] resesamordning [!UICONTROL ,]erbjudanden [!UICONTROL ,]människor [!UICONTROL ,]platser ,¥Mobile Services och säkerhetsbulletiner.

### Resesamordning {#journey}

Med Adobe Experience Platform kan ni samordna enskilda kundresor i stor skala över olika upplevelsekanaler genom att intelligent förutse varje enskild individs behov i realtid, oavsett vart resan tar dem.

* [Dokumentation](https://docs.adobe.com/content/help/en/journeys/using/journey-orchestration-home.html)
* [Versionsinformation](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html)
* [Instruktionsvideor](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Mobiltjänster och SDK för mobiler {#mobile}

Android 4.18.2 (3 april 2020):

* I App Messaging: Av säkerhetsskäl anger [!UICONTROL WebViews] som har skapats av SDK nu egenskapen `setAllowFileAccess` som är lika med _false_.

iOS 4.19.2 (24 mars 2020):

* Allmänt: Åtgärdade vissa läckor i [!DNL Target] koden.

Unity 4.19.0 (10 mars 2020):

* Uppdaterat [!UICONTROL Unity Plugin] till version 4.19.0 av iOS och 4.18.0 eller [!DNL Android].
* En ny förvärvsmetod har exponerats för [!DNL Android] att tillåta bearbetning av en URL som tillhandahålls av [!DNL Google Play] Referers-API:er.

### Ytterligare versionsinformation om Experience Platform

* [Versionsinformation](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html)om Experience Platform Launch.
* [Versionsinformation om Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Säkerhetsbulletiner och -anvisningar](https://helpx.adobe.com/security.html) (alla Adobe-produkter)

## ![Ikon](/assets/analytics.png) [!DNL Analytics]{#analytics}

>[!IMPORTANT]
>
>Underhållsutgåvan för Adobe Analytics från april har flyttats till 21 maj 2020. Information om den senaste versionen av Analytics finns i [Mars versionsinformation](c-legacy-releases/2020/03122020.md)

* [Customer Journey Analytics](#cust-journey)
<!--* [New features in Adobe Analytics](#aa-features)-->
* [Viktiga meddelanden för Analytics-administratörer](#aa-notices) (uppdaterad 16 april 2020)
* [AppMeasurement](#appm)
* [Självstudiekurser om nya analyser](#tutorials-analytics)

### Customer Journey Analytics {#cust-journey}

| Funktion | Beskrivning |
| -----------| ---------- |
| [!UICONTROL Customer Journey Analytics]: Automatiserad datauppsättningsbackfill | Med det nya alternativet kan du importera alla historiska data för en anslutning i [!UICONTROL kundreseanalysen]. [Läs mer](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-connections/create-connection.html) |

<!--### New features in Adobe Analytics {#aa-features}

| Feature    | Description  |
| -----------| ---------- |
|Analytics support for [!UICONTROL Experience Edge] |You can now forward data that was sent to [!UICONTROL Experience Edge] to Analytics.|
 |[!UICONTROL Workspace]: Automatically build Freeform Tables from a blank state|Previously, you could not drop components directly into a blank project or blank panel; you had to add a freeform table first. You can now drop components directly into a blank project or panel, and a freeform table will automatically be built for you in a recommended format. Additionally, improvements were made to how mixed component types (e.g. dimensions & metrics) are handled when dropped into a blank freeform table together.|

#### Analytics fixes

* Fixed an issue that caused missing Analytics segment data in Audience Manager. (AN-206221)
* Fixed an issue with [!UICONTROL Data Sources] processing showing the wrong dates. (AN-213604)
* Fixed an issue with classification files not getting uploaded to FTP properly. (AN-214102)
* Fixed an issue with the API method `Segments.Get` not returning a full response. (AN-206210)
* Fixed an issue where table line items were converted to special characters in [!DNL Workspace] PDF download. (AN-196153)
* Fixed an issue with Adobe Analytics API 1.4 call `visattrcustomeridcustomerattributes` not working properly. (AN-186873)
* Fixed an issue with data appearing in reports but missing from the [!UICONTROL Data Feed]. (AN-211923)
* Fixed an issue with being unable to copy [!UICONTROL Product Profile] permissions. (AN-211113)
* Fixed an issue where users with Federated IDs were not able to log in to Report Builder. (AN-207750)
* Fixed an issue with [!UICONTROL AdWords] data not showing in [!UICONTROL Advertising Analytics]. (AN-213249)
* Fixed an issue where classification data did not display in the trended view. (AN-212761)
* Fixed an issue that caused an incorrect published segment count in the [!UICONTROL Segment Manager]. (AN-213374)

#### Additional Analytics fixes

AN-212151; AN-214343; AN-215017; AN-115525; AN-123869; AN-101871; AN-152580; AN-160480; AN-199299; AN-209486; AN-212961; AN-211539; AN-213095; AN-212653; AN-211826; AN-206948; AN-208607; AN-204286; AN-214401; AN-212130; AN-211943; AN-212709; AN-212833; AN-211550; AN-212977; AN-213422; AN-213450; AN-214528; AN-213827; AN-214094; AN-214153; AN-214234; AN-214355; AN-214427; AN-214642; AN-214691; AN-214924; AN-215080; AN-215212 -->

### Viktiga meddelanden för [!DNL Analytics] administratörer {#aa-notices}

| Meddelande | Datum tillagt eller uppdaterat | Beskrivning |
| -----------| ---------- | ---------- |
| Borttagen kontrollen &quot;Segment använt i datalager&quot; | 16 april 2020 | Från och med den 16 april 2020 kontrollerar vi inte längre om ett segment används i en begäran om datalager, inifrån segmentbyggaren. Tidigare sökte den här kontrollen efter enskilda segment som tillämpades i datalagerbegäranden (flera segment uteslöts) och returnerade ett varningsmeddelande om true. Den här ändringen påverkar inte datalagrets produktkompatibilitetskontroll för segment. |
| Ändra till hur [!UICONTROL inmatningar/utmatningar] beräknas i [!UICONTROL arbetsytan] | 7 april 2020 | I [!UICONTROL Analysis Workspace], från mars 2020, har vi ändrat hur värdet _None_ interagerar med [!UICONTROL Entry/Exits]. Eftersom du nu kan aktivera och inaktivera _Inga_ i [!UICONTROL Analysis Workspace], använder vi värdet _None_ efter att posten eller avslutningen har angetts, medan det (för eVars) tidigare användes. Anta till exempel att den första träffen av ett besök inte har något värde för eVars, men att den andra träffen gör det. I [!UICONTROL Rapporter och analyser] visas det som _Ospecificerat_ för posten, men i [!UICONTROL Analysis Workspace] visas det som värdet för den andra träffen. |
| EOL för inställning av **[!UICONTROL konverteringsnivå]** | 3 mars 2020 | Den icke fungerande [inställningen för konverteringsnivå](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/general-acct-settings-admin.html) i **[!UICONTROL Administratörsverktyg]** > **[!UICONTROL Rapportsviter]** > **[!UICONTROL Allmänna kontoinställningar]** kommer att tas bort från gränssnittet den 12 mars 2020. |
| EOL för **[!UICONTROL instrumentpanelsarkiv]** | 27 mars 2020 | Inställningen **[!UICONTROL Visa arkiv]** under **[!UICONTROL Hantera instrumentpaneler]** i [!UICONTROL rapporter och analyser] är inte längre tillgänglig från och med oktober 2020. |
| Stöd för TLS 1.1 upphör | 3 oktober 2019 | Adobe Analytics tar bort stödet för TLS 1.1 senast den 31 mars 2020. Den här förändringen är en del av våra pågående ansträngningar att upprätthålla högsta säkerhetsstandarder och främja säkerheten för kunddata. |
| Ny Adobe Analytics-domän | 18 dec 2019 | Den 16 januari 2020 började Adobe Analytics gå över till en ny domän - `https://experience.adobe.com/analytics.`<br>**Obs!**Den här ändringen gäller alla användare som använder Analytics med sina Adobe ID:n eller Enterprise ID:n.<ul><li>Domänändringen kan orsaka cookie-problem när Analytics läses in i Safari. Om du avmarkerar _Förhindra spårning_ av webbplatser i [!DNL Safari] Sekretessinställningar aktiveras cookies i domäner (och alla upplevelser på olika webbplatser). Analytics kan dessutom användas i den nya Adobe Experience Cloud-domänen. Du kan använda andra webbläsare utan problem eftersom det bara påverkar [!DNL Safari] användare.</li><li>Domänändringen kan göra att [!UICONTROL aktivitetskartan] slutar fungera för vissa kunder [i vissa fall](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html).</li></ul> |
| Slutet av livscykeln - äldre API:er för analys | 9 januari 2020 | I november 2020 kommer följande API-tjänster för Analytics Legacy att ha nått sitt slutdatum och kommer att avslutas. Aktuella integreringar som byggts med dessa tjänster kommer att sluta fungera. <ul><li>1.3 API:er för analys</li><li>1.4 API:er för SOAP-analys</li><li>Äldre OAuth-autentisering (OAuth och JWT)</li></ul>Vi har tagit fram en [äldre API EOL - Frågor och svar](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) som kan hjälpa dig att besvara dina frågor och ge vägledning om hur du går vidare. API-integrationer som använder dessa tjänster kan migrera till [1.4-API:erna](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) för REST eller [2.0-API:erna](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)för analys. Äldre OAuth-konton kan migrera till ett [Adobe IO](https://console.adobe.io/home?mv=email) Analytics-integrationskonto, som kan användas för att komma åt både 1.4-API:er för analys och 2.0-API:er för analys. |
| San Jose FTP Broker Ending for London and Singapore | Juli 2020 | För kunder i London och Singapore stöder vi inte längre förmedling av data mellan London eller Singapore och datacentret [ftp.omniture.com](ftp://ftp.omniture.com/)i San Jose.<br/><ul><li>För London använder du [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Använd [ftp4.omniture.com för Singapore](ftp://ftp4.omniture.com/)</li></ul> |
| EOL för ad hoc-analys | 6 aug 2018 | Adobe har meddelat att man avser att göra en Ad hoc-analys vid slutet av livscykeln. Ett slutdatum delas så snart det är tillgängligt. Mer information finns på [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

### [!DNL AppMeasurement] {#appm}

Se [AppMeasurement for Javascript, versionsinformation](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html). Version 2.20.0 släpptes 5 mars 2020.

### Självstudiekurser om nya analyser {#tutorials-analytics}

| Innehåll | Beskrivning |
| -----------| ---------- |
| [Adobe Labs (förhandstitt på teknik) med Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/analytics-basics/adobe-labs-technology-previews.html) | Med Adobe Labs (förhandstitt på teknik) kan ni interagera med ny teknik, upptäcka värdefulla insikter och påverka framtida [!DNL Analytics] funktionsutveckling och prioriteringar. |
| [Förbättrad Experience Cloud Audience Publishing](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/integrations/experience-cloud/improved-experience-cloud-audience-publishing.html) | Förbättringar har gjorts i [!UICONTROL Experience Cloud Audience Publishing]. Nu kan ni publicera målgrupper (segment) och göra dem tillgängliga sex gånger snabbare. Detta minskar den aktuella latenstiden från 48 timmar till cirka 8 timmar, och möjligen snabbare, beroende på trafik och segmentstorlek. |
| [Flera rapportsviter på analysarbetsytan](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/using-panels/multiple-report-suites-in-analysis-workspace.html) | Flera rapportsviter kan analyseras i ett enda [!UICONTROL Workspace] -projekt genom att välja rapportsviter på panelnivå. På så sätt kan du utföra panelanalyser sida vid sida för olika datauppsättningar. |

Produktdokumentation finns på [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html) .

## ![Icon](/assets/audience-manager.png) Audience Manager {#aam}

Nya funktioner och korrigeringar i Adobe Audience Manager:

| Funktion | Beskrivning |
| -----------| ---------- |  
| [De vanligaste frågorna för kundsupport](https://docs.adobe.com/content/help/en/audience-manager/user-guide/top-support-issues/support-issues-overview.html) | Vi har lagt till ett nytt avsnitt i vår dokumentationsportal, som innehåller svar på de vanligaste frågorna som vårt kundsupportteam har fått. |

* Korrigerade ett problem som orsakade felaktig rapportering av [adresserbara målgrupper](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/addressable-audiences.html) för segment som innehåller mobila enhets-ID:n. Efter den här uppdateringen kan ni se en ökning av era [adresserbara målgrupper](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/addressable-audiences.html).
* Korrigerade ett problem som medförde att knapparna [!UICONTROL Duplicera test] och [!UICONTROL Duplicera allokeringsmall] i [!UICONTROL Audience Lab] inte fungerade. (AAM-53388)
* Korrigerade ett problem som medförde att målgrupper [!UICONTROL som kan] matcha frekvens [!UICONTROL och] segmentadresservisas som 0 när ett mål har konfigurerats för att exportera UUID. Matchningsfrekvens [!UICONTROL och] Segmentadresserbara målgrupper  visas nu som 100 %. (AAM-51615)
* Korrigerade ett problem som orsakade att trait-namn som innehåller specialtecken skulle HTML-kodas två gånger. (AAM-54001)
* Ett problem som hindrade vissa användare från att växla till andra Adobe Experience Cloud-program från [!DNL Audience Manager] användargränssnittet har korrigerats. (AAM-52917)
* Korrigerade ett problem som hindrade vissa användare från att skapa en SHA256-datakälla för personbaserade mål. (AAM-53525)
* Flera tillgänglighetsförbättringar i gränssnittet. (AAM-48986, AAM-49009, AAM-48984, AAM-48939, AAM-48940, AAM-48964, AAM-49032, AAM-493 (60)

## ![Ikon](/assets/aem.png) för Experience Manager {#aem}

Nya funktioner, korrigeringar och uppdateringar i Adobe Experience Manager (AEM). Adobe rekommenderar att kunder med anläggningsdistributioner driftsätter de senaste patcharna för att få bättre stabilitet, säkerhet och prestanda.

### Självhjälp

* **AEM Newsletter**

   Se det senaste [nyhetsbrevet](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html)om Adobe Experience Manager.

* **AEM som en molntjänst - Konfigurera Dynamic Media Cloud Service**

   Ett nytt alternativ är tillgängligt när du konfigurerar tjänsten Dynamic Media Cloud:

   **Selektiv publicering** - När du väljer det här alternativet innebär det att resurser automatiskt publiceras för säker förhandsvisning och att de kan publiceras explicit till AEM utan att publiceras till DMS7 för att distribueras i den offentliga domänen.

   Se [Konfigurera Dynamic Media Cloud-tjänsten](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/config-dm.html#configuring-dynamic-media-cloud-services).

* **Dynamiska medier - smart bildbehandling**

   Hela hjälpavsnittet för Smart Imaging uppdaterades med ny information, inklusive exempel på bildresurser som visar den nya optimeringen av Smart Imaging.

   Se [Smart bildbehandling](https://docs.adobe.com/content/help/en/experience-manager-65/assets/dynamic/imaging-faq.html).

* **Konfigurera dynamiska media - Scene7-läge**

   Det nya alternativet Synkronisera allt innehåll finns nu på sidan Dynamisk mediekonfiguration i **[!UICONTROL Verktyg > Cloud-tjänster]**.

   Se [Skapa en dynamisk mediekonfiguration](https://docs.adobe.com/content/help/en/experience-manager-65/assets/dynamic/config-dms7.html#configuring-dynamic-media-cloud-services).

* **AEM Assets Brand Portal stöder AEM Assets som en molntjänst**

   Du kan nu publicera resurser från AEM Assets som en molntjänst på AEM Assets Brand Portal.

   Se [Konfigurera AEM-resurser med varumärkesportalen](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/brand-portal/configure-aem-assets-with-brand-portal.html) och [Publicera resurser på varumärkesportalen](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/brand-portal/publish-to-brand-portal.html).

* **Adobe Asset Link 2.0 släppt**

   Adobe Asset Link 2.0 stöder arbete med flera AEM-miljöer och stöder AEM som molntjänst. AEM stöder marknadsförarnas behov av att konfigurera automatisk körning av arbetsflöde för mediebearbetning när resurser överförs till en mapp med hjälp av Adobe Asset Link.

   Se [Adobe Asset Link](https://helpx.adobe.com/enterprise/using/adobe-asset-link.html).

### Nya självstudiekurser för Experience Manager

| Innehåll | Beskrivning |
| -----------| ---------- |  
| [Konfigurera verktyg för lokal utskickare](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/dispatcher-tools.html) | Lär dig hur du underlättar konfigurering, validering och simulering av [!UICONTROL Dispatcher] lokalt. |
| [Konfigurera utvecklingsverktyg för AEM-projekt](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/development-tools.html) | Utvecklingsverktyg för Adobe Experience Manager (AEM) kräver att det finns en liten uppsättning utvecklingsverktyg installerade och installerade på utvecklingsdatorn. Dessa verktyg har stöd för utveckling och byggande av AEM-projekt. |
| [Konfigurera lokal AEM Runtime](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | Adobe Experience Manager (AEM) kan köras lokalt med AEM som [!UICONTROL QuickStart Jar]i molntjänst-SDK. Detta gör att utvecklare kan driftsätta och testa anpassad kod, konfiguration och innehåll innan de implementerar det på källkontroll och distribuera det till en AEM som en molntjänstmiljö. |
| [Navigering](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/authoring/navigation.html) | Grunderna för navigering med AEM Assets. |
| [Versioner](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/collaboration/versions.html) | Upptäck hur AEM skapar och underhåller resursversioner. |
| [AEM - [!DNL Magento] Integration med [!UICONTROL Commerce Integration Framework]](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/getting-started.html) | I den här videon får du hjälp med att konfigurera integreringen mellan AEM och [!DNL Magento]. |
| [Introduktion till AEM Architecture Stack](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-architecture.html) | CIF-projektarkitypen skapar ett minimalt CIF-projekt för Adobe Experience Manager (AEM) som utgångspunkt för kundprojekt med CIF-kärnkomponenter. |
| [Introduktion till OSGi](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-osgi.html) | En introduktion till OSGi, en dynamisk modulär arkitektur för Java-program som är grunden för Adobe Experience Manager. |
| [Introduktion till Java Content Repository (JCR)](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-jcr.html) | En introduktion till [Java Content Repository (JCR) som används av Adobe Experience Manager. |
| [Introduktion till Sling](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-sling.html) | En introduktion till [!DNL Sling], ett RESTful-webbramverk med öppen källkod som ingår i Adobe Experience Managers underliggande teknikstack. |
| [Introduktion till redigerings- och publiceringsnivå](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-author-publish.html) | En introduktion till [!UICONTROL redigerings] - och [!UICONTROL publiceringsnivåerna] som en del av arkitekturen i Adobe Experience Manager. |
| [Introduktion till Dispatcher](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-dispatcher.html) | En introduktion till funktionerna och funktionerna hos dispatchern som en del av AEM-arkitekturen. |
| [Introduktion till komponentutveckling](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/component-development.html) | Översikt över utveckling av komponenter med Adobe Experience Manager Sites. Innehåller en introduktion till [!UICONTROL dialogrutor], [!UICONTROL segmenteringsmodeller], [!UICONTROL HTML-skript]och [!UICONTROL klientbibliotek]. |
| [AEM Project Archetype](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/developing/aem-project-archetype.html) | AEM-projektet innehåller all kod och alla konfigurationer för en implementering. AEM [!UICONTROL Project Archetype] skapar ett minimalt, metodbaserat Adobe Experience Manager-projekt som utgångspunkt för dina egna AEM-projekt. |
| [Förstå kärnkomponenter](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/core-components-feature-video-understand.html) | AEM [!UICONTROL Core Components] är standardkomponenter som ska användas med Adobe Experience Manager. |
| [Använda AEM Quickstart JAR](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/developing/quickstart-jar.html) | Lär dig hur du installerar och kör en lokal instans av Adobe Experience Manager på bara några minuter med [!UICONTROL AEM Quickstart-burken]. |

### Ytterligare hjälpresurser

* [AEM as a Cloud Service](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 - startsida för utbildning och support](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 - startsida för utbildning och support](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 - startsida för utbildning och support](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 - utbildning och support - startsida](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Användarhandbok för Cloud Manager](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Äldre versioner av AEM-dokumentation](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic - hjälp - startsida](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Versionsinformation för Dynamic Media](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Versionsinformation för Livefyre](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## ![Ikon](/assets/campaign.png) [!DNL Campaign]{#ac}

Adobe Campaign är ett intuitivt och automatiserat sätt att leverera personliga meddelanden i alla marknadsföringskanaler, både online och offline. Nu kan ni förutse vad era kunder vill ha med upplevelser som bestäms av deras vanor och önskemål.

### Campaign Standard

* [Adobe Campaign Standard 20.2](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html)

### Nya självstudiekurser för Campaign Standard {#tutorials-acs}

| Innehåll | Beskrivning |
| -----------| ---------- |  
| [Profilersättning - Testa e-postmeddelanden med målprofiler](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/communication-channels/email/profile-substitution.html) | Testa dina e-postmeddelanden med funktionen Profilersättning. |

### Ytterligare kampanjhjälpresurser

* Adobe Campaign Standard: [Dokumentation](https://helpx.adobe.com/support/campaign/standard.html) - [Versionsinformation](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [instruktionsvideor](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [Viktig planering](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Dokumentation](https://helpx.adobe.com/support/campaign/classic.html) - [Versionsinformation](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Videofilmer om hur du gör](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Kontrollpanelen för Adobe Campaign: [Dokumentation](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [Versionsinformation](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

<!-- ## ![Icon](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Advertising Cloud release notes. -->

## ![Ikon](/assets/magento.png) [!DNL Magento]{#magento}

Versionsinformation om Magento finns i:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Ikon](/assets/marketo.png) [!DNL Marketo]{#marketo}

[!DNL Marketo Engage] är en komplett tillämpning för lead-hantering och B2B-marknadsförare som vill omvandla kundupplevelser genom att engagera sig i alla faser av komplexa inköpsresor.

### Uppdateringar om Core Marketo Engage

Mer information finns i [!DNL Marketo] versionsinformationen [](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) .

### Kommande funktioner

Följande funktioner släpps under hela kvartalet:

| Funktion | Beskrivning |
|------|---------|
| [!DNL Bizible] | <ul><li>Ny kontobaserad segmentering</li><li>Spara instrumentpanelsspecifika filter</li><li>Exportera dubbelsidiga kontrollpaneler som PDF-filer</li></ul> |
| Sales Connect | Disponera uppdateringar/förbättringar av fönster och kommandocentral |

### Meddelanden

**Marketo Engage Success Center:** Startar i februari 2020. Success Center är ett hjälpcenter i produkten som gör att du kan söka i produktdokument och communityn, starta guider, komma åt hjälpavsnitt och mycket annat. Obs! Den här funktionen lanseras som en betaversion i ANZ och kommer att lanseras i Nordamerika senare under kvartalet.

### Föråldringar

* **Resurs-API &quot;_method&quot;-parameter:** Efter september 2020 accepterar inte längre resurs-API-slutpunkter `_method` att skicka frågeparametrar i ett POST-brödtext för att kringgå URI-längdbegränsningar.
* **Stöd för Internet Explorer har tagits bort:** Från och med juliversionen den 31 juli 2020 stöds inte längre gränssnittet Marketo Engage i Internet Explorer.

Information om kumulativa och historiska releaser finns i [Marketo-versionsinformation](https://docs.marketo.com/x/CgA6Ag).
