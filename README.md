# Hoe te downloaden
**WINDOWS ONLY**

stap 1: 

open CMD en git clone de repo

stap 2:

unzip de file 

stap 3:

Download ffmpeg en sleep ffmpeg.exe in de unzip file

Stap 4:

Start de .bat file.

Stap 5: 

selecteer de video en laat het werk doen


De "herstelde" video stopt vaak eerder dan het origineel, omdat het corrupte deel (dat ffmpeg niet goed kan lezen) gewoon wordt genegeerd of verwijderd.

Waarom gebeurt dit?
De corruptie overschrijft een stukje data ergens halverwege de video.

Ffmpeg kan dan vaak alleen de stream correct decoderen tot het punt van corruptie.

De rest van de data na het corrupte stuk wordt vaak genegeerd of als onbruikbaar gezien.

Daarom wordt de video effectief ingekort.

Kan je dat vermijden?
Niet echt, want het beschadigde deel is écht kapot.

Je kunt proberen met ingewikkeldere reparatools, maar meestal geldt dat beschadigde frames/data verloren gaan.

De beste “herstel” is dus een video die speelt zonder fouten, maar dan wel korter.

Wat kan je doen?
Accepteer dat de video korter wordt.

Misschien het beschadigde deel handmatig knippen als dat te kort is.

Probeer verschillende ffmpeg opties, maar meestal helpt dit niet om de hele lengte te behouden.
