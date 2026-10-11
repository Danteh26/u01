# u01

Länk till sidan: https://magnificent-rabanadas-fe3d37.netlify.app/


Jag började att överväga om jag skulle skriva all html i en fil eller om jag skulle göra en html fil för varje sida. Jag valde att göra flera html filar eftersom jag tyckte det skulle vara mer organiserat i både html och CSS filarna. Sedan översatte jag all html skruktur i skissen till kod. Efter började jag med CSS:en för varsin sida. Eftersom html strukturen påverkar hur enkelt det är att skapa layouten med CSS behövde jag ibland ändra strukturen för att få layouten att fungera som jag ville. Ett exempel är att placera nav i en egen div i body, så att den kunde samverka med grid-template-areas i base CSS och på så sätt fungera korrekt i desktopversionen. Det svåraste var nog att få till projekt korten, det var en rätt mycket html och så blev det en del strul med att få till projekt bilderna. En annan sak var alla gradients och color mixes, dem fick mig alltid att tänka på vilket sätt färgerna skapades.

Jag använde header för sidhuvudet, nav för länkarna till sidorna, main till huvuddelen och footer för sidfoten. Inuti main använde jag section för att dela upp innehållet i större delar och article för självständiga delar, till exempel projektkorten. Jag använde även div där jag inte hittade något mer passande semantiskt element, exempelvis för att gruppera innehåll i projektkorten på about och projects sidorna. Dessa grupper behövdes främst för att kunna styra layouten med CSS. Jag använder h1 i headern, medans h2 finns under section och h3 under article om de finns, där rubriknivåerna vissar hur innehållet är uppdelat.


Jag använde Flexbox på många ställen eftersom jag tyckte att det var enklare att arbeta med när jag ville placera och fördela element i rader eller kolumner, exempelvis för nav länkarna eller texter som använder space-between. Jag använde Grid när jag behövde mer kontroll över större delar av layouten, exempelvis för att strukturera projektlistan i desktopversionen och för att placera huvudinnehållet på about sidan något längre åt vänster genom att exkludera den högra delen av main area. Jag lade brytpunkten för desktop versionen vid 1200px eftersom i skissen så är innehållet 1200px brett.


För att göra webbplatsen mer tillgänglig har jag gjort den responsiv så att den fungerar på både mobil och desktop. Jag har även kontrollerat att det går att navigera mellan länkarna med tangentbordet. Dessutom har jag testat textfärgernas kontrast mot WCAG AA riktlinjer och kontrollerat att sidan fungerar i Firefox. Jag har också sett till att sidan fungerar i dark mode.

Jag tycker att allt blev helt okej, Om jag hade mer tid skulle jag kunna ha gjort en fungerande hamburgar meny och testa webbplatsens tillgänglighet mer noggrant. Annars skulle jag gör sidan responsiv för flera storlekar som ipad.


Jag har använt ChatGPT som stöd under arbetet med webbplatsen, framför allt när jag har behövt lära mig hur man gör något i CSS, till exempel hur man skapade gradientfärger i text. Dessutom har jag använt det för att få hjälp med att lösa problem när koden inte fungerat som jag tänkt.
