---
title: Versionsinformation om Adobe Experience Cloud
description: Mall för versionsinformation om Experience Cloud
doc-type: release notes
last-update: March 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 745a054c15f05d7957e8c98b8adfa41b665b6fa6

---


# Versionsinformation om Adobe Experience Cloud - mars 2020

![Banderoll](/assets/experience-cloud-banner-3.png)

Nya funktioner och korrigeringar i [!DNL Adobe Experience Cloud].

>[!IMPORTANT]
>Den här sidan innehåller förhandsversion av innehåll som kan ändras före den planerade versionen.

>[!NOTE]
>Prenumerera på [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) om du vill få meddelanden via e-post om kommande versioner. Ny information som publiceras efter publiceringen markeras med publiceringsdatumet.

**Releasedatum: Mars 2020**

Senaste uppdatering: 11 mars 2020

* [Systemstatus för Adobe](#status)
* [Experience Clouds gränssnitt och bastjänster](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics) - Releasedatum: 12 **mars 2020**
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (länkar till lösningshjälp)
* [!DNL Advertising Cloud](#adcloud)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (länkar till lösningshjälp)
* [Ny dokumentation och självstudiekurser](#selfhelp)

Söker du hjälp hem? Se [Adobe Experience Cloud-dokumentation](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html).

(Vissa produktreleasedatum kan variera.)

## ![Ikon](/assets/adobe.png) för Adobe-systemstatus {#status}

[!UICONTROL Adobes systemstatus] innehåller detaljerad information, statusuppdateringar och e-postmeddelanden om Adobe-molnprodukter och -tjänster, driftstopp, avbrott och underhållshändelser. Kolla in den på [status.adobe.com](https://status.adobe.com/).

**Nyheter**

* Med ditt Adobe-ID kan du prenumerera på händelsemeddelanden med större detaljrikedom, ända ned till produkterbjudandet och tilläggsnivån. Leta efter den här nya funktionen i Experience Cloud-produkter, där självprenumerationsprocessen visar delerbjudanden för de produkter och tjänster som du vill prenumerera på. Den här förbättringen bör avsevärt minska antalet meddelanden du får och göra meddelandena mer relevanta för de produkter och funktioner du använder.  Kom igång på [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nya funktioner och förbättringar som är tillgängliga idag**

| Funktion | Beskrivning |
| -----------| ---------- |
| Personligt anpassad självprenumeration per produktunderleverantörer | <ul><li>Självprenumeration per produkterbjudande eller tillägg för Experience Cloud-produkter.</li><li>Händelsemeddelanden som tas emot är relevanta för dina produkt- och produkterbjudanden.</li></ul> |
| Personaliserade upplevelser baserat på användarpreferenser | <ul><li>Tidszonsinställningen baseras på webbläsarens inställning och används i e-postmeddelanden.</li><li>E-postbekräftelse skickad vid prenumeration/avprenumeration med alla valda inställningar.</li></ul> |
| Bättre leverans av händelsemeddelanden | <ul><li>Händelsehistorik sorterad baserat på uppdateringar av kronologiska händelser.</li><li>Tidsstämpel för händelseupplösning har lagts till i större/mindre stängda problem.</li></ul> |

## ![Ikon](/assets/experience-cloud.png) för Experience Cloud-gränssnittet och bastjänsterna {#ecloud}

Nya funktioner och korrigeringar i Experience Cloud-gränssnittet, inklusive administration och bastjänster (kundattribut, målgrupper, triggers, cookies och så vidare).

| Funktion | Releasedatum | Beskrivning |
| ----|----|---- |
| Administratörsverktyg - visa användarinformation | 26 februari 2020 | Administratörer kan visa en sorterbar och filterbar lista över alla Experience Cloud-användare och deras information i det nya administrationsverktyget. Användarinformationen innehåller information om en användares produktåtkomst, roller och den senast öppnade informationen. Mer information finns i hjälpen för [Experience Cloud Admin Tool](https://docs.adobe.com/content/help/en/core-services/interface/manage-users-and-products/admin-tool-experience-cloud.html) . |

### Enhetlig produktdomän

Adobe uppdaterar domänen och gränssnittshuvudet för att göra upplevelsen enhetlig och bättre i alla Experience Cloud-program. Dessa förbättringar är utformade för att förenkla din upplevelse på små men viktiga sätt. Dessa förbättringar kommer inte att ändra dina aktuella arbetsflöden.

Bland uppdateringarna finns:

* Nya URL:er för lösningar: `experience.adobe.com/<application name>`:
   * Alla produkter kommer så småningom att använda det här URL-mönstret. Leta efter nya URL:er som ska gälla hela månaden.
   * Stöd för webbläsare: De webbläsare som stöds är [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari]och [!DNL Opera] (de senaste versionerna). **Obs!** Trots att Experience Cloud-gränssnittet har stöd för dessa webbläsare kanske inte enskilda lösningar har stöd för alla webbläsare. ( [Analytics](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html) stöder till exempel inte [!DNL Opera]och [Target](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html) stöder inte [!DNL Safari].)
   * ([!DNL Safari] endast) Domänändringen kan orsaka cookie-problem i [!DNL Safari]. Om du avmarkerar _Förhindra spårning_ av webbplatser i [!DNL Safari] Sekretessinställningar aktiveras cookies i domäner (och alla upplevelser på olika webbplatser), och Experience Cloud kan fungera i den nya domänen.
* Enklare att växla mellan olika organisationer eller till olika applikationer.
* Förbättrad produkthjälp: Experience [!UICONTROL League] är integrerat i produkten så att en hjälpsökning även innehåller resultat från communityforum och videoinnehåll. Den här ändringen förenklar åtkomsten till mer innehåll och hjälper er att få ut mesta möjliga av Experience Cloud. Klicka dessutom på **[!UICONTROL Hjälp]** > **[!UICONTROL Feedback]** för att rapportera problem eller dela med dig av dina idéer till Adobe.
* Förbättrade meddelanden: Listrutan [!UICONTROL Meddelanden] har nu två flikar, en för dina egna produktmeddelanden och en för globala produktmeddelanden.

**Obs!** Sidan [!UICONTROL Feed] togs bort i januari 2020. Leta efter ett meddelande om borttagning av produkter.

Produktdokumentation finns i hjälpen för [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html) .

## ![Icon](/assets/platform.png) Experience Platform {#platform}

Versionsinformation om [!UICONTROL Experience Platform,] [!UICONTROL Experience Platform Launch,] [!UICONTROL Identity Service,] Journey Orchestration, Mobile Services och säkerhetsbulletiner.

* [Versionsinformation om Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [Resesamordning](#journey)
* [Mobiltjänster och SDK för mobiler](#mobile)
* [Säkerhetsbulletiner och -anvisningar](https://helpx.adobe.com/security.html) (alla Adobe-produkter)

### Experience Platform Launch {#launch}

Se [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) för versionsinformation och produktdokumentation.

### Resesamordning {#journey}

Med Adobe Experience Platform kan ni samordna enskilda kundresor i stor skala över olika upplevelsekanaler genom att intelligent förutse varje enskild individs behov i realtid, oavsett vart resan tar dem.

Q1-versionen har publicerats. [Läs mer](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html#q1-release---march-2020)

#### Ytterligare resurser för resesamordning

[Dokumentation](https://docs.adobe.com/content/help/en/journeys/using/journey-orchestration-home.html) - [Versionsinformation](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html) - [instruktionsvideor](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Mobiltjänster och SDK för mobiler {#mobile}

**iOS v4.19.1**

* Allmänt - En potentiell krasch har åtgärdats när [!UICONTROL Swift] -uppräkningar inkluderas i kontextdata för spåranrop.
* [!DNL Target] - [!DNL Target] Sessions-ID läggs nu till som en kontextdataparameter `a.target.sessionId` i den interna [!UICONTROL träffen Analytics-for-Target] som skickas till Adobe Analytics.

**Android v4.18.1**

* [!DNL Target] - [!DNL Target] Sessions-ID läggs nu till som kontextdataparametern a.target.sessionId i den interna [!UICONTROL Analytics-for-Target] -träff som skickas till Adobe Analytics.

## ![Ikon](/assets/analytics.png) [!DNL Analytics]{#analytics}

Releasedatum: 12 **mars 2020**

Nya funktioner och korrigeringar i Adobe Analytics:

* [Nya funktioner, förbättringar och korrigeringar i Adobe Analytics](#aa-features)
* [Viktiga meddelanden för Analytics-administratörer](#aa-notices)
* [AppMeasurement](#appm)

Produktdokumentation finns i [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Nya funktioner, förbättringar och korrigeringar i Adobe Analytics {#aa-features}

* **Flera rapportsviter i[!UICONTROL Analysis Workspace ]**: Nu kan du samla in data från flera rapportsviter i ett enda[!UICONTROL Analysis Workspace]-projekt och visa dem i paneler sida vid sida.[Läs mer...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/multiple-report-suites.html)
* **Experience Cloud Audience Optimization**: Med den här funktionen kan ni publicera segment till Experience Cloud inom 8 timmar (i stället för den tidigare 48-timmars bearbetningstiden). [Läs mer...](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segmentation-workflow/seg-publish.html)
* **Analysis Workspace - mall** för självstudiekurser: Den här nya standardmallen leder dig igenom vanliga termer och steg för att skapa din första analys i Workspace. Den är tillgänglig som en standardmall i [!UICONTROL Nytt projekt] och ersätter det exempelprojekt som finns idag för nya användare som inte har andra projekt i listan.

#### Korrigeringar

* Korrigerade ett problem i [!UICONTROL Rapporter och analyser] som förhindrade hämtning av `.xls` rapporter. Detta problem påverkade kunder som använde andra valutor än dollar och euro. (AN-206541, AN-204008)
* Lanseringen av ett nytt gränssnitt åtgärdade flera kundproblem i samband med byte av Experience Cloud-organisationer.(AN-200844, AN-186920)
* Ett problem har korrigerats där en uppdelning på _ospecificerad_ radpost (eller vissa andra rapportrader) utan att inkludera _ospecificerad (Ingen)_ i uppdelningens sökfilter inte gav några resultat vid uppdelningen.
* Korrigerade ett problem som uppstod när en klassificerad dimension användes, så att mätosummorna för in- eller utträde inte matchade radartikelsummorna för en uppdelning.
* Ett problem har korrigerats där den första beröringen och den sista beröringsmodellen i attribuerings-IQ inte räknade in korrekt för vissa radartiklar i vissa av boxdimensionerna.
* Ett problem har korrigerats där indelning av en datumdimension med en annan datumdimension skulle returnera felaktiga resultat.
* Korrigerade ett problem där ibland inmatnings- eller avslutningsvärden skulle räknas felaktigt när de tillämpas på &quot;Ospecificerad&quot; i en klassificerad dimensionsrapport.

### Viktiga meddelanden för [!DNL Analytics] administratörer {#aa-notices}

| Meddelande | Datum tillagt eller uppdaterat | Beskrivning |
| -----------| ---------- | ---------- |
| EOL för inställning av **[!UICONTROL konverteringsnivå]** | 3 mars 2020 | Inställningen för icke fungerande [konverteringsnivå](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/general-acct-settings-admin.html) i **[!UICONTROL Administratörsverktyg]>[!UICONTROL Rapportsviter]>[!UICONTROL Allmänna kontoinställningar]** kommer att tas bort från gränssnittet den 12 mars 2020. |
| EOL för **[!UICONTROL instrumentpanelsarkiv]** | 3 mars 2020 | Inställningen **[!UICONTROL Visa arkiv]** under **[!UICONTROL Hantera instrumentpaneler]** i [!UICONTROL rapporter och analyser] är inte längre tillgänglig från och med den 12 mars 2020. |
| Stöd för TLS 1.1 upphör | 3 oktober 2019 | Adobe Analytics tar bort stödet för TLS 1.1 senast den 31 mars 2020. Den här förändringen är en del av våra pågående ansträngningar att upprätthålla högsta säkerhetsstandarder och främja säkerheten för kunddata. |
| Ny Adobe Analytics-domän | 18 dec 2019 | Den 16 januari 2020 började Adobe Analytics gå över till en ny domän - `https://experience.adobe.com/analytics.`<br>**Obs!**Den här ändringen gäller alla användare som använder Analytics med sina Adobe ID:n eller Enterprise ID:n.<ul><li>Domänändringen kan orsaka cookie-problem när Analytics läses in i Safari. Om du avmarkerar _Förhindra spårning_ av webbplatser i [!DNL Safari] Sekretessinställningar aktiveras cookies i domäner (och alla upplevelser på olika webbplatser). Analytics kan dessutom användas i den nya Adobe Experience Cloud-domänen. Du kan använda andra webbläsare utan problem eftersom det bara påverkar [!DNL Safari] användare.</li><li>Domänändringen kan göra att [!UICONTROL aktivitetskartan] slutar fungera för vissa kunder [i vissa fall](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html).</li></ul> |
| Slutet av livscykeln - äldre API:er för analys | 9 januari 2020 | I november 2020 kommer följande API-tjänster för Analytics Legacy att ha nått sitt slutdatum och kommer att avslutas. Aktuella integreringar som byggts med dessa tjänster kommer att sluta fungera. <ul><li>1.3 API:er för analys</li><li>1.4 API:er för SOAP-analys</li><li>Äldre OAuth-autentisering (OAuth och JWT)</li></ul>Vi har tagit fram en [äldre API EOL - Frågor och svar](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) som kan hjälpa dig att besvara dina frågor och ge vägledning om hur du går vidare. API-integrationer som använder dessa tjänster kan migrera till [1.4-API:erna](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) för REST eller [2.0-API:erna](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)för analys. Äldre OAuth-konton kan migrera till ett [Adobe IO](https://console.adobe.io/home?mv=email) Analytics-integrationskonto, som kan användas för att komma åt både 1.4-API:er för analys och 2.0-API:er för analys. |
| San Jose FTP Broker Ending for London and Singapore | Juli 2020 | För kunder i London och Singapore stöder vi inte längre förmedling av data mellan London eller Singapore och datacentret [ftp.omniture.com](ftp://ftp.omniture.com/)i San Jose.<br/><ul><li>För London använder du [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Använd [ftp4.omniture.com för Singapore](ftp://ftp4.omniture.com/)</li></ul> |
| EOL för ad hoc-analys | 6 aug 2018 | Adobe har meddelat att man avser att göra en Ad hoc-analys vid slutet av livscykeln. Ett slutdatum delas så snart det är tillgängligt. Mer information finns på [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

### [!DNL AppMeasurement] {#appm}

Se [AppMeasurement for Javascript, versionsinformation](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html). Version 2.20.0 släpptes 5 mars 2020.

## ![Icon](/assets/audience-manager.png) Audience Manager {#aam}

Nya funktioner och uppdateringar i Audience Manager:

| Funktion | Beskrivning |
| -----------| ---------- |
| [Arbetsblad för grupphanteringsverktyg](https://docs.adobe.com/help/en/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html) | Det finns en ny version av kalkylbladet som åtgärdar ett problem som vissa kunder råkade ut för när de skapade algoritmiska modeller i 64-bitars operativsystemet Windows. Ladda ned den senaste versionen [här](https://docs.adobe.com/help/en/audience-manager/user-guide/reference/bulk-management-tools/assets/BAAAM_V2_20200311.xlsm). |

### Korrigeringar och förbättringar {#aam-fixes-and-improvements}

* Korrigerade ett fel där kunder inte kunde uppdatera segmentnamnet på grund av att RBAC-behörigheten [!UICONTROL VIEW_ALL_DESTINATIONS]saknades. Behörigheten [!UICONTROL VIEW_ALL_DESTINATIONS] ska inte krävas för att uppdatera ett segment. Mer information om RBAC-behörigheter finns i [Administration (RBAC-kontroller)](https://docs.adobe.com/help/en/audience-manager/user-guide/features/administration/administration-overview.html#wild-card-permissions). (AAM-52760)
* Korrigerade ett fel i [Data Explorer](https://docs.adobe.com/help/en/audience-manager/user-guide/features/data-explorer/data-explorer-overview.html) där vissa kunder inte kunde se innehåll i avsnittet med grundläggande information och operatorer i uttrycksverktyget när de skapade egenskaper baserade på [!UICONTROL Data Explorer] -signaler. (AAM-53130)
* Korrigerade ett fel där vissa kunder inte kunde läsa in gränssnittet [!UICONTROL Audience Marketplace] . (AAM-52070)
* Korrigerade ett fel i [!UICONTROL Segments API] där gränssnittet skulle låsas när användare försökte komma åt segmenten och användarna var tvungna att navigera bort från sidan på grund av vissa segment utan beskrivning. (AAM-53071)
* Flera tillgänglighetsförbättringar i hela gränssnittet. (AAM-48952, AAM-48969, AAM-48979, AAM-48993, AAM-49048, AAM-49057, AAM-49058, AAM-493 (92)

## ![Ikon](/assets/aem.png) för Experience Manager {#aem}

Nya funktioner, korrigeringar och uppdateringar i Adobe Experience Manager (AEM). Adobe rekommenderar att kunder med anläggningsdistributioner driftsätter de senaste patcharna för att få bättre stabilitet, säkerhet och prestanda.

### Produktuppdateringar

* **AEM 6.5.4.0** AEM 6.5, Service Pack 4.0 (6.5.4.0 släppt 5 mars 2020) är en viktig uppdatering med nya funktioner, viktiga kundförbättringar, förbättrade prestanda, stabilitet och säkerhet som släppts sedan den allmänna tillgängligheten av AEM 6.5 april 2019.
   * [Nyheter i Adobe Experience Manager 6.5, Service Pack 4](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/new-features-latest-service-pack.html)
   * [Versionsinformation](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [AEM Forms-releaser](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.8.0**

   AEM 6.4, Service Pack 8.0 (6.4.8.0 släppt 5 mars 2020) är en viktig uppdatering som innehåller viktiga kundkorrigeringar som släppts sedan den allmänna tillgängligheten av AEM 6.4, april 2018.
   * [Versionsinformation](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [AEM Forms CFP-releaser](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.3.3.8**

   AEM 6.3, Service Pack 3, Cumulative Fix Pack 8 (6.3.3.8 släppt 5 mars 2019) är en viktig uppdatering som innehåller viktiga kundkorrigeringar som släppts sedan den allmänna tillgängligheten av AEM 6.3, april 2017.
   * [Versionsinformation](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [AEM Forms CFP-releaser](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM Assets Brand Portal**

   AEM Assets Brand Portal 6.4, Service Pack 6 (6.4.6 släppt 5 mars 2020) förändrar hur AEM Assets konfigureras med [!UICONTROL varumärkesportalen.] Dessutom innehåller releasen andra förbättringar och felkorrigeringar.
   * [Versionsinformation](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)

### Självhjälp

* **AEM som molntjänst - rollbaserade behörigheter**

   Molnhanteraren har förkonfigurerade roller med lämplig behörighet. Var och en av rollerna har specifika behörigheter, förkonfigurerade uppgifter eller behörigheter som är kopplade till varje roll. Hjälpavsnittet [Rollbaserade behörigheter](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/what-is-required/role-based-permissions.html) identifierar tillgängliga funktioner och vilka roller som kan köra dem.

* **AEM som en molntjänst - Dispatcher**

   Avsnitten [Dispatcher, CDN](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/dispatcher/overview.html#dispatcher-cdn) och [Explicit Dispatcher cache invalidation](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/dispatcher/overview.html#explicit-invalidation) uppdaterades för att klargöra vilka alternativ som är tillgängliga och hur de fungerar.

* **Konfigurera AEM-resurser med varumärkesportalen**

   AEM Assets har nu konfigurerats med [!UICONTROL varumärkesportalen] via Adobe I/O, som anskaffar en IMS-token för godkännande av innehavaren av varumärkesportalen. Tidigare konfigurerades den i Classic-gränssnittet med hjälp av [!UICONTROL äldre OAuth-gateway.]
Se [Konfigurera AEM-resurser med varumärkesportalen](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/publish/configure-aem-assets-with-brand-portal.html).

* **AEM som en molntjänst - Smart beskärning i dynamiska media**

   Ett nytt alternativ är tillgängligt i AEM som molntjänst när du arbetar med Smart beskärning i komponenten Dynamic Media:

   **Aktivera matchning** av proportioner - Välj det här alternativet om du vill att Dynamic Media ska välja en smart beskärningsåtergivning som bäst matchar originalbildens proportioner.
Se [När du arbetar med smart beskärning](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/adding-dynamic-media-assets-to-pages.html#when-working-with-smart-crop).

### Community

* **AEM SKill Builder-webbinarier**

   * AEM Sites - Med början 17 mars 2020 får du lära dig grunderna för hur man skapar innehåll och hur AEM Sites fungerar och fungerar. [Anmäl dig nu](https://aemskillbuilder-sites.experienceleague.adobeevents.com/register).
   * AEM Assets - Från och med 19 mars 2020 får du tips om dina kunskaper inom digital resurshantering och lär dig grunderna i varumärkesportalen, [!UICONTROL Dynamic Media,] [!UICONTROL Asset Link med] mera. [Anmäl dig nu](https://aemskillbuilder-assets.experienceleague.adobeevents.com/register).

### Ytterligare resurser

* [AEM som molntjänst](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)
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

### Campaign Classic

* [Uppdatering för Campaign Classic 19.1.4](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

### Ytterligare resurser

* Adobe Campaign Standard: [Dokumentation](https://helpx.adobe.com/support/campaign/standard.html) - [Versionsinformation](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [instruktionsvideor](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [Viktig planering](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Dokumentation](https://helpx.adobe.com/support/campaign/classic.html) - [Versionsinformation](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Videofilmer om hur du gör](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Kontrollpanelen för Adobe Campaign: [Dokumentation](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [Versionsinformation](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## ![Icon](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Uppdaterad 20 mars 2020 för 21 mars:

| Visa | Funktion |
|------|---------|
| [!UICONTROL Portföljer] | Du kan nu lägga till YDN-kampanjer ( [!DNL Yahoo!] Japan Display Network) i portföljer för att optimera kampanjbudgeten och annonserbjudanden på gruppnivå. Samma bud gäller för alla annonser i en annonsgrupp. Data för japanska Display Network-kampanjer ingår i simuleringarna för portföljen. |
| [!UICONTROL Sök] > [!UICONTROL Bulksheets] | Nu kan du skapa, redigera och ta bort responsiva sökannonser för Google med hjälp av kalkylblad. Tidigare fanns support endast via standardgränssnittet för kampanjhantering på **[!UICONTROL Search]** > **[!UICONTROL Campaigns]** |
| [!UICONTROL Sök] > [!UICONTROL Kampanjer, Rapporter] | Google Ads-presentationsmått `Impr. (Abs. Top) %` och `Impr. (Top) %` finns nu i alla grundläggande rapporter och kampanjhanteringsvyer på entitetsnivå, utom för kundproduktgrupper, [!UICONTROL Campaign Daily Impression Share] och [!UICONTROL Keyword Daily Impression Share] -rapporter samt i etiketter och begränsningsvyer. |

## ![Ikon](/assets/magento.png) [!DNL Magento]{#magento}

Versionsinformation om Magento finns i:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Ikon](/assets/marketo.png) [!DNL Marketo]{#marketo}

[!DNL Marketo Engage] är en komplett lösning för lead-hantering och B2B-marknadsförare som vill omvandla kundupplevelser genom att engagera sig i alla faser av komplexa inköpsresor.

### Uppdateringar om Core Marketo Engage

Releasedatum: 21 februari 2020

* **Microsoft Dynamics _Change Owner i Microsoft_Flow Action:** Ändra en lead- eller kontaktägare direkt från Marketo Engage.
* **Förbättringar av API-anrop:**
   * API:er för användarhantering
   * API:er för anpassade objektscheman
   * API:er för omdirigeringsregler för landningssidor
* **Cachelagring av formulärbeskrivare:** Förbättringar av landningssidor och formulär.

Mer information finns i [!DNL Marketo] versionsinformationen för [februari 2020](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) .

### Kommande funktioner

Följande funktioner släpps under hela kvartalet:

| Funktion | Beskrivning |
|------|---------|
| [!DNL Bizible] | <ul><li>Ny kontobaserad segmentering</li><li>Spara instrumentpanelsspecifika filter</li><li>Exportera dubbelsidiga kontrollpaneler som PDF-filer</li></ul> |
| Sales Connect | Disponera uppdateringar/förbättringar av fönster och kommandocentral |

### Meddelanden

**Marketo Engage Success Center:** Startar i februari 2020. Success Center är ett hjälpcenter i produkten som gör att du kan söka i produktdokument och communityn, starta guider, komma åt hjälpavsnitt och mycket annat. Obs! Den här funktionen lanseras som en betaversion i ANZ och kommer att lanseras i Nordamerika senare under kvartalet.

### Föråldringar

* **Resurs-API &quot;_method&quot;-parameter:** Efter september 2020 kommer Resurs-API-slutpunkter inte längre att acceptera &quot;_method&quot; för att skicka Query Parameters i ett POST-brödtext för att kringgå URI-längdbegränsningar.
* **Stöd för Internet Explorer har tagits bort:** Från och med juliversionen den 31 juli 2020 stöds inte längre gränssnittet Marketo Engage i Internet Explorer.

Information om kumulativa och historiska releaser finns i [Marketo-versionsinformation](https://docs.marketo.com/x/CgA6Ag).

## ![Ikon](/assets/experience-cloud.png) Ny dokumentation och självstudiekurser {#selfhelp}

Nya självhjälpsartiklar och videor. <!--`https://jira.corp.adobe.com/secure/Dashboard.jspa?selectPageId=60327`-->

| Lösning | Innehåll | Beskrivning |
|----------| -----------| ---------- |  
| [!UICONTROL AEM Commerce] | Video - [skapa flera kategori- och produktsidor](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/tutorials.html#!AdobeDocs/commerce-cif-documentation/master/tutorials/04-style-cif-component.md) | Lär dig hur du skapar ett minimalt CIF-projekt för Adobe Experience Manager (AEM) som utgångspunkt för kundprojekt med CIF Core Components. Använd tema och CSS-format på komponenter och inspektera ett nytt AEM CIF-projekt, som genereras av arkitypen. Läs också om hur CSS och JavaScript som används av CIF-kärnkomponenter är organiserade. |
| [!UICONTROL AEM-formulär] | Artikel - [Autentisera till AEM Author med OKTA](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/single-sign-on-with-okta.html) | Lär dig hur du konfigurerar appen på OKTA-portalen och om de inställningar som du vanligtvis använder när du registrerar nya program. |
| [!UICONTROL AEM Commerce] | Självstudiekurs - [Anpassa CIF-kärnkomponenter](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/tutorials.html#!AdobeDocs/commerce-cif-documentation/master/tutorials/05-customize-cif-components.md) | Granska flera olika tilläggspunkter från CIF Core Components och AEM i allmänhet. CIF Core Components innehåller en standarduppsättning med Commerce-komponenter som kan användas för att snabba upp ett projekt som integrerar Adobe Experience Manager- (AEM) och Magento-lösningar. |
| [!DNL Adobe Campaign] - Målgrupper | Video - [Create an audience...](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/creating-audiences-using-segment-builder.html) | Skapa en målgrupp i Campaign Standard med Adobe [!UICONTROL Experience Platform Segment Builder]. Du kan komma åt den här funktionen direkt i Adobe Campaign Standard via [!UICONTROL målgruppsmodulerna] . |
| [!DNL Adobe Campaign] - Målgrupper | Video - [aktivera Adobe Experience Platform-målgrupper i ett marknadsföringsarbetsflöde](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/activating-aep-audiences.html) | Lär dig hur du aktiverar [!UICONTROL Data Services Query Audience] i ett arbetsflöde genom att använda aktiviteten [!UICONTROL Läs målgrupp] . |
| [!DNL Adobe Campaign] | Självstudiekurs - [push-meddelanden med Android](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/communication-channels/mobile/push/getting-started-push-notifications/getting-started-with-push-notifications-android.html) | Skicka personaliserade och segmenterade push-meddelanden till iOS- och Android-mobilenheter. I den här självstudiekursen får du hjälp med att skicka push-meddelanden från Adobe Campaign och ta emot dessa meddelanden i din Android-app. |
| [!DNL Adobe Campaign] | Video - [Skapa ett push-meddelande](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/communication-channels/mobile/push/creating-a-push-notification.html) | Skapa ett push-meddelande i Adobe Campaign Standard. Du kan skicka personaliserade och segmenterade push-meddelanden till iOS- och Android-mobilenheter. |
| [!DNL Adobe Campaign] - AEP Data Connector | Video - [Kontrollera status för ett dataöverföringsjobb](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/checking-status-of-data-ingestion-jobs.html) | Lär dig hur du kontrollerar statusen för ett dataöverföringsjobb och om data har importerats från Adobe Campaign Standard till Adobe Experience Platform. |
| [!DNL Adobe Campaign] - AEP Data Connector | Video - [Ändra datamappning](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/modifying-data-mapping.html) | Lär dig hur du kontrollerar status och ändrar datamappningen. |
| [!DNL Adobe Campaign] - AEP Data Connector | Video - [Kartupplevelsehändelser](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-experience-events.html) | Lär dig kartlägga upplevelsehändelser i Adobe Experience Platform. |
| [!DNL Adobe Campaign] - AEP Data Connector | Video - [Karta - anpassade resurser](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-custom-resources.html) | Lär dig hur du mappar olika datatyper mellan Adobe Campaign Standard och Adobe Experience Platform. |
| [!DNL Adobe Campaign] - AEP Data Connector | Video - [Förstå Adobe Experience Platform Data Connector](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/understanding-the-adobe-experience-platform-data-connector.html) | Lär dig hur du gör dina data tillgängliga på Adobe Experience Platform genom att mappa XTK-data (data som importerats i Campaign) till Experience Data Model-data (XDM) på Adobe Experience Platform. |
| [!DNL Adobe Campaign] - AEP Data Connector | Video - [Mappa starttabelldata](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-seed-table-data.html) | Lär dig hur du mappar startdata/testprofiler med Adobe Experience Platform. |
| [!DNL Adobe Campaign]- Målgrupper | Video - [Ändra målinriktningsdimensionen för en leverans för en plattformspublik](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/changing-targeting-dimension.html) | Lär dig hur du ändrar målgruppsdimensionen för en leverans för en plattformsmålgrupp utanför den primära profiltabellen i Adobe Campaign Standard. |
| [!DNL Adobe Campaign] | Video - [Big data management på Snowflake](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | Dra nytta av Snowflake-kontakten i Adobe Campaign Classic. |
| [!DNL Adobe Campaign] - Målgrupper | Artikel - [Målgrupper (BETA) - Översikt](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/audience-destinations-overview.html) | Lär dig utnyttja centraliserade och konsoliderade profildata från Adobe Experience Platform för marknadsföringskampanjer i Adobe Campaign Standard. |
| [!DNL Adobe Target] - Mobile SDK | Självstudiekurs - [Anpassa appupplevelser med Adobe Target](https://docs.adobe.com/content/help/en/target-learn/mobile-sdk-v4-android/overview.html) | Implementera Adobe Target i din egen Android-app. Validera konfigurationen av SDK för mobila tjänster och implementera [!DNL Target] förfrågningar som förhämtning av innehåll, blockeringsförfrågningar och mycket annat. |
| Adobe Analytics | Video - [Adobe Summit 2019 Super Session](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-high-tech.html) | Se välstrukturerade klipp från den högteknologiska supersessionen på Summit 2019. |
| Adobe Analytics | Video - [introduktion till beräknade värden i kundreseanalys](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/introduction-to-calculated-metrics-in-customer-journey-analytics.html) | Gå igenom grunderna för att skapa [!UICONTROL beräknade värden] i [!UICONTROL kundreseanalyser]. |
| Adobe Analytics | Video - [Adobe Summit 2019 Super Session](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-travel.html) | Se kuraterade klipp från rese- och turismsessionen på Summit 2019. |
| Adobe Analytics | Video - [Adobe Summit 2019 Super Session](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-retail.html) | Se kuraterade klipp från butikssessionen på Summit 2019. |
| Adobe Analytics | Video - [kundens användningsfall: Accent Group investerar i kundupplevelsen för att öka försäljningen](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/accent-group-invests-in-customer-experience-to-drive-sales.html) | Se hur Accent Group använder Adobe Experience Cloud för att skapa sömlösa digitala upplevelser. |
| Adobe Analytics | Video - [kundens användningsfall: ServiceNow får rätt insikter för att kommunicera med potentiella kunder](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/servicenow-gets-the-right-insights-to-connect-with-prospects.html) | Ta reda på hur [!DNL ServiceNow] får användbara data från dess marknadsföringskanaler och ökar avkastningen på betald sökannonsering med Adobe Advertising Cloud och Adobe Analytics. |
| Adobe Analytics | Video - [Adobe Analytics - It&#39;s More Than Data It&#39;s Customer Intelligence](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-analytics-customer-intelligence.html) | Lär dig mer om datadriven marknadsföring och hur ni kan ta er analysmognad till allt från data till insikter till åtgärder. |
| Adobe Analytics | Video - [Adobe Sensei och Adobe Analytics - Extended Version](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-sensei-and-adobe-analytics.html) | Se de viktigaste funktionerna i Adobe Analytics, som bygger på Adobe [!DNL Sensei,] inklusive [!UICONTROL avvikelseidentifiering,] [!UICONTROL bidragsanalys,][!UICONTROL intelligenta aviseringar,] [!UICONTROL kluster,] segmentanalys,Propensity och  [!UICONTROL segmentmodellering.] |
| Adobe Analytics | Video - [Hur Adobe Analysis Workspace kan förändra ert företag](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/how-adobe-analysis-workspace-can-change-your-business.html) | Lär dig hur du kan utföra ad hoc-analyser, flexibel analys, kohortanalys och utfallsanalys med [!UICONTROL Analysis Workspace]. Du kan också dela analysarbetsmiljön med alla på företaget, och med dra-och-släpp-funktionen kan alla enkelt analysera data och få insikter snabbt. |
| Adobe Analytics | Video - [kundens användningsfall: Home Depot Innovates med Customer Experience Management](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/the-home-depot-innovates-with-customer-experience-management.html) | Läs om hur ni [!DNL Home Depot] använder Adobes lösningar för att skapa varumärkeslojalitet och kundnöjdhet med en personaliserad, anpassad shoppingupplevelse. |
| Adobe Analytics | Presentation - [Förstå kundreseanalys](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/understanding-customer-journey-analytics.html) | Läs om hur Adobes [!UICONTROL kundreseanalys], en applikationstjänst som bygger på [!DNL Adobe Experience Platform], tar in [!UICONTROL Analysis Workspace] i Experience Platform. Med den här funktionen kan du göra flerkanalsanalyser av alla dina [!DNL Adobe Experience Platform] datauppsättningar. |
| Adobe Analytics | Video - [Cross-Channel Attribution i CJA](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/cross-channel-attribution-in-customer-journey-analytics.html) | Lär dig hur ni kan använda visualiseringar för att visa attribuering (ge krediter) i olika kanaler i [!UICONTROL kundreseanalysen]. |
| Adobe Analytics | Artikel - [Kundtips om hur du kan fortsätta din Adobe Analytics-utbildningsresa](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/tips-and-tricks/customer-tips-for-continuing-your-adobe-analytics-learning-journey.html) | Träffa tre Adobe-kunder som har tips och tricks om hur ni får ut det mesta av Adobe Analytics. |
| Adobe Analytics | Video - [Skapa visualiseringar över flera kanaler i CJA](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/creating-cross-channel-visualizations-in-customer-journey-analytics.html) | Upptäck hur [!UICONTROL kundreseanalys] gör det möjligt att skapa visualiseringar som inkluderar data från flera datauppsättningar över flera kanaler, inklusive att sammanfoga data per besökare. |
| Adobe Analytics | Video - [Flytta dina beräknade värden från Adobe Analytics till kundreseanalys](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/moving-your-calculated-metrics-from-adobe-analytics-to-customer-journey-analytics.html) | Hitta tips för att återskapa [!UICONTROLCberäknade analysvärden] i [!UICONTROL kundreseanalys]. |
