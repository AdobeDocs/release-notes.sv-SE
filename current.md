---
title: Versionsinformation om Adobe Experience Cloud
description: Mall för versionsinformation om Experience Cloud
doc-type: release notes
last-update: May 2020
author: mfrei
translation-type: tm+mt
source-git-commit: feb921205059c7ab4ba9d59964fae9b1954d12a0
workflow-type: tm+mt
source-wordcount: '5370'
ht-degree: 93%

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
* [!DNL Analytics](#analytics) (**Uppdaterad 4 juni 2020**)
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

Mer information finns i [versionsinformationen för Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md).

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
* [Versionsinformation om Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Säkerhetsbulletiner och rekommendationer](https://helpx.adobe.com/se/security.html) (alla Adobe-produkter)

## ![Ikon](/assets/analytics.png) [!DNL Analytics] {#analytics}

* [Nya funktioner i Adobe Analytics](#aa-features) (**uppdaterad 4 juni 2020**)
* [Nya funktioner i kundreseanalys](#cust-journey) (**uppdaterad 4 juni 2020**)
* [Nya funktioner i Media Analytics](#media-aa) (**uppdaterad 29 maj 2020**)
* [Viktiga meddelanden för Analytics-administratörer](#aa-notices) (**uppdaterad 1 juni 2020**)
* [Adobe Analytics-korrigeringar](#aa-fixes) (**uppdaterad 21 maj 2020**)
* [AppMeasurement](#appm)
* [Självstudiekurser för nya Analytics](#tutorials-analytics)

### Nya funktioner i Adobe Analytics {#aa-features}

<!--First-Party Domains Available in China RDC: June 18 - Enables customers with a cn domain to request a 1st-party domain for use inside of Mainland China. Learn more... 
Anomaly det. support in CJA - June 18; Project Sharing Roles - June 18; Blank panel in WS now includes panels and vizs - June 18; -->

| Funktion | [Allmän tillgänglighet](https://docs.adobe.com/content/help/en/analytics/landing/an-releases.html) - Måldatum | Beskrivning |
| -----------| ------------ | ---------- |
| [!UICONTROL Analytics for Target] panel i [!UICONTROL Workspace] | 25 juni 2020 | På [!UICONTROL Analytics for Target] (A4T)-panelen kan du analysera dina Adobe Target-aktiviteter och -upplevelser i [!UICONTROL Analysis Workspace.] [Läs mer...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/a4t-panel.html) |
| [!UICONTROL Quick Insights] panel i [!UICONTROL Workspace] | 25 juni 2020 | [!UICONTROL Quick Insights] ger vägledning för icke-analytiker och nya användare av [!UICONTROL Analysis Workspace] att lära sig att snabbt och enkelt svara på affärsfrågor. [Läs mer](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/quickinsight.html) |
| [!UICONTROL Bulk Data Insertion] API | 31 maj 2020 | Gör det möjligt för er att enkelt och oberoende importera batchar med Analytics-data. Användbar för data på serversidan och offline. [Läs mer...](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md) |
| Adobe Analytics support for [!UICONTROL Adobe Experience Platform Edge Network] | 31 maj 2020 | Gör att du kan använda en enda tagg för att skicka data till flera Adobe-lösningar, som Adobe Analytics, Adobe Target, Adobe Audience Manager, Adobe Experience Platform Data Lake, Unified Profile och Experience Cloud ID Service. [Läs mer...](https://docs.adobe.com/content/help/sv-SE/experience-platform/edge/solutions/analytics/analytics-overview.html) |
| [!UICONTROL Adobe Analytics dashboards] | 21 maj 2020 | [!UICONTROL Adobe Analytics dashboards] är en mobilapp som gör att användare alltid har tillgång till insikter från Adobe Analytics. Den här appen är avsedd för chefer som vill ha tillgång till nyckeltal överallt. Den ger tillgång till insamlade, interaktiva styrkort och finns för både iOS och Android. [Läs mer...](https://docs.adobe.com/content/help/sv-SE/analytics/analyze/mobapp/home.html) |
| [!UICONTROL Workspace]: Bygg automatiskt [!UICONTROL Freeform Tables] från tomt läge | [21 maj 2020 | Tidigare gick det inte att släppa komponenter direkt i ett tomt projekt eller en tom panel. Du måste lägga till en [!UICONTROL Freeform Table] först. Nu kan du släppa komponenter direkt i ett tomt projekt eller en tom panel, då skapas en [!UICONTROL Freeform Table] automatiskt i det format som rekommenderas. Dessutom har vi förbättrat hur blandade komponenttyper (som dimensioner och mätvärden) hanteras när de släpps i en tom frihandstabell tillsammans. |
| [!UICONTROL Adobe Analytics Package] läggs till på [!UICONTROL Feature Access Level] sida | 21 maj 2020 | Nu kan du se vilken [!UICONTROL Adobe Analytics Package] (SKU) ditt företag är kvalificerad till på **[!UICONTROL Admin]** > **[!UICONTROL Company Settings]** > **[!UICONTROL Feature Access Level]**. |
| Tillgänglighetsförbättringar | 21 maj 2020 | Adobe Analytics-teamet har gjort flera tillgänglighetsförbättringar för Analysis Workspace, och har bland annat förbättrat stöd för tangentbordsnavigering, färgkontrast och skärmläsare. [Läs mer...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/workspace-faq/aw-accessibility.html) |

### Nya funktioner i Customer Journey Analytics {#cust-journey}

| Funktion | [Allmän tillgänglighet](https://docs.adobe.com/content/help/en/analytics/landing/an-releases.html) - Måldatum | Beskrivning |
| -----------| --------- | ---------- |
| [!UICONTROL Quick Insights] panel i [!UICONTROL Workspace] | 25 juni 2020 | [!UICONTROL Quick Insights] ger vägledning för icke-analytiker och nya användare av [!UICONTROL Analysis Workspace] att lära sig att snabbt och enkelt svara på affärsfrågor. [Läs mer](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/quickinsight.html) |
| [!UICONTROL Customer Journey Analytics]: Global tillgänglighet | 21 maj 2020 | Gör [!UICONTROL Customer Journey Analytics] tillgängligt för kunder i EMEA och APAC. |
| [!UICONTROL Customer Journey Analytics]: Stöd för [!UICONTROL Adobe Experience Platform Sandboxes] | 21 maj 2020 | Gör att du kan välja [!UICONTROL Adobe Experience Platform Sandboxes] som ska användas för att bygga CJA-anslutningar. [Läs mer...](https://docs.adobe.com/content/help/sv-SE/analytics-platform/using/cja-connections/create-connection.html) |
| [!UICONTROL Workspace]: Bygg automatiskt [!UICONTROL Freeform Tables] från tomt läge | [21 maj 2020 | Tidigare gick det inte att släppa komponenter direkt i ett tomt projekt eller en tom panel. Du måste lägga till en [!UICONTROL Freeform Table] först. Nu kan du släppa komponenter direkt i ett tomt projekt eller en tom panel, då skapas en [!UICONTROL Freeform Table] automatiskt i det format som rekommenderas. Dessutom har vi förbättrat hur blandade komponenttyper (som dimensioner och mätvärden) hanteras när de släpps i en tom frihandstabell tillsammans. |
| Tillgänglighetsförbättringar | 21 maj 2020 | Adobe Analytics-teamet har gjort flera tillgänglighetsförbättringar för Analysis Workspace, och har bland annat förbättrat stöd för tangentbordsnavigering, färgkontrast och skärmläsare. [Läs mer...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/workspace-faq/aw-accessibility.html) |

#### Nya funktioner i [!UICONTROL Media Analytics] {#media-aa}

Uppdaterat den: **29 maj 2020**

**Spårning av spelarstatus:** [!UICONTROL Media Analytics] kunder kan fånga tittarinteraktion under uppspelning med en standarduppsättning lösningsvariabler för helskärmsvisning, undertexter, ljud av, bild-i-bild och i fokus. Du kan också skapa anpassade spelarlägen. Variabler för spårning av spelarstatus är nu tillgängliga för rapportering i [!UICONTROL Analysis Workspace]. Den här funktionen kräver något av följande:

* Media [!DNL JavaScript] SDK 3.0 eller senare
* För användning med [!DNL Adobe Experience Platform] (AEP) SDK:
   * [!UICONTROL Media Analytics Extension] (för webb): [!UICONTROL Adobe Media Analytics] (3.x SDK) för ljud och video v1.0 eller senare
   * [!UICONTROL Media Analytics Extension] (för mobil): [!UICONTROL Adobe Media Analytics for Audio] och video v2.0 eller senare
* [!UICONTROL Media Collection]

Se [Om spårning](https://docs.adobe.com/content/help/en/media-analytics/using/player-state-tracking/player-state-overview.html)av spelartillstånd.

#### Korrigeringar i Adobe Analytics {#aa-fixes}

* Adobe ändrade [!UICONTROL Time Spent]-metriken så att den aldrig inkluderade ”Ospecificerad” i beräkningen. Det innebär att vi, oavsett om användargränssnittet säger att ”Ospecificerad” ska inkluderas, gör ett särskilt undantag att alltid utesluta ”Ospecificerad” i [!UICONTROL Time Spent]-beräkningen. Även om du har konfigurerat en rapport som innehåller [!UICONTROL Time Spent]-metriken till att innehålla ”Ospecificerad” returnerar den därför alltid 0 tid för raden ”Ospecificerad”. Observera att detta kan ändra historikrapporteringen i både Reports &amp; Analytics och API:t v1.4. (AN-197958)
* Ett problem har korrigerats där instansen/besöket/besökaren inte räknades i nämnaren för [!UICONTROL Time Spent]-metriken.  Detta inträffar när en träff utan värde för dimensionen (t.ex. [!UICONTROL Pagename]) följs i samma sekund. (AN-211074)
* Ett problem som gjorde att [!DNL Analytics] segmentdata saknades i Audience Manager har korrigerats. (AN-206221)
* Ett problem har korrigerats med [!UICONTROL Data Sources]-bearbetning som visade fel datum. (AN-213604)
* Ett problem som gjorde att klassificeringsfiler inte överfördes till FTP på rätt sätt har korrigerats. (AN-214102)
* Ett problem med att API-metoden `Segments.Get` inte returnerade ett fullständigt svar har korrigerats. (AN-206210)
* Ett problem där tabellradsobjekt konverterades till specialtecken vid nedladdning av en [!DNL Workspace]-PDF har korrigerats. (AN-196153)
* Ett problem med Adobe Analytics API 1.4-anropet `visattrcustomeridcustomerattributes` har korrigerats. (AN-186873)
* Ett problem med data som visades i rapporter men saknades i [!UICONTROL Data Feed] har korrigerats. (AN-211923)
* Ett problem med att det inte gick att kopiera [!UICONTROL Product Profile] behörigheter har korrigerats. (AN-211113)
* Ett problem där användare med Federated ID inte kunde logga in på [!UICONTROL Report Builder] har korrigerats. (AN-207750)
* Ett problem med att [!UICONTROL AdWords]-data inte visades i [!UICONTROL Advertising Analytics] har korrigerats. (AN-213249)
* Ett problem där klassificeringsdata inte visades i trendvyn har korrigerats. (AN-212761)
* Ett problem som gjorde att fel antal publicerade segment visades i [!UICONTROL Segment Manager] har korrigerats. (AN-213374)
* Ett problem med alternativet **[!UICONTROL Show Upwards Trend As...]** i [!UICONTROL Calculated Metric Editor] har korrigerats. Det fungerade inte när filter användes. (AN-214223)
* Flera problem med import och export i [!UICONTROL Classification] har korrigerats. (AN-213488, AN-215309, AN-216345, AN-215307, AN-216671)
* Flera problem med [!UICONTROL Classification Rule Builder] har korrigerats. (AN-213826, AN-213550, AN-213095)
* Problem med [!UICONTROL Data Sources]-bearbetning har korrigerats. (AN-218083, AN-213604, AN-214102, AN-215485, AN-215339, AN-212911, AN-217551, AN-217947, AN-219018, AN-214691, AN-218401)
* Problem med FTP-anslutningar har korrigerats. (AN-115525)
* Flera problem med [!DNL Analytics] [!UICONTROL Data Feeds] har korrigerats. (AN-176769, AN-160480, AN-211923, AN-204286, AN-212977, AN-214528, AN-215080, AN-217784, AN-219093, AN-218817, AN-217798, AN-218267, AN-218382)
* Problem med [!UICONTROL Data Warehouse]-förfrågningar har korrigerats. (AN-181836)
* Problem med nedladdade PDF-filer för [!UICONTROL Workspace]-projekt där värden konverterades till specialtecken har korrigerats. (AN-196153)
* Ett problem med att det inte gick att kopiera [!UICONTROL Product Profile] behörigheter i [!UICONTROL Admin Console] har korrigerats. (AN-211113)
* Ett problem där tidsformat i beräknade mätvärden bröts upp för negativa värden har korrigerats. (AN-210900)
* Ett problem som hindrade användare från att ändra [!UICONTROL Attribution Model] för mätvärden på statiska rader har korrigerats. (AN-207872)
* Ett problem som gjorde att [!UICONTROL Scheduled Report]-byggaren fastnade i köat läge har korrigerats. (AN-215317)
* [!UICONTROL ExactTarget Data Connector] har korrigerats. (AN-210794)
* Latensproblem i [!UICONTROL Bulk Ingestion API] har korrigerats. (AN-210165)
* Ett problem där användare inte kunde logga in i [!UICONTROL Report Builder] med ett Federated ID har korrigerats. (AN-207750)
* Ett problem i [!UICONTROL Advertising Analytics] som förhindrade att [!DNL Google AdWords]-data visades har korrigerats. (AN-213249)
* Ett problem som förhindrade att [!UICONTROL Workspace] [!UICONTROL Project Viewed]-händelser visades i loggar har korrigerats. (AN-214134)
* Ett problem som inträffade när datumintervallet i [!UICONTROL Workspace] ändrades och **[!UICONTROL Apply to all panels]** valdes har korrigerats. Datumet ändrades inte på vissa paneler. (AN-214944)
* Ett problem som gjorde att det inte gick att skapa eller redigera aviseringar har korrigerats. (AN-215920)
* Ett problem med dynamiska datumintervall i [!UICONTROL Workspace] som visade fel datum på grund av att den första dagen i veckan slumpmässigt ändrades till en söndag från en måndag har korrigerats. (AN-218835)

#### Övriga korrigeringar i Adobe Analytics

AN-101871, AN-115525; AN-123869; AN-152580; AN-160480; AN-178128; AN-186907; AN-199299; AN-201342; AN-201397; AN-204286; AN-204518; AN-206045; AN-206948; AN-208607; AN-209486; AN-210743; AN-211550; AN-211539; AN-211826; AN-211943; AN-212130; AN-212151; AN-212653; AN-212673; AN-212709; AN-212833; AN-212961; AN-212977; AN-213095; AN-213422; AN-213450; AN-213490; AN-213752; AN-213827; AN-214094; AN-214153; AN-214214; AN-214234; AN-214253;  AN-214255; AN-214343; AN-214355; AN-214401; AN-214427; AN-214528; AN-214642; AN-214691; AN-214772; AN-214793; AN-214924; AN-215017; AN-215080; AN-215212; AN-215312; AN-215377; AN-215402; AN-215545; AN-215905; AN-215963; AN-216447; AN-216676; AN-216880; AN-216999; AN-217245; AN-218450; AN-218899; AN-219487; AN-219677

### Viktiga meddelanden för [!DNL Analytics]-administratörer {#aa-notices}

| Meddelande | Datum tillagt eller uppdaterat | Beskrivning |
| -----------| ---------- | ---------- |
| Migrering till den enhetliga produktdomänen | Datum för ikraftträdande: 28 maj 2020 | Övergången till en enhetlig produktdomän för Adobe Analytics, som började i januari 2020, slutfördes den 28 maj 2020. Adobe Analytics tar bort alla domänreferenser från sin arkitektur, men det är viktigt att vitlista `omniture.com` `omniture.com` som en cookie från tredje part. När den fullständiga arkitekturmigreringen är (snart) slutförd meddelar vi dig via versionsinformationen och det här vitlistestedet kommer inte längre att behövas. [Här](https://helpx.adobe.com/analytics/kb/adobe-ip-addresses.html) är en fullständig lista över rekommenderade IP-adresser och domäner som du bör vitlista.<br>Om din organisation blockerar cookies från tredje part kan du kontakta kundtjänst för att få tillgång till Adobe Analytics igen. |
| Ny startsida för Adobe Analytics | Startdatum: 18 juni 2020 | Den 18 juni 2020 ändras standardlandningssidan för Adobe Analytics från [!UICONTROL Reports] till [!UICONTROL Workspace]. Den här ändringen kommer att utföras för användare som inte tidigare har angett en anpassad landningssida. |
| Teknik från tredje part | (Datum för ikraftträdande: 12 mars 2020 | Adobe Analytics har börjat utnyttja teknik från tredje part för funktionshantering och produktsupport. Följande URL:er ska läggas till i alla nödvändiga vitlistor för nätverkets brandvägg för att säkerställa fullständig funktionsåtkomst:<ul><li>Gainsight: https://esp.aptrinsic.com</li><li>LaunchDarkly: https://app.launchdarkly.com</li></ul> |
| Förbättrad redundans för Analysis Workspace | 21 maj 2020 | Vi lägger till ett sekundärt CDN (Content Delivery Network) för förbättrad redundans och säkerställa Analysis Workspaces tillgänglighet. Följande URL:er ska läggas till i alla nödvändiga vitlistor för nätverkets brandvägg:<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul> |
| Ändra hur [!UICONTROL Entries/Exits] beräknas i [!UICONTROL Workspace] | 7 april 2020 | Från och med mars 2020, har vi ändrat hur värdet _Inga_ interagerar med [!UICONTROL Entries/Exits] i [!UICONTROL Analysis Workspace]. Eftersom du nu kan aktivera och inaktivera _Inga_ i [!UICONTROL Analysis Workspace] använder vi värdet _Inga_ efter första eller sista besökssidan i stället för före (för eVars). Anta till exempel att den första träffen för ett besök inte har ett värde för eVars, men att den andra träffen har det. I [!UICONTROL Reports & Analytics] visas den första träffen som _Ospecificerat_ för första besökssidan, men i [!UICONTROL Analysis Workspace] visas det som ett värde för den andra träffen. |
| Inställningen **[!UICONTROL Conversion Level]** tas bort | 3 mars 2020 | Inställningen för icke fungerande [konverteringsnivå](https://docs.adobe.com/content/help/sv-SE/analytics/admin/admin-tools/general-acct-settings-admin.html) i **[!UICONTROL Admin Tools]** > **[!UICONTROL Report Suites]** > **[!UICONTROL General Account Settings]** kommer att tas bort från gränssnittet den 12 mars 2020. |
| **[!UICONTROL Dashboard Archive]** tas bort | 27 mars 2020 | Inställningen **[!UICONTROL View Archive]** under **[!UICONTROL Manage Dashboards]** i [!UICONTROL Reports & Analytics] är inte tillgänglig från och med oktober 2020. |
| Stöd för TLS 1.1 upphör | 3 oktober 2019 | Adobe Analytics tar bort stödet för TLS 1.1 senast den 31 mars 2020. Den här ändringen är en del av våra löpande ansträngningar att upprätthålla högsta säkerhetsstandarder och skydda kunddata. |
| Ny Adobe Analytics-domän | 18 dec 2019 | Den 16 januari 2020 började Adobe Analytics gå över till en ny domän – `https://experience.adobe.com/analytics.`<br>**Obs!** Den här ändringen gäller alla användare som använder Analytics med sina Adobe ID:n eller Enterprise ID:n.<ul><li>Domänändringen kan orsaka cookie-problem när Analytics läses in i Safari. Om du avmarkerar _Förhindra spårning över webbplatser_ i [!DNL Safari] Sekretessinställningarna aktiveras cookies i domäner (och alla upplevelser på olika webbplatser) vilket gör att Analytics kan användas i den nya Adobe Experience Cloud-domänen. Du kan använda andra webbläsare utan problem eftersom det bara påverkar [!DNL Safari]-användare.</li><li>Domänändringen kan leda till att [!UICONTROL Activity Map] slutar fungera för vissa kunder [i en del fall](https://docs.adobe.com/content/help/sv-SE/analytics/analyze/activity-map/activity-map.html).</li></ul> |
| Slutet av livscykeln – äldre API:er för Analytics | 9 januari 2020 | I november 2020 kommer följande äldre API-tjänster för Analytics att ha nått slutet av sina livscykler och avslutas. Aktuella integreringar som byggts med dessa tjänster kommer att sluta fungera. <ul><li>1.3 API:er för Analytics</li><li>1.4 API:er för SOAP Analytics</li><li>Äldre OAuth-autentisering (OAuth och JWT)</li></ul>Vi har tagit fram [vanliga frågor och svar om upphörande av äldre API:er](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) som kan hjälpa dig att få svar på frågor och ge vägledning om hur du går vidare. API-integrationer som använder dessa tjänster kan migrera till [1.4 Analytics REST-API:er](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) eller [2.0 Analytics API:er](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Äldre OAuth-konton kan migrera till ett [Adobe IO](https://console.adobe.io/home?mv=email) Analytics-integreringskonto som kan användas för att få tillgång till både 1.4 Analytics API:er och 2.0 Analytics API:er. |
| San Jose FTP-hantering upphör för London och Singapore | Juli 2020 | För kunder i London och Singapore stöder vi inte längre datahantering mellan London eller Singapore och datacentret [ftp.omniture.com](ftp://ftp.omniture.com/) i San Jose.<br/><ul><li>I London använder du [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>I Singapore använder du [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Ad Hoc Analysis upphör | 6 aug 2018 | Adobe har meddelat att man avser att dra tillbaka Ad Hoc Analysis. Ett slutdatum meddelas så snart det är tillgängligt. Mer information finns i [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

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
| [Control Panel – hantering av Google TXT-poster](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/google-txt-record-management.html) | Lär dig hur du lägger till Google TXT-poster för webbplatsverifiering på alla dina underdomäner som används för att skicka e-post till GMAIL-adresser med Campaign Control Panel. |
| [Konfigurera och köra ett arbetsflöde med aktiviteten Externt API](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html) | Lär dig hur du anropar en extern REST API-slutpunkt med aktiviteten External API. |
| [Komma igång med push-meddelanden för Android – självstudiekurs](https://docs.adobe.com/content/help/en/campaign-standard-learn/getting-started-with-push-notifications-android/introduction.html) | I den här självstudiekursen beskrivs de steg som behövs för att konfigurera push-meddelanden med Campaign Standard och Android-appen. |

* Nya självstudiekurser för Campaign Classic

| Innehåll | Beskrivning |
| -----------| ---------- |  
| [Big data-hantering i Snowflake](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | Lär dig hur du kan utnyttja Snowflake-anslutningen i Adobe Campaign Classic. |
| [Control Panel – hantering av Google TXT-poster](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/google-txt-record-management.html) | Lär dig hur du lägger till Google TXT-poster för webbplatsverifiering på alla dina underdomäner som används för att skicka e-post till GMAIL-adresser med Campaign Control Panel. |

### Hjälpresurser för Campaign

* Adobe Campaign Standard: [Hjälpcenter](https://docs.adobe.com/content/help/sv-SE/campaign-standard/using/campaign-standard-home.html) – [Versionsinformation](https://docs.adobe.com/content/help/sv-SE/campaign-standard/using/release-notes/release-notes.html) – [Instruktionsvideor](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) – [Versionsplanering](https://docs.adobe.com/content/help/sv-SE/campaign-standard/using/release-notes/release-planning.html) – [Senaste dokumentationsuppdateringar](https://docs.adobe.com/content/help/sv-SE/campaign-standard/using/documentation-updates.html)
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
