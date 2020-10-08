| Befehl | Beispiel  | Erklärung |
| --- | --- | --- |
| SELECT [Distinct] (Ort)| Select [Tabelle.]Spalte  | Gibt den Inhalt der Spalte(n) zurück |
| FROM (Ort) | FROM Tabellenname | Gibt an mit welcher Tabelle gearbeitet wird |
| WHERE (Bedingung) | WHERE Attribut1 (Operator) Attribut2 | Falls Bedingung der Abfrage |
| GROUP BY | GROUP BY Attribut | Gruppierung/Kategorisierung der Tabelle nach Attribut |
| ORDER BY (Attribut) [ASC/DESC] | ORDER BY Attribut (ASC) | Sortierung der Tabelle nach Angegeben Attribut (Standard:ASC) |
| [LEFT/RIGHT/INNER] JOIN | FROM Tabelle1 [LEFT/RIGHT/INNER] JOIN Tabelle2 ON Attribut1 = Attribut2 | https://i.stack.imgur.com/VQ5XP.png |
| UNION | --- | --- |
| AS | --- | --- |
| NULL | NULL | NULL |
| <> | Attribut1 <> Attribut2 | Ungleich Operator |
| LIKE | LIKE "*Name*" | Vergleich; * kann durch beliebig viele Zeichen ersetzt werden; ? durch **ein** beliebiges Zeichen; # durch **eine** beliebige Zahl |
| IN | Attribut IN ("Daniel", "Jannik", "Magnus") | Ob Attribut in Liste/Innerer Abfrage enthalten ist |
| IS NULL | Attribut IS NULL | Prüft ob das Attribut NULL ist |
| AND/OR | Attribut (AND/OR) Attribut2 | AND oder OR Verknüpfung |
| NOT | NOT (Boolscher Wert) | Nicht  |
| COUNT | COUNT(Attribut1) [... GROUP BY Attribut2] | Zählen der Elemente [in der Gruppe] |
| SUM | SUM(Attribut1) [... GROUP BY Attribut2] | Addieren der Elemente [in der Gruppe] |
| MAX | MAX(Attribut1) [... GROUP BY Attribut2] | Maximum der Elemente [in der Gruppe] |
| MIN | MIN(Attribut1) [... GROUP BY Attribut2] | Minimum der Elemente [in der Gruppe] |
| AVG | AVG(Attribut1) [... GROUP BY Attribut2] | Arithmetisches Mittel der Elemente [in der Gruppe] |

