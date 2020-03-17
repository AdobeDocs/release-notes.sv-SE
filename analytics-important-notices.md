---
title: Viktiga meddelanden för analysadministratörer
description: Mall för versionsinformation om Experience Cloud
doc-type: release notes
last-update: March 2019
author: mfrei
translation-type: tm+mt
source-git-commit: 28b368ee99ec393ec4e2250390d61fb00fed4735

---


# Viktiga meddelanden för Analytics-administratörer {#aa-notices}

| Meddelande | Datum tillagt eller uppdaterat | Beskrivning |
| -----------| ---------- | ---------- |
| Kommande supportändringar för datumaktiverade och numeriska klassificeringar | 28 februari 2019 | Möjligheten att importera Numeric 2- och Date-Enabled-klassificeringar har tagits bort från kodbasen. Denna ändring träder i kraft i underhållsutgåvan från juni 2019. Om du har numeriska eller datumaktiverade kolumner i importfilen, ignoreras dessa celler och alla andra data i filen importeras som vanligt. <br/>Befintliga klassificeringar kan fortfarande exporteras via standardarbetsflödet för klassificering och kommer att vara tillgängliga i rapporter. |
| Dokumentationen för plugin-programmet getPercentPageViewed har uppdaterats avsevärt. | 12 februari 2019 | [https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/getPercentPageViewed.html](https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/getPercentPageViewed.html) |
| Admin > Allmänna kontoinställningar | 7 februari 2019 | * Inställningen _Ersätt den sista oktetten med IP-adresser med 0_ är aktiverad som standard för alla nya rapportsviter som skapats i London Data Center efter januari 2019, men bara om inställningarna för dessa rapportsviter kopieras från en mall som visas i Admin Console. Rapportsviter vars inställningar dupliceras från andra rapportsviter ärver alla inställningar från den valda rapportsviten.<br/> * Inställningen för _IP-fakturering_ är inte längre aktiverad som standard för alla kunder som har en rapportsvit inom EMEA. |
| Versionsnummer för mobilwebbläsare | 7 februari 2019 | Från och med 8 januari 2019 har vi ändrat trunkeringsnivån för versionsnummer för mobila webbläsare från 2 till 1. Från och med det datumet visar versioner bara de två första nivåerna (t.ex. _Firefox 64.0.2_ rapporteras nu som _Firefox 64.0_). |
| Slutet av livscykeln för Ad hoc-analys | Uppdaterad 29 januari 2019 | Den 6 augusti 2018 meddelade Adobe att man hade för avsikt att göra en Ad hoc-analys i slutet av livscykeln. Ett slutdatum delas så snart det är tillgängligt.<br/>Mer information, inklusive vilka versioner av Java som ska vara kompatibla under den här perioden, finns på [Discover Workspace](https://adobe.ly/discoverworkspace). |
| Länkar till korta analysrapporter | 14 januari 2019 | Eventuella länkar till korta analysrapporter som inte har besökt inom ett år kommer att rensas och tas bort från och med torsdagen den 17 januari 2019 enligt ett rullande schema. |
| Stöd för TLS 1.0 upphör | Uppdaterad 10 januari 2019 | Den 11 februari 2019 kommer Adobe Analytics-rapporter inte längre att ha stöd för TLS (Transport Layer Security) 1.0-kryptering. Den här förändringen är en del av våra pågående ansträngningar att upprätthålla högsta säkerhetsstandarder och främja säkerheten för kunddata. Om du inte kan ansluta till Adobe Analytics-rapporter efter den 11 februari 2019 bör du uppgradera webbläsaren till den [senaste versionen](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html).<br/> Från och med den 20 februari 2019 har Adobe Analytics-datainsamlingen inte längre stöd för TLS 1.0. Med den här ändringen kommer Adobe inte längre att samla in analysdata från slutanvändare med äldre enheter eller webbläsare som inte stöder TLS 1.1 eller senare. Vi förväntar oss inte att detta ska ha någon större inverkan på kunddata eller rapportering. (Om webbplatsen inte har stöd för TLS 1.0 påverkas den inte.) <br/>Från och med 11 april 2019 har Adobe Analytics Reporting API inte längre stöd för TLS 1.0-kryptering. Kunder som har åtkomst till API bör verifiera att de inte kommer att påverkas. <br/>* API-klienter som använder Java 7 med standardinställningar behöver [ändras för att stödja TLS 1.2](https://www.java.com/en/configure_crypto.html). (Se _Ändra TLS-standardprotokollversionen för klientslutpunkter: TLS 1.0 till TLS 1.2_.) <br/>* API-klienter som använder Java 8 bör inte påverkas eftersom standardinställningen är TLS 1.2. <br/>* API-klienter som använder andra ramverk måste kontakta sina leverantörer för att få information om TLS 1.2-stödet. |
| Uppdatera Adobe Report Builder på grund av att stödet för TLS 1.0 har upphört | 7 september 2018 | Eftersom stödet för TLS 1.0 har upphört rekommenderar vi användare av Adobe Report Builder (ARB) att hämta ARB v5.6.21 före 7 februari 2019. **Efter detta datum fungerar inte längre tidigare versioner av ARB.** |
| Uppdatera till CSV-nedladdningar från Analysis Workspace | 9 januari 2019 | Från och med den 7 februari 2019 kommer inte längre tusentalsavgränsaren att ingå i CSV-hämtningar (och kopiering till Urklipp) från Analysis Workspace. Obs! Användargränssnittet för Analysis Workspace kommer att fortsätta visa tusentalsavgränsaren. Dessutom kommer decimalavgränsaren att finnas kvar och följa det format som definieras under **[!UICONTROL Komponenter]** > **[!UICONTROL Rapportinställningar]** > **[!UICONTROL Tusentalsavgränsare]**. |
| Datafeed: kolumn efter_product_list - storleksändring | 9 januari 2019 | Den 7 februari 2019 planerar Adobe att utöka storleken på kolumnen post_product_list från 64 kB till 16 MB. Den här ändringen är avsedd att säkerställa att eVar-värden som läggs till efter_product_list under bearbetning inte orsakar trunkering av produkt- och intäktsvärden. Om du har processer som innehåller värden för post_product_list måste du se till att dessa processer kan hantera värden som är upp till 16 MB långa, eller så kortas värdet av vid 16 kB för att undvika dataproblem. |
| Hanteringsändringar som påverkar inaktiva liveströmslutpunkter i Analytics | 20 december 2018 | Från och med 1 februari 2019 kan liveströmslutpunkter utan aktiva konsumentanslutningar under 90 dagar inaktiveras. Du kan kontakta kundtjänst för att få information om dina liveströmsslutpunkter och, om det behövs, aktivera dem igen. Kontrollera dessutom att dina konsumentprocesser upprätthåller en beständig anslutning, enligt vad som avses i tjänstens utformning, och att de implementeras för återanslutning när anslutningen kopplas från eller avbryts. |
| Migrering av Dallas FTP-server (ftp2.omniture.com) | 19 oktober 2018 | Om du ansluter till ftp2.omniture.com via SFTP-protokollet den 23 oktober 2018 kan du behöva godkänna värdidentifieraren för SJ1-webbplatsen igen. Denna fråga gäller endast den 23 oktober. Se [Uppgradera Adobes FTP-servrar](https://docs.adobe.com/content/help/en/analytics/export/ftp-and-sftp/ftp-upgrade.html). |
| Dimensionen Uppdatera till mobil enhet | 16 oktober 2018 | Den 26 september uppdaterade Adobe sin enhetssökning till Device Atlas 2.1 API. Detta orsakade mer detaljerade enheter (t.ex. Apple iPhone 7, Apple iPhone 8 Plus osv.) visas i mobilenhetsdimensionen för vissa webbläsare. Den här nya detaljnivån för enheter bör användas direkt, eftersom den för närvarande inte omfattar alla enheter och webbläsartyper. |
| Stöd för Internet Explorer 11 har upphört | 12 september 2018 | Adobe upphör med stödet för Internet Explorer 11 i Adobe Analytics den 13 november 2018. Växla till Microsoft Edge eller någon annan webbläsare som stöds så snart som möjligt. |
| Slutet av livscykeln för Ad hoc-analys | 9 augusti 2018 | Den 6 augusti 2018 meddelade Adobe att man hade för avsikt att göra en Ad hoc-analys i slutet av livscykeln. Ett slutdatum delas så snart det är tillgängligt. Mer information finns på [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). Vi kommer inte att ändra [!UICONTROL Ad hoc-analys] för att stödja Java 9+ från och med nu. Om du uppgraderar till Java 9+ slutar [!UICONTROL Ad Hoc Analysis] att fungera. Endast Java 8 stöds. |
| Uppdatera Adobe [!UICONTROL Report Builder] på grund av att stödet för TLS 1.0 har upphört | 7 september 2018 | Eftersom stödet för TLS 1.0 har upphört rekommenderar vi att [!UICONTROL användare av Report Builder] (ARB) laddar ned ARB v 5.6.21 före februari 2019. Efter detta datum kommer tidigare versioner av ARB inte längre att fungera. |
| Ny hjälp för migrering av Analytics-användare | 10 maj 2018 | Vi uppdaterade hjälpen för migrering av användare-ID för Analytics med information om hur du migrerar Enterprise ID:n och Federated ID:n till Admin Console. Se [Migrate Analytics-användarkonton för Enterprise ID och Federated ID](https://docs.adobe.com/content/help/en/analytics/admin/user-product-management/user-management/migrate-users/c-migration-tool.html). |
| Rapport om kontoaktivitet kommer att tas bort | 10 maj 2018 | Kontoaktivitetsrapporten kommer att ersättas av funktionen Serversamtalsanvändning i sommarversionen av Adobe Analytics. Kontoaktivitetsrapporten tas bort permanent den 9 augusti 2018. Om du vill visa sammanfattningsdata om rapporttrafiken efter 9 augusti 2018 använder du funktionen Serversamtalsanvändning. |
| Ändringar av linjära allokeringsmodeller i beräknade värden | 19 juli 2018 | Den 19 juli kommer Adobe Analytics att se över hur allokeringsmodeller i beräknade värden utvärderas. Som en del av den här ändringen kommer beräknade värden som använder en icke-standardallokeringsmodell att migreras till nya och förbättrade attribueringsmodeller. [!UICONTROL Allokeringsmodellerna Senaste beröring] för marknadsföringskanalen och [!UICONTROL Marknadskanalen Första beröring] kommer att migreras till de nya [!UICONTROL attribueringsmodellerna Last Touch] och [!UICONTROL First Touch] . ([!UICONTROL Marknadskanaler] tas inte bort, bara de två allokeringsmodellerna som visas i beräknade värden). Dessutom kommer vi att korrigera hur linjär allokering beräknas. Om du använder beräknade värden med linjära allokeringsmodeller kan rapporterna ändras något för att återspegla den nya, korrigerade attribueringsmodellen. Den här förändringen av beräknade värden återspeglas i [!UICONTROL Analysis Workspace], [!UICONTROL Reports &amp; Analytics], [!UICONTROL Reporting API], [!UICONTROL Report Builder]och [!UICONTROL Ad Hoc Analysis]. Mer information om den här ändringen finns i dokumentationen [Beräknade mått](https://docs.adobe.com/content/help/en/analytics/components/calculated-metrics/calcmetric-workflow/m-metric-type-alloc.html) . |
| [!UICONTROL Funktionen Analys] av avvikelseidentifiering och [!UICONTROL bidragsanalys] har tagits bort från [!UICONTROL rapporter och analyser] | 10 april 2018 | Analysidentifiering och bidragsanalys har tagits bort från funktionerna Rapporter och analyser och är nu bara tillgängliga via Analysis Workspace. Adobe Analytics Select- och Foundation-kunder har endast tillgång till&quot;daglig granularitetsidentifiering&quot; i Workspace. |
| Adobe utfärdar inte längre s_vi-cookies från tredje part för Safari | 5 april 2018 | Den 20 mars 2018 slutade Adobe att utfärda s_vi-cookies från tredje part för webbläsaren Safari. Den här ändringen påverkar inte kunder som använder cookies från första part. Denna ändring tar också bort besöks- och besöksinflammation som vissa kunder upplever som en följd av Safari ITP. |
| Uppdatera Report Builder innan du migrerar användar-ID:n till Admin Console | 17 mars 2018 | **Viktigt:** Uppdatera installationen av Report Builder till den senaste versionen. Uppdateringen är en förutsättning för att du ska kunna migrera Analytics-användar-ID:t till Admin Console från och med april 2018. Information om migrering finns i [Användarmigrering för Analytics till Admin Console] . |
| Förändringar som påverkar rapporteringen | 11 april 2018 | En ändring av sökfunktionen (back-end) kommer att påverka rapporteringen på flera sätt. Observera att dessa ändringar trädde i kraft i slutet av februari 2018: Det går inte längre att byta namn på sidor. Du måste använda klassificeringar för att byta namn på sidor. Fram till 10 maj 2018-utgåvan kommer systemet att fortsätta bearbeta de namnändrade sidorna som de är konfigurerade. Adobe ber alla kunder att migrera till klassificeringar vid det datumet. Efter majversionen kommer befintliga namn inte längre att respekteras och kan ändras retroaktivt utan föregående meddelande. <br> <br>URL-ersättningsmetoden är annorlunda. Tidigare lagrar Adobe Analytics (oftast) den första URL som är kopplad till varje sidnamn varje månad. Vi kommer att lagra den senaste URL:en för varje sidnamn. (Uppdaterat 11 april 2018) Kategorirapporter för sammanslagningar och aktuella data i rapporter och analyser tillhandahålls inte längre. Borttagning av kategorisammanslagningsrapporter i webbtjänstens API gäller i underhållsutgåvan av Adobe Analytics från 10 maj 2018. Det finns inte längre något stöd för sid-/propdata från före ungefär januari 2007 (i vissa fall 2006). Detta påverkar bara sidor, utkast och sidhändelser (t.ex. anpassade länkar, avslutslänkar, hämtningslänkar). Obs! Den här ändringen påverkar inte rapportering i Analysis Workspace eller Data Warehouse. Om du har data som föregår dessa datum kan du förvänta dig följande: Data kommer inte att kombineras korrekt över gränsen före/efter januari 2007. Sökningar kommer inte att fungera mot data före ungefär januari 2007. |
| Kommande supportändringar för datumaktiverade och numeriska klassificeringar | 7 maj 2018 | I underhållsutgåvan från 10 maj 2018 börjar vi begränsa funktionaliteten för datumaktiverade och numeriska klassificeringar. Dessa klassificeringstyper kommer att tas bort från gränssnitten Admin och Klassificeringsimporter. Från och med det datumet går det inte att lägga till nya datumaktiverade och numeriska klassificeringar. Befintliga klassificeringar kan fortfarande hanteras (överföras till, tas bort) via standardarbetsflödet för klassificering, och kommer även i fortsättningen att vara tillgängliga vid rapportering. |
| Kommande supportändringar för marknadsföringskanalkostnader och budget | 28 februari 2018 | I underhållsversionen från april kommer vi att ta bort kostnaden och budgeten för marknadsföringskanalen från menyn Admin > Marknadskanal. Inga nya kostnads- och budgetdata kan läggas till. Befintliga kostnads- och budgetdata är fortfarande tillgängliga vid rapportering, men kan inte uppdateras. |
| Kodhanteraren - äldre H-kod | 8 februari 2018 | Det går inte längre att hämta äldre JavaScript-kod (H-kod) från kodhanteraren. |
| Datalagring: Kontrollera och ange din datalagringspolicy för Adobe Analytics | 1 februari 2018 | **Bakgrund:** I EU:s allmänna dataskyddsförordning (GDPR), som gäller från och med den 25 maj 2018, föreskrivs att Adobe i sin roll som personuppgiftsbiträde måste vidta lämpliga åtgärder för att hjälpa sina kunder med att uppfylla åtkomst, radering och andra förfrågningar från enskilda personer. Att tillämpa lämpliga, säkra och vältajmade principer för borttagning är en viktig del av att uppfylla denna skyldighet. Därför vill Adobe arbeta tillsammans med er för att införa en policy för datalagring innan GDPR börjar gälla den 25 maj 2018.<br> <br>**Vad du kan förvänta dig:**Om du inte redan har en Adobe Analytics-datalagringspolicy på plats, kommer Adobe att börja tillämpa datalagring enligt vad som för närvarande anges i kundkontrakt för Adobe Analytics, såvida inte andra arrangemang görs. I de flesta Adobe Analytics-kontrakt anges att Adobe kan ta bort data efter 25 månader. När en datalagringspolicy har införts för din organisation, tillämpas den löpande månadsvis. Datalagring under längre perioder än 25 månader kan fås mot en extra avgift. Datalagringsperioder för kortare perioder kan också konfigureras genom att kontakta kundtjänst. Du kommer snart att få ett e-postmeddelande med ytterligare information om din organisation.<br> <br>Datalagring påverkar alla metoder för åtkomst till historiska Adobe Analytics-data, inklusive, men inte begränsat till, Rapporter &amp; Analytics, Analysis Workspace, Report Builder, Web Services Reporting API:er, datalager och dataflöden. **Nästa steg:** Identifiera de intressenter i organisationen som ansvarar för att fatta beslut om datalagring. Din organisation är bäst lämpad att veta under vilken period Adobe Analytics-data ska lagras. Kontakta din Adobe Customer Success Manager om du har frågor om datalagring för Adobe Analytics. |
| Länka användarkonto | 26 oktober 2017 | Analysanvändare behöver inte längre länka sina konton manuellt mellan Experience Cloud och Analytics. Användare kan kontakta sin administratör för Admin Console för att begära Analytics-åtkomst. Med migreringen av användar-ID:n i Analytics kan administratörer enkelt migrera användarkonton från användarhantering i Analytics till Adobe Admin Console. När användarna har migrerats får de tillgång till de köpta lösningarna och bastjänsterna i Experience Cloud. [Läs mer om migrering](https://docs.adobe.com/content/help/en/analytics/admin/user-product-management/user-management/migrate-users/c-migration-tool.html)av användar-ID för Analytics. |