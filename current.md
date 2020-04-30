---
title: Versionsinformation om Adobe Experience Cloud
description: Mall för versionsinformation om Experience Cloud
doc-type: release notes
last-update: March 2020
author: mfrei
translation-type: tm+mt
source-git-commit: d3802d290f1d5192e5bc31f4003ee12fd0ad1ff4

---


# Versionsinformation om Adobe Experience Cloud – april 2020

![Banderoll](/assets/experience-cloud-banner-3.png)

Nya funktioner och korrigeringar i [!DNL Adobe Experience Cloud].

>[!NOTE]
>
>Prenumerera på [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) om du vill få meddelanden via e-post om kommande versioner. Ny information som publiceras efter lanseringen markeras med publiceringsdatumet.

**Lanseringsdatum: April 2020**

Senaste uppdatering: 30 **april 2020**

(Specifika lanseringsdatum kan variera.)

* [Adobe System Status](#status)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics) **(Uppdaterat 29 april)**
* [Audience Manager](#aam) **(uppdaterad 30 april)**
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (länkar till Targets hjälpsida)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (länkar till Primetimes hjälpsida)

Letar du efter startsidan i hjälpen? Se [Adobe Experience Cloud-dokumentationen](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html).

## ![Ikon](/assets/adobe.png) för Adobe System Status {#status}

[!UICONTROL Adobes systemstatus] innehåller detaljerad information, statusuppdateringar och e-postmeddelanden om Adobe-molnprodukter och -tjänster, driftstopp, avbrott och underhållshändelser. Kolla in det på [status.adobe.com](https://status.adobe.com/).

**Nyheter**

* Med ditt Adobe ID kan du prenumerera på händelseaviseringar med mer information ända ned på produkt- och tilläggsnivå. Processen för självprenumerationer i vår senaste version rekommenderar nu ett urval av produkter och tjänster baserat på dina produktbehörigheter. Det bör effektivisera prenumerationsprocessen genom att minska antalet beslut eller klick som krävs för att skapa prenumerationer och, viktigast av allt, du får mer relevanta meddelanden i inkorgen. Kom igång på [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nya funktioner och förbättringar som är tillgängliga nu**

| Funktion | Beskrivning |
| -----------| ---------- |
| Personaliserade prenumerationer baserade på behörigheter | <ul><li>Förvalda prenumerationsrekommendationer baserade på användarens DX-behörigheter.</li><li>Rekommenderade prenumerationer markeras högst upp i produktlistan för snabb överblick.</li><li>Mottagna e-postmeddelanden är relevanta för användarens produktbehörigheter.</li></ul> |
| Enklare hantering av prenumerationer | <ul><li>**[!UICONTROL Hantera prenumerationer]** har en ny användarupplevelse för att hantera både produkt- och eventprenumerationer.</li><li>Nytt alternativ där prenumerationer på produkter och händelser kan visas och redigeras separat.</li><li>The **[!UICONTROL Delete]** option allows you to unsubscribe from a product or event subscription.</li><li>The one-click **[!UICONTROL Unsubscribe all]** option is available for the product subscriptions.</li><li>UX-stöd finns för webben/mobiler/surfplattor och är lokaliserat till 19 språk.</li></ul> |

## ![Ikonen](/assets/ec_appicon_24.png) i Experience Cloud-gränssnittet {#ecloud}

Nya funktioner och korrigeringar i Experience Cloud-gränssnittet:

* Experience Cloud [!UICONTROL Feed] page was deprecated. (EXC-8505)
* Inloggningssidan för Experience Cloud har uppdaterats för att återspegla nya varumärkeselement. (EXC-10747)

Produktdokumentation finns i [hjälpen för Experience Cloud-gränssnittet](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

### Enhetlig produktdomän

Adobe uppdaterar domänen och gränssnittets sidhuvud för att skapa en enhetlig och förbättrad upplevelse i alla Experience Cloud-program. Dessa förbättringar är utformade för att förenkla upplevelsen på små, men viktiga sätt. Förbättringarna ändrar inte dina aktuella arbetsflöden.

Bland uppdateringarna finns:

* Nya program-URL:er: `experience.adobe.com/<application name>`:
   * Alla produkter kommer så småningom att använda det här URL-mönstret. Titta efter nya URL:er som börjar gälla under månaden.
   * Stöd för webbläsare: De webbläsare som stöds är [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] och [!DNL Opera] (de senaste versionerna). **Obs!** Trots att Experience Cloud-gränssnittet har stöd för dessa webbläsare kanske inte enskilda program har stöd för alla webbläsare. ([Analytics](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html) har till exempel inte stöd för [!DNL Opera] och [Target](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html) har inte stöd för [!DNL Safari].)
   * ([!DNL Safari] endast) Domänändringen kan orsaka cookie-problem i [!DNL Safari]. Om du avmarkerar _Förhindra spårning över webbplatser_ i [!DNL Safari] Sekretessinställningar aktiveras cookies i domäner (och alla upplevelser på olika webbplatser) och Experience Cloud kan fungera i den nya domänen.
* Enklare att växla mellan olika organisationer eller till ett annat program.
* Improved product help: [!UICONTROL Experience League] is integrated into the product so that a help search also includes results from community forums and video content. Den här ändringen gör det enklare att komma åt mer innehåll och hjälper dig att få ut mesta möjliga av Experience Cloud. Additionally, click **[!UICONTROL Help]** > **[!UICONTROL Feedback]** to report issues or share your ideas with Adobe.

## ![Ikon för](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Versionsinformation om [!DNL Experience Platform,] bland annat [!DNL Experience Platform Launch,] resesamordning [!UICONTROL ,]erbjudanden [!UICONTROL ,]människor [!UICONTROL ,]platser ,¥Mobile Services och säkerhetsbulletiner.

### Journey Orchestration {#journey}

Med Adobe Experience Platform kan ni orkestrera enskilda kundresor i stor skala över olika upplevelsekanaler genom att intelligent förutse varje enskild individs behov i realtid, oavsett vart resan bär.

* [Dokumentation](https://docs.adobe.com/content/help/en/journeys/using/journey-orchestration-home.html)
* [Versionsinformation](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html)
* [Instruktionsvideor](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Mobiltjänster och SDK:er för mobiler {#mobile}

Android 4.18.2 (3 april 2020):

* In App Messaging: For security reasons, [!UICONTROL WebViews] created by the SDK now set property `setAllowFileAccess` equal to _false_.

iOS 4.19.2 (24 mars 2020):

* Allmänt: Åtgärdade vissa läckor i [!DNL Target]-koden.

Unity 4.19.0 (10 mars 2020):

* Updated [!UICONTROL Unity Plugin] to use versions 4.19.0 of iOS and 4.18.0 or [!DNL Android].
* En ny förvärvsmetod har introducerats så att [!DNL Android] tillåter bearbetning av en URL som tillhandahålls av [!DNL Google Play] referent-API:er.

### Ytterligare versionsinformation om Experience Platform

* [Versionsinformation om Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html)
* [Versionsinformation om Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Säkerhetsbulletiner och rekommendationer](https://helpx.adobe.com/se/security.html) (alla Adobe-produkter)

## ![Ikon](/assets/analytics.png) [!DNL Analytics] {#analytics}

>[!IMPORTANT]
>
>Underhållsutgåvan av Adobe Analytics för april har flyttats till 21 maj 2020. Den senaste versionsinformationen för Analytics finns i [versionsinformationen för mars](c-legacy-releases/2020/03122020.md)

* [Customer Journey Analytics](#cust-journey)
<!--* [New features in Adobe Analytics](#aa-features)-->
* [Viktiga meddelanden för Analytics-administratörer](#aa-notices) (uppdaterad 16 april 2020)
* [AppMeasurement](#appm)
* [Självstudiekurser för nya Analytics](#tutorials-analytics)

### Customer Journey Analytics {#cust-journey}

| Funktion | Beskrivning |
| -----------| ---------- |
| Data Workbench 6.74 (**uppdatering 4/29/2020**) | Uppdatering av IMS-certifikatparsning (Identity Management Service) för TLS i serverimplementeringen. Uppdateringen utökar parsningen från strängmatchning till reguljära uttryck, inklusive möjligheten att hantera SAN-certifikat (subject alternative name). See [Data Workbench release notes](https://docs.adobe.com/content/help/en/data-workbench/using/release-notes/release-notes.html) for more information. |
| [!UICONTROL Customer Journey Analytics]: Automatiserad datauppsättningsbackfill | This new option lets you import all historical data for a connection in [!UICONTROL Customer Journey Analytics]. [Läs mer](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-connections/create-connection.html) |

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

### Viktiga meddelanden för [!DNL Analytics]-administratörer {#aa-notices}

| Meddelande | Datum tillagt eller uppdaterat | Beskrivning |
| -----------| ---------- | ---------- |
| Kontrollen Segment används i datalager har tagits bort | 16 april 2020 | Från och med den 16 april 2020 kontrollerar vi inte längre om ett segment används i en datalagerbegäran i segmentbyggaren. Tidigare sökte den här kontrollen efter enskilda segment som användes i datalagerförfrågningar (flera segment uteslöts) och returnerade ett varningsmeddelande om true. Den här ändringen påverkar inte datalagrets produktkompatibilitetskontroll för segment. |
| Ändra till hur [!UICONTROL inmatningar/utmatningar] beräknas i [!UICONTROL arbetsytan] | 7 april 2020 | In [!UICONTROL Analysis Workspace], as of March 2020, we have changed how the _None_ value interacts with [!UICONTROL Entries/Exits]. Because you can now turn _Nones_ on and off in [!UICONTROL Analysis Workspace], we apply the _None_ value after the entry or exit, whereas (for eVars) it used to be applied before. Anta till exempel att den första träffen för ett besök inte har ett värde för eVars, men att den andra träffen har det. In [!UICONTROL Reports &amp; Analytics] it will show up as _Unspecified_ for the Entry, but in [!UICONTROL Analysis Workspace] it will show up as the value on the second hit. |
| EOL för inställning av **[!UICONTROL konverteringsnivå]** | 3 mars 2020 | Den icke fungerande [inställningen för konverteringsnivå](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/general-acct-settings-admin.html) i **[!UICONTROL Administratörsverktyg]** > **[!UICONTROL Rapportsviter]** > **[!UICONTROL Allmänna kontoinställningar]** kommer att tas bort från gränssnittet den 12 mars 2020. |
| EOL för **[!UICONTROL instrumentpanelsarkiv]** | 27 mars 2020 | Inställningen **[!UICONTROL Visa arkiv]** under **[!UICONTROL Hantera instrumentpaneler]** i [!UICONTROL rapporter och analyser] är inte längre tillgänglig från och med oktober 2020. |
| Stöd för TLS 1.1 upphör | 3 oktober 2019 | Adobe Analytics tar bort stödet för TLS 1.1 senast den 31 mars 2020. Den här ändringen är en del av våra löpande ansträngningar att upprätthålla högsta säkerhetsstandarder och skydda kunddata. |
| Ny Adobe Analytics-domän | 18 dec 2019 | Den 16 januari 2020 började Adobe Analytics gå över till en ny domän – `https://experience.adobe.com/analytics.`<br>**Obs!** Den här ändringen gäller alla användare som använder Analytics med sina Adobe ID:n eller Enterprise ID:n.<ul><li>Domänändringen kan orsaka cookie-problem när Analytics läses in i Safari. Om du avmarkerar _Förhindra spårning över webbplatser_ i [!DNL Safari] Sekretessinställningarna aktiveras cookies i domäner (och alla upplevelser på olika webbplatser) vilket gör att Analytics kan användas i den nya Adobe Experience Cloud-domänen. Du kan använda andra webbläsare utan problem eftersom det bara påverkar [!DNL Safari]-användare.</li><li>The domain change may cause [!UICONTROL Activity Map] to stop working for some customers [in specific cases](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html).</li></ul> |
| Slutet av livscykeln – äldre API:er för Analytics | 9 januari 2020 | I november 2020 kommer följande äldre API-tjänster för Analytics att ha nått slutet av sina livscykler och avslutas. Aktuella integreringar som byggts med dessa tjänster kommer att sluta fungera. <ul><li>1.3 API:er för Analytics</li><li>1.4 API:er för SOAP Analytics</li><li>Äldre OAuth-autentisering (OAuth och JWT)</li></ul>Vi har tagit fram [vanliga frågor och svar om upphörande av äldre API:er](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) som kan hjälpa dig att få svar på frågor och ge vägledning om hur du går vidare. API-integrationer som använder dessa tjänster kan migrera till [1.4 Analytics REST-API:er](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) eller [2.0 Analytics API:er](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Äldre OAuth-konton kan migrera till ett [Adobe IO](https://console.adobe.io/home?mv=email) Analytics-integreringskonto som kan användas för att få tillgång till både 1.4 Analytics API:er och 2.0 Analytics API:er. |
| San Jose FTP-hantering upphör för London och Singapore | Juli 2020 | För kunder i London och Singapore stöder vi inte längre datahantering mellan London eller Singapore och datacentret [ftp.omniture.com](ftp://ftp.omniture.com/) i San Jose.<br/><ul><li>I London använder du [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>I Singapore använder du [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Ad Hoc Analysis upphör | 6 aug 2018 | Adobe har meddelat att man avser att dra tillbaka Ad Hoc Analysis. Ett slutdatum meddelas så snart det är tillgängligt. Mer information finns i [Upptäck Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

### [!DNL AppMeasurement] {#appm}

Se [versionsinformationen om AppMeasurement för Javascript](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html). Version 2.20.0 släpptes 5 mars 2020.

### Självstudiekurser för nya Analytics {#tutorials-analytics}

| Innehåll | Beskrivning |
| -----------| ---------- |
| [Adobe Labs (Technology Previews) med Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/analytics-basics/adobe-labs-technology-previews.html) | Med Adobe Labs (Technology Previews) kan ni interagera med nya tekniker, upptäcka värdefulla insikter och påverka framtida funktionsutveckling och prioriteringar i [!DNL Analytics]. |
| [Förbättringar i Experience Cloud Audience Publishing](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/integrations/experience-cloud/improved-experience-cloud-audience-publishing.html) | Förbättringar har gjorts i [!UICONTROL Experience Cloud Audience Publishing]. Nu kan du publicera målgrupper (segment) och göra dem tillgängliga sex gånger snabbare. Det minskar den aktuella svarstiden från 48 timmar till cirka 8 timmar eller mindre beroende på trafik och segmentstorlek. |
| [Flera rapportsviter i Analysis Workspace](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/using-panels/multiple-report-suites-in-analysis-workspace.html) | Multiple report suites can be analyzed in a single [!UICONTROL Workspace] project by selecting report suites at the panel level. Det gör att du kan utföra panelanalyser sida vid sida för olika datauppsättningar. |

Se produktdokumentationen på [startsidan för Adobe Analytics-hjälpen](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

## ![Ikonen](/assets/audience-manager.png) Audience Manager {#aam}

Nya funktioner och korrigeringar i Adobe Audience Manager:

**(Uppdaterat 30 april)**

| Funktion | Beskrivning |
| -----------| ---------- |  
| [Prediktiva målgrupper](../features/algorithmic-models/predictive-audiences.md) | [!UICONTROL Med prediktiva målgrupper] kan ni klassificera en okänd målgrupp i distinkta personligheter, i realtid, med avancerad datavetenskap. <br><br> I ett marknadsföringssammanhang är en person ett målgruppssegment som definieras av besökare, användare eller potentiella köpare som delar en viss uppsättning egenskaper, som demografi, surfvanor, shoppinghistorik osv.<br><br>[!UICONTROL Prediktiva målgruppsmodeller] tar detta koncept ett steg längre genom att göra det möjligt för er att använda Audience Managers maskininlärningsfunktioner för att klassificera okända målgrupper i distinkta personligheter. <br><br>Audience Manager hjälper er att uppnå detta genom att beräkna sannolikheten för er okända förstapartsmålgrupp för en uppsättning kända förstapartsmålgrupper. |
| Ytterligare [!UICONTROL regeltillägg] för profilsammanslagning | [!UICONTROL Regler] för profilsammanslagning ger Audience Manager-kunder möjlighet att definiera, hantera och aktivera målgruppssegment baserat på identitet snarare än enheter. <br><br> Från och med den 29 april kan Audience Manager-kunder bättre förstå hur enheter och enheter delas upp i olika ID-populationer för egenskaper och segment inom både individuell segmentering och bulkrapportering i Audience Manager-gränssnittet. <br><br> Detta ger bättre insikter om identitet i Audience Manager och ger kunderna en helhetsbild av den totala segmentpopulationen per enhet, person och hushåll. Export av både enhets- och enhets-ID:n i flera spår kommer också att uppdateras för att återspegla dessa förbättringar.<br><br>  Bland uppdateringarna finns möjligheten att: <ul><li>Rapportera mot [enhets-ID](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/ids-in-aam.html) i [allmänna](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reporting/general-reports.html) rapporter och [trendrapporter](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reporting/trend-reports.html) .</li><li>Förbättra [!UICONTROL Trait Selector] i [Segment Builder](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/segments/segment-builder.html) så att den omfattar trait-populationer som är sparade i [CRM ID](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/ids-in-aam.html).</li><li>Skapa korrekt trait-export som är avaktiverad för [enhets-ID](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/ids-in-aam.html).</li><li>Skapa korrekt trait-export som är avaktiverad för [enhets-ID](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/ids-in-aam.html) (bör inte inkludera autentiserade egenskaper),</li><li>Returnera korrekt antal för egenskaper som är kopplade till [CRM-ID:n](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/ids-in-aam.html) när de efterfrågas med [BAAAM](https://docs.adobe.com/help/en/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html) -verktyget.</li></ul> |
| [De vanligaste supportfrågorna](https://docs.adobe.com/content/help/en/audience-manager/user-guide/top-support-issues/support-issues-overview.html) | Vi har lagt till ett nytt avsnitt i dokumentationsportalen som innehåller svar på de vanligaste frågorna som vårt supportteam får. |

* Vi har korrigerat ett problem som orsakade felaktig rapportering av [adresserbara målgrupper](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/addressable-audiences.html) för segment som innehåller mobila enhets-ID:n. Efter den här uppdateringen kan ni se en ökning av era [adresserbara målgrupper](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/addressable-audiences.html).
* Korrigerade ett problem som medförde att knapparna [!UICONTROL Duplicera test] och [!UICONTROL Duplicera allokeringsmall] i [!UICONTROL Audience Lab] inte fungerade. (AAM-53388)
* Fixed an issue causing the [!UICONTROL Match Rate] and [!UICONTROL Segment Addressable Audiences] to be displayed as 0 when a destination is configured to export UUIDs. Matchningsfrekvens [!UICONTROL och] Segmentadresserbara målgrupper  visas nu som 100 %. (AAM-51615)
* Ett problem har korrigerats som gjorde att trait-namn som innehåller specialtecken HTML-kodades två gånger. (AAM-54001)
* Ett problem har korrigerats som hindrade vissa användare från att växla till andra Adobe Experience Cloud-program från [!DNL Audience Manager]-användargränssnittet. (AAM-52917)
* Ett problem har korrigerats som hindrade vissa användare från att skapa en SHA256-datakälla för personbaserade mål. (AAM-53525)
* Flera tillgänglighetsförbättringar i hela gränssnittet. (AAM-48986, AAM-49009, AAM-48984, AAM-48939, AAM-48940, AAM-48964, AAM-49032, AAM-49360)

## ![Ikonen](/assets/aem.png) för Experience Manager {#aem}

Nya funktioner, korrigeringar och uppdateringar i Adobe Experience Manager (AEM). Adobe rekommenderar att kunder med lokala distributioner driftsätter de senaste korrigeringarna för bättre stabilitet, säkerhet och prestanda.

### Självhjälp

* **AEM nyhetsbrev**

   Läs det senaste [Adobe Experience Manager nyhetsbrevet](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html).

* **AEM as a Cloud Service – Konfigurera Dynamic Media Cloud Service**

   Ett nytt alternativ är tillgängligt när du konfigurerar Dynamic Media Cloud Service:

   **Selektiv publicering** – När du väljer det här alternativet innebär det att resurser automatiskt publiceras för säker förhandsvisning och att de kan publiceras explicit till AEM utan att publiceras till DMS7 för distribution i den offentliga domänen.

   Se [Konfigurera Dynamic Media Cloud Service](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/config-dm.html#configuring-dynamic-media-cloud-services).

* **Dynamic Media – smart bildbehandling**

   Hela hjälpavsnittet om smart bildbehandling har uppdaterats med ny information, inklusive exempel på bildresurser som visar den nya optimeringen i Smart bildbehandling.

   Se [Smart bildbehandling](https://docs.adobe.com/content/help/en/experience-manager-65/assets/dynamic/imaging-faq.html).

* **Konfigurera Dynamic Media – Scene7-läge**

   A new Sync all content option is now available on the Dynamic Media Configuration page found in **[!UICONTROL Tools > Cloud Services]**.

   Se [Skapa en Dynamic Media-konfiguration](https://docs.adobe.com/content/help/en/experience-manager-65/assets/dynamic/config-dms7.html#configuring-dynamic-media-cloud-services).

* **AEM Assets-varumärkesportalen har stöd för AEM Assets as a Cloud Service**

   Du kan nu publicera resurser från AEM Assets as a Cloud Service på AEM Assets-varumärkesportalen.

   Se [Konfigurera AEM Assets med varumärkesportalen](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/brand-portal/configure-aem-assets-with-brand-portal.html) och [Publicera resurser på varumärkesportalen](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/brand-portal/publish-to-brand-portal.html).

* **Adobe Asset Link 2.0 har lanserats**

   Adobe Asset Link 2.0 har stöd för arbete i flera AEM-miljöer och AEM as a Cloud Service. AEM uppfyller marknadsförarnas behov av att konfigurera automatisk körning av arbetsflöden för mediebearbetning när resurser överförs till en mapp med Adobe Asset Link.

   Se [Adobe Asset Link](https://helpx.adobe.com/se/enterprise/using/adobe-asset-link.html).

### Nya självstudiekurser för Experience Manager

| Innehåll | Beskrivning |
| -----------| ---------- |  
| [Konfigurera verktyg för lokal Dispatcher](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/dispatcher-tools.html) | Learn about facilitating configuring, validating, and simulating [!UICONTROL Dispatcher] locally. |
| [Konfigurera utvecklingsverktyg för AEM-projekt](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/development-tools.html) | För utveckling med Adobe Experience Manager (AEM) måste en liten uppsättning utvecklingsverktyg installeras och konfigureras på utvecklingsmaskinen. Dessa verktyg har stöd för utveckling och byggande av AEM-projekt. |
| [Konfigurera lokal AEM-körningsmiljö](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | Adobe Experience Manager (AEM) can be run locally using the AEM as a Cloud Service SDK&#39;s [!UICONTROL QuickStart Jar]. Det gör att utvecklare kan driftsätta och testa anpassad kod, konfigurationer och innehåll innan de skickas för källkontroll och distribueras till en AEM as a Cloud Service-miljö. |
| [Navigering](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/authoring/navigation.html) | Läs mer om grunderna för navigering i AEM Assets. |
| [Versioner](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/collaboration/versions.html) | Läs mer om hur AEM skapar och underhåller resursversioner. |
| [AEM - [!DNL Magento] Integration med [!UICONTROL Commerce Integration Framework]](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/getting-started.html) | Den här videon visar hur du konfigurerar integreringen mellan AEM och [!DNL Magento]. |
| [Introduktion till AEM Architecture Stack](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-architecture.html) | CIF-projektarketypen skapar ett minimalt Adobe Experience Manager (AEM) CIF-projekt som utgångspunkt för kundprojekt med CIF-kärnkomponenter. |
| [Introduktion till OSGi](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-osgi.html) | En introduktion till OSGi, en dynamisk modulär arkitektur för Java-program som är grunden för Adobe Experience Manager. |
| [Introduktion till Java Content Repository (JCR)](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-jcr.html) | En introduktion till [Java Content Repository (JCR) som används av Adobe Experience Manager. |
| [Introduktion till Sling](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-sling.html) | En introduktion till [!DNL Sling], ett RESTful-webbramverk med öppen källkod som ingår i Adobe Experience Managers underliggande teknikstack. |
| [Introduktion till redigerings- och publiceringsnivå](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-author-publish.html) | An introduction to the [!UICONTROL Author] and [!UICONTROL Publish] tiers as part of the architecture in Adobe Experience Manager. |
| [Introduktion till Dispatcher](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-dispatcher.html) | En introduktion till funktionerna i Dispatcher som är en del av AEM-arkitekturen. |
| [Introduktion till komponentutveckling](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/component-development.html) | En översikt över utveckling av komponenter med Adobe Experience Manager Sites. Innehåller en introduktion till [!UICONTROL dialogrutor], [!UICONTROL segmenteringsmodeller], [!UICONTROL HTML-skript]och [!UICONTROL klientbibliotek]. |
| [AEM-projektarketyp](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/developing/aem-project-archetype.html) | AEM-projekt innehåller all kod och alla konfigurationer som behövs för en implementering. The AEM [!UICONTROL Project Archetype] creates a minimal, best-practices-based Adobe Experience Manager project as a starting point for your own AEM projects. |
| [Förstå kärnkomponenter](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/core-components-feature-video-understand.html) | AEM [!UICONTROL Core Components] are a standard set components to be used with Adobe Experience Manager. |
| [Använda AEM Quickstart JAR](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/developing/quickstart-jar.html) | Learn how to install and run a local instance of Adobe Experience Manager in just a few minutes with the [!UICONTROL AEM Quickstart jar]. |

### Ytterligare hjälpresurser

* [AEM as a Cloud Service](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 – startsida för utbildning och support](https://helpx.adobe.com/se/support/experience-manager/6-5.html)
* [AEM 6.4 – startsida för utbildning och support](https://helpx.adobe.com/se/support/experience-manager/6-4.html)
* [AEM 6.3 – startsida för utbildning och support](https://helpx.adobe.com/se/support/experience-manager/6-3.html)
* [AEM 6.2 – startsida för utbildning och support](https://helpx.adobe.com/se/support/experience-manager/6-2.html)
* [Användarhandbok för Cloud Manager](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Äldre versioner av AEM-dokumentation](https://helpx.adobe.com/se/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic – startsida för hjälp](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Versionsinformation för Dynamic Media](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Versionsinformation för Livefyre](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## ![Ikon](/assets/campaign.png) [!DNL Campaign] {#ac}

Adobe Campaign är ett intuitivt och automatiserat sätt att leverera personliga meddelanden i alla marknadsföringskanaler, både online och offline. Nu kan ni förutse vad era kunder vill ha med upplevelser som bestäms av deras vanor och önskemål.

### Campaign Standard

* [Adobe Campaign Standard 20.2](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html)

### Nya självstudiekurser för Campaign Standard {#tutorials-acs}

| Innehåll | Beskrivning |
| -----------| ---------- |  
| [Profilersättning – Testa e-postmeddelanden med målprofiler](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/communication-channels/email/profile-substitution.html) | Testa dina e-postmeddelanden med funktionen Profilersättning. |

### Fler hjälpresurser för Campaign

* Adobe Campaign Standard: [Dokumentation](https://helpx.adobe.com/se/support/campaign/standard.html) – [Versionsinformation](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) – [Instruktionsvideor](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) – [Versionsplanering](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Dokumentation](https://helpx.adobe.com/se/support/campaign/classic.html) – [Versionsinformation](https://docs.campaign.adobe.com/doc/AC/en/RN.html) – [Instruktionsvideor](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Kontrollpanelen för Adobe Campaign: [Dokumentation](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) – [Versionsinformation](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

<!-- ## ![Icon](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Advertising Cloud release notes. -->

## ![Ikon](/assets/magento.png) [!DNL Magento] {#magento}

Versionsinformation om Magento finns i:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Ikon](/assets/marketo.png) [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] är ett komplett program för lead-hantering för B2B-marknadsförare som vill transformera kundupplevelser genom engagemang under alla faser av komplexa inköpsresor.

### Uppdateringar om Core Marketo Engage

Mer information finns i [!DNL Marketo] [versionsinformationen](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720).

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
