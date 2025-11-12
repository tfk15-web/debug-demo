1. Board giver altid horisontale skibe grundet fejl i input til getRandomInteger i funktionen calculateEndPoint. getRandomInteger skal have input 2 for at returnere 0 eller 1.

2. Ved 3 hit skal resultatet være skib sunket men grundet fejl i funktionen isSunk bliver det aldrig tilfældet. isSunk returnerer true kun når antallet af hit er større end 3. Funktionen rettet til at returnere true ved større eller lig 3.

3. java.lang.ArrayIndexOutOfBoundsException opstår når koden i programmet prøver at tilfå en indeks i array som ikke findes. I dette tilfælde index 10 som er det 11. element i board som består af 10x10 elementer. Fejl løses ved at sikre vi altid tilgår elementer der findes inden for bord størrelsen.


Anvendte teknikker:
Breakpoints til at standse programmet og gennemgå koden linje for linje.
Step Into / Step Over til at følge programflowet og se, hvordan metoder blev kaldt.
Variabelinspektion til at kontrollere værdier som koordinater og tilstande under kørsel.
Evaluate Expression til at teste logiske udtryk direkte under debugging.
Konsollens stack trace til at finde årsagen til exceptions.