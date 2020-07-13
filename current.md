---
title: Versionsinformation om Adobe Experience Cloud
description: Versionsinformation om Adobe Experience Cloud
doc-type: release notes
last-update: July 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 19591a3d807cd772df0eb20e457d94cc9f7d5cfb
workflow-type: tm+mt
source-wordcount: '4123'
ht-degree: 58%

---


# Tidig åtkomst - Versionsinformation om Adobe Experience Cloud - juli 2020

![Banderoll](/assets/experience-cloud-banner-3.png)

Den här sidan beskriver nya funktioner, korrigeringar och viktiga meddelanden i [!DNL Adobe Experience Cloud]. Här finns också ny dokumentation, kurser och videokurser som hjälper dig att få ut mesta möjliga av Experience Cloud.

>[!IMPORTANT]
>
>Den här sidan innehåller innehåll som släppts i förväg och omfattas av ändringar före den planerade releasen.

>[!NOTE]
>
>Prenumerera på [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) om du vill få meddelanden via e-post om kommande versioner.

**Releasedatum: 16 juli 2020**

Datum för produktreleaser kan variera. Leta ofta efter uppdateringar.

Senaste uppdatering: **10 juli 2020**

* [Adobe – systemstatus](#status)
* [Experience Cloud-gränssnitt](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Analyser](#analytics) och [Customer Journey Analytics](#cust-journey)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/sv-SE/target/using/release-notes/target-release-notes.html)
* [!DNL Magento](#magento)
* [!DNL Marketo Engage](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/se/primetime/user-guide.html) (länkar till Primetimes hjälpsida)

Behöver du hjälp? Besök [Adobe Experience League](https://experienceleague.adobe.com/#home) för att hitta produkt- och teknisk dokumentation, kurser, videokurser, snabbsvar, communityinsikter och lärarledd utbildning.

## ![Ikon för](/assets/adobe.png) Adobe – systemstatus {#status}

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

## ![Ikonen i](/assets/ec_appicon_24.png) Experience Cloud-gränssnittet {#ecloud}

Allmänna uppdateringar av gränssnittet i Experience Cloud.

**Uppdaterad gränssnittsmeny**

I Experience Cloud uppdateras listrutan Programväljare i **juli 2020** -versionen. Den har strömlinjeformats så att logotyper för lösningar tas bort och menyn visar endast de program och tjänster som du har tillgång till.

Ett exempel finns i [produktdokumentationen](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html) för gränssnittetExperience Cloud.

**Enhetlig produktdomän**

Adobe har uppdaterat domänen och gränssnittets sidhuvud för att skapa en enhetlig och förbättrad upplevelse i alla Experience Cloud-program. Dessa förbättringar är utformade för att förenkla upplevelsen på små, men viktiga sätt. Förbättringarna ändrar inte dina aktuella arbetsflöden.

Bland uppdateringarna finns:

* Nya program-URL:er: `experience.adobe.com/<application name>`:
   * Alla produkter kommer så småningom att använda det här URL-mönstret. Titta efter nya URL:er som börjar gälla under månaden.
   * Stöd för webbläsare: De webbläsare som stöds är [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] och [!DNL Opera] (de senaste versionerna). **Obs!** Trots att Experience Cloud-gränssnittet har stöd för dessa webbläsare kanske inte enskilda program har stöd för alla webbläsare. ([Analytics](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html) har till exempel inte stöd för [!DNL Opera] och [Target](https://docs.adobe.com/help/sv-SE/target/using/implement-target/before-implement/supported-browsers.html) har inte stöd för [!DNL Safari].)
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

## ![Ikon för](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Versionsinformation för [!DNL Experience Platform] inklusive [!DNL Experience Platform Launch,] [!UICONTROL Offers], [!UICONTROL People], [!UICONTROL Places], [!UICONTROL Mobile Services], och säkerhetsbulletiner.

Latest release date: **June 10, 2020**

I versionsinformationen [för](https://docs.adobe.com/content/help/sv-SE/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md) Experience Platform finns den senaste informationen om Experience Platform.

## ![Ikon](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Med Adobe Experience Platform kan ni orkestrera enskilda kundresor i stor skala över olika upplevelsekanaler genom att intelligent förutse varje enskild individs behov i realtid, oavsett vart resan bär.

### Ytterligare resurser för resesamordning

[Dokumentation](https://docs.adobe.com/content/help/sv-SE/journeys/using/journey-orchestration-home.html) – [Versionsinformation](https://docs.adobe.com/content/help/sv-SE/journeys/using/release-notes/release-notes.html) – [Instruktionsvideor](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

## ![Ikon](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Releasedatum: **16 juli 2020**

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
| Arbetsyta: Nya förinställningar för datumintervall | Lagt till fyra nya datumintervall (_Denna vecka/månad/kvartal/år_ (förutom idag)) så att användare kan välja från datumintervall som inte innehåller data för delar av dagen från och med idag. |
| API för datareparation - betaversion | API:t för datareparation är ett självbetjäningsalternativ för kunder som vill ta bort kolumner med Adobe Analytics-data. När den allmänna betaversionen släpps kommer API:t att ha stöd för att ta bort data från Activity Map. Ytterligare funktioner kommer att lanseras senare. Kontakta kundtjänst för att få tillgång till detta API. |

### Nya funktioner i Customer Journey Analytics {#cust-journey}

| Funktion | [Allmän tillgänglighet](https://docs.adobe.com/content/help/sv-SE/analytics/landing/an-releases.html) – Måldatum | Beskrivning |
| -----------| ---------- |-----|
| Inga nya funktioner den här månaden |  |  |

### Nya funktioner i [!UICONTROL Media Analytics] {#media-aa}

Uppdaterat den: **16 juli 2020**

| Funktion | [Allmän tillgänglighet](https://docs.adobe.com/content/help/sv-SE/analytics/landing/an-releases.html) – Måldatum | Beskrivning |
| -----------| ---------- | ---------- |
| [Enheter och plattformar som stöds](https://docs.adobe.com/content/help/sv-SE/media-analytics/using/supported-devices.html) | 18 juni 2020 | Media Launch Extension med AEP SDK har nu stöd för följande OTT-enheter:<ul><li>Apple TV (tvOS)</li><li>Fire TV (Fire OS)</li><li>Android TV</li></ul> |  | [Enheter och plattformar som stöds](https://docs.adobe.com/content/help/sv-SE/media-analytics/using/supported-devices.html) | 18 juni 2020 | Media Launch Extension med AEP SDK har nu stöd för följande OTT-enheter:<ul><li>Apple TV (tvOS)</li><li>Fire TV (Fire OS)</li><li>Android TV</li></ul> |
| [Spårning av spelarens tillstånd](https://docs.adobe.com/content/help/sv-SE/media-analytics/using/player-state-tracking/player-state-overview.html) | 29 maj 2020 | [!UICONTROL Media Analytics]-kunder kan samla in tittarinteraktioner under uppspelning med en standarduppsättning lösningsvariabler för helskärmsvisning, undertexter, ljud av, bild-i-bild och i fokus. Du kan också skapa anpassade spelarlägen. Variabler för spårning av spelarstatus är nu tillgängliga för rapportering i [!UICONTROL Analysis Workspace]. Den här funktionen kräver något av följande: <ul><li>Media [!DNL JavaScript] SDK 3.0 eller senare</li><li>För användning med [!DNL Adobe Experience Platform] (AEP) SDK:</li><li>[!UICONTROL Media Analytics Extension] (för webb): [!UICONTROL Adobe Media Analytics] (3.x SDK) för ljud och video v1.0 eller senare</li><li>[!UICONTROL Media Analytics Extension] (för mobil): [!UICONTROL Adobe Media Analytics for Audio] och video v2.0 eller senare</li><li>[!UICONTROL Media Collection]</li></ul> |

### Korrigeringar i Adobe Analytics {#aa-fixes}

* Korrigerade ett problem som uppstod efter växling till en rapportserie med en annan valuta. Raddiagrammet [!UICONTROL Workspace] återspeglar inte rätt valuta. (AN-216655)
* Problem med att visualiseringar inte kan läsas i hämtade PDF-filer har åtgärdats. (AN-217949)
* Korrigerade ett problem som orsakade ett fel när en hierarkivariabel lades till i en rapportserie. (AN-211974)
* Ett problem som uppstod när en datafeed som är kopplad till en rapportsvit som har en annan tidszon än den valda [!UICONTROL Reports & Analytics] rapportsviten redigerades har åtgärdats. (AN-222474)
* Fixed an issue with the [!UICONTROL Classification Rule Builder] not working. (AN-219662)
* Flera problem med klassificerings- och klassificeringsregler har korrigerats. (AN-223492, AN-220654, AN-219662, AN-223260)
* Korrigerade ett problem med att samma segment returnerade olika data i en virtuell rapportsvit jämfört med den överordnade rapportsviten. (AN-201074)
* Ett problem som gjorde att inställningarna för rapportsviten inte kunde hämtas har åtgärdats. (AN-223690)
* Ett problem som gjorde [!UICONTROL Intelligent Alerts] att e-postlänken _avanmälan från schemat_ inte fungerade har åtgärdats. (AN-223875)
* Korrigerade ett problem med felaktig visning av valuta för en virtuell rapportsvit. (AN-224781)
* Korrigerade ett problem med _saknade komponenter_ i virtuella rapportsviter. (AN-224782)

#### Övriga korrigeringar i Adobe Analytics

AN-222672, AN-222813; AN-222892; AN-223272, AN-223432; AN-224062; AN-224108; AN-224163; AN-224339; AN-224456; AN-224449; AN-224552; AN-224553; AN-224786

### Viktiga meddelanden för [!DNL Analytics]-administratörer {#aa-notices}

| Meddelande | Datum tillagt eller uppdaterat | Beskrivning |
| -----------| ---------- | ---------- |
| Rapportera mappning av programsvit till IMS-organisation | Juli 2020 | Rapportsvitens mappningsverktyg kommer att upphöra i november 2020. Den här funktionen hanterar integreringar som Advertising Analytics och Experience Cloud i segmentpubliceringen i Adobe Analytics. En rapportsvit måste mappas till en IMS-organisation för att dessa och andra tjänster ska kunna aktiveras. Nyare rapportsviter mappas automatiskt när de skapas. Äldre rapportsviter måste dock mappas manuellt till en IMS-organisation. Se [Mappa rapportsviter till en organisation](https://docs.adobe.com/content/help/sv-SE/core-services/interface/about-core-services/report-suite-mapping.html) i användarhandboken för bastjänster för att se till att alla rapportsviter tillhör en IMS-organisation. |
| Migrering till den enhetliga produktdomänen | Datum för ikraftträdande: 28 maj 2020 | Övergången till en enhetlig produktdomän för Adobe Analytics, som började i januari 2020, slutfördes den 28 maj 2020. Adobe Analytics utelämnar alla `omniture.com`-domänreferenser från arkitekturen, men det är viktigt att vitlista `omniture.com` som en cookie från tredje part. När den fullständiga arkitekturmigreringen (snart) är klar kommer vi att meddela dig via release-notiserna och detta tillåtelseliststeg kommer inte längre att behövas. [Här](https://helpx.adobe.com/se/analytics/kb/adobe-ip-addresses.html) är en fullständig lista över rekommenderade IP-adresser och domäner som du bör vitlista.<br>Om din organisation blockerar cookies från tredje part kan du kontakta kundtjänst för att få tillgång till Adobe Analytics igen. |
| Ny startsida för Adobe Analytics | Startdatum: 18 juni 2020 | Den 18 juni 2020 ändras standardlandningssidan för Adobe Analytics från [!UICONTROL Reports] till [!UICONTROL Workspace]. Den här ändringen sker för användare som inte tidigare har angett en anpassad landningssida. |
| Tredjepartsteknologi | 12 mars 2020 (giltighetsdatum) | Adobe Analytics har börjat utnyttja teknik från tredje part för funktionshantering och produktsupport. Följande URL:er ska läggas till alla nödvändiga nätverksbrandväggstillstånd för att säkerställa fullständig åtkomst till funktionen:<ul><li>Gainsight: https://esp.aptrinsic.com</li><li>LaunchDarkly: https://app.launchdarkly.com</li></ul> |
| Förbättrad redundans för [!UICONTROL Analysis Workspace] tillgänglighet | 21 maj 2020 | Vi lägger till ett sekundärt CDN (Content Delivery Network) för förbättrad redundans och säkerställa tillgänglighet till [!UICONTROL Analysis Workspace]. Följande URL:er ska läggas till alla nödvändiga nätverks brandväggstillståndslistor:<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul> |
| Ändra hur [!UICONTROL Entries/Exits] beräknas i [!UICONTROL Workspace] | 7 april 2020 | Från och med mars 2020, har vi ändrat hur värdet _Inga_ interagerar med [!UICONTROL Entries/Exits] i [!UICONTROL Analysis Workspace]. Eftersom du nu kan aktivera och inaktivera _Inga_ i [!UICONTROL Analysis Workspace] använder vi värdet _Inga_ efter första eller sista besökssidan i stället för före (för eVars). Anta till exempel att den första träffen för ett besök inte har ett värde för eVars, men att den andra träffen har det. I [!UICONTROL Reports & Analytics] visas den första träffen som _Ospecificerat_ för första besökssidan, men i [!UICONTROL Analysis Workspace] visas det som ett värde för den andra träffen. |
| **[!UICONTROL Dashboard Archive]** tas bort | 27 mars 2020 | Inställningen **[!UICONTROL View Archive]** under **[!UICONTROL Manage Dashboards]** i [!UICONTROL Reports & Analytics] är inte tillgänglig från och med oktober 2020. |
| Slutet av livscykeln – äldre API:er för Analytics | 9 januari 2020 | I november 2020 kommer följande äldre API-tjänster för Analytics att ha nått slutet av sina livscykler och avslutas. Aktuella integreringar som byggts med dessa tjänster kommer att sluta fungera. <ul><li>1.3 API:er för Analytics</li><li>1.4 API:er för SOAP Analytics</li><li>Äldre OAuth-autentisering (OAuth och JWT)</li></ul>Vi har tagit fram [vanliga frågor och svar om upphörande av äldre API:er](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) som kan hjälpa dig att få svar på frågor och ge vägledning om hur du går vidare. API-integrationer som använder dessa tjänster kan migrera till [1.4 Analytics REST-API:er](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) eller [2.0 Analytics API:er](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Äldre OAuth-konton kan migrera till ett [Adobe IO](https://console.adobe.io/home?mv=email) Analytics-integreringskonto som kan användas för att få tillgång till både 1.4 Analytics API:er och 2.0 Analytics API:er. |
| San Jose FTP-hantering upphör för London och Singapore | Juli 2020 | För kunder i London och Singapore stöder vi inte längre datahantering mellan London eller Singapore och datacentret [ftp.omniture.com](ftp://ftp.omniture.com/) i San Jose.<br/><ul><li>I London använder du [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>I Singapore använder du [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Ad Hoc Analysis upphör | 6 aug 2018 | Adobe har meddelat att man avser att dra tillbaka Ad Hoc Analysis. Ett slutdatum meddelas så snart det är tillgängligt. Mer information finns i [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

#### AppMeasurement

Uppdaterad information om de senaste AppMeasurement-versionerna finns i [versionsinformationen för AppMeasurement för JavaScript](https://docs.adobe.com/content/help/sv-SE/analytics/implementation/appmeasurement-updates.html).

#### Hjälpresurser för Analytics

* [Adobe Analytics självstudiekurser](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Adobe Analytics – produktdokumentation](https://docs.adobe.com/content/help/sv-SE/analytics/landing/home.html)

## ![Ikonen](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Nya funktioner, korrigeringar, dokumentation och självstudiekurser för Audience Manager.

Releasedatum: **16 juli 2020**

### Nya funktioner och korrigeringar i Adobe Audience Manager

* Korrigerade ett problem där kunderna inte kunde mappa vissa segment till Amazon-destinationer. (AAM-54373)
* Korrigerade ett problem där webbläsarskärmen skulle frysa när kunderna öppnade ett segment på en ny flik. (AAM-55213)
* Korrigerade ett problem i [rapporten](https://docs.adobe.com/help/en/audience-manager/user-guide/reporting/onboarding-status-report.html)om introduktionsstatus, där kunderna kunde se ett datummatchningsfel mellan datumet när de klickade på ett fält i diagrammet och datumet i tabellen. (AAM-55235)
* Korrigerade ett fel i administrationsavsnittet där användargränssnittet skulle visa en felikon i stället för ett bekräftelsemeddelande när kunderna försökte ta bort användare. (AAM-55186)
* Korrigerade ett problem med Swagger-API:t, där sidhuvudet inte lades till i `x-api-key` begäran. (AAM-55392)
* Förbättrad standardsorteringsordning för segment som mappas till mål i målvyn. De mappade segmenten sorteras nu efter startdatum för segmentmappningen och sedan efter segment-ID. (AAM-38494)
* Flera tillgänglighetsförbättringar i hela gränssnittet. (AAM-48956, AAM-49012, AAM-49364, AAM-49363, AAM-49374, AAM-49579, AAM-55037).

## ![Ikonen för](/assets/aem.png) Adobe Experience Manager {#aem}

Nya funktioner, korrigeringar och uppdateringar i Adobe Experience Manager (AEM). Adobe rekommenderar att kunder med lokala distributioner driftsätter de senaste korrigeringarna för bättre stabilitet, säkerhet och prestanda.

### Uppdateringar

* **Dynamic Media Classic**

   Dynamic Media Classic-användare har nu tillgång till en ny skrivbordsappsupplevelse som inte längre är beroende av Adobe Flash-teknik i webbläsaren. Den nya appen finns nu för Windows och macOS.

   Se [Adobe Dynamic Media Classic för datorer - nu tillgängligt.](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/new-ui-2020.html)

* **Stöd för 3D-resurser som lagts till i Dynamic Media**

   Med Dynamic Media i AEM 6.5 och AEM som Cloud Service kan du nu överföra, hantera, visa och leverera 3D-resurser som engagerande upplevelser.

   * I AEM som Cloud Service, se [Arbeta med 3D-resurser i Dynamic Media.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/assets-3d.html)
   * I AEM 6.5, se [Arbeta med 3D-resurser i Dynamic Media.](https://docs.adobe.com/content/help/en/experience-manager-65/assets/dynamic/assets-3d.html)

### Självhjälp

* **Uppdateringar av AEM 6.5.5-formulärdokumentation**

   * Nya funktioner och förbättringar i version 6.5.5:

      * [Anpassa kolumnerna](https://docs.adobe.com/content/help/en/experience-manager-65/authoring/essentials/inbox.html#inbox-admin-control)i Inkorgen Adobe Experience Manager.
      * [Spara interaktiv kommunikation som ett utkast.](https://docs.adobe.com/content/help/en/experience-manager-65/forms/interactive-communications/prepare-send-interactive-communication.html#save-as-draft)
      * Stöd för Oracle WebLogic-programservrar för [enskilda server](https://helpx.adobe.com/content/dam/help/en/experience-manager/6-5/forms/pdf/prepare-install-single-server.pdf) - och [klusterinstallationer](https://helpx.adobe.com/content/dam/help/en/experience-manager/6-5/forms/pdf/prepare-install-cluster.pdf) .
      * [Tillgänglighetsförbättringar.](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/new-features-latest-service-pack.html#accessibility-improvements)
      * [X-509 certifikatbaserad autentisering för SOAP-baserade webbtjänster i formulärdatamodellen.](https://docs.adobe.com/content/help/en/experience-manager-65/forms/form-data-model/configure-data-sources.html#configure-soap-web-services)
      * [Stöd för Oracle RAC.](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/new-features-latest-service-pack.html#other-improvements)
      * [Förbättrad felloggning i transaktionsrapportering.](https://docs.adobe.com/content/help/en/experience-manager-65/forms/transaction-reports/viewing-and-understanding-transaction-reports.html#view-transaction-reporting-logs)
   * Nya funktioner och förbättringar i version 6.4.8.1:
      * [X-509 certifikatbaserad autentisering för SOAP-baserade webbtjänster i formulärdatamodellen.](https://docs.adobe.com/content/help/en/experience-manager-64/forms/form-data-model/configure-data-sources.html#configure-soap-web-services)
      * [Förbättrad felloggning i transaktionsrapportering.](https://docs.adobe.com/content/help/en/experience-manager-64/forms/transaction-reports/viewing-and-understanding-transaction-reports.html#view-transaction-reporting-logs)

### **Community**

* **AEM Community-diskussion**

   Nu kan du se alla AEM-meddelanden och intressanta referenser till interna och externa bloggare på ett och samma ställe. Se [Diskussionsavsnittet](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/bd-p/adobe-experience-manager-discussions) i AEM Community.

### Nya Experience Manager-kurser och självstudiekurser

Nya videor, självstudiekurser eller kurser som publicerats under den senaste månaden.

| Publicerad | Namn | Typ | Beskrivning |
| -----------| ---------- | ---------- | ---------- |
| 25 juni 2020 | [Komma igång med adaptiva formulär](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/creating-your-first-adaptive-form/adaptive-forms-getting-started-tutorial-use.html) | Video | De här självstudiekurserna vägleder dig genom de steg som krävs för att skapa anpassade formulär med flera flikar. Lär dig använda tabeller, dragspelslayout och regelredigerare för att skapa affärsregler. |
| 25 juni 2020 | [Skapa ett granskningsarbetsflöde i AEM Forms](https://video.tv.adobe.com/v/35821/quality=9?captions=swe) | Video | Lär dig skapa ett arbetsflöde för att granska skickade data från en aktiv formulärsändning. |
| 23 juni 2020 | [Bearbeta profiler](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/processing-profiles.html) | Video | Bearbetningsprofiler definierar de återgivningar som ska skapas för resurser i AEM som en Cloud Service. |
| 23 juni 2020 | [Dynamic Media Classic - bästa praxis](https://docs.adobe.com/content/help/en/experience-manager-learn/dynamic-media-classic-tutorial/overview.html) | Artikel | Befintliga och nya användare kan lära sig mer om Dynamic Media Classic, dess kärnfunktioner samt _arbetsflödet för att skapa_, _skapa_ och _leverera_ . |
| 23 juni 2020 | [Felsöka AEM som Cloud Service och driftsätta](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-as-a-cloud-service/build-and-deployment.html) | Artikel | Lär dig hur du felsöker bygge och distributioner för AEM som en Cloud Service. |
| 16 juni 2020 | [Felsöka AEM som en Cloud Service med hjälp av loggar](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-as-a-cloud-service/logs.html) | Artikel | Lär dig hur du använder loggar för att felsöka AEM som en Cloud Service. Loggar fungerar som en frontlinje för felsökning av AEM-program, men är beroende av korrekt inloggning i det distribuerade AEM-programmet. |
| 10 juni 2020 | [Använda Dynamic Media 3D med AEM Assets](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/dynamic-media/dynamic-media-3d-feature-video.html) | Video | Med Dynamic Media 3D-stöd för Adobe Experience Manager kan du enkelt anpassa och leverera interaktiva 3D-upplevelser i stor skala. |
| 5 juni 2020 | [SPA Editor-projekt](https://docs.adobe.com/content/help/en/experience-manager-learn/spa-react-tutorial/create-project.html) | Artikel | Lär dig hur du använder projekttypen Adobe Experience Manager (AEM) för att generera ett Maven-projekt med flera moduler som utgångspunkt för ett React-program som är integrerat med AEM SPA Editor. |
| 3 juni 2020 | [Hantera inskickning av HTML5-formulär - självstudiekurs](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/html5-forms/handle-mobile-form-submission.html) | Artikel | Lär dig hur du får åtkomst till skickade data i den anpassade överföringshanteraren. |

### Versionsinformation för Experience Manager

Alla versionsinformation för Experience Manager finns på följande sidor:

* [AEM som Cloud Service](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/release-notes/home.html)
* [AEM Cloud Manager – versionsinformation](https://docs.adobe.com/content/help/sv-SE/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Versionsinformation om automatisk formulärkonverteringstjänst](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/using/release-notes.html)
* [Versionsinformation om AEM 6.5 Service Pack](https://docs.adobe.com/content/help/sv-SE/experience-manager-65/release-notes/service-pack/sp-release-notes.translate.html)
* [Versionsinformation om AEM 6.4 Cumulative Fix Pack](https://docs.adobe.com/content/help/sv-SE/experience-manager-64/release-notes/cfp-release-notes.translate.html)
* [Versionsinformation för AEM Assets Dynamic Media](https://docs.adobe.com/content/help/sv-SE/dynamic-media-developer-resources/release-notes/s7rn2017.translate.html)
* [Versionsinformation om AEM Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)
* [Versionsinformation för AEM-skrivbordsapp](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/release-notes.html)
* [Versionsinformation om AEM Dispatcher](https://docs.adobe.com/content/help/en/experience-manager-dispatcher/using/getting-started/release-notes.html)
* [Versionsinformation om Adobe Primetime](https://docs.adobe.com/content/help/en/primetime/release-notes/home.html)
* [Versionsinformation för Livefyre](https://docs.adobe.com/content/help/sv-SE/livefyre/using/release-notes/c-rn.html)

### Ytterligare hjälpresurser för AEM

* [AEM som användarhandbok för Cloud Service](https://docs.adobe.com/content/help/sv-SE/experience-manager-cloud-service/landing/home.html)
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

* Ny stabil Gold Standard-version. [Läs mer](https://docs.adobe.com/content/help/sv-SE/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

#### Campaign Control Panel

* Granskning av deldomänsleverans - [Läs mer](https://docs.adobe.com/content/help/en/control-panel/using/subdomains-and-certificates/setting-up-new-subdomain.html)

* Hantering av GPG-nycklar - [Läs mer](https://docs.adobe.com/content/help/en/control-panel/using/instances-settings/gpg-keys-management.html)

### Nya kurser och självstudiekurser i Campaign

Nya videor, självstudiekurser eller kurser som publicerats under den senaste månaden.

| Publicerad | Namn | Lösning | Beskrivning |
| ----------- | ----------- | ---------- | ---------- |  
| 26 juni 2020 | [Utforska användargränssnittet i Adobe Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/exploring-the-adobe-campaign-classic-user-interface.html) | Campaign Classic | I den här videon förklaras huvudgränssnittet i Adobe Campaign Classic och du får se hur du navigerar i huvudfunktionerna. |
| 8 juli 2020 | [Installera och konfigurera Adobe Campaign-klienten](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/install-and-setup-the-adobe-campaign-client.html) | Campaign Classic | Lär dig hur du hämtar och installerar Adobe Campaign-klientkonsolen, skapar och hanterar anslutningar till flera miljöer och verifierar åtkomst till Adobe Campaign-klientkonsolen. |
| 19 juni 2020 | [Introduktion till Adobe Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/introduction-to-adobe-campaign-classic.html) | Campaign Classic | Läs om hur Adobe Campaign Classic passar in i Adobe Digital Experience-portföljen, liksom i de viktigaste funktionerna. |
| 12 juni 2020 | [Distribuera en mall för tillfällig e-postleverans](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/using-delivery-templates/deploying-ad-hoc-email-delivery-template.html) | Campaign Classic | Lär dig hur du distribuerar en tillfällig e-postmall |
| 12 juni 2020 | [Konfigurera en leveransmall](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/using-delivery-templates/configuring-a-delivery-template.html) | Campaign Classic | Lär dig hur du konfigurerar en e-postmall |
| 12 juni 2020 | [Ange egenskaper för leveransmall](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/using-delivery-templates/setting-delivery-template-properties.html) | Campaign Classic | Lär dig hur du anger egenskaper för e-postmallar |
| 12 juni 2020 | [GPG-nyckelhantering](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/gpg-key-management-overview.html) | Campaign Classic/Kontrollpanelen | Lär dig hur du skapar och installerar ett offentligt/privat GPG-nyckelpar för datakryptering och hur du importerar och installerar en offentlig nyckel för datadekryptering. |
| 26 juni 2020 | [Komma igång med användargränssnittet i Adobe Campaign Standarden](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/getting-started/getting-started-with-the-ui.html) | Campaign Standard | I den här videon får du en översikt över Adobe Campaign Standardens användargränssnitt och en beskrivning av hur du navigerar till viktiga funktioner. |
| 26 juni 2020 | [GPG-nyckelhantering](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/gpg-key-management/gpg-key-management-overview.html) | Campaign Standard/Kontrollpanelen | Lär dig hur du skapar och installerar ett offentligt/privat GPG-nyckelpar för datakryptering och hur du importerar och installerar en offentlig nyckel för datadekryptering. |

### Hjälpresurser

* Adobe Campaign Standard: [Hjälpcenter](https://docs.adobe.com/content/help/sv-SE/campaign-standard/using/campaign-standard-home.html) – [Versionsinformation](https://docs.adobe.com/content/help/sv-SE/campaign-standard/using/release-notes/release-notes.html) – [Instruktionsvideor](https://docs.adobe.com/content/help/sv-SE/campaign-standard-learn/tutorials/overview.html) – [Versionsplanering](https://docs.adobe.com/content/help/sv-SE/campaign-standard/using/release-notes/release-planning.html) – [Senaste dokumentationsuppdateringar](https://docs.adobe.com/content/help/sv-SE/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Hjälpcenter](https://docs.adobe.com/content/help/sv-SE/campaign-classic/using/campaign-classic-home.html) – [Versionsinformation](https://docs.adobe.com/content/help/sv-SE/campaign-classic/using/release-notes/latest-release.html) – [Instruktionsvideor](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html) – [Senaste dokumentationsuppdateringar](https://docs.adobe.com/content/help/sv-SE/campaign-classic/using/documentation-updates.html)
* Kontrollpanelen för Adobe Campaign: [Dokumentation](https://docs.adobe.com/content/help/sv-SE/control-panel/using/control-panel-home.html) – [Versionsinformation](https://docs.adobe.com/content/help/sv-SE/control-panel/using/release-notes.html) - Instruktionsvideor för [Campaign Standard](https://docs.adobe.com/content/help/sv-SE/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.translate.html) / [Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html)

## ![Ikon](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Versionsinformation om Adobe Advertising Cloud.

### Nya funktioner i [!UICONTROL Advertising Cloud Search] {#adcloud-search}

Uppdaterad 8 **juli 2020** för versionen från den 11 juli.

| Funktion | Beskrivning |
| -----------| ---------- |
| [!UICONTROL Alerts Beta] | Du kan nu öppna en skrivskyddad, filtrerad vy som innehåller data för en avisering och sedan öppna en filtrerad vy över enheterna i den relevanta kampanjhanteringsvyn, varifrån du kan redigera enhetsposterna. |
| [!UICONTROL Portfolios] | Borttagningen av positionsbaserade mått i begränsningar och portföljinställningar sköts upp till den 8 augusti. |

## ![Ikon](/assets/magento.png) [!DNL Magento] {#magento}

Versionsinformation om Magento finns i:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Ikon](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] är ett komplett program för lead-hantering för B2B-marknadsförare som vill transformera kundupplevelser genom engagemang under alla faser av komplexa inköpsresor.

### Uppdateringar om Core Marketo Engage

Den senaste informationen finns i [!DNL Marketo] [versionsinformationen](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720).

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
