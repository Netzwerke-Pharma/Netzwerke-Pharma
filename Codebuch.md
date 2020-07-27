Codebuch Stand 2020-07-12
erstellt von Jasmin Maya, Nora Schwarz, Verena Nagel, Julian Hammerstein, Samuel Müller, Janina Hofmann
(jm133@hdm-stuttgart.de, ns136@hdm-stuttgart.de, vn009@hdm-stuttgart.de, jh229@hdm-stuttgart.de, sm222@hdm-stuttgart.de, jh231@hdm-stuttgart.de)

Inhalt

    Edges.csv (Edgelist)
    Nodes.csv (Nodelist)
    Codebuch.rm (Codierung der Datensätze)

Ursprung und Datenerhebung

Im Interesse der Forschung stehen die vergangenen und aktuellen Nebentätigkeiten und Berufe der Mitglieder des Bundesgesundheitsministeriums. Hierbei soll herausgefunden werden, ob die jeweiligen Nebentätigkeiten ebenfalls in der Gesundheits- oder gar Pharmabranche angesiedelt sind.

Durch Mitgliedschaften in bestimmten Institutionen, Organisationen, Ausschüssen oder Vereinen können reziproke Verbindungen entstehen, weshalb es sich um ein ungerichtetes Netzwerk handelt. Anhand der Dauer der Nebentätigkeit könnte die Gewichtung der Kanten ebenfalls miteinbezogen werden. Untersucht werden die letzten vier Legislaturperioden (16.-19. Wahlperiode, 2005-2021).

Die Daten werden über Transparency International Deutschland e.V., correctiv.org, Bundestag.de und Abgeordnetenwatch erhoben.

Das Netzwerk ist ein ungerichtetes two-mode Netzwerk. Untersucht wird generell ein Gesamtnetzwerk. 


EDGE-Attribute

id
(jede ID entspricht einer Institution oder einem Mitglied des Gesundheitsministeriums)

relation 
(Art der Beziehung zu einer Institution)
1 = Hauptamt
2 = Nebenamt
3 = Ehrenamt
4 = Mitgliedschaften
5 = einmalige entgeldliche Tätigkeiten
6 = Sonstiges

duration
(Dauer der Tätigkeit)
1 = 0-3 Jahre
2 = 3-6 Jahre
3 = 6-9 Jahre
4 = 9-12 Jahre
5 = 12-15 Jahre
6 = mehr als 15 Jahre

status 
(aktiv)
1 = Ja
2 = Nein

health
(Tätigkeit im Gesundheitssektor)
1 = Ja
2 = Nein

NODE-Attribute

id
(identische ID wie aus der Edgelist zur Identifikation der Knoten)

label
(vollständige Bezeichnung der Knoten)

sex
(Geschlecht)
1 = weiblich
2 = männlich
3 = divers

type
(Person oder Institution)
1 = Person
2 = Unternehmen
3 = Verein/Organisation
4 = politische Institution
5 = Stiftung

period
(Wahlperiode)
1 = 2005-2009
2 = 2009-2013
3 = 2013-2017
4 = 2017-2021

age
(Alter der Mitglieder)
1 = 20-30 Jahre
2 = 30-40 Jahre
3 = 40-50 Jahre
4 = 50-60 Jahre
5 = 60-70 Jahre
6 = 70-80 Jahre
7 = 80-90 Jahre
8 = tot

education
(höchster Bildungsabschluss)
1 = Hauptschulabschluss
2 = Mittlere Reife
3 = Fachhochschulreife
4 = Abitur
5 = Berufsausbildung
6 = Bachelor
7 = Master
8 = Staatsexamen
9 = Promotion

background
(Tätigkeiten im Gesundheitssektor)
1 = Ja
2 = Nein

party
(Fraktionszugehörigkeit der Mitglieder)
1 = CDU/CSU
2 = SPD
3 = DIE LINKE
4 = DIE GRÜNEN
5 = FDP

state
(Verortung nach Bundesländern)
1 = Baden-Württemberg
2 = Bayern
3 = Berlin
4 = Brandenburg
5 = Bremen
6 = Hamburg
7 = Hessen
8 = Mecklenburg-Vorpommern
9 = Niedersachsen
10 = Nordrhein-Westfahlen 
11 = Rheinland-Pfalz
12 = Saarland 
13 = Sachsen
14 = Sachsen-Anhalt
15 = Schleswig-Holstein
16 = Thüringen

function
(Funktion im Bundesgesundheitsministerium)
1 = Bundesgesundheitsminister
2 = Staatssekretär
3 = Drogenbeauftragte
4 = Sonstige

health sector
(Institution im Gesundheitssektor)
1 = Ja
2 = Nein
