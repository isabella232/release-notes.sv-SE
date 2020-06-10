---
title: Versionsinformation om Adobe Experience Cloud
description: Mall för versionsinformation om Experience Cloud
doc-type: release notes
last-update: May 2020
author: mfrei
translation-type: tm+mt
source-git-commit: be2f2b5ad468ad63bfcb2fdd67d063203ac08654
workflow-type: tm+mt
source-wordcount: '4919'
ht-degree: 79%

---


# Versionsinformation om Adobe Experience Cloud – maj 2020

![Banderoll](/assets/experience-cloud-banner-3.png)

Den här sidan beskriver nya funktioner, korrigeringar och viktiga meddelanden i [!DNL Adobe Experience Cloud]. Lösningens lanseringsdatum kan variera. Kom tillbaka regelbundet för de senaste uppdateringarna.

>[!NOTE]
>
>Prenumerera på [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) om du vill få meddelanden via e-post om kommande versioner.

**Lanseringsdatum: maj 2020**

Senaste uppdatering: **4 juni 2020**

* [Adobe System Status](#status)
* [Experience Cloud-gränssnitt](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics) (**Uppdaterat 4 juni 2020**)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/sv-SE/target/using/release-notes/target-release-notes.html) (länkar till Targets hjälpsida)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/se/primetime/user-guide.html) (länkar till Primetimes hjälpsida)

