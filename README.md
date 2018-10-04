# Fredrik Grape

--------------------------------------------------
Balansträning för äldre människor med Hololens AR
--------------------------------------------------
* Scenario 1: https://www.youtube.com/watch?v=Wj6sc34tSP4
* Scenario 2: https://www.youtube.com/watch?v=_CUvQ8QteYY

Notera att både bildkvalitén och antalet bilder per sekund tyvärr är betydligt sämre i inspelade videor med Hololensen.

Scenario 1
----------
Här är tanken att användaren ska träna på att flytta sin tyngdpunkt från sida till sida för att fånga bollar som kommer flygandes mot dem. Det är möjligt att ställa in svårighetsgrader och ändra mellan att bollarna kommer från en sida till en annan, till att de kommer mot en med en slumpad vinkel.

Scenario 2
----------
Här är tanken att användaren ska träna på att rotera huvudet för att följa en boll som svävar i luften. I båda scenarier är det möjligt att vända sig om och fortsätta spela och även att gå fram och tillbaka (spelet följer med användaren). Allt detta är i syfte att träna så många olika delar av balanssinnet som möjligt.

Kodutdrag
---------

BILDER PÅ KODEN

-------------------------------------------------------------------------------------------------------
GitSamling.zip filen innehåller fyra program jag har skrivit för olika kurser vid uppsala universitet.
-------------------------------------------------------------------------------------------------------

--------------------------
  1. Studsande Bollar
--------------------------

Ett javaprogram för att simulera bollar som studsar i en låda. Kör GoBounce.java för att få (den simpla) UIn där man kan ändra parametrar och köra programmet. 

-----------------------------
  2. Binär multiplikation
-----------------------------

Ett rekursivt program skrivet i Python för att beräkna produkten mellan två binära tal.

-------------------------
  3. Ring detektion
-------------------------

Ett program skrivet i Python för att kolla om en graf innehåller en ring. De två första metoderna (ring och ring_visit) returnerar enbart sant eller falskt beroende på om det existerar en ring eller inte. Metoderna ring_extended och ring_visit_extended returnerar även vilka noder som ingår i ringen.

-------------------------
  4. RPN miniräknare
-------------------------

En Reverse Polish Notation miniräknare skrivet i en MIPS assembly simulator (MARS). Miniräknaren hanterar plus, minus, gånger, delat med och roten ur. För att använda en RPN miniräknare, skriv först som input de tal du vill lägga på stacken, tex:

4
3
2
1

om ett plustecken nu anges som input kommer de två översta talen poppas från stacken (4 och 3) och adderas, och sedan läggas tillbaks på stacken som nu kommer se ut som sådan:

7
2
1

RPN miniräknare blev populära under en tid då datorminne var väldigt begränsat.
