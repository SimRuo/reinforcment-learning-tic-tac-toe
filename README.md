Projektet är fokuserat på att träna en AI att spela Tic-Tac-Toe med hjälp av reinforcment learning. Jag använde mig av:

- **Policy Gradient Learning**  
- **Q-learning**

Projektet börjar med en fördefinierad "perfekt policy" och en slumpmässig policy, och förbättrar sedan iterativt en tränad policy genom självspel. Policy gradient metoden använder sig enkelt av positiva 'rewards' för vinster, ingenting för oavgjort och 'straff' för förluster.

Q-learning anväder sig av en exploration- och exploitation strategi för att ytterligare optimera beslutsfattandet.

## Mätning av prestanda
Projektet spårar vinstfrekvenser mot både en slumpmässig och en perfekt policy för att utvärdera AI:ns prestanda.

## Slutmål
Det slutliga målet är att utveckla en AI som kan spela Tic-Tac-Toe effektivt genom att lära sig från tidigare spel och exportera dessa policier i JSON format. Dessa kommer jag använda för att implementera i en react app.

main.ipynb lägger jag i gitignore tillsvidare då en del av koden kan användas till en kurs som inte alla deltagare har klarat än. Uppdaterar när alla examinationstillfällen är klara
