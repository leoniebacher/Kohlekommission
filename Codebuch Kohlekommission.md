**Codebuch der Kohlekommission**


**EDGE-List**

id (eindeutige Codierung der Knoten)
Codiert mit Namen der Person/Organisation/Verband/Partei

from = id des Knoten
ID Mitglied der Kommission

to = id des Knoten
Alle Mitgliedschaften der Person (bspw. politische Partei)


**NODE-List**

**id**
Identische ID aus der Edgelist um die Knoten zu identifizieren

**name**
Die vollständig ausformulierten Namen der Knoten

**type**

0=Keine Angabe, wegen Organisation
2=Person


**sex **

0=Keine Angabe, wegen Organisation
4=female
5=male


**age**

0=Keine Angabe, wegen Organisation
4=bis 40 Jahre
5=41 bis 50 Jahre
6=51 bis 60 Jahre
7=61 Jahre und älter


**representation** (Funktion innerhalb der Kommission)

0=Keine Angabe, wegen Organisation
4=Gewerkschaft
5=Wirtschaft
6=Politik
7=Umwelt
8=Wissenschaft
9=Regionen


**party**

0=keine Partei
4=CSU
5=Tierschutz
6=FDP
7=Grünen
8=SPD
9=CDU


**position**

0=Keine Angabe, wegen Organisation
3=kein Stimmrecht
4=Mitglied
5=Vorsitz


**state** (Bundesland)

0=Keine Angabe, wegen Organisation
4=Berlin
5=Brandenburg
6=Bayern
7=Baden-Württemberg
8=Hessen
9=Hamburg
10=Nordrhein-Westfalen
11=Niedersachsen
12=Sachsen
13=Schleswig-Holstein