Behöver du hjälp? Besök [[!DNL Adobe Experience League]](https://experienceleague.adobe.com/#home) för att hitta kurser, teknisk dokumentation, snabba svar, communityinsikter och lärarledd utbildning från Adobe.

## ![Ikon för ](/assets/adobe.png)Adobe System Status {#status}

[!UICONTROL Adobe System Status] ger detaljerad information, statusuppdateringar och e-postmeddelanden om Adobe-molnprodukter och -tjänster, driftstopp, avbrott och underhållshändelser. Kolla in det på [status.adobe.com](https://status.adobe.com/).

Lanseringsdatum: **21 maj 2020**

**Nyheter**

* Med ditt Adobe ID kan du prenumerera på händelseaviseringar med mer information ända ned på produkt- och tilläggsnivå. Processen för självprenumerationer rekommenderar nu ett urval av produkter och tjänster baserat på dina produktbehörigheter vilket hjälper dig att konfigurera prenumerationer snabbare. Det bör minska antalet e-postmeddelanden du får och leda till att du får mer relevanta meddelanden i inkorgen. Kom igång på [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nya funktioner och förbättringar som är tillgängliga nu**

| Funktion | Beskrivning |
| -----------| ---------- |
| Förbättrad användarupplevelse för prenumerationer och meddelanden | <ul><li>Regionala [!DNL Marketo Engage]-platser filtreras nu baserat på den lista med produkterbjudanden som valts.</li><li>[!DNL Marketo Engage] e-postmeddelanden är relevanta för användarens region, plats och miljöinställningar.</li></ul> |
| Bekräftelse av händelseprenumeration | <ul><li>Du kan nu få en bekräftelse via e-post när du prenumererar på löpande uppdateringar om händelser.</li></ul> |
| Förbättrad global navigering | <ul><li>Enhetlig användarupplevelse med `Adobe.com` på den översta nivån i navigeringsmenyn.</li></ul> |

## ![Ikonen i](/assets/ec_appicon_24.png) Experience Cloud-gränssnittet {#ecloud}

Allmänna uppdateringar av Experience Cloud-gränssnittet.

**Enhetlig produktdomän**

Adobe har uppdaterat domänen och gränssnittets sidhuvud för att skapa en enhetlig och förbättrad upplevelse i alla Experience Cloud-program. Dessa förbättringar är utformade för att förenkla upplevelsen på små, men viktiga sätt. Förbättringarna ändrar inte dina aktuella arbetsflöden.

Bland uppdateringarna finns:

* Nya program-URL:er: `experience.adobe.com/<application name>`:
   * Alla produkter kommer så småningom att använda det här URL-mönstret. Titta efter nya URL:er som börjar gälla under månaden.
   * Stöd för webbläsare: De webbläsare som stöds är [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] och [!DNL Opera] (de senaste versionerna). **Obs!** Trots att Experience Cloud-gränssnittet har stöd för dessa webbläsare kanske inte enskilda program har stöd för alla webbläsare. ([Analytics](https://docs.adobe.com/content/help/sv-SE/analytics/admin/sys-reqs.html) har till exempel inte stöd för [!DNL Opera] och [Target](https://docs.adobe.com/help/sv-SE/target/using/implement-target/before-implement/supported-browsers.html) har inte stöd för [!DNL Safari].)
   * ([!DNL Safari] endast) Domänändringen kan orsaka cookie-problem i [!DNL Safari]. Om du avmarkerar _Förhindra spårning över webbplatser_ i [!DNL Safari] Sekretessinställningar aktiveras cookies i domäner (och alla upplevelser på olika webbplatser) och Experience Cloud kan fungera i den nya domänen.
* Enklare att växla mellan olika organisationer eller till ett annat program.
* Förbättrad produkthjälp: [!UICONTROL Experience League] är integrerat i produkten så att en hjälpsökning även visar resultat från communityforum och videoinnehåll. Den här ändringen gör det enklare att komma åt mer innehåll och hjälper dig att få ut mesta möjliga av Experience Cloud. Dessutom kan du klicka på **[!UICONTROL Help]** > **[!UICONTROL Feedback]** om du vill rapportera problem eller dela med dig av dina idéer till Adobe.

Följande program använder den nya domänen experience.adobe.com:

| Program eller tjänst | Domän |
| -----------| ---------- |
| Experience Clouds startsida | `experience.adobe.com/home` |
| Adobe Target | `experience.adobe.com/target` |
| Adobe Audience Manager | `experience.adobe.com/audience-manager` |
| Adobe Launch | `experience.adobe.com/launch` |
| Adobe Experience Platform | `experience.adobe.com/platform` |
| Journey Management | `experience.adobe.com/journeys` |
| Customer Journey Analytics | `experience.adobe.com/platform/analytics` |
| Adobe Campaign Control Panel | `experience.adobe.com/controlpanel` |
| Cloud Manager | `experience.adobe.com/cloud-manager` |
| Places Service | `experience.adobe.com/places` |
| Software Distribution | `experience.adobe.com/downloads` |
| Admin Tool (beta) | `experience.adobe.com/admin` |

>[!NOTE]
>
>**[!UICONTROL Board & Collections]**, ett äldre filter i [!UICONTROL Marketing Cloud Assets]-väljaren, tas ur bruk.

## ![Ikon för](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Versionsinformation för [!DNL Experience Platform,] inklusive [!DNL Experience Platform Launch,] [!UICONTROL Journey Orchestration], [!UICONTROL Offers], [!UICONTROL People], [!UICONTROL Places], [!UICONTROL Mobile Services] och säkerhetsbulletiner.

### Gränssnittsförbättringar

Uppdaterat: **15 maj 2020**

[!DNL Adobe Experience Platform] uppdaterar domänen och sidhuvudet för att skapa en enhetlig och förbättrad upplevelse i alla Experience Cloud-program. Bland uppdateringarna finns:

* Enklare att växla mellan olika organisationer eller till ett annat program.
* Förbättrad användarhjälp, inklusive aktuella artiklar och sammanhangsberoende dokumentation på Hjälp-menyn.
* Möjlighet att ge feedback om Experience Platform och skicka supportärenden.

Mer information finns i [versionsinformationen för Experience Platform](https://docs.adobe.com/content/help/sv-SE/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md).

### Customer Attributes – ny dokumentation

Uppdaterat: **15 maj 2020**

* [Customer Attributes har stöd för CCPA](https://docs.adobe.com/content/help/sv-SE/core-services/interface/customer-attributes/ccpa.html) (California Consumer Privacy Act)
* [Customer Attributes har stöd för GDPR](https://docs.adobe.com/content/help/sv-SE/core-services/interface/customer-attributes/gdpr.html) (allmänna dataskyddsförordningen)

### Journey Orchestration {#journey}

Med Adobe Experience Platform kan ni orkestrera enskilda kundresor i stor skala över olika upplevelsekanaler genom att intelligent förutse varje enskild individs behov i realtid, oavsett vart resan bär.

* [Dokumentation](https://docs.adobe.com/content/help/sv-SE/journeys/using/journey-orchestration-home.html)
* [Versionsinformation](https://docs.adobe.com/content/help/sv-SE/journeys/using/release-notes/release-notes.html)
* [Instruktionsvideor](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Ytterligare versionsinformation om Experience Platform

* [Versionsinformation om Experience Platform Launch](https://docs.adobe.com/content/help/sv-SE/launch/using/intro/release-notes/current.html)
* [Versionsinformation om Experience Platform](https://docs.adobe.com/content/help/sv-SE/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md)
* [Säkerhetsbulletiner och rekommendationer](https://helpx.adobe.com/se/security.html) (alla Adobe-produkter)

## ![Ikon](/assets/analytics.png) [!DNL Analytics] {#analytics}

Updated **June, 2020**

* [Nya funktioner i Adobe Analytics](#aa-features)
* [Nya funktioner i Customer Journey Analytics](#cust-journey)
* [Nya funktioner i Media Analytics](#media-aa)
* [Korrigeringar i Adobe Analytics](#aa-fixes)
* [Viktiga meddelanden för Analytics-administratörer](#aa-notices)
* [AppMeasurement](#appm)
* [Självstudiekurser för nya Analytics](#tutorials-analytics)

### Nya funktioner i Adobe Analytics {#aa-features}

| Funktion | [Allmän tillgänglighet](https://docs.adobe.com/content/help/sv-SE/analytics/landing/an-releases.html)- Måldatum | Beskrivning |
| -----------| ---------- |-------|
| Attribution IQ: Algoritmisk attribuering | 18 juni 2020 | I [!UICONTROL Algorithmic Attribution] modellen i Analysis Workspace används statistiska tekniker för att dynamiskt fastställa den optimala kreditallokeringen för det valda måttet. [Läs mer...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/algorithmic.html) |
| Attribution IQ: Anpassade uppslagsfönster | 18 juni 2020 | Du kan nu konfigurera alla attribueringsmodeller i så [!UICONTROL Attribution IQ] att de inkluderar kontaktytor från upp till 90 dagar före rapporttidsperioden. Detta ökar vanligen attribueringens exakthet för händelser som inträffar tidigt under rapporteringsperioden genom att redovisa interaktioner som inträffat under föregående månad(er). [Läs mer...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/attribution.html#lookback-windows) |
| Projektroller för delade arbetsyteprojekt | 18 juni 2020 | När du delar ett Workspace-projekt kan du nu placera mottagare i en av tre projektroller, beroende på vilken erfarenhet du vill att de ska ha: Redigera, Duplicera och Visa. [Läs mer...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Visa endast arbetsyteprojekt | 18 juni 2020 | Arbetsyteprojekt kan bara delas till användare som&quot;Kan visa&quot;. När en Visa-mottagare öppnar det delade projektet får de en mer restriktiv projekterfarenhet, utan någon vänster spårsträcka och begränsad interaktion. [Läs mer...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/view-only-projects.html) |
| Möjlighet att samredigera projekt i arbetsytan | 18 juni 2020 | Mottagare som läggs till i rollen Kan redigera kan spara över ett projekt som har delats med dem. Detta gäller både administratörer och icke-administratörer. [Läs mer...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Uppdaterad tom panel i arbetsytan | 18 juni 2020 | Den tomma panelen i Workspace innehåller nu paneler och visualiseringar, vilket gör det enklare att välja det analysarbetsflöde som fungerar bäst för dig. |
| Första parts domäner är tillgängliga i Kinas domänkontrollant | 18 juni 2020 | Gör det möjligt för kunder med en `.cn` domän att begära en förstahandsdomän för användning i Mainland China. (Dokumentation finns vid köp av&quot;China Performance Optimization&quot; SKU.) |
| Panelen Snabbinformation i Workspace | 25 juni 2020 | Quick Insights ger vägledning för icke-analytiker och nya användare av Analysis Workspace så att de snabbt och enkelt kan få svar på affärsfrågor. [Läs mer...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/quickinsight.html) |
| Analyser för målpanelen i arbetsytan | 25 juni 2020 | På A4T-panelen (Analytics for Target) kan du analysera dina Adobe Target-aktiviteter och -upplevelser i Analysis Workspace. [Läs mer...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/a4t-panel.html) |

### Nya funktioner i Customer Journey Analytics {#cust-journey}

| Funktion | [Allmän tillgänglighet](https://docs.adobe.com/content/help/sv-SE/analytics/landing/an-releases.html)- Måldatum | Beskrivning |
| -----------| ---------- |-----|
| Stöd för avvikelseidentifiering | 18 juni 2020 | Analysidentifiering är en statistisk metod för att fastställa hur ett givet mätresultat har ändrats i förhållande till tidigare data. [Läs mer...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/virtual-analyst/anomaly-detection/anomaly-detection.html) |
| Projektroller för delade arbetsyteprojekt | 18 juni 2020 | När du delar ett Workspace-projekt kan du nu placera mottagare i en av tre projektroller, beroende på vilken erfarenhet du vill att de ska ha: Redigera, Duplicera och Visa. [Läs mer...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Visa endast arbetsyteprojekt | 18 juni 2020 | Arbetsyteprojekt kan bara delas till användare som&quot;Kan visa&quot;. När en Visa-mottagare öppnar det delade projektet får de en mer restriktiv projekterfarenhet, utan någon vänster spårsträcka och begränsad interaktion. [Läs mer...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/view-only-projects.html) |
| Möjlighet att samredigera projekt i arbetsytan | 18 juni 2020 | Mottagare som läggs till i rollen Kan redigera kan spara över ett projekt som har delats med dem. [Läs mer...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |

### Nya funktioner i [!UICONTROL Media Analytics] {#media-aa}

Uppdaterat den: **29 maj 2020**

**Spårning av spelarstatus:** [!UICONTROL Media Analytics] kunder kan fånga tittarinteraktion under uppspelning med en standarduppsättning lösningsvariabler för helskärmsvisning, undertexter, ljud av, bild-i-bild och i fokus. Du kan också skapa anpassade spelarlägen. Variabler för spårning av spelarstatus är nu tillgängliga för rapportering i [!UICONTROL Analysis Workspace]. Den här funktionen kräver något av följande:

* Media [!DNL JavaScript] SDK 3.0 eller senare
* För användning med [!DNL Adobe Experience Platform] (AEP) SDK:
   * [!UICONTROL Media Analytics Extension] (för webb): [!UICONTROL Adobe Media Analytics] (3.x SDK) för ljud och video v1.0 eller senare
   * [!UICONTROL Media Analytics Extension] (för mobil): [!UICONTROL Adobe Media Analytics for Audio] och video v2.0 eller senare
* [!UICONTROL Media Collection]

Se [Om spårning av spelartillstånd](https://docs.adobe.com/content/help/sv-SE/media-analytics/using/player-state-tracking/player-state-overview.html).

### Adobe Analytics Fixes {#aa-fixes}

* Korrigerade ett problem som gjorde att segment med flerbytessökningar efter vissa rapportsviter inte matchade något. De kommer nu att matcha rätt strängar. AN-220043
* Ett problem har korrigerats med att objektfiltret i rapporter och analyser inte fungerade. AN-206132
* Korrigerad långsam svarstid i användargränssnittet för schemalagda projekt. AN-214837
* Ett problem med att Analytics Reporting API 2.0 genererade ett datumintervallfel har korrigerats. AN-215087
* Korrigerade ett fall där instansen/besökaren/besökaren inte räknades i nämnaren för tidsanvändningens mått. Detta inträffar när en träff utan värde för dimensionen (t.ex. Pagename) följs i samma sekund. AN-211074
* Ett problem har korrigerats med användare som inte har åtkomst till arbetsyteprojekt som delas med dem. AN-217561
* Ett problem med att nycklar inte klassificerades av klassificeringsregelbyggaren har korrigerats. AN-221538
* Korrigerade ett problem med serveranropsanvändningen som inte rapporterade några användningsdata. AN-210452
* Korrigerade problem med publicerade Adobe Analytics-segment som saknar data i AAM. AN-220208, AN-220659
* Ett problem med rapporter som visar data har korrigerats, men datafeeds-loggar som anger &quot;Inga data Warehouse-data&quot;. AN-220784, AN-220858
* Korrigerade problem som förhindrade att Ad Hoc Analysis startades från `experiencecloud.com` domänen. AN-219680, AN-221629
* Problem med att använda snabbtangenten &quot;Ctrl (eller Kommando) + C&quot; har korrigerats. AN-221101, AN-221537
* Ett problem med aktiveringssidan för aktivitetskartan har korrigerats. AN-222029, AN-221242
* Korrigerade ett problem med att det inte gick att lägga till en kontaktyta mitt i en utfallsvisualisering. AN-221648

#### Övriga korrigeringar i Adobe Analytics

AN-218269; AN-218455; AN-218492; AN-219888; AN-220447; AN-220546; AN-220788; AN-220866; AN-221165; AN-221545; AN-221712; AN-221832; AN-221853; AN-222000; AN-222505; AN-222559

### Viktiga meddelanden för [!DNL Analytics]-administratörer {#aa-notices}

| Meddelande | Datum tillagt eller uppdaterat | Beskrivning |
| -----------| ---------- | ---------- |
| Migrering till den enhetliga produktdomänen | Datum för ikraftträdande: 28 maj 2020 | Övergången till en enhetlig produktdomän för Adobe Analytics, som började i januari 2020, slutfördes den 28 maj 2020. While Adobe Analytics works to remove all `omniture.com` domain references from its architecture, it is important to allowlist `omniture.com` as a third-party cookie. När den fullständiga arkitekturmigreringen är (snart) slutförd meddelar vi dig via versionsinformationen och det här steget för vitlistning kommer inte längre att behövas. [Här](https://helpx.adobe.com/se/analytics/kb/adobe-ip-addresses.html) är en fullständig lista över rekommenderade IP-adresser och domäner som du bör tillåta.<br>Om din organisation blockerar cookies från tredje part kan du kontakta kundtjänst för att få tillgång till Adobe Analytics igen. |
Om din organisation blockerar cookies från tredje part kan du kontakta kundtjänst för att få tillgång till Adobe Analytics igen.
|Ny standardlandningssida för Adobe Analytics|Startdatum: 18 juni 2020|18 juni 2020 ändras standardstartsidan för Adobe Analytics från Reports till Workspace. Den här ändringen sker för användare som inte tidigare har angett en anpassad landningssida.|
|Teknologi från tredje part|12 mars 2020 (giltighetsdatum)|Adobe Analytics har börjat utnyttja tredjepartstekniker för funktionshantering och produktsupport. Följande URL:er bör läggas till i alla nödvändiga tillståndslistor för nätverkets brandvägg för att säkerställa fullständig funktionsåtkomst:<ul><li>Gainsight: https://esp.aptrinsic.com</li><li>LaunchDarkly: https://app.launchdarkly.com</li></ul>|
|Förbättrad redundans för Analysis Workspace-tillgänglighet|21 maj 2020|För att Analysis Workspace ska vara tillgängligt lägger vi till ett sekundärt CDN (Content Delivery Network) för förbättrad redundans. Följande URL:er ska läggas till i alla nödvändiga vitlistor för nätverkets brandvägg:<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul>|
|Ändra till hur [!UICONTROL Entries/Exits] beräkningen görs i [!UICONTROL Workspace]|7 april 2020|I mars 2020 [!UICONTROL Analysis Workspace]har vi ändrat hur värdet _Ingen_ interagerar med [!UICONTROL Entries/Exits]. Eftersom du nu kan aktivera och inaktivera _Inga_ i [!UICONTROL Analysis Workspace] använder vi värdet _Inga_ efter första eller sista besökssidan i stället för före (för eVars). Anta till exempel att den första träffen för ett besök inte har ett värde för eVars, men att den andra träffen har det. I [!UICONTROL Reports & Analytics] visas den första träffen som _Ospecificerat_ för första besökssidan, men i [!UICONTROL Analysis Workspace] visas det som ett värde för den andra träffen.|
|EOL of **[!UICONTROL Dashboard Archive]**|March 27, 2020|The **[!UICONTROL View Archive]** setting under **[!UICONTROL Manage Dashboards]** in [!UICONTROL Reports & Analytics] will no longer be available as of October, 2020.|
|End of Life - Analytics Legacy API:er|9 januari 2020|I november 2020 kommer följande Analytics Legacy API-tjänster att ha nått sitt slutdatum och kommer att avslutas. Aktuella integreringar som byggts med dessa tjänster kommer att sluta fungera. <ul><li>1.3 API:er för Analytics</li><li>1.4 API:er för SOAP Analytics</li><li>Äldre OAuth-autentisering (OAuth och JWT)</li></ul>Vi har tagit fram [vanliga frågor och svar om upphörande av äldre API:er](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) som kan hjälpa dig att få svar på frågor och ge vägledning om hur du går vidare. API-integrationer som använder dessa tjänster kan migrera till [1.4 Analytics REST-API:er](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) eller [2.0 Analytics API:er](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Äldre OAuth-konton kan migrera till ett [Adobe IO](https://console.adobe.io/home?mv=email) Analytics-integreringskonto som kan användas för att få tillgång till både 1.4 Analytics API:er och 2.0 Analytics API:er.|
|San Jose FTP Broker Ending for London and Singapore|Juli 2020|För kunder i London och Singapore stöder vi inte längre förmedling av data mellan London eller Singapore och datacentret [ftp.omniture.com](ftp://ftp.omniture.com/)i San Jose.<br/><ul><li>I London använder du [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>I Singapore använder du [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul>|
|EOL of Ad Hoc Analysis|6 augusti 2018|Adobe meddelade sin avsikt att avsluta Ad Hoc Analysis. Ett slutdatum meddelas så snart det är tillgängligt. Mer information finns i [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/).|

### [!DNL AppMeasurement] {#appm}

Se [versionsinformationen om AppMeasurement för Javascript](https://docs.adobe.com/content/help/sv-SE/analytics/implementation/appmeasurement-updates.html). Version 2.20.0 släpptes 5 mars 2020.

### Självstudiekurser för nya Analytics {#tutorials-analytics}

| Innehåll | Beskrivning |
| -----------| ---------- |
| [Självstudiemall i Analysis Workspace](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/navigating-workspace-projects/training-tutorial-template-in-analysis-workspace.html) | Självstudiekursen [!UICONTROL Analysis Workspace] vägleder dig genom vanliga termer och steg för att skapa ditt första projekt i [!UICONTROL Workspace]. |
| [Lägga till jämförelser med föregående månad och år i trender](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/calendar-and-date-ranges/adding-prior-month-and-year-comparisons-to-trends.html) | Lär dig hur du använder anpassade datumintervall för att skapa månads- och årsvisa trendjämförelser för alla mätvärden i [!UICONTROL Analysis Workspace]. |
| [Tillägg för mörkt läge i Analysis Workspace](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/dark-mode-extension-for-analysis-workspace.html) | Aktivera Chrome-tillägget Dark Reader om du vill använda mörkt läge i Analysis Workspace. |
| [Tillägg för färgpipett för definition av anpassade paletter](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/color-eyedropper-extension-for-defining-custom-palettes.html) | Lär dig hur du använder Chrome-tillägget ColorPick EyeDropper för att enkelt hitta de hexvärden du behöver för en anpassad färgpalett i dina [!UICONTROL Workspace]-projekt. |

#### Hjälpresurser för Analytics

* [Adobe Analytics självstudiekurser](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Adobe Analytics – produktdokumentation](https://docs.adobe.com/content/help/sv-SE/analytics/landing/home.html)

## ![Ikonen](/assets/audience-manager.png) Audience Manager {#aam}

Nya funktioner, korrigeringar, dokumentation och självstudiekurser för Audience Manager.

### Uppdaterat användargränssnitt

Audience Manager uppdaterar domänen och sidhuvudet för att skapa en enhetlig och förbättrad upplevelse i alla Experience Cloud-program.

* Enklare att växla mellan olika organisationer eller till ett annat program.
* Förbättrad användarhjälp, inklusive aktuella artiklar och sammanhangsberoende videoklipp på Hjälp-menyn.
* Möjlighet att ge feedback om Experience Platform och skicka supportärenden.
* Ett nytt och enklare URL-mönster. Uppdatera dina bokmärken till den nya adressen: `experience.adobe.com/audience-manager`.

Uppdateringarna gäller bara användare som loggar in med Adobe ID. Mer information om hur du byter till Adobe ID-inloggning finns i [Hantera Experience Cloud-användare och -produkter](https://docs.adobe.com/content/help/sv-SE/core-services/interface/manage-users-and-products/admin-getting-started.html).

### Nya funktioner och korrigeringar i Adobe Audience Manager

| Funktion | Beskrivning |
| -----------| ---------- |  
| [Verktyg för satsvis hantering (BAAAM)](https://docs.adobe.com/content/help/sv-SE/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html#download) | Vi har laddat upp ett nytt kalkylblad för satsvisa hanteringsverktyg som: <br><br><ul><li>Gör att du kan lista undermapparna i din trait-hierarki (AAM-51528)</li><li>Hämtar mätvärden på begäran för traits som är kopplade till CRM-ID:n (enhetsövergripande ID:n) (AAM-52135)</li><li>Ett språkkodningsproblem för koreanska tecken har korrigerats (AAM-AAM-54006)</li></ul> |

**Korrigeringar**

* Ett problem har korrigerats där trendrapporter orsakade timeout för mappar med många traits. (AAM-54457)
* Ett problem har korrigerats där kunderna inte kunde se [!UICONTROL Expression builder] i arbetsflödet för att skapa/redigera traits. (AAM-54255)
* Ett problem har korrigerats där felmeddelanden i användargränssnittet bara visades en kort tid och försvann innan kunderna hann läsa dem. Det inträffade till exempel när ett segment som var mappat till ett mål skulle tas bort. (AAM-54031)
* Ett problem har korrigerats där kunder som inte använder [!UICONTROL Audience Marketplace] längre fick e-postmeddelanden med månatliga fakturor. (AAM-54602)
* Ett problem har korrigerats där kunder som klickade på vissa traits från andra platser i användargränssnittet såg brutna länkar i stället för traits. (AAM-54768)
* Ett problem har korrigerats där ett tryck på ENTER i redigeringsläget för anpassade uttryck gjorde att sidan uppdaterades och trait-uttrycket gick förlorat. (AAM-54210)
* Flera tillgänglighetsförbättringar i hela gränssnittet. (AAM-47781, AAM-49075, AAM-49360, AAM-49361, AAM-49376, AAM-50432, AAM-52550, AAM-54660).

### Nya självstudiekurser för Audience Manager {#tutorials-aam}

| Innehåll | Beskrivning |
| -----------| ---------- |  
| [Förstå grundläggande termer och begrepp i Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-basic-terms-and-concepts-in-audience-manager.html) | Den här videon innehåller några av de grundläggande termer och begrepp som får dig att komma igång med Audience Manager, bland annat signaler, traits, segment osv. |
| [Förstå dataflödet i Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-the-data-flow-in-audience-manager.html) | Den här videon hjälper dig att förstå Adobe Audience Manager genom att beskriva dataflödet till och från samt inuti programmet. |
| [Audience Manager – Översikt över en plattform för datahantering](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-overview-of-a-dmp.html) | Förstå de största utmaningarna med kanalövergripande personalisering och hur Adobe Audience Manager styr kundresan. Lär dig också vilka datatyper som kan registreras i Audience Manager och identifiera de systempartners för annonsteknologier som är integrerade i Audience Manager. |
| [Användningsexempel för Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-use-cases.html) | I den här videon ger vi exempel på fyra vanliga användningsområden för Audience Manager och beskriver de bästa metoderna. |
| [Förstå enhetsövergripande mätvärden i Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/profile-merge/understanding-cross-device-metrics-in-audience-manager.html) | I den här videon diskuterar vi skillnaden mellan enhetsprofiler och enhetsövergripande profiler och visar var siffrorna i användargränssnittet matchar de olika profiltyperna. |
| [Förstå prediktiva målgrupper i Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/understanding-predictive-audiences.html) | I den här videon berättar vi vad prediktiva målgrupper är i Audience Manager, beskriver hur de fungerar och ger exempel på användning. |
| [Konfigurera och rapportera om prediktiva målgrupper i Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/configure-and-report-on-predictive-audiences.html) | I den här videon går vi igenom konfigurationen för prediktiva målgrupper i Audience Manager-gränssnittet. Vi tittar också på rapporter som visar resultat för modellen. |

## ![Ikonen för](/assets/aem.png) Experience Manager {#aem}

Nya funktioner, korrigeringar och uppdateringar i Adobe Experience Manager (AEM). Adobe rekommenderar att kunder med lokala distributioner driftsätter de senaste korrigeringarna för bättre stabilitet, säkerhet och prestanda.

### Uppdateringar

* **AEM as a Cloud Service**

   * Förbättringar och korrigeringar i resursbearbetning. Dialogrutan för återanvändning av resurser ger användaren bättre kontroll, gör att en viss bearbetningsprofil kan väljas och om ett arbetsflöde för efterbehandling ska aktiveras.
   * Prestandaförbättringar för import av Dynamic Media-filer.

### Självhjälp

* **Automated Forms Conversion-tjänst – version AFC-2020.03.1**

   Ett nytt alternativ är tillgängligt när du installerar den senaste anslutningen:

   **[!UICONTROL Auto-detect logical sections]**: du kan använda alternativet [!UICONTROL Auto-detect logical sections] för att släppa sidnivåpaneler (sidnummerbaserade paneler) och endast skapa logiska paneler. Det enar också fälten som inte tillhör något avsnitt med föregående logiska avsnitt och fält i ett logisk avsnitt spritt över två angränsande sidor i ett enda logiskt avsnitt. Till exempel, om vissa fält i ett logiskt avsnitt finns i slutet av sidan ett och vissa är i början av sidan två, enas alla sådana fält i ett enda logiskt avsnitt.

* **Bildformat som inte stöds i Dynamic Media**

   Information om de undertyper av rastrerade bildfilsformat som inte stöds i [!UICONTROL Dynamic Media].

   Se [Rastrerade bildformat som inte stöds i Dynamic Media](https://docs.adobe.com/content/help/sv-SE/experience-manager-65/assets/administer/assets-formats.html#unsupported-image-formats-dynamic-media).

* **Content Fragments**

   Information om [stöd för Content Fragments i AEM Assets HTTP API](https://docs.adobe.com/content/help/sv-SE/experience-manager-cloud-service/assets/admin/assets-api-content-fragments.html), [anpassa och utöka Content Fragments](https://docs.adobe.com/content/help/sv-SE/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-customizing.html) och [konfigurera Content Fragments-komponenter för återgivning](https://docs.adobe.com/content/help/sv-SE/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-configuring-components-rendering.html).

* **AEM Experience League Community**

   Kommunicera med [AEM Experience League-communityn](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/ct-p/adobe-experience-manager-community): Ställ frågor till andra som lär sig AEM och AEM-experter, bläddra bland trådar och dela med dig av dina tips och din expertis!

* **AEM-nyhetsbrev**

   AEM-nyhetsbrev från [!UICONTROL Experience League] är utformade för att hjälpa dig att komma igång med AEM så att du kan få valuta för investeringen direkt. Här är det senaste nyhetsbrevet:

   * [Volume 30](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html): Experience Manager is now available as a cloud service.
   * [Prenumerera](https://adobeeventsonline.com/AEM/2017/NL/Optin/) på nyhetsbrevet Experience Insider.
   * Arkiverade nyhetsbrev finns i avsnittet med [AEM-resurser](https://helpx.adobe.com/se/support/experience-manager/6-5.html) på sidan Utbildning och support för Adobe Experience Manager 6.5.

### Nya självstudiekurser för Experience Manager

| Innehåll | Beskrivning |
| -----------| ---------- |  
| [Konfigurera lokal AEM-körningsmiljö](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | Adobe Experience Manager (AEM) kan köras lokalt med [!UICONTROL AEM as a Cloud Service] [!UICONTROL Quickstart Jar] i SDK:erna. Det gör att utvecklare kan driftsätta och testa anpassad kod, konfigurationer och innehåll innan de skickas för källkontroll och distribueras till en [!UICONTROL AEM as a Cloud Service]-miljö. |
| [Komma igång med AEM Assets](https://video.tv.adobe.com/v/33624?captions=swe) | En introduktionsvideo om hur du kommer igång med AEM Assets för företagsanvändare. |
| [Mappscheman för metadata](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-folder-schemas.html) | Med metadatamappscheman kan användare hantera och granska metadata som är kopplade till själva resursmapparna, i stället för direkt till resurser. |
| [Taggar](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/tagging.html) | Taggar är ett viktigt verktyg för att hantera resurser i resursernas mapphierarki. Det är viktigt att skapa en taggningstaxonomi så att användarna kan identifiera och ordna resurser i AEM. |
| [Metadataprofiler](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-profiles.html) | Med metadataprofiler kan du automatiskt tillämpa standardmetadata på resurser i resursmappar. Det minskar arbetet med metadatahantering för AEM-användarna och ger enhetligare metadata. |
| [Metadatascheman](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-schemas.html) | Metadatascheman definierar gränssnittet som visar metadata för resurser i AEM. I den här videon beskriver vi metoder som kan kombineras när resurser används. |

### Ytterligare resurser

* [AEM as a Cloud Service – versionsinformation ](https://docs.adobe.com/content/help/sv-SE/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)
* [AEM as a Cloud Service – dokumentation ](https://docs.adobe.com/content/help/sv-SE/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 – startsida för utbildning och support](https://helpx.adobe.com/se/support/experience-manager/6-5.html)
* [AEM 6.4 – startsida för utbildning och support](https://helpx.adobe.com/se/support/experience-manager/6-4.html)
* [AEM 6.3 – startsida för utbildning och support](https://helpx.adobe.com/se/support/experience-manager/6-3.html)
* [AEM 6.2 – startsida för utbildning och support](https://helpx.adobe.com/se/support/experience-manager/6-2.html)
* [Användarhandbok för Cloud Manager](https://docs.adobe.com/content/help/sv-SE/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
* [AEM Cloud Manager – versionsinformation](https://docs.adobe.com/content/help/sv-SE/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Äldre versioner av AEM-dokumentation](https://helpx.adobe.com/se/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic – startsida för hjälp](https://docs.adobe.com/content/help/sv-SE/dynamic-media-classic/using/home.html)
* [Versionsinformation för Dynamic Media](https://docs.adobe.com/content/help/sv-SE/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Versionsinformation för Livefyre](https://docs.adobe.com/content/help/sv-SE/livefyre/using/release-notes/c-rn.html)

## ![Ikon](/assets/campaign.png) [!DNL Campaign] {#ac}

Adobe Campaign är ett intuitivt och automatiserat sätt att leverera personliga meddelanden i alla marknadsföringskanaler, både online och offline. Nu kan ni förutse vad era kunder vill ha med upplevelser som bestäms av deras vanor och önskemål.

### Campaign Standard

* [Adobe Campaign Standard 20.3 version](https://docs.adobe.com/content/help/sv-SE/campaign-standard/using/release-notes/release-notes.html)

### Campaign Classic

* [Adobe Campaign Classic 20.1.3](https://docs.adobe.com/content/help/sv-SE/campaign-classic/using/release-notes/latest-release.html#release-20-1-3-build-9124)
* [Adobe Campaign Classic 19.1.4](https://docs.adobe.com/content/help/sv-SE/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

### Campaign Control Panel

| Funktion | Beskrivning |
| -----------| ---------- |  
| Hantering av GPG-nycklar | Installera och/eller generera GPG-nycklar för en marknadsinstans för att kryptera data som skickas från Campaign och dekryptera inkommande data. |
| Certifikathantering för CNAME-underdomäner | Med Control Panel kan du nu förnya SSL-certifikaten för dina underdomäner som har delegerats med CNAME-metoden. |

### Nya självstudiekurser för Campaign

* Nya självstudiekurser för Campaign Standard

| Innehåll | Beskrivning |
| -----------| ---------- |  
| [Control Panel – hantering av Google TXT-poster](https://docs.adobe.com/content/help/sv-SE/campaign-standard-learn/tutorials/administrating/control-panel/google-txt-record-management.html) | Lär dig hur du lägger till Google TXT-poster för webbplatsverifiering på alla dina underdomäner som används för att skicka e-post till GMAIL-adresser med Campaign Control Panel. |
| [Konfigurera och köra ett arbetsflöde med aktiviteten Externt API](https://docs.adobe.com/content/help/sv-SE/campaign-standard-learn/tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html) | Lär dig hur du anropar en extern REST API-slutpunkt med aktiviteten External API. |
| [Komma igång med push-meddelanden för Android – självstudiekurs](https://docs.adobe.com/content/help/sv-SE/campaign-standard-learn/getting-started-with-push-notifications-android/introduction.html) | I den här självstudiekursen beskrivs de steg som behövs för att konfigurera push-meddelanden med Campaign Standard och Android-appen. |

* Nya självstudiekurser för Campaign Classic

| Innehåll | Beskrivning |
| -----------| ---------- |  
| [Big data-hantering i Snowflake](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | Lär dig hur du kan utnyttja Snowflake-anslutningen i Adobe Campaign Classic. |
| [Control Panel – hantering av Google TXT-poster](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/google-txt-record-management.html) | Lär dig hur du lägger till Google TXT-poster för webbplatsverifiering på alla dina underdomäner som används för att skicka e-post till GMAIL-adresser med Campaign Control Panel. |

### Hjälpresurser för Campaign

* Adobe Campaign Standard: [Hjälpcenter](https://docs.adobe.com/content/help/sv-SE/campaign-standard/using/campaign-standard-home.html) – [Versionsinformation](https://docs.adobe.com/content/help/sv-SE/campaign-standard/using/release-notes/release-notes.html) – [Instruktionsvideor](https://docs.adobe.com/content/help/sv-SE/campaign-standard-learn/tutorials/overview.html) – [Versionsplanering](https://docs.adobe.com/content/help/sv-SE/campaign-standard/using/release-notes/release-planning.html) – [Senaste dokumentationsuppdateringar](https://docs.adobe.com/content/help/sv-SE/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Hjälpcenter](https://docs.adobe.com/content/help/sv-SE/campaign-classic/using/campaign-classic-home.html) – [Versionsinformation](https://docs.adobe.com/content/help/sv-SE/campaign-classic/using/release-notes/latest-release.html) – [Instruktionsvideor](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html) – [Senaste dokumentationsuppdateringar](https://docs.adobe.com/content/help/sv-SE/campaign-classic/using/documentation-updates.html)
* Kontrollpanelen för Adobe Campaign: [Dokumentation](https://docs.adobe.com/content/help/sv-SE/control-panel/using/control-panel-home.html) – [Versionsinformation](https://docs.adobe.com/content/help/sv-SE/control-panel/using/release-notes.html)

## ![Ikon](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

* [Nya funktioner i Advertising Cloud DSP](#adcloud-dsp)
* [Nya funktioner i Advertising Cloud Search](#adcloud-search)

### Nya funktioner i Advertising Cloud DSP {#adcloud-dsp}

| Funktion | Beskrivning |
| -----------| ---------- |
| [!UICONTROL Campaigns Classic] och [!UICONTROL Campaigns Beta] | IAS-mätningsinställningar för bedrägeri och varumärkessäkerhet, som du kan konfigurera för varje kampanj, innehåller nu alternativ för att mäta VAST- och VPAID-lager. |
| [!UICONTROL Campaigns Beta] | Datavisualiseringar och sidinläsningstider har förbättrats. |
|  | På alla sidor kan du nu hämta Excel-rapporter som baseras på de aktuella filtren och vyerna. |
|  | (Version från 22 maj) Nya mätvärden inkluderar All-time metrics, Current Interval Delivery, Date Specific OTS. |
| [!UICONTROL Blacklists] | Prognossystemet använder nu automatiskt svartlistor på annonsör- eller kontonivå. Användare behöver inte längre klistra in svartlistan i platsinställningarna. |
| [!UICONTROL Inventory Deals] | (Stängd betaversion) Med ett nytt, förenklat formulär kan du snabbt konfigurera, redigera och felsöka erbjudanden på leverantörsplattformar (SSP:er) som inte finns i Deal ID-inkorgen. |
|  | När du godkänner ett paket med programmatiska garanterade erbjudanden i Deal ID-inkorgen får du nu ett meddelande om att du måste skapa en standardplats för varje Deal ID. |

### Nya funktioner i [!UICONTROL Advertising Cloud Search] {#adcloud-search}

| Funktion | Beskrivning |
| -----------| ---------- |
| [!UICONTROL Campaigns] | (Google Ads-konton, betatjänst) Från och med slutet av maj kommer Advertising Cloud Search att kunna synkronisera data för dina Google Gmail displaykampanjer och dina Google Smart Shopping-kampanjer med Google-konverteringar för spårning och rapportering. Med tjänsten kan du även redigera kampanjinställningarna och inställningarna för annonsgrupper för befintliga kampanjer från vyerna Campaigns och Ad Groups. Tjänsten är valfri. När tjänsten blir allmänt tillgänglig tillkommer en extra avgift.<br>Kontakta din kontoansvariga på Adobe om du vill ha mer information om tjänsten, inklusive betaprogrammet och dess framtida omfattning. |

## ![Ikon](/assets/magento.png) [!DNL Magento] {#magento}

Versionsinformation om Magento finns i:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Ikon](/assets/marketo.png) [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] är ett komplett program för lead-hantering för B2B-marknadsförare som vill transformera kundupplevelser genom engagemang under alla faser av komplexa inköpsresor.

### Uppdateringar om Core Marketo Engage

Den senaste informationen finns i [!DNL Marketo] [versionsinformationen](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720).

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
