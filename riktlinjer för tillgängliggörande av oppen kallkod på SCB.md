# Riktlinjer för tillgängliggörande av Öppen källkod på SCB

## Vad är öppen källkod?

Open Source eller öppen källkod är ett fenomen som har funnits en längre tid inom it-branschen. Den mest accepterade definitionen av öppen källkod är The Open Source Definition[^1], OSD, som har tagits fram av den ideella stiftelsen Open Source Initiative[^2], OSI. Denna definition begränsar inte öppen källkod till att en användare enbart ska ha tillgång till källkoden dvs den programkod som en programvara är uppbyggd av. Istället kräver OSD att källkoden ska vara fritt tillgänglig för användarna. Den ger användaren rätt att studera, ändra och dela med sig av källkoden, antigen i modifierad eller icke modifierad form. Med andra ord handlar det om hur källkoden får vidareförädlas och distribueras. Det bör poängteras att det är användarens egen kopia av den ursprungliga källkoden som hen har rätt att modifiera och inte originalet.

Rent praktiskt tillgängliggörs källkoden under en licensform och det är licensen som avgör om det är en öppen källkod. Det finns i dagsläget en uppsjö av olika licensformer[^3] som följer OSD.

## Varför öppen källkod?

Tack vare att öppen källkod möjliggör byggandet av nya tillämpningar utifrån existerande lösningar så har den varit, och är fortfarande, en stor bidragande faktor till digitaliseringen och den snabbt ökande innovationskraften runtom i världen. Storföretag som Google, IBM och Microsoft har insett detta och anpassat sina strategier, men även flera organisationer och länder. Bland annat har Europakommissionen i sin Open Source Software Strategy[^4] kommit fram till att de vill stärka nyttjandet av programvara som bygger på öppen källkod vid upphandlingar. De vill även bidra till öppna källkodsprojekt och erbjuda egenutvecklade applikationer som öppen källkod. Ett annat exempel är den Brittiska regeringen som 2016 beslutade att de som standard skulle tillgängliggöra sina egenutvecklade applikationer som öppen källkod[^5]. Även i statistikvärlden tillgängliggörs programkod som öppen källkod. Den nederländska statistikbyrån har delat med sig av flera funktioner och programvaror som öppen källkod. De har även sammanställt en lista av funktioner och programvaror som kan användas vid statistikproduktion som kan ses här: [https://github.com/SNStatComp/awesome-official-statistics-software](https://github.com/SNStatComp/awesome-official-statistics-software).

Även Norges och Storbritanniens statistikbyråer har tillgängliggjort[^6] några av sina egenutvecklade programvaror och bjudit in till samarbete kring dessa.

Inom EU finns också en strategi för öppen källkod för kommissionens interna utvecklingsprojekt i syfte att stärka och styra användningen av programvara med öppen källkod, se Open Source Software Strategy.

I regeringsdokumentet "Så enkelt som möjligt för så många som möjligt - från strategi till handling för e-förvaltning" finns nedanstående rekommendation:

Drivkrafterna till att nyttja och/eller bidra till öppen källkod är flera - spara på kostnader, skapa en plattform för samarbeten, skapa mernytta, väcka intresse hos andra, attrahera IT-personal, öka transparensen etc.

## Hur gör vi med öppen källkod på SCB

SCB ska använda sig av och bidra till öppen källkod där det är strategiskt rätt.

SCB ska tillgängliggöra egenutvecklad programvara då det är relevant, förutsatt att programkoden går att tillgängliggöra ur säkerhetsperspektiv, det ligger i linje med eventuella avtal och att det är ekonomiskt försvarbart.

SCB ska bidra till öppen källkod för att stärka samarbetet mellan myndigheter, kanske främst andra statistikansvariga myndigheter, men även andra statistikbyråer.

SCB ska bidra till öppen källkod då vi är skattefinansierade och det kan finnas andra aktörer som kan dra nytta av den utveckling och förvaltning som vi gör, samt att det ökar vår transparens.

SCB utvecklar kod enligt OWASP principer och tillgängliggör öppen källkod för ändamålet erkända plattformar.

### Ansvarsfördelning

Då SCB erbjuder Open sourceprogramvaror ska det alltid finnas en dokumenterad granskning och beslut av som lägst IT-chef och IT-säkerhetsansvarig. Det ska bl.a. alltid ske en kodgranskning av källkoden innan det är godkänt att lämna ut källkoden (som sedan ska vara skriftligt beslutat). Utlämnandet sker enligt SCB:s process för granskning av källkod.

Det ska finnas en aktiv förvaltning av programvaran. Dessa ska förvaltas på samma sätt som övriga programvaror inom myndigheten.

Huruvida en programvara är relevant att tillgängliggöras som öppen källkod bereds inom det förvaltningsobjekt som programvaran tillhör. Beredningen stödjs av Arkitekturstyrningen som representeras av IT-, SÄK- samt process och metodområdet. Vid behov kan ytterligare beredning ske med hjälp av rättssekretariatet. Det formella beslutet tas därefter av ansvarig sektionschef IT för aktuellt förvaltningsobjekt. Dessa ska därtill omfattas av en ny bedömning minst en gång per år.

IT-avdelningens interna förvaltning ”Realisera IT-stöd” ansvarar för det IT-stöd som behövs för hantering av öppen källkod.

## Delade verktyg

SCB tillgängliggör PxWeb som öppen källkod för att skapa erfarenhet och bygga upp en kompetens kring öppen källkod.

Valet av PxWeb är gjort av flera anledningar. Bland annat använder ett flertal statistikansvariga myndigheter redan PxWeb för att sprida sin statistik. Desamma gäller för ett flertal andra statistikbyråer runt om i världen. PxWeb har redan en aktiv Community av användare som är redo att bidra. Inom ESS-projektet SERV har viss finansiering skapats för att vidareutveckla PxWeb förutsatt att det blir öppen källkod.

PxWeb tillgängliggörs under Apache License 2.0 på Github.

---

*Dnr: A2022/0573* 

[^1]: Läs hela OSD på https://opensource.org/docs/osd

[^2]: Läs mer om OSI på https://opensource.org/

[^3]: En komplett lista går att läsa på https://opensource.org/licenses

[^4]: https://ec.europa.eu/info/departments/informatics/open-source-software-strategy_en

[^5]: https://www.gov.uk/government/publications/open-source-guidance

[^6]: SSB:s projekt finns samlade på Github under deras organisation [https://github.com/statisticsnorway](https://github.com/statisticsnorway) och ONS på [https://github.com/ONSdigital](https://github.com/ONSdigital)