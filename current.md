---
title: Senaste versionsinformation
description: Läs mer om den senaste versionsinformationen, nya funktioner och ny dokumentation för produkter och tjänster från Experience Cloud. Hitta ny hjälp och självstudiekurser om Experience Cloud, Creative Cloud för företag och Document Cloud.
doc-type: release notes
last-update: June 2021
author: mfrei
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: 8adc3fe8f3f4b174d1c41cc7c3162d38a984d661
workflow-type: tm+mt
source-wordcount: '4947'
ht-degree: 14%

---

# Versionsinformation om Adobe Experience Cloud – juni 2021

![Banderoll](assets/experience-cloud-banner-3.png)

Experience Cloud program och tjänster uppdateras varje månad. Den här sidan är din centrala plats där du kan hitta de senaste versionsuppdateringarna, dokumentationen och självstudiekurserna för [!DNL Experience Cloud] och [!DNL Experience Platform]. Du kan även hitta ny dokumentation för [!DNL Creative Cloud for Enterprise] och [!DNL Document Cloud].

>[!NOTE]
>
>Prenumerera på den månatliga [produktuppdateringen Adobe Priority](https://www.adobe.com/subscription/priority-product-update.html) för att få e-postmeddelanden om uppdateringar av den här sidan. Den här sidan underhålls hela månaden, så du bör regelbundet kontrollera om det finns uppdateringar av Adobe Enterprise-produkten och Experience League-dokumentationen.

Senaste uppdatering: **11 juni 2021**

* [Gränssnittskomponenter i Experience Cloud](#ecloud)
* [Adobe – systemstatus](#status)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [offer decisioning](#offer-decisioning)
* [[!DNL Analytics]](#analytics)och [Customer Journey Analytics](#cust-journey)
* [[!DNL Audience Manager]](#aam)
* [[!DNL Experience Manager]](#aem)
* [[!DNL Campaign]](#ac)
* [[!DNL Advertising]](#adcloud)
* [[!DNL Target]](#target)
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo)
* [[!DNL Workfront]](#workfront)
* [Document Cloud](#doc-cloud)
* [Creative Cloud Enterprise](#creative-cloud)

Behöver du hjälp? Besök [Adobe Experience League](https://experienceleague.adobe.com/#home) för att hitta produkt- och teknisk dokumentation, kurser, videokurser, snabbsvar, communityinsikter och lärarledd utbildning.

## ![](/assets/ec_appicon_24.png) IkonExperience Cloud Central UI-komponenter {#ecloud}

Experience Cloud Central Interface Components innehåller uppdateringar som du kan få åtkomst till från det enhetliga produkthuvudet, som självhjälp, sökning och inställningar för användarkonton. Uppdateringar av personer, platser (plats) och produkthantering finns här.

| Funktion | Datum | Beskrivning |
| ------- | ------- | ------- |
| Stöd för enkel inloggning för Adobe Federated ID:n | 17 juni 2021 | Om du använder Federated ID:n kan du logga in på Experience Cloud utan att behöva ange en e-postadress eller ett lösenord. Om du vill använda den här funktionen lägger du till **#/sso:@domain** i Experience Cloud-URL:en. <br><br>Anta till exempel att du äger domänen  **adobeccustomer.** comand och vill logga in på Adobe Analytics. URL:en skulle vara: **https://experience.adobe.com/#/sso:@adobecustomer.com/analytics**. |
| Experience League Search | 1 juni 2021 | Experience League dokumentationssökning har förbättrats. Navigera till [Experience League](https://experienceleague.adobe.com/docs/?lang=en) och använd fältet **[!UICONTROL Search]** för att hitta självstudiekurser, dokumentation, kurser med mera. |

{style=&quot;table-layout:auto&quot;}

**Fler hjälpresurser**

* Administrationshjälp för [Central Interface Components](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en) och användarhantering
* Hjälp- och versionsinformation för [Platser - Platstjänst](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=en)
* Hjälp om [Personer - Kundattribut och målgruppsbibliotek](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=en)
Produktdokumentation om de här funktionerna finns i [Experience Cloud Central Interface Components](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en).

## ![Ikon](/assets/adobe.png) Adobe – systemstatus {#status}

[!UICONTROL Adobe System Status] ger detaljerad information, statusuppdateringar och e-postmeddelanden om Adobe-molnprodukter och -tjänster, driftstopp, avbrott och underhållshändelser. Kolla in det på [status.adobe.com](https://status.adobe.com/).

De senaste uppdateringarna av systemstatusen för Adobe finns på [Adobe systemstatus - 21 maj 2020](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2020/05212020.html?lang=en) för den senaste versionsinformationen.

## ![Ikon för](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Innehåller uppdateringsinformation och ny dokumentation för Experience Platform och Experience Platform Launch.

* **26 maj 2021:** [Experience Platform versionsinformation](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html)
* **17 maj 2021: Versionsinformation** [ om ](https://experienceleague.adobe.com/docs/launch/using/release-notes/current.html) Experience Platform Data Collection (tidigare Experience Platform Launch)

### Självstudiekurser och kurser för Experience Platform {#tutorials-platform}

Nya videor, självstudiekurser eller kurser publicerade för Experience Platform och tjänster.

| Publicerad | Namn | Typ | Beskrivning |
| -----------| ---------- | ---------- | ---------- |
| Juni 2021 | [Förbered data](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/prepare-data.html) | Video | Lär dig hur du rensar, förbereder och kombinerar data från flera datauppsättningar för att skapa en datauppsättning med hjälp av funktionerna Skapa tabell som (CTAS) och Spark SQL för rapportering och instrumentpaneler. |
| Juni 2021 | [Kopiera scheman mellan sandlådor](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/copy-schemas-between-sandboxes.html) | Video | Lär dig hur du kopierar ett schema från en sandlåda till en annan i Adobe Experience Platform med [!UICONTROL Export/Import Schema API]. Bygg och testa dina scheman i utvecklingssandlådor och kopiera dem sedan till produktion. |
| Juni 2021 | [Uppdatera scheman](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/update-schemas.html) | Video | Lär dig grunderna som du bör känna till när du uppdaterar befintliga scheman i Adobe Experience Platform. |
| Juni 2021 | [Byggstenar för schema](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/schema-building-blocks.html) | Video | Lär dig grunderna i byggstenarna i XDM-scheman (Experience Data Model), inklusive fält, datatyper, schemafältgrupper, klasser och beteenden. |
| Juni 2021 | [Skapa klasser](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-classes.html) | Video | Lär dig hur du skapar klasser i Adobe Experience Platform för användning i XDM-scheman (Experience Data Model). |
| Juni 2021 | [Konfigurera relationer mellan scheman](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/configure-relationships-between-schemas.html) | Video | Lär dig hur du konfigurerar en relation mellan två scheman i Adobe Experience Platform. Med relationer kan du använda en datamängd som uppslagstabell för en annan. |
| Juni 2021 | [Skapa datatyper](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-data-types.html) | Video | Lär dig hur du skapar egna datatyper i Adobe Experience Platform för användning i XDM-scheman (Experience Data Model). |
| Juni 2021 | [Konvertera din datamodell till en upplevelsedatamodell](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/convert-your-data-model-to-xdm.html) | Video | Lär dig hur dataarkitekter kan ta sin befintliga transaktionsdatamodell och konvertera den till en Experience Data Model. I den här videon visas skillnaden i modelleringsmetoder med hjälp av entitetsrelationsdiagram. |
| Juni 2021 | [Planera din datamodell](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/plan-your-data-model.html) | Video | Lär dig vad du ska göra innan du börjar skapa scheman i Adobe Experience Platform. Dokumentera era användningsexempel, förstå er plattformslicens, veta vilka produktsäkerhetsutkast och identifiera vilka data ni ska importera innan ni slutför er datamodell. |
| Juni 2021 | [Tableau](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/psql-client-tableau.html) | Video | Lär dig hur du ansluter till [!UICONTROL Query Service] från olika skrivbordsklientprogram som stöder `PostgreSQL`-protokoll och hur du använder `PostgreSQL`-verktyg och drivrutiner för att ansluta till och skriva frågor. |
| Juni 2021 | [Adobe-definierade funktioner](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/adobe-defined-functions.html) | Video | Lär dig hur du använder Adobe-definierade funktioner i Adobe Experience Platform [!UICONTROL Query Service] för att utföra vanliga affärsrelaterade uppgifter på Experience Event-data. |
| Juni 2021 | [Utforska data](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/explore-data.html) | Video | Lär dig hur du validerar inkapslade data, förhandsgranskar data och utforskar statistiska och analytiska egenskaper för data med hjälp av SQL-funktioner. |
| Juni 2021 | [Översikt över frågetjänsten](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/understanding-query-service.html) | Video | Läs mer om Query Service i Adobe Experience Platform och hur det hjälper er att förstå kundbeteenden och generera slagkraftiga insikter. |
| Juni 2021 | [Översikt över användargränssnittet för frågetjänsten](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/query-service-ui.html) | Video | Lär dig hur du skriver och kör frågor, visar frågor som har körts tidigare och får åtkomst till frågor som har sparats av andra användare i din IMS-organisation i Adobe Experience Platform Query Service. |
| Juni 2021 | [Fråge-API](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/query-service-api.html) | Video | Lär dig hur du skriver och kör frågor, skapar schemafrågor och skapar en frågemall med Adobe Experience Platform [!UICONTROL Query Service API]. |

{style=&quot;table-layout:auto&quot;}

## ![Ikon](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Använd Experience Platform för att samordna kundens resa i stor skala över olika upplevelsekanaler genom att intelligent förutse varje enskild individs behov i realtid.

* Uppdaterad juni 2021 - [Versionsinformation för Journey Orchestration](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=en)

**Fler resurser för Journey Orchestration**

[Dokumentation](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=en) – [Versionsinformation](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=en) – [Instruktionsvideor](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=en)

## ![](/assets/experience_platform_appicon_24.png) IconOffer Decision  {#offer-decisioning}

[!UICONTROL Offer Decisioning] är en programtjänst som är integrerad i Adobe Experience Platform. Använd [!UICONTROL Offer Decisioning] för att leverera det bästa erbjudandet och upplevelsen till era kunder via alla kontaktytor vid rätt tidpunkt.

* Uppdaterad april 2021 - [Versionsinformation för Offer decisioning](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/release-notes.html?lang=en#new)

**Fler resurser för Offer decisioning**

[Dokumentation](https://experienceleague.adobe.com/docs/offer-decisioning/using/offer-decisioning-home.html?lang=en) – [Versionsinformation](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/release-notes.html?lang=en#new) – [Instruktionsvideor](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/overview.html?lang=en)

## ![Ikon](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Releasedatum: **17 juni 2021**

* [Nya funktioner i Adobe Analytics](#aa-features)
* [Nya funktioner i Customer Journey Analytics](#cust-journey)
* [Korrigeringar i Adobe Analytics](#aa-fixes)
* [Viktiga meddelanden för Analytics-administratörer ](#aa-notices)
* [Kurser och självstudiekurser i analyser](#tutorials-analytics)
* [AppMeasurement](#appm)

### Nya funktioner i Adobe Analytics {#aa-features}

| Funktion | [Allmän tillgänglighet](https://experienceleague.adobe.com/docs/analytics/landing/an-releases.html?lang=en) – Måldatum | Beskrivning |
| ----------- | ---------- | ------- |
| Ej tillämpligt | Ej tillämpligt |

{style=&quot;table-layout:auto&quot;}

### Nya funktioner i Customer Journey Analytics {#cust-journey}

| Funktion | [Allmän tillgänglighet](https://experienceleague.adobe.com/docs/analytics/landing/an-releases.html?lang=en) – Måldatum | Beskrivning |
| ----------- | ---------- | ----- |
| Ej tillämpligt | Ej tillämpligt |

{style=&quot;table-layout:auto&quot;}

### Korrigeringar i Adobe Analytics {#aa-fixes}

* Korrigerade ett problem med felaktig valuta i rapporten Revenue Real-Time. (AN-254649)
* Dokumentationen om [skiftlägeskänslighet för eVar i rapportering](https://experienceleague.adobe.com/docs/analytics/components/dimensions/evar.html) har uppdaterats. (AN-246438)
* Dokumentationen har uppdaterats för att ge en bättre förklaring till [implementering av dataflöden](https://experienceleague.adobe.com/docs/analytics/export/analytics-data-feed/create-feed.html) och [här](https://experienceleague.adobe.com/docs/analytics/export/analytics-data-feed/df-faq.html#BucketOwnerFullControl). (AN-219485)
* Åtgärdade problem med att vissa data inte skickades i rapporten från Data warehouse (AN-259951). AN-259712; AN-260107; AN-259953)

#### Ytterligare korrigeringar i Adobe Analytics eller CJA

AN-246344; AN-250035; AN-250354; AN-252482; AN-254661; AN-254965; AN-255424; AN-256515; AN-257232; AN-257572; AN-257893; AN-258393; AN-259203; AN-259513; AN-259614; AN-259665; AN-259931; AN-260074; AN-260085; AN-260147; AN-260190; AN-260198; AN-260290; AN-260306 (CJA); AN-260508; AN-260625; AN-260793; AN-260861; AN-260938; AN-260945; AN-261149; AN-261317

### Viktiga meddelanden för [!DNL Analytics]-administratörer {#aa-notices}

| Meddelande | Datum tillagt eller uppdaterat | Beskrivning |
| ----------- | ---------- | ---------- |
| Webbläsaranvändaragenter återspeglar felaktiga operativsystemversioner för macOS | 19 maj 2021 | Alla större webbläsare rapporterar för närvarande felaktigt användare av macOS X 11 och senare som om de använder macOS 10, vilket anges i webbläsarens användaragentsträng. Det här problemet påverkar Adobe Analytics rapportering, eftersom användaragenten används för att fastställa enhetsinformation som operativsystem. Denna brist tycks föreligga för att förhindra kompatibilitetsproblem för vissa webbplatser. Se den här [Bugzilla-biljetten](https://bugs.webkit.org/show_bug.cgi?id=213622&amp;utm_source=convertkit&amp;utm_medium=email&amp;utm_campaign=User+Agent+strings%2C+new+BigQuery+features%2C+custom+Google+Tag+Manager+loader..+%E2%80%93+Simmer+Newsletter+%2311%20-%205873454) för referens. Det står inte klart när eller om problemet kommer att åtgärdas.<br>I vissa webbläsare spelades MacOS 11 in korrekt. Det kan därför finnas viss trafik som matchar det här värdet. På grund av den felaktiga rapporteringen är filtrering för operativsystemet macOS 11 emellertid inte användbart.<br>Problemet är viktigt eftersom Apple från och med Safari i macOS 11 har uppdaterat tidsbegränsningarna för ITP-cookies för CNAME-implementeringar (se  [WebKit-blogginlägget](https://webkit.org/blog/11338/cname-cloaking-and-bounce-tracking-defense/)).<br>Innan den här uppdateringen tillämpades dessa begränsningar endast på cookies på klientsidan som angetts via JavaScript. Denna brist gör det svårt att bedöma hur mycket trafik som använder OS 11 och påverkas därmed av ITP-ändringen. Du kan läsa mer om cookies och Adobe Analytics [här](https://experienceleague.adobe.com/docs/analytics/technotes/cookies/cookies.html#cookies). |
| Slutet av livscykeln för tre API-tjänster för analys | 19 maj 2021 | Den 18 augusti 2021 nådde följande API-tjänster för Analytics Legacy sitt slutdatum och avslutades. Alla integreringar som byggts med dessa tjänster slutade fungera den dagen.<ul><li>1.3 API:er för Analytics</li><li>1.4 API:er för SOAP Analytics</li><li>Äldre OAuth-autentisering (OAuth och JWT)</li></ul>Adobe har tillhandahållit en [Vanliga frågor om äldre API-versioner av fjärrskrivbordsversioner](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) som kan hjälpa dig att besvara dina frågor och ge vägledning om hur du fortsätter. API-integrationer som använder dessa tjänster kan migrera till [1.4 Analytics REST-API:er](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) eller [2.0 Analytics API:er](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Äldre OAuth-konton kan migrera till ett [Adobe I/O](https://console.adobe.io/home?mv=email#) Analytics-integrationskonto, som kan användas för att komma åt både 1.4-API:er för analyser och 2.0-API:er för analyser. |
| 2021 ISO-regionuppdateringar | 13 maj 2021 | Adobe kommer att genomföra 2021 års ISO-regionuppdateringar den 21 maj 2021. Efter den här versionen förväntas mindre uppdateringar visas. |
| EOL för datakällor med fullständig databehandling | 12 april 2021 | Adobe planerar att ta bort datakällor med fullständig bearbetning den 31 juli 2021. Från och med den 25 mars 2021 går det inte längre att skapa ny import av den här typen. Använd [API för datainfogning i grupp](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md) för att importera den här datatypen. |
| Logga in uppdatering till [!UICONTROL Report Builder] | 9 april 2021 | 14 januari 2021 tog [!UICONTROL Report Builder]-inloggningsuppdateringarna bort beroenden till äldre tekniker och anpassade inloggningsprocessen till Experience Cloud. Experience Cloud använder ditt Enterprise ID (e-post och lösenord). För att säkerställa oavbruten åtkomst till [!UICONTROL Report Builder] måste du uppdatera tillägget [!UICONTROL Report Builder] till version 5.6.47 eller senare senast den 22 juli 2021. Report Builder version 5.6.47 och senare stöder endast inloggning på Experience Cloud och stöder inte enkel inloggning. |
| Ändringar i datafeed och IP-adress för Data warehouse | 6 april 2021 | Från och med den 17 juni kommer dataflödena och leveranssystemet Data warehouse att flyttas inom datacentralerna i Adobe, vilket kan leda till att de externa IP-adresserna ändras. Adobe rekommenderar att du bekräftar att alla IP CIDR-block för datacentret där rapporter och feeds kommer finns i brandväggar för målsystem som du kontrollerar. [Här är en fullständig lista över IP-adressintervall som ska placeras i brandväggens tillåtelselista](https://experienceleague.adobe.com/docs/analytics/technotes/ip-addresses.html#data-collection-and-ftp-ip-address-blocks). |
| Meddelande om kommande ändringar på Analytics-menyn | 24 mars 2021 | Den 22 april 2021 uppdaterade Adobe listrutorna **[!UICONTROL Components]**, **[!UICONTROL Tools]** och **[!UICONTROL Admin]** för att uppnå vissa prestandavinster. Alla dessa sidor är fortfarande tillgängliga under länkarna **[!UICONTROL All Components]**, **[!UICONTROL All Tools]** och **[!UICONTROL All Admin]** - de kommer att tas bort från listrutan. Här är de menyalternativ som kommer att tas bort från listrutan och placeras på respektive länksida:<br><br> [!UICONTROL Components]<ul><li>[!UICONTROL Bookmarks]</li><li>[!UICONTROL Dashboards]</li><li>[!UICONTROL Targets]</li><li>[!UICONTROL Calendar Events]</li><li>[!UICONTROL Scheduled Reports]</li><li>[!UICONTROL Report Settings]</li></ul>[!UICONTROL Tools]<ul><li>[!UICONTROL Recommendations Classic]</li><li>[!UICONTROL Search & Promote]</li></ul>[!UICONTROL Admin]<ul><li>[!UICONTROL User Management]</li><li>[!UICONTROL Classification Importer]</li><li>[!UICONTROL Classification Rule Builder]</li><li>[!UICONTROL Data Sources]</li><li>[!UICONTROL Data Connectors]</li><li>[!UICONTROL Company Settings]</li><li>[!UICONTROL Logs]</li><li>[!UICONTROL Dynamic Tag Management]</li><li>[!UICONTROL Code Manager]</li><li>[!UICONTROL Exclude by IP]</li><li>[!UICONTROL Traffic Management]</li></ul> |
| Bearbetning av VISTA-SiteCatalyst PÅ | 17 mars 2021 | 17 juni 2021 uppdateras alla rapportsviter till att ha [!UICONTROL Same-as-SiteCatalyst VISTA Processing] inställt på ON. Den här förändringen påverkar Data warehouse-rapporteringen genom att data bearbetas för att matcha bearbetningsreglerna. Om du har frågor eller klargöranden kan du kontakta kundtjänst. |
| Alternativ för landningssidor för rapporter och analyser | 19 februari 2021 | Den 25 mars 2021 togs alternativen för att ställa in nya paneler för Rapporter och analyser eller annat innehåll allt eftersom Adobe Analytics landningssida togs bort. Om du tidigare har angett en rapport- och analyssida som din anpassade landningssida fortsätter den att fungera tills landningssidan ändras i [!UICONTROL User Preferences]. |
| Adobe Data Connectors upphör | 13 juli 2020 | Adobe [!UICONTROL Data Connectors] drivs av äldre teknik som inte längre är användbar eller stöds. En ny standard finns i [Adobe Exchange Partner Program](https://partners.adobe.com/exchangeprogram/experiencecloud). Du kan använda den standarden för alla integreringar för att fortsätta att erbjudas och få support. Det officiella slutdatumet är 1 augusti 2021. [Läs mer...](https://experienceleague.adobe.com/docs/analytics/import/dataconnectors/data-connectors-eol.html?lang=en) |

{style=&quot;table-layout:auto&quot;}

### AppMeasurement {#appm}

Uppdaterad information om de senaste AppMeasurement-versionerna finns i [versionsinformationen för AppMeasurement för JavaScript](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=en).

### Nya kurser och självstudiekurser i Analytics {#tutorials-analytics}

Nya kurser, självstudiekurser och artiklar i [!DNL Analytics] och [!UICONTROL Customer Journey Analytics].

| Publicerad | Namn | Typ | Beskrivning |
| -----------| ---------- | ---------- | ---------- |
| Juni 2021 | [Komma igång med Customer Journey Analytics för administratörer](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-A-1-2020.1) | Kurs | Lär dig hur du konfigurerar, konfigurerar och administrerar Customer Journey Analytics. Lär dig några grundläggande koncept som ger dig en grund och gå sedan vidare till fler konfigurationssteg. Kursen är sedan begränsad med några rekommendationer om hur man migrerar beräknade värden och segment från Adobe Analytics till Customer Journey Analytics. |
| Juni 2021 | [Konfigurera interna sökrapporter](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/configure-internal-site-search-reports.html?lang=en) | Video | Skapa och konfigurera frihandstabeller i Analysis Workspace för att analysera intern sökfunktion på din webbplats. |
| Juni 2021 | [Mappa Web SDK-variabler till Adobe Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/map-web-sdk-variables-into-adobe-analytics.html?lang=en) | Video | Lär dig hur du mappar analysvariabler från Web SDK till Adobe Analytics med bearbetningsregler. |
| Juni 2021 | [Implementera interna sökvariabler med Web SDK](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/implement-internal-search-variables-using-web-sdk.html?lang=en) | Video | Lär dig hur du använder Web SDK för att implementera Adobe Analytics-variabler för en intern sökterm tracking-användning. Se dataflödet från sidan till Experience Edge och sedan till Adobe Analytics. |
| Juni 2021 | [Implementera interna sökvariabler med AppMeasurement](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/implement-internal-search-variables-using-appmeasurement.html?lang=en) | Video | I den här videon får du lära dig hur du implementerar interna sökvariabler för Adobe Analytics med Experience Platform Data Collection/Launch, inklusive sökterm, antal resultat med mera. |
| Juni 2021 | [Definiera affärskrav för intern webbplatssökning](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/defining-your-internal-site-search-business-requirements.html?lang=en) | Video | När du bestämmer dig för att spåra intern sökning på din webbplats är det viktigt att först bestämma vilka aspekter av sökningen du vill spåra och vilka åtgärder som kan vidtas när resultaten analyseras. I den här videon går vi igenom dokumentationen av verksamhetskrav. |

{style=&quot;table-layout:auto&quot;}

### Hjälpresurser för Analytics

* [Adobe Analytics produktdokumentation och Tutorials](https://experienceleague.adobe.com/docs/analytics.html)

## ![Ikonen](/assets/audience-manager.png) Audience Manager {#aam}

Korrigeringar och förbättringar i Audience Manager.

### Korrigeringar och förbättringar {#aam-fixes-and-improvements}

* En förbättring av [rapporten om aktivitetsanvändning](https://experienceleague.adobe.com/docs/audience-manager/user-guide/features/administration/activity-usage-reporting.html?lang=en) har släppts. Nu kan du granska data som är äldre än ett år. (AAM-58268)
* Adobe ger Audience Manager-kunder nycklar för användaråtkomst för Audience Manager Amazon S3-bucket. Av säkerhetsskäl inaktiveras nycklarna nu automatiskt efter 100 dagars inaktivitet. Mer information finns i frågan längst ned på sidan i [Vanliga frågor om datainsamling och produktintegrering](https://experienceleague.adobe.com/docs/audience-manager/user-guide/faqs/faq-data-collection.html?lang=en).

## ![Ikonen för](/assets/aem.png) Experience Manager {#aem}

Nya funktioner, korrigeringar och uppdateringar i Experience Manager (AEM). Adobe rekommenderar att kunder med lokal driftsättning driftsätter de senaste patcharna för att säkerställa högre stabilitet, säkerhet och prestanda.

>[!NOTE]
>
>Adobe rekommenderar att du går till sidan [Experience Manager release updates and roadmaps](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html) för att hålla dig uppdaterad om versionsinformation.

### AEM produktuppdateringar

* **Experience Manager 6.5.9.0**

   AEM 6.5, Service Pack 9.0 (6.5.9.0 släppt 27 maj 2021) är en viktig uppdatering som innehåller nya funktioner, viktiga förbättringar som kunderna efterfrågat, förbättrade prestanda, stabilitet och säkerhet som släppts sedan den allmänna tillgängligheten av den AEM 6.5 april 2019.

   * [Versionsinformation](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=en)
   * [AEM Forms-releaser](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html?lang=en)

### AEM produktreleaser

* **Experience Manager as a Cloud Service**

   Nya funktioner i Experience Manager som Cloud Service:

   * **Adobe Experience Manager som Cloud Service Foundation**

      * [Prerelease Channel](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/prerelease.html?lang=en): Förgranska kommande funktioner en månad innan de publiceras live!
      * [API-borttagning](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/deprecated-apis.html?lang=en): En lista med de senaste inaktuella API:erna.
      * [Experience Manager som Cloud Service SDK Build Analyzer Maven Plugin](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/developing/archetype/build-analyzer-maven-plugin.html?lang=en): Uppdatera dina maven-projekt till den senaste versionen, som innehåller en inaktuell Java™ API-kontroll och andra förbättringar.
   * **Experience Manager Sites as a Cloud Service**

      * **GraphQL-slutpunkter:** det går nu att aktivera Experience Manager GraphQL API för enskilda Experience Manager Sites-konfigurationer och att skapa anpassade GraphQL-slutpunkter för dessa konfigurationer med ett nytt GraphQL-konsolgränssnitt. Användargränssnittet tillåter även hantering av GraphQL-slutpunkter.
      * **Innehållsmodeller, förbättrad datatyp för datum och tid:** det går nu att konfigurera datumtypen Datum och tid så att endast datum-, tid- eller datum- och tidsinformation kan redigeras.
      * **Innehållsmodeller, förbättrad taggdatatyp:** det går nu att konfigurera datatypen Taggar så att du kan skapa en eller flera taggar.
      * **Innehållsmodeller, ny flik, platshållardatatyp:** den nya tabbplatshållardatatypen gör att du kan gruppera datatyper i avsnitt som återges under flikar i innehållsfragmentredigeraren.
   * **Experience Manager Assets as a Cloud Service**

      Nu kan du verifiera innehåll på en ny [förhandsgranskningsnivå](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/authoring/fundamentals/previewing-content.html?lang=en) för att simulera det slutliga utseendet och utseendet som på publiceringsnivån. Den här nya funktionen aktiveras av guiden Hantera publikation för Experience Manager Sites, som gör att du kan välja ett publiceringsmål mellan [!UICONTROL Publish] eller [!UICONTROL Preview]. Du kan sedan komma åt upplevelser på [!UICONTROL Preview] via en dedikerad URL. Efter valideringen [!UICONTROL Preview] kan innehåll publiceras från [!UICONTROL Author] till [!UICONTROL Publish] som vanligt. Att aktivera tjänsten [!UICONTROL Preview] i Experience Manager som Cloud Service kommer gradvis att byggas ut de närmaste veckorna.

   * **Experience Manager Assets as a Cloud Service**

      Nya funktioner i prerelease-kanalen:

      * Metadata-scheman kan tillämpas direkt på mappegenskaperna.
      * Med [!UICONTROL Asset Bulk Ingestor]-verktyget kan du lägga till metadata vid ett gruppberoende.
      * En förbättrad användarupplevelse visar antalet resurser i en mapp. För mer än 1 000 resurser i en mapp visas 1 000+ i Experience Manager Assets.

      Nya funktioner i [!UICONTROL Dynamic Media]:

      * Med optimering av pixelproportioner för smarta bildbehandlingsenheter (DPR) och nätverksbandbredd kan du leverera bilder av högsta kvalitet effektivt på enheter med högupplösta skärmar och begränsad nätverksbandbredd. Se [Vanliga frågor om smart bildbehandling](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/dynamicmedia/imaging-faq.html?lang=en).




### **AEM**

* [Samköp av alla bloggar i Experience Manager](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/bd-p/adobe-experience-manager-discussions)

* [Riktlinjer för inlämning av nya Experience Manager Idea](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/guidelines-for-submitting-a-new-experience-manager-aem-idea/td-p/382376)

* [Adobe Summit 2021 Sneaks med Dan Levy](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-summit-2021-sneaks-with-dan-levy/td-p/405865): En gång om året har anställda i Adobe, från ingenjörer och datavetare till UX-designers och produktchefer, en chans att dela innovativa idéer för att utveckla hur varumärken interagerar med sina kunder. Följ oss på Adobe Sneaks, där vi delar de sju främsta projekten och utnyttjar den senaste tekniken inom områden som AI och lågkodsappar.

### Versionsinformation för Experience Manager

All versionsinformation för Experience Manager finns på följande sidor:

* [Experience Manager som Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/home.html?lang=en)
* [Versionsinformation om Experience Manager Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=en)
* [Versionsinformation för konverteringstjänsten för automatiserade formulär](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=en)
* [Versionsinformation om Experience Manager 6.5 Service Pack](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=en)
* [Versionsinformation för Experience Manager 6.4 Cumulative Fix Pack](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=en)
* [Versionsinformation om Experience Manager Assets Dynamic Media](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=en)
* [Versionsinformation för Experience Manager Brand Portal](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=en)
* [Versionsinformation för Experience Manager-datorprogrammet](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=en)
* [Versionsinformation om Experience Manager Dispatcher](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=en)
* [Versionsinformation för Livefyre](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=en)

### Nya Experience Manager-kurser och självstudiekurser {#tutorials-aem}

Nya videor, självstudiekurser och kurser som publicerats under den senaste månaden.

| Publicerad | Namn | Typ | Beskrivning |
| -----------| ---------- | ---------- | ---------- |
| Juni 2021 | [Implementera gränssnittsmetoderna](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/implement-interface.html?lang=en) | Artikel | Lär dig hur du implementerar gränssnittsmetoder för att skapa PDF-filer med Document Cloud REST API. |
| Juni 2021 | [Skapa tjänstgränssnitt](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/create-interface.html) | Artikel | Definiera metoderna i gränssnittet som du vill visa. |
| Juni 2021 | [Skapa anpassad OSGi-konfiguration](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/create-doc-cloud-configuration.html?lang=en) | Artikel | Lär dig mer om anpassad OSGi-konfiguration så att du kan hämta projektinformation från Adobe I/O. |
| Juni 2021 | [Skapa innehållsanalys](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/get-content-analyzer.html?lang=en) | Artikel | Lär dig hur du skapar JSON-delen som innehåller information om indataparametrarna för Create PDF REST-anropet. |
| Juni 2021 | [Skapa anpassat processsteg](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/custom-process-step.html?lang=en) | Artikel | Visa den fullständiga koden för det anpassade processsteget som konverterar och ersätter originalfilerna med de konverterade PDF-filerna. Det här anpassade steget söker efter alla bilagor under mappnamnet, som anges som ett processargument i arbetsflödet. Det här anpassade processsteget använder metoderna i den anpassade `DocumentCloudSDKService` för att skapa PDF-filer. |
| Juni 2021 | [GraphQL-beständiga frågor](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/video-series/graphql-persisted-queries.html?lang=en) | Video | Lär dig hur du aktiverar, skapar, uppdaterar och kör beständiga frågor i Experience Manager. |
| Juni 2021 | [Skapa din första servlet i AEM Forms](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/creating-your-first-osgi-bundle/create-servlet.html?lang=en) | Artikel | Bygg din första försäljningsserver så att du kan sammanfoga data med en formulärmall. |
| Juni 2021 | [Skapa din första OSGi-tjänst med Experience Manager-formulär](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/creating-your-first-osgi-bundle/create-osgi-service.html?lang=en) | Artikel | Bygg din första OSGi-tjänst med AEM Forms så att du kan generera PDF-filer genom att sammanfoga data med mallar. |

{style=&quot;table-layout:auto&quot;}

### Andra hjälpresurser för Experience Manager

* [Handböcker om Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/landing/home.html?lang=en)
* [Experience Manager 6.5 - startsida för utbildning och support](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=en)
* [Experience Manager 6.4 - startsida för utbildning och support](https://experienceleague.adobe.com/docs/experience-manager-64.html)
* [Experience Manager 6.3 - startsida för utbildning och support](https://helpx.adobe.com/se/support/experience-manager/6-3.html)
* [Experience Manager 6.2 - utbildning och support - startsida](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Äldre versioner av Experience Manager-dokumentation](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Användarhandbok för Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=en)
* [Dynamic Media Classic – startsida för hjälp](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=en)
* [Dokumentation för Experience Manager: Senaste uppdateringar](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=en#aem-as-a-cloud-service)

## ![Ikon](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign är ett intuitivt och automatiserat sätt att leverera personliga meddelanden i alla marknadsföringskanaler, både online och offline. Nu kan ni förutse vad era kunder vill ha med upplevelser som bestäms av deras vanor och önskemål.

### Senaste produktreleaser

Läs mer om de senaste funktionerna, förbättringarna och korrigeringarna:

* **Nya Adobe Campaign v8** med betydande förbättringar vad gäller infrastruktur, säkerhet, leveransbarhet och övervakning. Genom att använda [!DNL Snowflake], en molndatabasteknik, förbättrar Adobe Campaign dramatiskt sin skala och hastighet, med möjlighet att hantera ett större antal kundprofiler, samt mycket högre leveransfrekvenser och transaktioner per timme. Läs mer i [Campaign v8-dokumentationen](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html).

* **Adobe Campaign Classic version** 21.1.3: Läs mer i versionsinformationen om  [Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html).

* **Adobe Campaign Standard 21.2-utgåvan**: Läs mer i  [Campaign Standardens versionsinformation](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html).

### Nya [!UICONTROL Campaign] kurser och självstudiekurser {#tutorials-campaign}

| Publicerad | Namn | Lösning | Beskrivning |
| -----------| ---------- | ---------- | ---------- |
| Juni 2021 | [Integrera Campaign Standard med Analytics för att optimera er e-postmarknadsföring](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2021.1.integration) | Campaign Standard | (Kurs) Lär dig hur du integrerar Campaign Standard med Adobe Analytics och optimerar dina e-postmarknadsföringsstrategier med realtidsdata. Den här kursen visar hur du skapar en Campaign Standard i Adobe Analytics. Lär dig sedan hur du använder Experience Cloud Triggers och Platform launch för att konfigurera marknadsförings- och transaktionsmeddelanden baserat på kundaktivitet. |
| Juni 2021 | [Självstudiekurser om Adobe Campaign V8](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/overview.html) | Campaign V8 | Den här användarhandboken innehåller videor och självstudiekurser om de många funktioner och möjligheter som finns i Adobe Campaign V8. |
| Juni 2021 | [Skapa och designa e-postleveranser](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/content-creation/email/create-and-design-email-deliveries.html) | Kampanj V8 | (Video) Förstå processen med att skapa e-postleveranser och lär dig hur du utformar och anpassar e-postinnehåll. |
| Juni 2021 | [Designa e-postmeddelanden för levererbarhet](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/email/design-emails-for-deliverability.html) | Kampanj V8 | (Video) Lär dig hur du tillämpar bästa praxis för leverans på e-postleveranser. |
| Juni 2021 | [Hantera trötthet med typologiregler](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/fatigue-management/typology-rules-for-fatigue-management.html) | Kampanj V8 | (Video) Lär dig hur du implementerar trötthetshantering genom att tillämpa typologiregler. |
| Juni 2021 | [Ställa in trötthetshantering med filter](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/fatigue-management/fatigue-management-using-filters.html) | Campaign Standard | (Video) Lär dig hur du implementerar trötthetshantering i Adobe Campaign med hjälp av filter. |

{style=&quot;table-layout:auto&quot;}

### Hjälpresurser för Campaign

* Adobe Campaign Standard: [Hjälpcenter](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=en) – [Versionsinformation](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=en) – [Instruktionsvideor](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=sv) – [Versionsplanering](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=en) – [Senaste dokumentationsuppdateringar](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=en)
* Adobe Campaign Classic: [Hjälpcenter](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=en) – [Versionsinformation](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=en) – [Instruktionsvideor](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=sv) – [Senaste dokumentationsuppdateringar](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=en)
* Kontrollpanelen för Adobe Campaign: [Dokumentation](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=sv) – [Versionsinformation](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=en)  - Instruktionsvideor för [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=en) / [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=en)

## ![](/assets/advertising-cloud.png) IconAdvertising {#adcloud}

Versionsinformation för [!DNL Adobe Advertising].

* [Nya funktioner i Advertising DSP](#adcloud-dsp)
* [Nya funktioner i Advertising Search](#adcloud-search)

### Nya funktioner i [!DNL Advertising DSP] {#adcloud-dsp}

Senast uppdaterad: **10 juni 2021 för 16 juni**

| Funktion | Beskrivning |
| -----------| ---------- |
| Kampanjhantering | (16 juni) Prognoser finns tillgängliga för standardbildskärmsplaceringar med placering på placeringsnivå och budgetar. |

{style=&quot;table-layout:auto&quot;}

### Nya funktioner i [!DNL Advertising Search] {#adcloud-search}

Senast uppdaterad: **19 maj 2021, för 18 maj-utgåvan**

| Funktion | Beskrivning |
| -----------| ---------- |
| [!UICONTROL Notification Center Beta] | [!UICONTROL Notification Center Beta] är tillgänglig för alla användare. Använd prenumerationen på e-post och webbmeddelanden om kontoautentiseringsfel, anpassade aviseringar som utlöses och slutförande av [!UICONTROL Advertising Insights] som du genererar.<br>Du kan visa meddelanden från:<ul><li>Panelen [!UICONTROL Notifications], som öppnas från meddelandelänken i det övre högra hörnet på en sida.</li><li>[!UICONTROL Notification Center] vid [!UICONTROL Insights & Reports >Notification Center Beta].</li></ul><br><b>Obs!</b> På grund av förbättringar i hur meddelanden lagras rensades alla befintliga meddelanden. |

{style=&quot;table-layout:auto&quot;}

## ![Ikon](/assets/magento.png) [!DNL Magento] {#magento}

Information om den senaste versionen finns i Magento Commerce och Open Source [versionsinformation](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html).

## ![Ikon](/assets/target.png)[!DNL Target] {#target}

Den senaste informationen finns i [[!DNL Target]  versionsinformationen](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=en).

## ![Ikon](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] är en komplett applikation för lead-hantering och B2B-marknadsförare som vill omvandla kundupplevelser genom att engagera sig i alla faser av komplexa inköpsresor.

### Uppdateringar om Core Marketo Engage

Se [!DNL Marketo Engage] [releaseschema](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=en) för information om det senaste releaseschemat och versionsinformation.

## ![Ikon](/assets/workfront.png) [!DNL Workfront] {#workfront}

Adobe [!DNL Workfront] är ett enhetligt program för att utbyta idéer, skapa innehåll, hantera komplexa processer och göra sitt bästa.

På sidan [[!DNL Workfront] releases](https://one.workfront.com/s/product-releases) finns en sammanfattning av den senaste informationen om alla produkter.

## ![](/assets/document-cloud-24.png) IconDocument Cloud  {#doc-cloud}

Nya videor, självstudiekurser eller kurser publicerade för Adobe Document Cloud.

### Document Cloud kurser och självstudiekurser {#tutorials-doc-cloud}

| Publicerad | Namn | Typ | Beskrivning |
| -----------| ---------- | ---------- | ---------- |
| Juni 2021 | [Adobe Acrobat för Google Drive](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/acrobatandgoogle.html) | Video | Få tillgång till tidsbesparande PDF-verktyg och arbetsflöden för e-signering direkt inifrån Google Drive-appen. |

{style=&quot;table-layout:auto&quot;}

Mer information om Document Cloud finns i:

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html)
* [Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html)
* [Document Cloud studiematerial och support](https://helpx.adobe.com/support/document-cloud.html)

## ![](/assets/creative-cloud-24.png) IkonCreative Cloud Enterprise  {#creative-cloud}

| Publicerad | Namn | Typ | Beskrivning |
| ----------| --------- | --------- | --------- |
| Juni 2021 | [Prova din hand på Fresco på iPad (och iPhone)](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/frescoworkshop.html) | Video | Utforska en helt ny värld av digital ritning och målning med Adobe Fresco i denna 15-minuters praktiska workshop. Lär dig arbeta snabbt med lager och urklippsmasker för att anpassa färg och texturer till en grundform. |
| Juni 2021 | [Avkodning av alfabet-soppa för grafikformat](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/alphabetsoup.html) | Video | PG-, PNG-, SVG-, GIF- och EPS-filer används ofta i design, vissa för webbsidor, andra för presentationer, publikationer och kreativa projekt. Men... vad menar de, och vilka ska du välja? Ta reda på det i den här 15-minuters praktiska workshopen. |

{style=&quot;table-layout:auto&quot;}

De senaste självstudiekurserna finns i [Creative Cloud för Enterprise Tutorials](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=en).
