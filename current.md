---
title: Versionsinformation om Adobe Experience Cloud
description: Mall för versionsinformation om Experience Cloud
doc-type: release notes
last-update: June 2020
author: mfrei
translation-type: tm+mt
source-git-commit: dd357da4e362c01ab350891b1082020c90eb77fe
workflow-type: tm+mt
source-wordcount: '6343'
ht-degree: 33%

---


# Tidig åtkomst - Versionsinformation om Adobe Experience Cloud - juni 2020

![Banderoll](/assets/experience-cloud-banner-3.png)

This page describes new features, fixes, and important notices in [!DNL Adobe Experience Cloud]. Här finns också ny dokumentation, kurser och videokurser som hjälper dig att få ut mesta möjliga av Experience Cloud.

>[!IMPORTANT]
>
>Den här sidan innehåller förhandsversion av innehåll som kan ändras före den planerade versionen.

>[!NOTE]
>
>Subscribe to the [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases.

**Releasedatum: 18 juni 2020**

Produktreleasedatum kan variera. Leta ofta efter uppdateringar.

Senaste uppdatering: **12 juni 2020**

* [Adobe – systemstatus](#status)
* [Experience Cloud-gränssnitt](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Analyser](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/sv-SE/target/using/release-notes/target-release-notes.html)
* [!DNL Magento](#magento)
* [!DNL Marketo Engage](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/se/primetime/user-guide.html) (länkar till Primetimes hjälpsida)

Behöver du hjälp? Besök [Adobe Experience League](https://experienceleague.adobe.com/#home) för att hitta produkt- och teknisk dokumentation, kurser, videokurser, snabbsvar, communityinsikter och lärarledd utbildning.

## ![Ikon för ](/assets/adobe.png)Adobe – systemstatus {#status}

[!UICONTROL Adobe System Status] ger detaljerad information, statusuppdateringar och e-postmeddelanden om Adobe-molnprodukter och -tjänster, driftstopp, avbrott och underhållshändelser. Kolla in det på [status.adobe.com](https://status.adobe.com/).

Släppt: **21 maj 2020**

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
| Adobe Analytics | `experience.adobe.com/analytics` |
| Customer Journey Analytics | `experience.adobe.com/platform/analytics` |
| Adobe Campaign Control Panel | `experience.adobe.com/controlpanel` |
| Cloud Manager | `experience.adobe.com/cloud-manager` |
| Places Service | `experience.adobe.com/places` |
| Software Distribution | `experience.adobe.com/downloads` |
| Administratörsverktyg (beta) | `experience.adobe.com/admin` |

>[!NOTE]
>
>**[!UICONTROL Board & Collections]**, ett äldre filter i [!UICONTROL Marketing Cloud Assets]-väljaren, tas ur bruk.

## ![Ikon](/assets/experience_platform_appicon_24.png) för Adobe Experience Platform {#platform}

Release notes for the [!DNL Experience Platform] and application services, including [!DNL Experience Platform Launch,] [!UICONTROL Offers], [!UICONTROL People], [!UICONTROL Places], [!UICONTROL Mobile Services], and security bulletins.

Releasedatum: **10 juni 2020**

[!DNL Adobe Experience Platform] innehåller följande nya funktioner:

* **Data Science Workspace:** I [!DNL JupyterLab Launcher] den ingår nu en startsida för [!DNL Python] maskininlärning i realtid (Alpha).
* **Segmentering:** Ett fördelningsdatumfält för datumfunktioner har lagts till, vilket gör att användare kan utvärdera datum utan år.
* **Källor:** Nya källkopplingar för [!DNL Apache HDFS] och [!DNL Couchbase].

Mer information om de här funktionerna finns i Versionsinformation om [Experience Platform](https://docs.adobe.com/content/help/sv-SE/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md).

### Ytterligare versionsinformation om Experience Platform

* [Versionsinformation om Experience Platform Launch](https://docs.adobe.com/content/help/sv-SE/launch/using/intro/release-notes/current.html)
* [Säkerhetsbulletiner och rekommendationer](https://helpx.adobe.com/se/security.html) (alla Adobe-produkter)

### Kurser och självstudiekurser på nya Experience Platform {#tutorials-plat}

| Innehåll | Innehållstyp | Beskrivning |
| -----------| ---------- | ---------- |
| [Introduktion till Adobe Experience Platform](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-U-1-2020.1) | Kurs | Läs om hur Adobe Experience Platform hjälper er att leverera rätt upplevelse genom att omvandla era data till stabila kundprofiler i realtid och AI-drivna insikter som ni kan aktivera i alla kanaler. Denna introduktionsnivå ger er en översikt över Experience Platforms funktioner, användningsfall, relation med Adobe Experience Cloud, grundläggande arkitektur, gränssnitt och projektroller. |
| [Introduktion till Web SDK och Edge Network](https://docs.adobe.com/content/help/en/platform-learn/tutorials/data-ingestion/web-sdk/introduction-to-web-sdk-and-edge-network.html) | Videosjälvstudiekurs | En översikt över Adobe Experience Platform SDK och Edge Network. Experience Platform Web SDK är ett JavaScript-bibliotek på klientsidan som gör det möjligt för kunder att använda ett JavaScript-bibliotek, en beacon-typ, en dataström, en och serversidans mål för att skicka data till alla Adobe-program och till tredjepartsmål. |
| [Demo av Web SDK och Edge Network](https://docs.adobe.com/content/help/en/platform-learn/tutorials/data-ingestion/web-sdk/demo-of-web-sdk-and-edge-network.html) | Videosjälvstudiekurs | Se hur Adobe Experience Platform Web SDK och Edge Network fungerar i praktiken, med ett enda anrop till Adobe som skickar data till Experience Platform, Analytics, Audience Manager och Target. |
| [Demo av kunddataplattform i realtid](https://docs.adobe.com/content/help/en/platform-learn/tutorials/rtcdp/demo.html) | Videosjälvstudiekurs | Lär dig hur CDP används i realtid för att samla in data från flera källor. Ni kan slå samman dessa data till en enda kundprofil i realtid och aktivera dessa data för att skapa personaliserade kundupplevelser. |

## ![Icon](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Med Adobe Experience Platform kan ni orkestrera enskilda kundresor i stor skala över olika upplevelsekanaler genom att intelligent förutse varje enskild individs behov i realtid, oavsett vart resan bär.

### Senaste versionen

Q2-versionen har publicerats. [Läs mer](https://docs.adobe.com/content/help/sv-SE/journeys/using/release-notes/release-notes.html)

### Nya kurser och självstudiekurser i samband med färjesamordning {#jo-tutorials}

| Innehåll | Innehållstyp | Beskrivning |
| -----------| ---------- | ---------- |
| [Getting Started with Journey Orchestration for Administrators](https://experienceleague.adobe.com/?recommended=JourneyOrchestration-A-1-2020.2) | Kurs | Lär dig hur du konfigurerar och använder Journey Orchestration. Kursen omfattar de viktigaste begreppen och de konfigurationssteg som krävs för att möjliggöra samordning av en resa. Lär dig hur du skapar, publicerar och analyserar dina samordnade resor. |
| [Komma igång med Journey Orchestration för företagsanvändare](https://experienceleague.corp.adobe.com/?recommended=JourneyOrchestration-U-1-2020.1) | Kurs | Lär dig hur du konfigurerar och använder Journey Orchestration. Kursen omfattar de viktigaste begreppen. Du får lära dig att skapa, publicera, rapportera om och analysera dina orkestrerade resor. |

### Ytterligare resurser för resesamordning

[Dokumentation](https://docs.adobe.com/content/help/sv-SE/journeys/using/journey-orchestration-home.html) - [Versionsinformation](https://docs.adobe.com/content/help/sv-SE/journeys/using/release-notes/release-notes.html) - [instruktionsvideor](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

## ![Ikon](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Updated **June 10, 2020**

* [Nya funktioner i Adobe Analytics](#aa-features)
* [Nya funktioner i Customer Journey Analytics](#cust-journey)
* [Nya funktioner i Media Analytics](#media-aa)
* [Korrigeringar i Adobe Analytics](#aa-fixes)
* [Viktiga meddelanden för Analytics-administratörer](#aa-notices)
* [Nya kurser och självstudiekurser i Adobe Analytics](#tutorials-analytics)
* [AppMeasurement](#appm)

### Nya funktioner i Adobe Analytics {#aa-features}

| Funktion | [Allmän tillgänglighet](https://docs.adobe.com/content/help/sv-SE/analytics/landing/an-releases.html) – Måldatum | Beskrivning |
| -----------| ---------- |-------|
| Attribution IQ: [!UICONTROL Algorithmic Attribution] | 18 juni 2020 | I [!UICONTROL Algorithmic Attribution] modellen i [!UICONTROL Analysis Workspace] används statistiska tekniker för att dynamiskt fastställa den optimala kreditfördelningen för det valda måttet. [Läs mer...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/algorithmic.html) |
| Attribution IQ: Anpassade uppslagsfönster | 18 juni 2020 | Du kan nu konfigurera alla attribueringsmodeller i [!UICONTROL Attribution IQ] så att de inkluderar beröringspunkter från upp till 90 dagar före rapporteringsperioden. Detta ökar vanligen attribueringens exakthet för händelser som inträffar tidigt under rapporteringsperioden genom att redovisa interaktioner som inträffat under föregående månad(er). [Läs mer...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/attribution.html#lookback-windows) |
| Projektroller för delade [!UICONTROL Workspace] projekt | 18 juni 2020 | När du delar ett [!UICONTROL Workspace] projekt kan du nu placera mottagare i en av tre projektroller, beroende på vilken erfarenhet du vill att de ska ha: Redigera, Duplicera och Visa. [Läs mer...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Visa endast [!UICONTROL Workspace] projekt | 18 juni 2020 | [!UICONTROL Workspace] projekt kan _[!UICONTROL Can View]_bara delas med användare. När en Visa-mottagare öppnar det delade projektet får de en mer restriktiv projekterfarenhet utan vänster spår och begränsad interaktion.[Läs mer...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/view-only-projects.html) |
| Möjlighet att samredigera [!UICONTROL Workspace] projekt | 18 juni 2020 | Mottagare som läggs till i rollen kan spara över ett projekt som har delats med dem. _[!UICONTROL Can Edit]_Detta gäller både administratörer och icke-administratörer.[Läs mer...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Uppdaterad tom panel i [!UICONTROL Workspace] | 18 juni 2020 | Panelen Tom i innehåller [!UICONTROL Workspace] nu paneler och visualiseringar, vilket gör det enklare att välja det analysarbetsflöde som fungerar bäst för dig. |
| Första parts domäner är tillgängliga i Kinas domänkontrollant | 18 juni 2020 | Gör det möjligt för kunder med en `.cn` domän att begära en förstahandsdomän för användning i Mainland China. (Dokumentation finns vid köp av SKU för prestandaoptimering i Kina.) |
| Panelen Snabbinformation i [!UICONTROL Workspace] | 25 juni 2020 | Quick Insights provides guidance for non-analysts and new users of [!UICONTROL Analysis Workspace] to learn how to answer business questions quickly and easily. [Läs mer...](https://docs.adobe.com/content/help/sv-SE/analytics/analyze/analysis-workspace/panels/quickinsight.html) |
| [!UICONTROL Analytics for Target]-panel i [!UICONTROL Workspace] | 25 juni 2020 | The [!UICONTROL Analytics for Target] (A4T) panel lets you analyze your Adobe Target activities and experiences in [!UICONTROL Analysis Workspace]. [Learn more...](https://docs.adobe.com/content/help/sv-SE/analytics/analyze/analysis-workspace/panels/a4t-panel.html) |

### Nya funktioner i Customer Journey Analytics {#cust-journey}

| Funktion | [Allmän tillgänglighet](https://docs.adobe.com/content/help/sv-SE/analytics/landing/an-releases.html) – Måldatum | Beskrivning |
| -----------| ---------- |-----|
| Attribution IQ: [!UICONTROL Algorithmic Attribution] | 18 juni 2020 | I [!UICONTROL Algorithmic Attribution] modellen i [!UICONTROL Analysis Workspace] används statistiska tekniker för att dynamiskt fastställa den optimala kreditfördelningen för det valda måttet. [Läs mer...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/algorithmic.html) |
| Attribution IQ: Anpassade uppslagsfönster | 18 juni 2020 | Du kan nu konfigurera alla attribueringsmodeller i [!UICONTROL Attribution IQ] så att de inkluderar beröringspunkter från upp till 90 dagar före rapporteringsperioden. Detta ökar vanligen attribueringens exakthet för händelser som inträffar tidigt under rapporteringsperioden genom att redovisa interaktioner som inträffat under föregående månad(er). [Läs mer...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/attribution.html#lookback-windows) |
| Stöd för [!UICONTROL Anomaly Detection] | 18 juni 2020 | [!UICONTROL Anomaly Detection] innehåller en statistisk metod för att fastställa hur ett givet mätvärde har ändrats i förhållande till tidigare data. [Läs mer...](https://docs.adobe.com/content/help/sv-SE/analytics/analyze/analysis-workspace/virtual-analyst/anomaly-detection/anomaly-detection.html) |
| Projektroller för delade [!UICONTROL Workspace] projekt | 18 juni 2020 | När du delar ett [!UICONTROL Workspace] projekt kan du nu placera mottagare i en av tre projektroller, beroende på vilken erfarenhet du vill att de ska ha: Redigera, Duplicera och Visa. [Läs mer...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Visa endast [!UICONTROL Workspace] projekt | 18 juni 2020 | [!UICONTROL Workspace] projekt kan _[!UICONTROL Can View]_bara delas med användare. När en Visa-mottagare öppnar det delade projektet får de en mer restriktiv projekterfarenhet utan vänster spår och begränsad interaktion.[Läs mer...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/view-only-projects.html) |
| Möjlighet att samredigera [!UICONTROL Workspace] projekt | 18 juni 2020 | Mottagare som läggs till i rollen kan spara över ett projekt som har delats med dem. _[!UICONTROL Can Edit]_[Läs mer...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Panelen Snabbinformation i [!UICONTROL Workspace] | 25 juni 2020 | Quick Insights provides guidance for non-analysts and new users of [!UICONTROL Analysis Workspace] to learn how to answer business questions quickly and easily. [Läs mer...](https://docs.adobe.com/content/help/sv-SE/analytics/analyze/analysis-workspace/panels/quickinsight.html) |

### Nya funktioner i [!UICONTROL Media Analytics] {#media-aa}

Uppdaterat den: **29 maj 2020**

**Spårning av spelarstatus:** [!UICONTROL Media Analytics] kunder kan fånga tittarinteraktion under uppspelning med en standarduppsättning lösningsvariabler för helskärmsvisning, undertexter, ljud av, bild-i-bild och i fokus. Du kan också skapa anpassade spelarlägen. Variabler för spårning av spelarstatus är nu tillgängliga för rapportering i [!UICONTROL Analysis Workspace]. Den här funktionen kräver något av följande:

* Media [!DNL JavaScript] SDK 3.0 eller senare
* För användning med [!DNL Adobe Experience Platform] (AEP) SDK:
   * [!UICONTROL Media Analytics Extension] (för webb): [!UICONTROL Adobe Media Analytics] (3.x SDK) för ljud och video v1.0 eller senare
   * [!UICONTROL Media Analytics Extension] (för mobil): [!UICONTROL Adobe Media Analytics for Audio] och video v2.0 eller senare
* [!UICONTROL Media Collection]

Se [Om spårning av spelartillstånd](https://docs.adobe.com/content/help/sv-SE/media-analytics/using/player-state-tracking/player-state-overview.html).

### Korrigeringar i Adobe Analytics {#aa-fixes}

* Korrigerade ett problem som gjorde att segment med flerbytessökningar efter vissa rapportsviter inte matchade något. De kommer nu att matcha rätt strängar. (AN-220043)
* Korrigerade ett problem med [!UICONTROL Item Filter] om att [!UICONTROL Reports & Analytics] inte fungerar. (AN-206132)
* Fast långsam svarstid i [!UICONTROL Scheduled Projects] gränssnittet. (AN-214837)
* Ett problem med att Analytics Reporting API 2.0 genererade ett datumintervallfel har korrigerats. (AN-215087)
* Fixed a case in which the instance/visit/visitor wasn&#39;t being counted in the denominator for the [!UICONTROL Time Spent] metrics. Detta inträffar när en träff utan värde för dimensionen (t.ex. Pagename) följs i samma sekund. (AN-211074)
* Ett problem har korrigerats med användare som inte har åtkomst till projekt som delas med dem. [!UICONTROL Workspace] (AN-217561)
* Ett problem med att nycklar inte klassificerades av [!UICONTROL Classification Rule Builder]har korrigerats. (AN-221538)
* Ett problem med att inga användningsdata rapporterades har åtgärdats. [!UICONTROL Server Call Usage] (AN-210452)
* Korrigerade problem med publicerade Adobe Analytics-segment som saknar data i Audience Manager. (AN-220208, AN-220659)
* Ett problem har korrigerats med rapporter som visar data men [!UICONTROL Data Feeds] loggar som anger &quot;Inga data Warehouse-data&quot;. (AN-220784, AN-220858)
* Korrigerade problem som förhindrade start av [!UICONTROL Ad Hoc Analysis] från `experiencecloud.com` domänen. (AN-219680, AN-221629)
* Problem med att använda snabbtangenten &quot;Ctrl (eller Kommando) + C&quot; har korrigerats. (AN-221101, AN-221537)
* Ett problem med [!UICONTROL Activity Map] aktiveringssidan har korrigerats. (AN-222029, AN-221242)
* Ett problem har korrigerats där det inte gick att lägga till en kontaktpunkt mitt i en [!UICONTROL Fallout] visualisering. (AN-221648)

#### Övriga korrigeringar i Adobe Analytics

AN-218269; AN-218455; AN-218492; AN-219888; AN-220447; AN-220546; AN-220788; AN-220866; AN-221165; AN-221545; AN-221712; AN-221832; AN-221853; AN-222000; AN-222505; AN-222559

### Viktiga meddelanden för [!DNL Analytics]-administratörer {#aa-notices}

| Meddelande | Datum tillagt eller uppdaterat | Beskrivning |
| -----------| ---------- | ---------- |
| Migrering till den enhetliga produktdomänen | Datum för ikraftträdande: 28 maj 2020 | Övergången till en enhetlig produktdomän för Adobe Analytics, som började i januari 2020, slutfördes den 28 maj 2020. While Adobe Analytics works to remove all `omniture.com` domain references from its architecture, it is important to allowlist (formerly, allowlist) `omniture.com` as a third-party cookie. När den fullständiga arkitekturmigreringen är (snart) slutförd meddelar vi dig via versionsinformationen och det här steget behövs inte längre. [Här](https://helpx.adobe.com/se/analytics/kb/adobe-ip-addresses.html) är en fullständig lista över rekommenderade IP-adresser och domäner som du bör tillåta.<br>Om din organisation blockerar cookies från tredje part kan du kontakta kundtjänst för att få tillgång till Adobe Analytics igen. |
| Ny startsida för Adobe Analytics | Startdatum: 18 juni 2020 | Den 18 juni 2020 ändras standardlandningssidan för Adobe Analytics från [!UICONTROL Reports] till [!UICONTROL Workspace]. Den här ändringen sker för användare som inte tidigare har angett en anpassad landningssida. |
| Tredjepartsteknologi | 12 mars 2020 (giltighetsdatum) | Adobe Analytics har börjat utnyttja teknik från tredje part för funktionshantering och produktsupport. Följande URL:er bör läggas till i alla nödvändiga tillståndslistor för nätverkets brandvägg för att säkerställa fullständig funktionsåtkomst:<ul><li>Gainsight: https://esp.aptrinsic.com</li><li>LaunchDarkly: https://app.launchdarkly.com</li></ul> |
| Improved redundancy for [!UICONTROL Analysis Workspace] availability | 21 maj 2020 | In order to ensure availability of [!UICONTROL Analysis Workspace], we are adding a secondary CDN (Content Delivery Network) for improved redundancy. Följande URL:er ska läggas till i alla nödvändiga tillståndslistor för nätverkets brandvägg:<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul> |
| Ändra hur [!UICONTROL Entries/Exits] beräknas i [!UICONTROL Workspace] | 7 april 2020 | Från och med mars 2020, har vi ändrat hur värdet _Inga_ interagerar med [!UICONTROL Entries/Exits] i [!UICONTROL Analysis Workspace]. Eftersom du nu kan aktivera och inaktivera _Inga_ i [!UICONTROL Analysis Workspace] använder vi värdet _Inga_ efter första eller sista besökssidan i stället för före (för eVars). Anta till exempel att den första träffen för ett besök inte har ett värde för eVars, men att den andra träffen har det. I [!UICONTROL Reports & Analytics] visas den första träffen som _Ospecificerat_ för första besökssidan, men i [!UICONTROL Analysis Workspace] visas det som ett värde för den andra träffen. |
| **[!UICONTROL Dashboard Archive]** tas bort | 27 mars 2020 | Inställningen **[!UICONTROL View Archive]** under **[!UICONTROL Manage Dashboards]** i [!UICONTROL Reports & Analytics] är inte tillgänglig från och med oktober 2020. |
| Slutet av livscykeln – äldre API:er för Analytics | 9 januari 2020 | I november 2020 kommer följande äldre API-tjänster för Analytics att ha nått slutet av sina livscykler och avslutas. Aktuella integreringar som byggts med dessa tjänster kommer att sluta fungera. <ul><li>1.3 API:er för Analytics</li><li>1.4 API:er för SOAP Analytics</li><li>Äldre OAuth-autentisering (OAuth och JWT)</li></ul>Vi har tagit fram [vanliga frågor och svar om upphörande av äldre API:er](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) som kan hjälpa dig att få svar på frågor och ge vägledning om hur du går vidare. API-integrationer som använder dessa tjänster kan migrera till [1.4 Analytics REST-API:er](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) eller [2.0 Analytics API:er](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Äldre OAuth-konton kan migrera till ett [Adobe IO](https://console.adobe.io/home?mv=email) Analytics-integreringskonto som kan användas för att få tillgång till både 1.4 Analytics API:er och 2.0 Analytics API:er. |
| San Jose FTP-hantering upphör för London och Singapore | Juli 2020 | För kunder i London och Singapore stöder vi inte längre datahantering mellan London eller Singapore och datacentret [ftp.omniture.com](ftp://ftp.omniture.com/) i San Jose.<br/><ul><li>I London använder du [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>I Singapore använder du [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Ad Hoc Analysis upphör | 6 aug 2018 | Adobe har meddelat att man avser att dra tillbaka Ad Hoc Analysis. Ett slutdatum meddelas så snart det är tillgängligt. Mer information finns i [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

#### Nya kurser och självstudiekurser i Analytics {#tutorials-analytics}

Nya kurser, självstudiekurser och artiklar i Analytics och Customer Journey Analytics.

| Innehåll | Innehållstyp | Beskrivning |
| -----------| ---------- | ---------- | 
| [Komma igång med kundreseanalys för användare](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-U-1-2020.1) | Kurs | I den här kursen får du lära dig att använda kundreseanalys (CJA) för att analysera data från många olika datakällor. Du får lära dig om skillnaderna mellan Adobe Analytics och Customer Journey Analytics och hur data hanteras i CJA. Efter den här kursen bör ni kunna skapa och anpassa visualiseringar över flera kanaler för att få en ökad förståelse för era kunder. |
| [Komma igång med kundreseanalys för administratörer](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-A-1-2020.1) | Kurs | Lär dig hur du konfigurerar och använder [!UICONTROL Journey Orchestration]. Kursen omfattar de viktigaste begreppen och de konfigurationssteg som krävs för att kunna samordna en resa. Du får lära dig att skapa, publicera och rapportera och analysera dina orkestrerade resor. |
| [Getting Started with Customer Journey Analytics for Data Engineers](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-D-1-2020.1) | Kurs | I den här kursen får du lära dig mer om de data som kommer in i kundreseanalysen och hur de påverkar analytikernas rapporter. Kursen bygger på dina allmänna kunskaper om Adobe Experience Platform. |
| [Komma igång med kundreseanalys för administratörer](https://video.tv.adobe.com/v/34349?captions=swe) | Videosjälvstudiekurs | En introduktionsvideo till kundreseanalys för administratörer. |
| [Implementering av guidad analys](https://experienceleague.adobe.com/?recommended=Analytics-D-1-2019.1) | Kurs | I den här kursen får du lära dig hur du kommer igång med att implementera Adobe Analytics, förstå Analytics-koncept, skapa en plan och implementera Adobe Analytics med Experience Platform Launch. |
| [Adobe Analytics Fundamentals for Leaders](https://experienceleague.adobe.com/?recommended=Analytics-L-1-2020.1) | Kurs | I den här kursen får du lära dig mer om grunderna i Analytics och hur Analysis Workspace kan förändra er verksamhet. Läs om hur du kan få insikter med Adobe Sensei, få kundutlåtanden och se vad branschexperterna tycker på Summit 2019. |
| [Komma igång med Analysis Workspace](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2020.1.workspace) | Kurs | Lär dig hur du kommer igång med Analysis Workspace. Bygg ditt första projekt, lär dig definiera datumintervall, tillämpa segment och dela och samarbeta i projekt. |
| [Adobe Analytics-instrumentpaneler i Styrkort](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/additional-tools/analytics-dashboards/adobe-analytics-dashboards-scorecard-builder.html) | Videosjälvstudiekurs | I den här videon får du lära dig hur du skapar och delar [!UICONTROL Scorecards] i [!UICONTROL Analysis Workspace] som ska visas på Adobe Analytics-instrumentpaneler (mobilapp). |
| [Adobe Analytics-instrumentpaneler i appupplevelsen](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/additional-tools/analytics-dashboards/adobe-analytics-dashboards-in-app-experience.html) | Videosjälvstudiekurs | I den här videon får du lära dig hur du använder Adobe Analytics-instrumentpaneler (mobilapp) för att komma åt och visa [!UICONTROL Scorecards] som skapats av eller delats med dig. |

#### Hjälpresurser för Analytics

* [Adobe Analytics självstudiekurser](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Adobe Analytics – produktdokumentation](https://docs.adobe.com/content/help/sv-SE/analytics/landing/home.html)

## ![Ikon](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Nya funktioner, korrigeringar, dokumentation och självstudiekurser för Audience Manager.

Updated **June 10, 2020**

### Uppdaterat användargränssnitt

Audience Manager uppdaterar domänen och sidhuvudet för att skapa en enhetlig och förbättrad upplevelse i alla Experience Cloud-program.

* Enklare att växla mellan olika organisationer eller till ett annat program.
* Förbättrad användarhjälp, inklusive aktuella artiklar och sammanhangsberoende videoklipp på Hjälp-menyn.
* Möjlighet att ge feedback om Experience Platform och supportärenden.
* Ett nytt och enklare URL-mönster. Uppdatera dina bokmärken till den nya adressen: `experience.adobe.com/audience-manager`.

Uppdateringarna gäller bara användare som loggar in med Adobe ID. Mer information om hur du byter till Adobe ID-inloggning finns i [Hantera Experience Cloud-användare och -produkter](https://docs.adobe.com/content/help/sv-SE/core-services/interface/manage-users-and-products/admin-getting-started.html).

### Nya funktioner och korrigeringar i Adobe Audience Manager

| Funktion | Beskrivning |
| -----------| ---------- |  
| [Plugin-programmet Audience Manager för IAB TCF v2.0 ](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/consent-management/aam-iab-plugin.html) | Adobe fortsätter att fokusera på sekretess via design och uppgraderar nu Audience Manager-pluginen för IAB TCF till IAB Transparency &amp; Consent Framework (TCF) version 2.0 från och med 10 juni 2020. Kunder som har implementerat Audience Manager Plug-in för IAB TCF måste uppgradera till version 2.0 senast 15 augusti 2020 för att kunna fortsätta använda funktionen. Efter 15 augusti 2020 kommer version 1.1 att bli inaktuell och inte längre stödjas. |

**Korrigeringar**

* Uppdaterade formuläret [!UICONTROL Audience Marketplace Terms & Conditions] för att återspegla rättsliga krav inom specifika områden. (AAM-54518)
* Korrigerade ett problem där åtkomsten till [!UICONTROL Traits] sidan från bokmärken resulterade i ett 404-fel. (AAM-54768)
* Korrigerade ett problem där API:t för måluppdatering skulle få timeout vid hämtning [!UICONTROL Algorithmic Models]. (AAM-54342)
* Användarna kan nu se en noggrannhetsindikator för [!UICONTROL Smart Personas]modellklassificering. (AAM-54847)
* Ett problem har korrigerats där ett uttryck skulle tas bort om du tryckte på Retur efter att ha lagt till det i stället för att det sparades. (AAM-54210)
* Ett problem har korrigerats där anrop till metoden GET för [!UICONTROL Traits] API skulle misslyckas för användare som inte hade behörigheten VIEW_MODELS. (AAM-53104)
* Ett problem har korrigerats där användare inte kunde ta bort [!UICONTROL Algorithmic Models] innehållet [!UICONTROL Folder Traits]. (AAM-50192)
* Uttryck med långa drag radbryts nu över flera rader. (AAM-54972)
* Ett problem har korrigerats där användare med skrivskyddad behörighet kunde se knappen på sidorna med algoritmiska modeller. [!UICONTROL Create New] (AAM-54889)
* Korrigerade ett problem som fick inläsningsindikatorn [!UICONTROL General] och [!UICONTROL Trend] rapporten att fortsätta snurra efter att CSV-hämtningen var klar. (AAM-54571)
* Ett problem har korrigerats där användare inte kunde lägga till gruppegenskaper i segment i [!UICONTROL Segment Builder]. (AAM-55033)
* Flera tillgänglighetsförbättringar i hela gränssnittet. (AAM-47269, AAM-48966, AAM-48976, AAM-49369, AAM-49023, AAM-49042).

### Nya kurser och självstudiekurser i Audience Manager {#tutorials-aam}

| Innehåll | Innehållstyp | Beskrivning |
| -----------| ---------- | ---------- |  
| [Introduktion till Audience Manager](https://experienceleague.adobe.com/?recommended=AudienceManager-U-1-2020.1) | Kurs | Kursen lär dig grunderna i Audience Manager och de problem du kan lösa med hjälp av den. Lär dig mer om vanliga användningsområden och viktiga termer och koncept i Audience Manager. |
| [Introduktion till identitet i Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/introduction-to-identity-in-audience-manager.html) | Videosjälvstudiekurs | Läs om hur Adobe Audience Manager hanterar identitet, inklusive interna profiler och profilsammanslagning samt ID-synkronisering med partners. |
| [Understanding and Configuring the LinkedIn People-Based Destination](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/data-activation/people-based-destinations/understanding-and-configuring-the-linkedin-pbd.html) | Kurs | I den här videon får du hjälp med att skapa ett personbaserat mål för LinkedIn. Det bygger på ytterligare videor och dokumentation om personbaserade destinationer. |
| [Skapa regelbaserade egenskaper](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/creating-rule-based-traits.html) | Videosjälvstudiekurs | Lär dig hur du använder [!UICONTROL Trait Builder] i Audience Manager-gränssnittet för att skapa en regelbaserad trait som gör att du kan samla in realtidsaktivitet i Audience Manager-profiler. |
| [Aktivera plugin-programmet Audience Manager för IAB TCF 2.0](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/setup-and-admin/data-governance-and-privacy/iab-tcf-support.html#enabling-iab-tcf) | Videosjälvstudiekurs | Lär dig hur du aktiverar plugin-programmet Audience Manager för IAB TCF. Det är enkelt att aktivera det här plugin-programmet om du använder Adobe Experience Platform Launch. |
| [Demo av Audience Manager Plugin för IAB TCF 2.0](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/setup-and-admin/data-governance-and-privacy/iab-tcf-support.html#demo) | Videosjälvstudiekurs | I den här videon ser du hur cookies och fyrar från Experience Cloud ID-tjänsten och lösningarna påverkas av IAB:s val av användare. |

## ![Ikon](/assets/aem.png) för Adobe Experience Manager {#aem}

Nya funktioner, korrigeringar och uppdateringar i Adobe Experience Manager (AEM). Adobe rekommenderar att kunder med lokala distributioner driftsätter de senaste korrigeringarna för bättre stabilitet, säkerhet och prestanda.

### Uppdateringar

* **AEM 6.5.5.0**

   AEM 6.5, Service Pack 5 (6.5.5.0 släppt 4 juni 2020) är en viktig uppdatering som innehåller nya funktioner, viktiga förbättringar som kunderna efterfrågat samt prestanda, stabilitet, säkerhetsförbättringar som släppts sedan den allmänna tillgängligheten av AEM 6.5 i april 2019.

   * [Versionsinformation](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
   * [AEM Forms-releaser](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.8.1**

   AEM 6.4, Service Pack 8, Cumulative Fix Pack (6.4.8.1 släppt 4 juni 2020) är en viktig uppdatering som innehåller flera interna korrigeringar och kundkorrigeringar sedan den allmänna tillgängligheten för AEM 6.4, Service Pack 8 (6.4.8.0) i mars 2020.

   * [Versionsinformation](https://docs.adobe.com/content/help/en/experience-manager-64/release-notes/cfp-release-notes.html)
   * [AEM Forms-releaser](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

### Självhjälp

* **AEM as a Cloud Service**

   Nyheter i AEM som molntjänst?

   Högdagrarna är:

   * AEM Sites Commerce Integration Framework.
   * Förbättrade smarta taggar och nya funktioner för guidad utbildning i användargränssnittet.
   * Stöd för Adobe Asset Link för Adobe Xd.
   * Stöd för AEM Assets Dynamic Media 3D.
   * Nya självbetjäningsförbättringar minskar beroendet av Adobe för sandlådeåtgärder.
      * Förbättrat stöd för självbetjäningssandlådor i Cloud Manager gör att berättigade användare kan ta bort alla miljöer i en sandlåda och få krediter.
      * Sandlådemiljöer med automatisk viloläge&quot;förbereds&quot; automatiskt i sandlådor efter en tids inaktivitet. Kunderna kan aktivt utlösa&quot;avviloläge&quot;.
   * Övergångsverktyg som stöder molnacceleration
   Med målet att minska tiden och kostnaden för övergången från lokal till molntjänst lanserades två övergångsverktyg den här månaden. Dessa verktyg är utformade för att automatisera några av de viktigaste uppgifterna under övergångsprocessen och därmed minska den totala arbetsinsatsen. .

   1. [Med verktyget](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/using-content-transfer-tool.html) Innehållsöverföring (tillgängligt på SD) effektiviseras innehållsöverföringsaktiviteten och blir skalbar. Med ett användarvänligt användargränssnitt är verktyget självbetjäning för befintliga kunder och partners (på plats/AMS) som går över till AEM som en molntjänst.
   1. [AMS Dispatcher Converter](https://github.com/adobe/aem-cloud-service-dispatcher-converter) (Open-source) för att automatisera konvertering av AMS Dispatcher-konfigurationer till Cloud Service Dispatcher-konfigurationer.
   [Versionsinformation för AEM som molntjänst 2020.6.0](https://docs.adobe.com/content/help/sv-SE/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)

   Övergångsverktyg:

   https://github.com/adobe/aem-cloud-service-dispatcher-converter

   https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/using-content-transfer-tool.html

* **Kärnkomponenter**

   Core Components version 2.9.0 introducerar integrering med [Adobe Client Data Layer](https://github.com/adobe/adobe-client-data-layer) och en ny Progress Bar-komponent och är nu tillgänglig tillsammans med [redigeringsdokumentation](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/introduction.html) och [utvecklarinformation samt nedladdning av projekt som finns på GitHub](https://github.com/adobe/aem-core-wcm-components).

* **Gå till AEM som molntjänst**

   [När du går över till AEM som molntjänst](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/home.html) beskrivs den rekommenderade övergångsresan för en befintlig AEM-kund som går över till molntjänsten. Målet med denna dokumentation är att förse kunderna med information, vägledning och bästa metoder för att hjälpa dem att förbereda sig för övergången och göra resan strukturerad och förutsägbar.

   Ett av verktygen för molnövergång - innehållsöverföring släpptes. [Verktyget](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/overview-content-transfer-tool.html) för innehållsöverföring har utvecklats av Adobe och kan användas för att flytta befintligt innehåll från en AEM-källinstans (lokalt eller AMS) till målinstansen av AEM Cloud-tjänsten.

   Ett av verktygen för kodkorrigering - AEM Dispatcher Converter släpptes. [AEM Dispatcher Converter](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/refactoring-tools/dispatcher-transformation-utility-tools.html) är ett verktyg för konvertering av befintliga AEM Dispatcher-konfigurationer till AEM som en konfiguration för Cloud Service Dispatcher och är tillgängligt.

* **Tillgänglighet och WCAG 2.1-riktlinjerna**

   Uppdateringar i förhållande till WCAG 2.1-riktlinjerna:

   * [Adobe Experience Manager as a Cloud Service  och riktlinjerna för webbtillgänglighet](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/accessibility/web-accessibility.html)
   * [En snabbguide till WCAG 2.1](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/accessibility/quick-guide-wcag.html)
   * [Skapa tillgängligt innehåll (WCAG 2.1-överensstämmelse)](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/sites/authoring/fundamentals/accessible-content.html)

* **AEM-nyhetsbrev**

   AEM Newsletter från Experience League är utformat för att hjälpa er att komma igång med AEM så att ni kan börja inse värdet direkt. Här är det senaste nyhetsbrevet:

   * [Volym 31](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.31.html): Experience Manager är nu tillgängligt som en molntjänst.
   * [Prenumerera](https://adobeeventsonline.com/AEM/2017/NL/Optin/) på nyhetsbrevet Experience Insider.
   * Arkiverade nyhetsbrev finns i avsnittet med [AEM-resurser](https://helpx.adobe.com/se/support/experience-manager/6-5.html) på sidan Utbildning och support för Adobe Experience Manager 6.5.

### **Community**

* **AEM Community-diskussion**

   Nu kan du se alla AEM-meddelanden och intressanta referenser till interna och externa bloggare på ett och samma ställe. Se avsnittet [Diskussion i AEM Community.](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/bd-p/adobe-experience-manager-discussions)

### Nya Experience Manager-kurser och självstudiekurser

| Innehåll | Innehållstyp | Beskrivning |
| -----------| ---------- | ---------- |
| [Komma igång med Adobe Asset Link för företagsanvändare](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.asset.link) | Kurs | Här får du lära dig hur du använder funktionerna i Adobe Asset Link för att understödja din kreativa design med innehåll som lagras i Adobe Experience Manager Assets. Kursen omfattar allt från hur du startar en Adobe-länk för resurser, grundläggande åtgärder för resurser, sök- och bläddringsalternativ samt hur du samarbetar effektivt med andra användare. |
| [Komma igång med AEM Assets för företagsanvändare](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.assets) | Kurs | Lär dig hur du kommer igång med AEM Assets för företagsanvändare. Utforska grunderna i AEM Assets, samarbetsfunktioner, sökning, sortering av resurser och nedladdning av resurser och deras renderingar. |
| [Komma igång med AEM Sites för företagsanvändare](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.sites) | Kurs | Lär dig hur du använder AEM Sites kärnfunktioner för att hantera organisationens webbsidor. Kursen omfattar allt från en introduktion till AEM Sites, grundläggande redigeringskoncept, avancerade redigeringsfunktioner och funktioner för sidhantering. |
| [AEM-projektstruktur](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/developing/aem-project-content-package-structure.html) | Artikel | Beskriver de ändringar som krävs i Adobe Experience Manager Maven-projekt så att de är AEM Cloud-kompatibla. |
| [Sling Models](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/osgi-web-consoles.html#sling-models) | Videosjälvstudiekurs | Lär dig mer om felsökning av AEM som en molntjänst-SDK:s lokala snabbstart med webbkonsolen Sling Models. |
| [Komponenter i AEM Web Console](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/osgi-web-consoles.html#components) | Videosjälvstudiekurs | Lär dig mer om felsökning av AEM som en molntjänst-SDK:s lokala snabbstart med webbkonsolen Komponenter. |
| [Felsöka AEM SDK:s lokala snabbstart med hjälp av loggar](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/logs.html) | Videosjälvstudiekurs | Lär dig mer om felsökning av AEM som en molntjänst-SDK:s lokala snabbstart med webbkonsolen Bundles. |
| [Fjärrfelsökning av AEM som lokal snabbstart för en molntjänst-SDK](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/remote-debugging.html) | Videosjälvstudiekurs | Lär dig mer om fjärrfelsökning i Java från din utvecklingsmiljö, så att du kan stega igenom direktkörning av kod i AEM för att förstå det exakta körningsflödet. |
| [Inställningar för smarta taggar](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/metadata/smart-tags-technical-video-setup.html) | Videosjälvstudiekurs | Stegvisa instruktioner för att integrera Adobe Experience Manager (AEM) med Smart Content Service med hjälp av Adobe I/O. |
| [Batchgenerering av dokument](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/interactive-communications/batch-generation-interactive-communications.html) | Artikel | Lär dig hur du använder API:t Batch för att skapa flera interaktiva dokument från en mall. |
| [Skapa dokument för utskriftskanal i AEM-formulär](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/ic-print-channel-tutorial/introduction.html) | Artikel | Lär dig stegen som behövs för att skapa en interaktiv kommunikation för tryckkanalen. |
| [Åtkomst till Adobe Asset Link](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/launch-adobe-asset-link.html) | Videosjälvstudiekurs | Lär dig hur du får åtkomst till innehåll som lagras i Adobe Experience Manager Assets (AEM Assets), utan att lämna de Creative Cloud-datorprogram du är mest bekant med. |
| [Översikt över panelen Resurslänk](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/panel-overview.html) | Videosjälvstudiekurs | Med Adobe Asset Link kan kreativa användare bläddra bland, söka efter, checka ut och checka in resurser som lagrats i AEM Resurser via panelen i appen i InDesign, Photoshop och Illustrator. Få en introduktion till användargränssnittet och funktionerna i panelen Adobe Asset Link. |
| [Resurssökning](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/asset-search.html) | Videosjälvstudiekurs | Creative-användare kan söka efter resurser som lagras i AEM Resurser med hjälp av nyckelord eller söka på en viss plats. |
| [Filversionshantering och kommentarer](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/file-versioning-and-comments.html) | Videosjälvstudiekurs | Med Adobe Asset Link-panelen kan du komma åt filinformation för resurser i AEM Resurser, som miniatyrbilder, grundläggande metadata och versioner från panelen. |
| [Checka in-utcheckning](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/check-in-check-out.html) | Videosjälvstudiekurs | Med Adobe Asset kan du checka ut AEM Assets direkt från det kreativa program du arbetar i och du kan börja redigera direkt. |
| [För återgivning endast för placering för AEM-resurser](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/for-placement-only.html) | Videosjälvstudiekurs | Lär dig hur du skapar och använder en FPO-återgivning (For Placement Only) för AEM-resurser. |
| [Montera kopia](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/place-copy.html) | Videosjälvstudiekurs | Lär dig hur du använder resurser från AEM Resurser med funktionen Montera kopia. |
| [Hämta och överföra](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/download-and-upload.html) | Videosjälvstudiekurs | Lär dig hur du hämtar och överför resursfiler från och till AEM Resurser med hjälp av panelen Resurslänk. |
| [Filer och samlingar](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/files-and-collections.html) | Videosjälvstudiekurs | Lär dig hur du snabbt och enkelt kommer åt AEM Resurser och samlingar från panelen Resurslänk. |
| [Hämta](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/sharing/download.html) | Videosjälvstudiekurs | Lär dig hur du hämtar resurser och deras återgivningar till din lokala dator för användning och delning. |

### Ytterligare resurser

* [AEM as a Cloud Service](https://docs.adobe.com/content/help/sv-SE/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 – startsida för utbildning och support](https://helpx.adobe.com/se/support/experience-manager/6-5.html)
* [AEM 6.4 – startsida för utbildning och support](https://helpx.adobe.com/se/support/experience-manager/6-4.html)
* [AEM 6.3 – startsida för utbildning och support](https://helpx.adobe.com/se/support/experience-manager/6-3.html)
* [AEM 6.2 – startsida för utbildning och support](https://helpx.adobe.com/se/support/experience-manager/6-2.html)
* [Användarhandbok för Cloud Manager](https://helpx.adobe.com/se/experience-manager/cloud-manager/user-guide.html)
* [Äldre versioner av AEM-dokumentation](https://helpx.adobe.com/se/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic – startsida för hjälp](https://docs.adobe.com/content/help/sv-SE/dynamic-media-classic/using/home.html)
* [Versionsinformation för Dynamic Media](https://docs.adobe.com/content/help/en/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Versionsinformation för Livefyre](https://docs.adobe.com/content/help/en/livefyre/using/release-notes/c-rn.html)

## ![Ikon](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign är ett intuitivt och automatiserat sätt att leverera personliga meddelanden i alla marknadsföringskanaler, både online och offline. Nu kan ni förutse vad era kunder vill ha med upplevelser som bestäms av deras vanor och önskemål.

### Campaign Standard

#### Nya kurser och självstudiekurser i Campaign Standard

| Innehåll | Innehållstyp | Beskrivning |
| -----------| ---------- | ---------- |  
| [Komma igång med Adobe Campaign Standard för företagsanvändare](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.standard) | Kurs | Lär dig navigera i gränssnittet, arbeta med leveranser och skapa och hantera mottagardata. |

### Campaign Classic

#### Senaste versionen

[Adobe Campaign Classic 20.2](https://docs.adobe.com/content/help/sv-SE/campaign-classic/using/release-notes/latest-release.html)

#### Självstudiekurser för Campaign Classic

| Innehåll | Innehållstyp | Beskrivning |
| -----------| ---------- | ---------- |  
| [Installera och konfigurera Adobe Campaign-klienten](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/install-and-setup-the-adobe-campaign-client.html) | Videosjälvstudiekurs | Lär dig hur du hämtar och installerar Adobe Campaign-klientkonsolen, skapar och hanterar anslutningar till flera miljöer och verifierar åtkomst till Adobe Campaign-klientkonsolen. |

### Campaign Control Panel

| Funktion | Beskrivning |
| -----------| ---------- |  
| Övervakning av aktiva profiler | Med Kontrollpanelen kan du övervaka den aktiva profilanvändningen för var och en av dina Campaign-instanser. Den här funktionen är i betaversion och tillgänglig för kunder som har AWS som värd från Campaign Standard 10368-versionen och Campaign Classic 8931-versionen. [Läs mer](https://docs.adobe.com/content/help/en/control-panel/using/performance-monitoring/active-profiles-monitoring.html) |

### Hjälpresurser för Campaign

* Adobe Campaign Standard: [Hjälpcenter](https://docs.adobe.com/content/help/sv-SE/campaign-standard/using/campaign-standard-home.html) – [Versionsinformation](https://docs.adobe.com/content/help/sv-SE/campaign-standard/using/release-notes/release-notes.html) – [Instruktionsvideor](https://docs.adobe.com/content/help/sv-SE/campaign-standard-learn/tutorials/overview.html) – [Versionsplanering](https://docs.adobe.com/content/help/sv-SE/campaign-standard/using/release-notes/release-planning.html) – [Senaste dokumentationsuppdateringar](https://docs.adobe.com/content/help/sv-SE/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Hjälpcenter](https://docs.adobe.com/content/help/sv-SE/campaign-classic/using/campaign-classic-home.html) – [Versionsinformation](https://docs.adobe.com/content/help/sv-SE/campaign-classic/using/release-notes/latest-release.html) – [Instruktionsvideor](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html) – [Senaste dokumentationsuppdateringar](https://docs.adobe.com/content/help/sv-SE/campaign-classic/using/documentation-updates.html)
* Kontrollpanelen för Adobe Campaign: [Dokumentation](https://docs.adobe.com/content/help/sv-SE/control-panel/using/control-panel-home.html) – [Versionsinformation](https://docs.adobe.com/content/help/sv-SE/control-panel/using/release-notes.html) - Instruktionsvideor för [Campaign Standard](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html) / [Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html)

## ![Ikon](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Updated **June 3, 2020**

* [Nya funktioner i Advertising Cloud DSP](#adcloud-dsp)
* [Nya funktioner i Advertising Cloud Search](#adcloud-search)

### Nya funktioner i Advertising Cloud DSP {#adcloud-dsp}

| Funktion | Beskrivning |
| -----------| ---------- |
| [!UICONTROL Campaign] Start | (3 juni) Det finns nya paketeringsvärden på kampanjnivå som baseras på den kampanjbudget och förflutna tid. |
| Placeringsprognos | (3 juni) För CTV- och videomaterial med optimering på placeringsnivå innehåller placeringsinställningarna nu prognoser för flera annonslängder (15 sek och 30 sek). De innehåller även prognoser för både VAST- och VPAID-lager. |
| CPA/ROAS-optimering | (20 maj-utgåvan) Kampanjcheferna behöver inte längre begränsa antalet nya placeringar i paket för att förhindra överbeläggning av budgeten. Praktiktjänstgöring får nu en dynamisk budgettilldelning baserat på deras prestanda för CPM eller CPA/ROAS. |

### Nya funktioner i [!UICONTROL Advertising Cloud Search] {#adcloud-search}

| Funktion | Beskrivning |
| -----------| ---------- |
| [!UICONTROL Campaigns] | Microsoft Advertising (tidigare Bing Ads) tar bort genomsnittliga positionsvärden efter den 30 september 2020. Med början den 11 juli kommer positionsbaserade begränsningar att ignoreras och positionsbaserade villkor i alla typer av begränsningar kommer också att ignoreras. |
| [!UICONTROL Advertising Insights] | (13 juni) Följande insikter har tagits bort:<br/><br/><ul><li>Prestanda för målgruppsmål (den nyare versionen)</li><li>Historiska prestanda (den nyare versionen)</li><li>Matcha typ (den nyare versionen)</li><li>Granskning av inställningar (den nyare versionen)</li><li>Portfolio för-post (äldre)</li></ul><br/>De återstående insikterna är äldre versioner och etiketten _Äldre_ har tagits bort från namnen. Dessutom togs Live-/redigeringslägena bort. |

## ![Ikon](/assets/magento.png) [!DNL Magento] {#magento}

Versionsinformation om Magento finns i:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Ikon](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

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
