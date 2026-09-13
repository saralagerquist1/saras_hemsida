# Sara's hemsida

En webbplats där jag berättar lite om mitt liv och mina intressen, samt ett sätt att kontakta mig.

## Tekniker
Projektet är byggt med:
* HTML

## Min publicerade versioner
* [GitHub Pages](https://saralagerquist1.github.io/saras_hemsida/) 
* [Netlify](https://sarahemsida.netlify.app/)

## Frågor
* Vad är skillnaden mellan git add och git commit?  
Skillnaden mellan git add och git commit är att git add lägger till en fil i staging area, medans git commit skapar en snapshot i historiken som beskriver ändringen/ändringarna som har gjorts.
* Varför använder man branches istället för att jobba direkt i main?  
Det är ett säkrare sätt att jobb som minskar chansen att komprimera den version (main) som fungerar korrekt. Det är ett sätt att kunna jobba parallellt i team, underlättar när fel uppstår, samt bidrar till ett tydligare, strukturerat arbete.
* Vad händer rent praktiskt när man gör en merge?  
När man gör en merge slår man ihop branches med main där deras historik och ändringar görs samman T.ex. en separat branch där man har gjort ändringar, för att sen slål ihop den med main när den fungerar korrekt.
* Vad är skillnaden mellan att pusha till GitHub och att publicera direkt på t.ex. Netlify?  
I GitHub lagrar man sina Git-repon på molnet och deras kod(alla filer, historik och ändringar i sjäva koden), på Netlify synliggörs webbplatsen endast.
* Om du vill exkludera någon fil i projektet från versionshanteringen, hur gör du då?  
Filen kan då läggas i en mapp vid namn .gitignore, där ignorerat Git den och undviker att versionshantera.