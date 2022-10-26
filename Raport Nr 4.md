

|**RAPORT TESTÓW EKSPLORACYJNYCH**|***Wersja dokumentu:*** Raport Nr 4|
| :- | :- |
|***Autor:*** Adrian Wąś|***Data i godzina rozpoczęcia testów:***<br>26.03.2022r. 10:30|
|||
|||
|**Przedmiot testów:** https://testujpl.gitlab.io/pomodoro-kanban-test/|
||
|***Środowisko testowe:*** <br>PC, Windows 10 Pro**<br>Google Chrome     Wersja 99.0.4844.51|
||
||
|**Czas trwania sesji:** 90 minut|
|***Czas przygotowania środowiska:*** <br>10 min|***Czas eksploracji:***<br>50 min|***Czas raportowania:***<br>30 min|
|***Cel eksploracji:*** Sprawdzenie** migracji zadań między kolumnami i okienek pop-up.|
||
||
|***Procent realizacji celu:*** 100%|
|***Obszary poddane eksploracji:*** Strona główna aplikacji |
|<p>**Znalezione defekty podczas eksploracji:***<br></p><p>**D4.1 - Źle działające okienko pop-up po zatrzymaniu zadania<br><br>Priorytet:** Wysoki<br><br>**Warunki wstępne:**<br>1. Czas zadania ustawiony na 40 min<br><br>**Kroki reprodukcji:**<br><br>1. Klikamy Start pod zegarem w celu rozpoczęcia odliczania czasu zadania<br>2. Czekamy 10s i klikamy Stop pod zegarem w celu zatrzymania odliczania czasu zegara<br>3. Wyskakuje okienko pop-up z potwierdzeniem swojej decyzji<br>4. Klikamy Nope<br><br>**Efekt oczekiwany:** Okienko pop-up znika, a zegar dalej odmierza czas zadania <br>**Efekt rzeczywisty:** Okienko pop-up znika, a zegar zostaje zresetowany<br><br>**Załączniki:<br><https://drive.google.com/file/d/1ac50m5KuACbhIoWtcQHbecXEu1u8WQ4V/view?usp=sharing>**</p><p></p><p></p><p>*<br>**D4.2 - Ponowne odliczanie zakończonych zadań<br><br>Priorytet:** Średni<br><br>**Warunki wstępne:**<br>1. W kolumnie Done posiadamy minimum 1 zakończone zadanie<br><br>**Kroki reprodukcji:**<br><br>1. Za pomocą kursora przesuwamy zakończone zadanie z kolumny Done do kolumny InProgress.<br><br>**Efekt oczekiwany:** Nie można zakończonego zadania przesunąć z kolumny Done do kolumny InProgress. <br>**Efekt rzeczywisty:** Zakończone zadanie można przesunąć do kolumny InProgress co spowoduje ponowne odliczanie zadania.<br><br>**Załączniki:<br><https://drive.google.com/file/d/1vQuKRbR5rG__lbK66tKN778mxqckHvu6/view?usp=sharing>**</p><p></p><p></p><p><br>**D4.3 - Przenoszenie trwającego zadania do kolumny Done<br><br>Priorytet:** Średni<br><br>**Warunki wstępne:**<br>1. W kolumnie Inprogress posiadamy zadanie w trakcie odliczania.<br><br>**Kroki reprodukcji:**<br><br>1. Za pomocą kursora przesuwamy odliczane zadanie z kolumny InProgress do kolumny Done.<br><br>**Efekt oczekiwany:** Nie można przenieść trwającego zadania z kolumny InProgress do kolumny Done <br>**Efekt rzeczywisty:** Zadanie aktualnie odliczane można niezakończone przenieść do kolumny Done.<br><br>**Załączniki:<br><https://drive.google.com/file/d/14WAyrn0UXMyMMsI7rI38allNbkxoJ6oU/view?usp=sharing>**</p><p></p>|
||
||
||
||
|***Dodatkowe informacje:*<br><br>Sugestia:** <br>1. W momencie gdy przesuwamy zakończone zadanie z kolumny Done do kolumny InProgress mogłaby wyskakiwać informacja, że zadanie już jest wykonane lub pytanie, czy chcemy zadanie wykonać ponownie.<br>2. W momencie gdy przesuwamy odliczane już zadanie z kolumny InProgress do kolumny ToDo mogłoby wyskakiwać<br>pytanie czy chcemy przerwać aktualne zadanie.<br>3. W momencie gdy zakończy odliczać zadanie w kolumnie InProgress fajnie byłoby gdyby wyskoczyła informacja czy zadanie zostało zakończone i można je przesunąć do kolumny Done.|
|<p>**Użyte programy:** </p><p>Screenpresso (przechwytywanie ekranu)</p>|



