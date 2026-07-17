# 1fgl_Test_repo_readwrite
Teste mit den Tools/Klassen aus dem Projekt JAZxJgit 
- den Lese-/Schreibzugriff auf Github (commit, push, pull) 
  ... und damit einhergehend, ob SSH korrekt eingestellt ist,
  ... die Verwendung von HTTPS klappt etc.

- das automatisierte Erzeugen von Konflikten und das Auflösen der Konflikte
  ... Erzeuge dazu in den JUnit Tests folgende Struktur:
  
  testdata/
|
+-- remote.git/           (Bare Repository)
|
+-- workingcopy_A/
|
+-- workingcopy_B/


Remote
   ^
   |
+--+----------------+
|                   |
Clone A         Clone B


