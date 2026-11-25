# Spiekbrief Git en GitHub

## 1. Clone, commit, push en pull

Met clone haal je een complete kopie van een repository van GitHub naar je eigen computer.  
Een commit is een soort momentopname: je bewaart je wijzigingen lokaal samen met een kort berichtje.  
Met push stuur je die commits vanaf je computer naar de repository op GitHub.  
Pull doet precies het tegenovergestelde: je haalt de nieuwste wijzigingen van GitHub op en voegt ze toe aan je lokale project.

## 2. Een goed commitbericht

Goed voorbeeld: "Spiekbrief: voeg uitleg over gitignore toe"
Slecht voorbeeld: "update"

Het goede voorbeeld is beter omdat het met "Spiekbrief: " begint en meteen duidelijk maakt wat er 
exact is veranderd, terwijl "update" veel te vaag is en later niet helpt om wijzigingen terug te 
vinden.

## 3. Gitignore

Een ".gitignore"-bestand zorgt ervoor dat Git opgegeven bestanden en patronen zoals tijdelijke 
systeem- of logbestanden negeert en niet meeneemt in je commits.

## 4. Pull

Ik heb een wijziging die rechtstreeks op GitHub was gemaakt met een pull binnengehaald naar mijn 
lokale computer. Je doet aan het begin van elke les altijd eerst een pull zodat je zeker weet dat 
je op de allerlaatste versie verder werkt en geen conflicten veroorzaakt.

## 5. Terugdraaien

De foute commit verdwijnt niet uit de geschiedenis omdat Git een onveranderlijk logboek bijhoudt
een revert maakt een nieuwe commit aan die de eerdere wijziging weer ongedaan maakt.
