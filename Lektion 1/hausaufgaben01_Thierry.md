# Hausaufgaben 01, Lektion 1

## Commandline-Übungen

0. Kopiere dieses File und speichere es im Folder mit Deinem Namen ab.
Öffne dieses File nun mit dem Programm Atom.

1. Öffne Deine Commandline und navigiere zum Desktop.

Eingabe: cd Desktop

2. Von der Commandline, kreiere einen Order namens "Google Government Removal Requests".

Eingabe: mkdir "Google Government Removal Requests"

3. Navigiere in diesen Ordner.

Eingabe: cd Google\ Government\ Removal\ Requests

4. Speichere [dieses Zip-File](https://storage.googleapis.com/transparencyreport/google-government-removals.zip) in den Ordner von der Commandline mit Wget ab. Vielleicht musst Du dafür zuerst Wget auf
der Commandline installieren. Wenn Du nicht mehr weisst wie, google!

Eingabe: wget https://storage.googleapis.com/transparencyreport/google-government-removals.zip

5. Zeige den Inhalt des Ordners an.

Eingabe: ls

6. Entpacke das File.

Eingabe: tar xvf google-government-removals.zip

7. Navigiere in den neuen Folder.

Eingabe: cd google-government-removals

8. Zeige die ersten 10 Zeilen an.

Eingabe: head -n 10 google-government-detailed-removal-requests.csv

9. Zeige die letzten 50 Zeilen an.

Eingabe: tail -n 10 google-government-detailed-removal-requests.csv

10. Zeige nur Einträge der Schweiz an.

Eingabe: grep Switzerland google-government-detailed-removal-requests.csv

11. Zeige nur Einträge, die die "National Security" betreffen.

Eingabe: _______

12. Zeige nur Einträge, die die "Schweiz" UND "National Security" betreffen.

Eingabe: grep "National Security" google-government-detailed-removal-requests.csv

13. Zeige nur Einträge, die die "Schweiz" UND "National Security" betreffen.

Eingabe: grep -E "National Security" google-government-detailed-removal-requests.csv | grep -E "Switzerland"
[Mehr hier](http://www.thegeekstuff.com/2011/10/grep-or-and-not-operators).

14. Navigiere zurück auf Deinen Desktop.

Eingabe: cd /Users/tseiler/Desktop 

##### EXTRA-ÜBUNG
15. Lade nun die gesamte Pnos-Seite auf Deinen Computer mit dem Programm Wget.
Achte darauf, dass es wirklich die ganze Seite ist. Wenn Du nicht weisst wie,
google!

Eingabe: wget --recursive http://wwww.pnos.ch

## Lektüre

Wer mehr dazu lesen will. [Data Science from the Commandline](http://www.ruxizhang.com/uploads/4/4/0/2/44023465/janssens2014.pdf)

## Github-Übungen

16. Erkunde Python-Trending Repos auf Github

Eingabe: _______

17. Forke eine beliebige Python Repo

Eingabe: Auf Github.

18. Clone sie auf Deinem Desktop

Eingabe: _______

19. Checke eine Branch aus, auf der obersten Ebene des Ordners 'Pythonrecherche':

Eingabe: _______

Eingabe: _______

Eingabe: _______

Eingabe: _______

20. Nun auf der Github-Website einen so genannten Pull-Request kreieren, und
darauf warten, dass der Verwalter der Orginial-Repo die Änderungen absegnet
und merged und update Deine Repo, damit es ganz sicher auf dem neuesten Stand
ist.

Eingabe: _______

Gratuliere, Du hast die ersten Hausgaben erledigt!
