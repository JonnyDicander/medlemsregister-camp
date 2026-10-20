## Ett problem vi löste

Jag fick ett problem när jag skulle slå ihop ändringarna på GitHub. Det berodde på att samma rad med välkomsttexten i filen
src/Main.java hade ändrats i två olika grenar. Git kunde därför inte avgöra vilken version som skulle användas.
Jag öppnade filen i IntelliJ och kollade vad som skiljde de två versionerna åt.
Sedan valde jag vilken text som skulle vara kvar och tog bort konfliktmarkeringarna.
Efter det testade jag koden med javac för att kontrollera att inga fel fanns kvar.
När allt fungerade använde jag git add och git commit för att spara ändringarna och till sist git push för att ladda upp dem till GitHub.