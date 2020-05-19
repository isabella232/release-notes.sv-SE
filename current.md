---
title: Versionsinformation om Adobe Experience Cloud
description: Mall för versionsinformation om Experience Cloud
doc-type: release notes
last-update: May 2020
author: mfrei
translation-type: tm+mt
source-git-commit: e10656f2a2d2180295c61b7aad9e75391e23ccbd
workflow-type: tm+mt
source-wordcount: '4601'
ht-degree: 32%

---


# Tidig åtkomst - Versionsinformation om Adobe Experience Cloud - maj 2020

![Banderoll](/assets/experience-cloud-banner-3.png)

Den här sidan innehåller nya funktioner, korrigeringar och viktiga meddelanden i [!DNL Adobe Experience Cloud]. Utgivningsdatum för lösningen kan variera. Kolla regelbundet in de senaste uppdateringarna.

>[!IMPORTANT]
>
>This page contains pre-release content and is subject to change before May 21, 2020. Ny information som publiceras därefter kommer att noteras tillsammans med datumet som läggs till.

>[!NOTE]
>
>Prenumerera på [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) om du vill få meddelanden via e-post om kommande versioner.

**Releasedatum: Maj 2020**

Senaste uppdatering: **19 maj 2020**

* [Adobe System Status](#status)
* [Experience Cloud-gränssnittet](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (länkar till Targets hjälpsida)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/se/primetime/user-guide.html) (länkar till Primetimes hjälpsida)

Behöver du hjälp? Besök [[!DNL Adobe Experience League]](https://experienceleague.adobe.com/#home) för att hitta kurser, teknisk dokumentation, snabba svar, communityinsikter och lärarledd utbildning från Adobe.

## ![Ikon för ](/assets/adobe.png)Adobe System Status {#status}

[!UICONTROL Adobe System Status] ger detaljerad information, statusuppdateringar och e-postmeddelanden om Adobe-molnprodukter och -tjänster, driftstopp, avbrott och underhållshändelser. Kolla in det på [status.adobe.com](https://status.adobe.com/).

Releasedatum: **21 maj 2020**

**Nyheter**

* Med ditt Adobe ID kan du prenumerera på händelseaviseringar med mer information ända ned på produkt- och tilläggsnivå. För att du snabbare ska kunna konfigurera din prenumeration rekommenderar självprenumerationsprocessen nu ett urval av produkter och erbjudanden baserat på dina produkträttigheter. Detta bör minska antalet e-postmeddelanden du får och leverera mer relevanta meddelanden i inkorgen. Kom igång på [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nya funktioner och förbättringar som är tillgängliga nu**

| Funktion | Beskrivning |
| -----------| ---------- |
| Förbättrad användarupplevelse för prenumerationer och meddelanden | <ul><li>[!DNL Marketo Engage] de lokala platserna filtreras nu baserat på den lista med produkterbjudanden som valts.</li><li>[!DNL Marketo Engage] e-postmeddelanden är relevanta för användarens region, plats och miljöinställningar.</li></ul> |
| Bekräftelse av händelseprenumeration | <ul><li>Du kan nu få en bekräftelse via e-post när du prenumererar på pågående uppdateringar för en enstaka händelse.</li></ul> |
| Förbättrad global navigeringsanvändbarhet | <ul><li>Enhetlig användarupplevelse med `Adobe.com` den översta navigeringsmenyn.</li></ul> |

## ![Ikonen i](/assets/ec_appicon_24.png) Experience Cloud-gränssnittet {#ecloud}

Allmänna uppdateringar av Experience Cloud-gränssnittet.

**Enhetlig produktdomän**

Adobe har uppdaterat domänen och gränssnittshuvudet för att göra alla Experience Cloud-program enhetliga och förbättra er upplevelse. Dessa förbättringar är utformade för att förenkla upplevelsen på små, men viktiga sätt. Dessa förbättringar påverkar inte dina aktuella arbetsflöden.

Bland uppdateringarna finns:

* Nya program-URL:er: `experience.adobe.com/<application name>`:
   * Alla produkter kommer så småningom att använda det här URL-mönstret. Titta efter nya URL:er som börjar gälla under månaden.
   * Stöd för webbläsare: De webbläsare som stöds är [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] och [!DNL Opera] (de senaste versionerna). **Obs!** Trots att Experience Cloud-gränssnittet har stöd för dessa webbläsare kanske inte enskilda program har stöd för alla webbläsare. ([Analytics](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html) har till exempel inte stöd för [!DNL Opera] och [Target](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html) har inte stöd för [!DNL Safari].)
   * ([!DNL Safari] endast) Domänändringen kan orsaka cookie-problem i [!DNL Safari]. Om du avmarkerar _Förhindra spårning över webbplatser_ i [!DNL Safari] Sekretessinställningar aktiveras cookies i domäner (och alla upplevelser på olika webbplatser) och Experience Cloud kan fungera i den nya domänen.
* Enklare att växla mellan olika organisationer eller till ett annat program.
* Förbättrad produkthjälp: [!UICONTROL Experience League] är integrerat i produkten så att en hjälpsökning även visar resultat från communityforum och videoinnehåll. Den här ändringen gör det enklare att komma åt mer innehåll och hjälper dig att få ut mesta möjliga av Experience Cloud. Dessutom kan du klicka på **[!UICONTROL Help]** > **[!UICONTROL Feedback]** om du vill rapportera problem eller dela med dig av dina idéer till Adobe.

Följande program använder den nya domänen experience.adobe.com:

| Program eller tjänst | Domän |
| -----------| ---------- |
| Experience Clouds hemsida | `experience.adobe.com/home` |
| Adobe Target | `experience.adobe.com/target` |
| Adobe Audience Manager | `experience.adobe.com/audience-manager` |
| Adobe Launch | `experience.adobe.com/launch` |
| Adobe Experience Platform | `experience.adobe.com/platform` |
| Resehantering | `experience.adobe.com/journeys` |
| Customer Journey Analytics | `experience.adobe.com/platform/analytics` |
| Kontrollpanelen för Adobe Campaign | `experience.adobe.com/controlpanel` |
| Cloud Manager | `experience.adobe.com/cloud-manager` |
| Platstjänst | `experience.adobe.com/places` |
| Programvarudistribution | `experience.adobe.com/downloads` |
| Admin Tool (beta) | `experience.adobe.com/admin` |

## ![Ikon för](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Versionsinformation för [!DNL Experience Platform,] inklusive [!DNL Experience Platform Launch,] [!UICONTROL Journey Orchestration], [!UICONTROL Offers], [!UICONTROL People], [!UICONTROL Places], [!UICONTROL Mobile Services] och säkerhetsbulletiner.

### Gränssnittsförbättringar

Uppdaterat: **15 maj 2020**

[!DNL Adobe Experience Platform] släpper uppdateringar i domän- och huvudfältet för att förbättra din upplevelse och göra den enhetlig med andra Experience Cloud-program. Bland uppdateringarna finns:

* Enklare att växla mellan olika organisationer eller till ett annat program.
* Förbättrad användarhjälp, inklusive artiklar och sammanhangsberoende dokumentation på Hjälp-menyn.
* Möjlighet att ge feedback om Experience Platform och supportärenden.

See [Experience Platform release notes](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md) for more information.

### Kundattribut - ny dokumentation

Uppdaterat: **15 maj 2020**

* [Kundattribut för CCPA](https://docs.adobe.com/content/help/en/core-services/interface/customer-attributes/ccpa.html) (California Consumer Privacy Act)
* [Kundattribut för GDPR](https://docs.adobe.com/content/help/en/core-services/interface/customer-attributes/gdpr.html) (General Data Protection Regulation)

### Journey Orchestration {#journey}

Med Adobe Experience Platform kan ni orkestrera enskilda kundresor i stor skala över olika upplevelsekanaler genom att intelligent förutse varje enskild individs behov i realtid, oavsett vart resan bär.

* [Dokumentation](https://docs.adobe.com/content/help/en/journeys/using/journey-orchestration-home.html)
* [Versionsinformation](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html)
* [Instruktionsvideor](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Ytterligare versionsinformation om Experience Platform

* [Versionsinformation om Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html)
* [Versionsinformation om Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Säkerhetsbulletiner och rekommendationer](https://helpx.adobe.com/se/security.html) (alla Adobe-produkter)

## ![Ikon](/assets/analytics.png) [!DNL Analytics] {#analytics}

* [Nya funktioner i kundreseanalys](#cust-journey)
* [Nya funktioner i Adobe Analytics](#aa-features)
* [Viktiga meddelanden för Analytics-administratörer](#aa-notices)
* [AppMeasurement](#appm)
* [Självstudiekurser för nya Analytics](#tutorials-analytics)

### Nya funktioner i kundreseanalys {#cust-journey}

| Funktion | Beskrivning |
| -----------| ---------- |
| [!UICONTROL Customer Journey Analytics]: Global tillgänglighet | Gör [!UICONTROL Customer Journey Analytics] tillgänglig för kunder i EMEA och APAC. |
| [!UICONTROL Customer Journey Analytics]: Stöd för [!UICONTROL Adobe Experience Platform Sandboxes] | Gör att du kan välja [!UICONTROL Adobe Experience Platform Sandboxes] att bygga CJA-anslutningar från. [Läs mer...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-connections/create-connection.html) |

### Nya funktioner i Adobe Analytics {#aa-features}

<!-- Bulk Ingest: Enables you to ingest batches of Analytics data. Useful for server-side and offline data. Learn more...
First-Party Domains Available in China RDC: Enables customers with a cn domain to request a 1st-party domain for use inside of Mainland China. Learn more... -->

| Funktion | Beskrivning |
| -----------| ---------- |
| Analysstöd för [!UICONTROL Adobe Experience Platform Edge Network] | Gör att du kan använda en enda tagg för att skicka data till flera Adobe-lösningar, som Adobe Analytics, Adobe Target, Adobe Audience Manager, Adobe Experience Platform Data Lake, Unified Profile och Experience Cloud ID Service. [Läs mer...](https://docs.adobe.com/content/help/en/experience-platform/edge/home.html) |
| [!UICONTROL Adobe Analytics dashboards] | [!UICONTROL Adobe Analytics dashboards] är en mobilapp som gör att användare alltid har tillgång till insikter från Adobe Analytics. Den här appen är avsedd för chefer som vill ha tillgång till nyckeltal oavsett var de är. Den ger tillgång till välstrukturerade, interaktiva styrkort och kommer att finnas tillgängliga för både operativsystemen iOS och Android. [Läs mer...](https://docs.adobe.com/content/help/en/analytics/analyze/mobapp/home.html) |
| [!UICONTROL Workspace]: Bygg automatiskt [!UICONTROL Freeform Tables] från ett tomt läge | Tidigare gick det inte att släppa komponenter direkt i ett tomt projekt eller en tom panel. du var tvungen att lägga till en [!UICONTROL Freeform Table] först. Nu kan du släppa komponenter direkt i ett tomt projekt eller en tom panel, och en [!UICONTROL Freeform Table] byggs automatiskt i det format som rekommenderas. Dessutom har det gjorts förbättringar av hur blandade komponenttyper (som dimensioner och mätvärden) hanteras när de tas bort i en tom friformstabell tillsammans. |
| [!UICONTROL Adobe Analytics Package] läggs till på [!UICONTROL Feature Access Level] sida | Nu kan du visa vilken [!UICONTROL Adobe Analytics Package] (SKU) ditt företag är berättigat till på [!UICONTROL Admin] > [!UICONTROL Company Settings] > [!UICONTROL Feature Access Level] -sidan. |

#### Adobe Analytics-korrigeringar

* Ett problem som orsakade saknade [!DNL Analytics] segmentdata i Audience Manager har korrigerats. (AN-206221)
* Korrigerade ett problem med [!UICONTROL Data Sources] bearbetning som visade fel datum. (AN-213604)
* Ett problem med att klassificeringsfiler inte överfördes till FTP på rätt sätt har korrigerats. (AN-214102)
* Ett problem med API-metoden som `Segments.Get` inte returnerade ett fullständigt svar har korrigerats. (AN-206210)
* Ett problem där tabellradsobjekt konverterades till specialtecken vid hämtning av [!DNL Workspace] PDF har korrigerats. (AN-196153)
* Ett problem med anropet till Adobe Analytics API 1.4 har `visattrcustomeridcustomerattributes` korrigerats. (AN-186873)
* Korrigerade ett problem med data som visas i rapporter men saknas i [!UICONTROL Data Feed]. (AN-211923)
* Ett problem har korrigerats med att det inte gick att kopiera [!UICONTROL Product Profile] behörigheter. (AN-211113)
* Ett problem har korrigerats där användare med Federated ID inte kunde logga in på [!UICONTROL Report Builder]. (AN-207750)
* Ett problem med att data inte visades i har korrigerats [!UICONTROL AdWords] [!UICONTROL Advertising Analytics]. (AN-213249)
* Ett problem där klassificeringsdata inte visades i trendvyn har korrigerats. (AN-212761)
* Korrigerade ett problem som orsakade ett felaktigt antal publicerade segment i [!UICONTROL Segment Manager]. (AN-213374)
* Ett problem med **[!UICONTROL Show Upwards Trend As...]** alternativet i [!UICONTROL Calculated Metric Editor] - det fungerade inte när filter användes har åtgärdats. (AN-214223)
* Flera problem med [!UICONTROL Classification] Import och Export har korrigerats. (AN-213488, AN-215309, AN-216345, AN-215307, AN-216671)
* Flera problem med [!UICONTROL Classification Rule Builder]har korrigerats. (AN-213826, AN-213550, AN-213095)
* Åtgärdade problem med [!UICONTROL Data Sources] bearbetning. (AN-218083, AN-213604, AN-214102, AN-215485, AN-215339, AN-212911, AN-217551, AN -217947, AN-219018, AN-214691, AN-218401)
* Korrigerade FTP-anslutningsproblem. (AN-115525)
* Flera [!DNL Analytics] [!UICONTROL Data Feeds] problem har korrigerats. (AN-176769, AN-160480, AN-211923, AN-204286, AN-212977, AN-214528, AN-215080, AN -217784, AN-219093, AN-218817, AN-217798, AN-218267, AN-218382)
* Åtgärdade problem med [!UICONTROL Data Warehouse] begäranden. (AN-181836)
* Korrigerade problem i PDF-nedladdade [!UICONTROL Workspace] projekt där värden konverterades till specialtecken. (AN-196153)
* Korrigerade ett problem med att det inte gick att kopiera [!UICONTROL Product Profile] behörigheter i [!UICONTROL Admin Console]. (AN-211113)
* Ett problem har korrigerats där tidsformat i beräknade värden bryts för negativa värden. (AN-210900)
* Korrigerade ett problem som hindrade användare från att ändra värdena [!UICONTROL Attribution Model] för statiska radvärden. (AN-207872)
* Korrigerade ett problem som gjorde att [!UICONTROL Scheduled Report] byggaren hamnade i kö. (AN-215317)
* Fixade [!UICONTROL ExactTarget Data Connector]. (AN-210794)
* Åtgärdade latensproblem i [!UICONTROL Bulk Ingestion API]. (AN-210165)
* Ett problem har korrigerats där användare inte kunde logga in [!UICONTROL Report Builder] med ett Federated ID. (AN-207750)
* Ett fel som gjorde [!UICONTROL Advertising Analytics] att [!DNL Google AdWords] data inte kunde visas har korrigerats. (AN-213249)
* Korrigerade ett problem som förhindrade [!UICONTROL Workspace] att [!UICONTROL Project Viewed] händelser visades i loggar. (AN-214134)
* Korrigerade ett problem som uppstod när datumintervallet i [!UICONTROL Workspace] och markeringen ändrades **[!UICONTROL Apply to all panels]**. Datumet ändrades inte i vissa paneler. (AN-214944)
* Ett problem har korrigerats där det inte gick att skapa eller redigera aviseringar. (AN-215920)
* Korrigerade ett problem med alla dynamiska datumintervall när felaktiga datum [!UICONTROL Workspace] visades på grund av att veckodagens första dag sporadiskt växlade till en söndag från en måndag. (AN-218835)

#### Ytterligare Adobe Analytics-korrigeringar

AN-101871, AN-115525; AN-123869; AN-152580; AN-160480; AN-178128; AN-186907; AN-199299; AN-201342; AN-201397; AN-204286; AN-204518; AN-206045; AN-206948; AN-208607; AN-209486; AN-210743; AN-211550; AN-211539; AN-211826; AN-211943; AN-212130; AN-212151; AN-212653; AN-212673; AN-212709; AN-212833; AN-212961; AN-212977; AN-213095; AN-213422; AN-213450; AN-213490; AN-213752; AN-213827; AN-214094; AN-214153; AN-214214; AN-214234; AN-214253;  AN-214255; AN-214343; AN-214355; AN-214401; AN-214427; AN-214528; AN-214642; AN-214691; AN-214772; AN-214793; AN-214924; AN-215017; AN-215080; AN-215212; AN-215312; AN-215377; AN-215402; AN-215545; AN-215905; AN-215963; AN-216447; AN-216676; AN-216880; AN-216999; AN-217245; AN-218450; AN-218899; AN-219487; AN-219677

### Viktiga meddelanden för [!DNL Analytics]-administratörer {#aa-notices}

| Meddelande | Datum tillagt eller uppdaterat | Beskrivning |
| -----------| ---------- | ---------- |
| Ändra hur [!UICONTROL Entries/Exits] beräknas i [!UICONTROL Workspace] | 7 april 2020 | Från och med mars 2020, har vi ändrat hur värdet _Inga_ interagerar med [!UICONTROL Entries/Exits] i [!UICONTROL Analysis Workspace]. Because you can now turn _Nones_ on and off in [!UICONTROL Analysis Workspace], we apply the _None_ value after the entry or exit, whereas (for eVars) it used to be applied before entry or exit. Anta till exempel att den första träffen av ett besök inte har något värde för eVars, men att den andra träffen gör det. In [!UICONTROL Reports & Analytics] the first hit will show as _Unspecified_ for the Entry, but in [!UICONTROL Analysis Workspace] it will show up as the value on the second hit. |
| Inställningen **[!UICONTROL Conversion Level]** tas bort | 3 mars 2020 | Inställningen för icke fungerande [konverteringsnivå](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/general-acct-settings-admin.html) i **[!UICONTROL Admin Tools]** > **[!UICONTROL Report Suites]** > **[!UICONTROL General Account Settings]** kommer att tas bort från gränssnittet den 12 mars 2020. |
| **[!UICONTROL Dashboard Archive]** tas bort | 27 mars 2020 | Inställningen **[!UICONTROL View Archive]** under **[!UICONTROL Manage Dashboards]** i [!UICONTROL Reports & Analytics] är inte tillgänglig från och med oktober 2020. |
| Stöd för TLS 1.1 upphör | 3 oktober 2019 | Adobe Analytics tar bort stödet för TLS 1.1 senast den 31 mars 2020. Den här ändringen är en del av våra löpande ansträngningar att upprätthålla högsta säkerhetsstandarder och skydda kunddata. |
| Ny Adobe Analytics-domän | 18 dec 2019 | Den 16 januari 2020 började Adobe Analytics gå över till en ny domän – `https://experience.adobe.com/analytics.`<br>**Obs!** Den här ändringen gäller alla användare som använder Analytics med sina Adobe ID:n eller Enterprise ID:n.<ul><li>Domänändringen kan orsaka cookie-problem när Analytics läses in i Safari. Om du avmarkerar _Förhindra spårning över webbplatser_ i [!DNL Safari] Sekretessinställningarna aktiveras cookies i domäner (och alla upplevelser på olika webbplatser) vilket gör att Analytics kan användas i den nya Adobe Experience Cloud-domänen. Du kan använda andra webbläsare utan problem eftersom det bara påverkar [!DNL Safari]-användare.</li><li>Domänändringen kan leda till att [!UICONTROL Activity Map] slutar fungera för vissa kunder [i en del fall](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html).</li></ul> |
| Slutet av livscykeln – äldre API:er för Analytics | 9 januari 2020 | I november 2020 kommer följande äldre API-tjänster för Analytics att ha nått slutet av sina livscykler och avslutas. Aktuella integreringar som byggts med dessa tjänster kommer att sluta fungera. <ul><li>1.3 API:er för Analytics</li><li>1.4 API:er för SOAP Analytics</li><li>Äldre OAuth-autentisering (OAuth och JWT)</li></ul>Vi har tagit fram [vanliga frågor och svar om upphörande av äldre API:er](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) som kan hjälpa dig att få svar på frågor och ge vägledning om hur du går vidare. API-integrationer som använder dessa tjänster kan migrera till [1.4 Analytics REST-API:er](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) eller [2.0 Analytics API:er](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Äldre OAuth-konton kan migrera till ett [Adobe IO](https://console.adobe.io/home?mv=email) Analytics-integreringskonto som kan användas för att få tillgång till både 1.4 Analytics API:er och 2.0 Analytics API:er. |
| San Jose FTP-hantering upphör för London och Singapore | Juli 2020 | För kunder i London och Singapore stöder vi inte längre datahantering mellan London eller Singapore och datacentret [ftp.omniture.com](ftp://ftp.omniture.com/) i San Jose.<br/><ul><li>I London använder du [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>I Singapore använder du [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Ad Hoc Analysis upphör | 6 aug 2018 | Adobe har meddelat att man avser att dra tillbaka Ad Hoc Analysis. Ett slutdatum meddelas så snart det är tillgängligt. Mer information finns i [Upptäck Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

### [!DNL AppMeasurement] {#appm}

Se [versionsinformationen om AppMeasurement för Javascript](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html). Version 2.20.0 släpptes 5 mars 2020.

### Självstudiekurser för nya Analytics {#tutorials-analytics}

| Innehåll | Beskrivning |
| -----------| ---------- |
| [Utbildningsmall på analysarbetsytan](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/navigating-workspace-projects/training-tutorial-template-in-analysis-workspace.html) | Självstudiekursen ( [!UICONTROL Analysis Workspace] Training Tutorial) leder dig genom vanliga termer och steg för hur du skapar ditt första projekt i [!UICONTROL Workspace]. |
| [Lägga till jämförelser med föregående månad och år i trender](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/calendar-and-date-ranges/adding-prior-month-and-year-comparisons-to-trends.html) | Lär dig hur du använder anpassade datumintervall för att skapa månads- och årsvisa trendjämförelser för alla mätvärden i [!UICONTROL Analysis Workspace]. |
| [Tillägg för mörkt läge för analysarbetsytan](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/dark-mode-extension-for-analysis-workspace.html) | Aktivera tillägget Mörk Reader Chrome om du vill göra Analysis Workspace mörkt. |
| [Färgpipetttillägg för definition av anpassade paletter](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/color-eyedropper-extension-for-defining-custom-palettes.html) | Lär dig hur du använder tillägget ColorPick EyeDropper Chrome för att enkelt hitta de hexvärden du behöver för en anpassad färgpalett i dina [!UICONTROL Workspace] projekt. |

#### Hjälpresurser för analyser

* [Självstudiekurser för Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Produktdokumentation för Adobe Analytics](https://docs.adobe.com/content/help/en/analytics/landing/home.html)

## ![Ikonen](/assets/audience-manager.png) Audience Manager {#aam}

Nya funktioner, korrigeringar, dokumentation och självstudiekurser i Audience Manager.

### Uppdateringar av användargränssnittet

Audience Manager släpper uppdateringar i domän- och huvudfältet för att förbättra upplevelsen och göra den enhetlig med andra Experience Cloud-program.

* Enklare att växla mellan olika organisationer eller till ett annat program.
* Förbättrad användarhjälp, inklusive artiklar och sammanhangsberoende videoklipp på Hjälp-menyn.
* Möjlighet att ge feedback om Experience Platform och supportärenden.
* Ett nytt enklare URL-mönster. Uppdatera bokmärkena till den nya URL:en: `experience.adobe.com/audience-manager`.

Uppdateringarna är bara tillgängliga för användare som loggar in med Adobe ID. Mer information om hur du byter till en Adobe ID-inloggning finns i [Hantera Experience Cloud-användare och -produkter](https://docs.adobe.com/content/help/en/core-services/interface/manage-users-and-products/admin-getting-started.html).

### Nya funktioner och korrigeringar i Adobe Audience Manager

| Funktion | Beskrivning |
| -----------| ---------- |  
| [Bulkhanteringsverktyg (BAAAM)](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html#download) | Vi har laddat upp ett nytt kalkylblad för grupphanteringsverktyg som: <br><br><ul><li>Gör att du kan lista undermapparna i din trait-hierarki (AAM-51528)</li><li>Hämtar mått när du uppmanas att ange egenskaper som är kopplade till CRM-ID:n (enhets-ID) (AAM-52135)</li><li>Korrigerar ett språkkodningsproblem för koreanska tecken (AAM-AAM-54006)</li></ul> |

**Korrigeringar**

* Ett problem har korrigerats där trendrapporter orsakade timeout för mappar med många egenskaper. (AAM-54457)
* Korrigerade ett problem där kunderna inte kunde se [!UICONTROL Expression builder] i arbetsflödet för att skapa/redigera egenskaper. (AAM-54255)
* Korrigerade ett problem där felmeddelanden i användargränssnittet bara visades en kort tid och försvann innan kunderna kunde läsa dem. Detta inträffade till exempel när ett segment som var mappat till ett mål skulle tas bort. (AAM-54031)
* Ett problem har korrigerats där kunder som inte använder [!UICONTROL Audience Marketplace] längre fick e-postmeddelanden med månatliga faktureringar. (AAM-54602)
* Ett problem har korrigerats där kunder som klickade på vissa egenskaper från andra platser i användargränssnittet skulle se brutna länkar i stället för egenskaperna. (AAM-54768)
* Ett problem har korrigerats där, i redigeringsläget för anpassade uttryck, tryck på RETUR skulle uppdatera sidan och trait-uttrycket skulle gå förlorat. (AAM-54210)
* Flera tillgänglighetsförbättringar i hela gränssnittet. (AAM-47781, AAM-49075, AAM-49360, AAM-49361, AAM-49376, AAM-50432, AAM-52550, AAM-54660).

### Nya självstudiekurser för Audience Manager {#tutorials-aam}

| Innehåll | Beskrivning |
| -----------| ---------- |  
| [Grundläggande termer och begrepp i Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-basic-terms-and-concepts-in-audience-manager.html) | Den här videon innehåller några av de grundläggande termer och begrepp som får dig att komma igång med Audience Manager, bland annat signaler, egenskaper, segment osv. |
| [Förstå dataflödet i Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-the-data-flow-in-audience-manager.html) | I den här videon får du hjälp att förstå Adobe Audience Manager genom att beskriva dataflödet in i, genom och ut från programmet. |
| [Audience Manager - Översikt över en plattform för datahantering](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-overview-of-a-dmp.html) | Förstå de största utmaningarna med kanalövergripande personalisering och hur Adobe Audience Manager hanterar kundresan. Lär dig också vilka datatyper som kan registreras i Audience Manager och identifiera de ekosystempartners för annonseringsteknologier som är integrerade med Audience Manager. |
| [Användningsexempel för Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-use-cases.html) | I den här videon identifierar vi fyra vanliga Audience Manager-användningsfall och beskriver de bästa metoderna som är kopplade till dem. |
| [Understanding Cross-Device Metrics in Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/profile-merge/understanding-cross-device-metrics-in-audience-manager.html) | I den här videon diskuterar vi skillnaden mellan enhetsprofiler och enhetsövergripande profiler och visar var siffrorna i användargränssnittet matchar de olika profiltyperna. |
| [Förstå prediktiva målgrupper i Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/understanding-predictive-audiences.html) | I den här videon diskuterar vi vad Audience Manager Predictive Audiences är, presenterar detaljer om hur de fungerar och visar användningsexempel. |
| [Konfigurera och rapportera om prediktiva målgrupper i Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/configure-and-report-on-predictive-audiences.html) | I den här videon går vi igenom konfigurationen för prediktiva målgrupper i Audience Manager-gränssnittet. Vi ser också rapporter som visar modellens resultat. |

## ![Ikonen för](/assets/aem.png) Experience Manager {#aem}

Nya funktioner, korrigeringar och uppdateringar i Adobe Experience Manager (AEM). Adobe rekommenderar att kunder med lokala distributioner driftsätter de senaste korrigeringarna för bättre stabilitet, säkerhet och prestanda.

### Produktuppdateringar

* **AEM as a Cloud Service**

   * Förbättringar och korrigeringar av tillgångsbearbetning. Dialogrutan Återanvändning av resurser ger användaren bättre kontroll, gör det möjligt att välja en viss bearbetningsprofil och huruvida efterbearbetningsarbetsflödet ska aktiveras.
   * Prestandaförbättringar för inmatning av dynamiska mediefiler.

### Självhjälp

* **Tjänsten Automated Forms Conversion - release AFC-2020.03.1**

   Ett nytt alternativ är tillgängligt när du installerar den senaste anslutningen:

   **[!UICONTROL Auto-detect logical sections]**: Du kan använda alternativet för att [!UICONTROL Auto-detect logical sections] släppa paneler på sidnivå (sidnummerbaserade paneler) och endast skapa logiska paneler. Det klär också de fält som inte hör till något avsnitt med föregående logiska avsnitt och fält i ett logiskt avsnitt som sprids över två intilliggande sidor till ett enda logiskt avsnitt. Om t.ex. vissa fält i ett logiskt avsnitt finns i slutet av sida 1 och vissa finns i början av sida 2, klubbar alla sådana fält in i ett enda logiskt avsnitt.

* **Bildformat som inte stöds i Dynamic Media**

   Information om de undertyper av rasterbildfilformat som inte stöds i [!UICONTROL Dynamic Media].

   Se [Rasterbildformat som inte stöds i Dynamic Media](https://docs.adobe.com/content/help/en/experience-manager-65/assets/administer/assets-formats.html#unsupported-image-formats-dynamic-media).

* **Innehållsfragment**

   Information om stöd för [innehållsfragment i AEM Assets HTTP API](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/admin/assets-api-content-fragments.html), tillsammans med [anpassning och utökning av innehållsfragment](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-customizing.html)och [innehållsfragment som konfigurerar komponenter för återgivning](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-configuring-components-rendering.html).

* **AEM Experience League Community**

   Kommunicera med [AEM Experience League Community](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/ct-p/adobe-experience-manager-community): Ställ frågor till andra studerande och AEM-experter, bläddra bland trådar och dela med dig av dina tips och din expertis!

* **AEM-nyhetsbrev**

   AEM Newsletter från [!UICONTROL Experience League] är utformat för att hjälpa dig att komma igång med AEM så att du kan börja inse värdet direkt. Här är det senaste nyhetsbrevet:

   * [Volym 30](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html): Experience Manager finns nu som en molntjänst.
   * [Prenumerera](https://adobeeventsonline.com/AEM/2017/NL/Optin/) på Experience Insider Newsletter.
   * Se nyhetsbrevarkiv i [AEM-resursavsnittet](https://helpx.adobe.com/se/support/experience-manager/6-5.html) på sidan Utbildning och support för Adobe Experience Manager 6.5.

### Nya självstudiekurser för Experience Manager

| Innehåll | Beskrivning |
| -----------| ---------- |  
| [Konfigurera lokal AEM Runtime](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | Adobe Experience Manager (AEM) can be run locally using the [!UICONTROL AEM as a Cloud Service] SDK&#39;s [!UICONTROL Quickstart Jar]. This allows developers to deploy to, and test custom code, configuration, and content prior to committing it to source control, and deploying it to a [!UICONTROL AEM as a Cloud Service] environment. |
| [Komma igång med AEM Assets](https://video.tv.adobe.com/v/33624?captions=swe) | En introduktionsvideo om hur du kommer igång med AEM Assets för företagsanvändare. |
| [Mappscheman för metadata](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-folder-schemas.html) | Med metadatamappscheman kan användare hantera och granska metadata som är kopplade till själva resursmapparna, i stället för direkt på resurser. |
| [Taggar](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/tagging.html) | Taggar är ett viktigt verktyg för att hantera resurser i resursernas mapphierarki. Det är viktigt att skapa en taggningstaxonomi så att användarna kan identifiera och ordna resurser i AEM. |
| [Metadataprofiler](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-profiles.html) | Med metadataprofiler kan du automatiskt tillämpa standardmetadata på resurser i resursmappar. Detta minskar belastningen på AEM-användarnas metadatahantering och ger enhetligare metadata. |
| [Metadata-scheman](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-schemas.html) | Metadata-scheman definierar gränssnittet som visar metadata för resurser i AEM. I den här videon utforskas kombinationen av metoder som används för att tillämpa resurser. |

### Ytterligare resurser

* [AEM som Versionsinformation för molntjänster](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)
* [AEM som molntjänstdokumentation](https://docs.adobe.com/content/help/sv-SE/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 – startsida för utbildning och support](https://helpx.adobe.com/se/support/experience-manager/6-5.html)
* [AEM 6.4 – startsida för utbildning och support](https://helpx.adobe.com/se/support/experience-manager/6-4.html)
* [AEM 6.3 – startsida för utbildning och support](https://helpx.adobe.com/se/support/experience-manager/6-3.html)
* [AEM 6.2 – startsida för utbildning och support](https://helpx.adobe.com/se/support/experience-manager/6-2.html)
* [Användarhandbok för Cloud Manager](https://helpx.adobe.com/se/experience-manager/cloud-manager/user-guide.html)
* [Versionsinformation om AEM Cloud Manager](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Äldre versioner av AEM-dokumentation](https://helpx.adobe.com/se/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic – startsida för hjälp](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Versionsinformation för Dynamic Media](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Versionsinformation för Livefyre](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## ![Ikon](/assets/campaign.png) [!DNL Campaign] {#ac}

Adobe Campaign är ett intuitivt och automatiserat sätt att leverera personliga meddelanden i alla marknadsföringskanaler, både online och offline. Nu kan ni förutse vad era kunder vill ha med upplevelser som bestäms av deras vanor och önskemål.

### Campaign Standard

* [Adobe Campaign Standard 20.3](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html)

### Campaign Classic

* [Adobe Campaign Classic 20.1.3](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html#release-20-1-3-build-9124)
* [Adobe Campaign Classic 19.1.4](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

### Kontrollpanelen för kampanj

| Funktion | Beskrivning |
| -----------| ---------- |  
| Hantering av GPG-nycklar | Installera och/eller generera GPG-nycklar på en marknadsinstans för att kryptera data som skickas från Campaign och för att dekryptera inkommande data. |
| Certifikathantering för CNAME-underdomäner | Med kontrollpanelen kan du nu förnya SSL-certifikaten för dina underdomäner som har delegerats med CNAME-metoden. |

### Nya Campaign-självstudiekurser

* Nya självstudiekurser för Campaign Standard

| Innehåll | Beskrivning |
| -----------| ---------- |  
| [Kontrollpanelen - Google TXT-posthantering](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/google-txt-record-management.html) | Lär dig hur du lägger till Google TXT-webbplatsverifieringsposter i alla dina underdomäner som används för att skicka e-post till GMAIL-adresser med Campaign-kontrollpanelen. |
| [Konfigurera och köra ett arbetsflöde med aktiviteten Externt API](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html) | Lär dig hur du anropar en extern REST API-slutpunkt med hjälp av Extern API-aktivitet. |
| [Komma igång med push-meddelanden för Android-självstudiekurs](https://docs.adobe.com/content/help/en/campaign-standard-learn/getting-started-with-push-notifications-android/introduction.html) | I den här självstudiekursen beskrivs de steg som krävs för att ställa in push-meddelanden med Campaign Standard och Android-appen. |

* Nya Campaign Classic-självstudiekurser

| Innehåll | Beskrivning |
| -----------| ---------- |  
| [Stor datahantering i Snowflake](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | Lär dig hur du kan utnyttja Snowflake-kontakten i Adobe Campaign Classic. |
| [Kontrollpanelen - Google TXT-posthantering](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/google-txt-record-management.html) | Lär dig hur du lägger till Google TXT-webbplatsverifieringsposter i alla dina underdomäner som används för att skicka e-post till GMAIL-adresser med Campaign-kontrollpanelen. |

### Kampanjhjälpresurser

* Adobe Campaign Standard: [Help Center](https://docs.adobe.com/content/help/en/campaign-standard/using/campaign-standard-home.html) - [versionsinformation](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [instruktionsvideor](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [versionsplanering](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-planning.html) - [senaste dokumentationsuppdateringar](https://docs.adobe.com/content/help/en/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Help Center](https://docs.adobe.com/content/help/en/campaign-classic/using/campaign-classic-home.html) - [versionsinformation](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html) - [instruktionsvideor](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)- [Senaste dokumentationsuppdateringar](https://docs.adobe.com/content/help/en/campaign-classic/using/documentation-updates.html)
* Kontrollpanelen för Adobe Campaign: [Dokumentation](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) – [Versionsinformation](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## ![Icon](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

* [Nya funktioner i Advertising Cloud DSP](#adcloud-dsp)
* [Nya funktioner i Advertising Cloud Search](#adcloud-search)

### Nya funktioner i Advertising Cloud DSP {#adcloud-dsp}

| Funktion | Beskrivning |
| -----------| ---------- |
| [!UICONTROL Campaigns Classic] och [!UICONTROL Campaigns Beta] | IAS-mätningsinställningar för bedrägeri och varumärkessäkerhet, som du kan konfigurera för varje kampanj, innehåller nu alternativ för att mäta VAST- och VPAID-lager. |
| [!UICONTROL Campaigns Beta] | Datavisualiseringar och sidinläsningstider har förbättrats. |
|  | På alla sidor kan du nu hämta Excel-rapporter som baseras på de aktuella filtren och vyerna. |
|  | (22 maj) Nya mätvärden inkluderar heltidsstatistik, Aktuell intervallleverans, Datumspecifika alternativ. |
| [!UICONTROL Blacklists] | Prognossystemet använder nu automatiskt annonser eller svartlistor på kontonivå. Användare behöver inte längre klistra in svartlistan i placeringsinställningarna. |
| [!UICONTROL Inventory Deals] | (Stängt betaversion) Med ett nytt, förenklat formulär kan du snabbt konfigurera, redigera och felsöka erbjudanden på leverantörsplattformar som inte finns i Inkorgen för avtal-ID. |
|  | När du godkänner ett paket med programmatiska garanterade erbjudanden i Inkorgen för avtal-ID får du nu ett meddelande om att du måste skapa en standardplacering för varje erbjudande-ID. |

### Nya funktioner i [!UICONTROL Advertising Cloud Search] {#adcloud-search}

| Funktion | Beskrivning |
| -----------| ---------- |
| [!UICONTROL Campaigns] | (Google Ads-konton; betatjänst) Från och med slutet av maj kommer Advertising Cloud Search att kunna synkronisera data för dina Google Gmail-kampanjer och dina Google Smart Shopping-kampanjer med Google-konverteringar för spårning och rapportering. Tjänsten gör det även möjligt att redigera kampanjinställningarna och inställningarna för annonsgrupper för befintliga kampanjer från vyerna Campaigns och Ad Groups. Tjänsten är valfri. När tjänsten är allmänt tillgänglig tillkommer en extra avgift.<br>Kontakta din kontoansvarige på Adobe om du vill ha mer information om tjänsten, inklusive betaprogrammet och det framtida omfånget. |

## ![Ikon](/assets/magento.png) [!DNL Magento] {#magento}

Versionsinformation om Magento finns i:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Ikon](/assets/marketo.png) [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] är ett komplett program för lead-hantering för B2B-marknadsförare som vill transformera kundupplevelser genom engagemang under alla faser av komplexa inköpsresor.

### Uppdateringar om Core Marketo Engage

Den senaste versionsinformationen finns i [!DNL Marketo][versionsinformationen](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) .

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
