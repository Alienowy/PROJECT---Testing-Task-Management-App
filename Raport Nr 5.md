

|**RAPORT TESTÓW EKSPLORACYJNYCH**|***Wersja dokumentu:*** Raport Nr 5|
| :- | :- |
|***Autor:*** Adrian Wąś|***Data i godzina rozpoczęcia testów:***<br>26.03.2022r. 12:30|
|||
|||
|**Przedmiot testów:** https://testujpl.gitlab.io/pomodoro-kanban-test/|
||
|***Środowisko testowe:*** <br>PC, Windows 10 Pro**<br>Google Chrome     Wersja 99.0.4844.51|
||
||
|**Czas trwania sesji:** 90 minut|
|***Czas przygotowania środowiska:*** <br>10 min|***Czas eksploracji:***<br>50 min|***Czas raportowania:***<br>30 min|
|***Cel eksploracji:*** Sprawdzenie poprawności naliczanych pomidorów.(Zakończone i odrzucone zadania)|
||
||
|***Procent realizacji celu:*** 100%|
|***Obszary poddane eksploracji:*** Strona główna aplikacji |
|<p>**Znalezione defekty podczas eksploracji:<br><br>D5.1 - Złe naliczanie pomidorów.<br><br>Priorytet:** Średni<br><br>**Warunki wstępne:**<br>1. W kolumnie InProgress posiadamy zadanie ustawione na 15s<br><br>**Kroki reprodukcji:**<br>1. Klikamy Start pod zegarem w celu odmierzania zadania**<br>1. Przenosimy niezakończone zadanie z kolumny InProgress do kolumny ToDo<br><br>**Efekt oczekiwany:** Przerywa odliczanie zadania i pomidor nie zostaje naliczony do puli pomidorów zebranych <br>**Efekt rzeczywisty:** Zegar dalej odlicza oraz po zakończeniu odliczania dodaje pomidora do puli zadań zakończonych.<br><br>**Załączniki:<br><https://drive.google.com/file/d/107Gfe9LNhkWHnFgVIr5bCaqEtZycdFXu/view?usp=sharing>**</p><p></p><p></p><p><br>**D5.2 -  Pomidory naliczane bez zadań w kolumnie InProgress<br><br>Priorytet:** Średni<br><br>**Warunki wstępne:**<br>1. Czas zadania ustawiony na 15s<br>2. Pusta kolumna InProgress<br><br>**Kroki reprodukcji:**<br>1. Startujemy odmierzanie czasu zegara<br>2. Czekamy na zakończenie odmierzania czasu<br><br>**Efekt oczekiwany:** Zegar kończy odmierzać czas i pomidor nie zostaje dodany do puli zadań zakończonych<br>**Efekt rzeczywisty:** Zegar kończy odmierzać czas i dodaje pomidora do puli zadań zakończonych<br><br>**Załączniki:**<br><https://drive.google.com/file/d/1s1BLzyn8IgtUFV-maBUuxJ-2FKeXK3Yu/view?usp=sharing></p>|
||
||
||
||
|***Dodatkowe informacje:*** Brak***<br><br>|
|<p>**Użyte programy:** </p><p>Screenpresso (przechwytywanie ekranu)</p>|


