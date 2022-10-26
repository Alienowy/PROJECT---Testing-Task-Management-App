

|**RAPORT TESTÓW EKSPLORACYJNYCH**|***Wersja dokumentu:*** Raport Nr 3|
| :- | :- |
|***Autor:*** Adrian Wąś|***Data i godzina rozpoczęcia testów:***<br>24.03.2022r. 17:30|
|||
|||
|**Przedmiot testów:** https://testujpl.gitlab.io/pomodoro-kanban-test/|
||
|***Środowisko testowe:*** <br>PC, Windows 10 Pro**<br>Google Chrome     Wersja 99.0.4844.51|
||
||
|**Czas trwania sesji:** 90 minut|
|***Czas przygotowania środowiska:*** <br>10 min|***Czas eksploracji:***<br>50 min|***Czas raportowania:***<br>30 min|
|***Cel eksploracji:*** Sprawdzenie panelu ustawień oraz poprawności działania opcji ustawień. |
||
||
|***Procent realizacji celu:*** 70%|
|***Obszary poddane eksploracji:*** Strona główna aplikacji, Okno panelu ustawień|
|<p>**Znalezione defekty podczas eksploracji:<br><br>D3.1 - Źle wyświetlany zakres czasu na suwaku “Pomodoro time”<br><br>Priorytet:** Średni<br><br>**Warunki wstępne:**<br>1. Otwarte okno panelu ustawień<br>2. Zakładka Timer<br><br>**Kroki reprodukcji:**<br>1. Kursorem myszy łapiemy suwak Pomodoro time<br>2. Przesuwamy suwak i ustawiamy maksymalny czas zadania<br><br>**Efekt oczekiwany:** Maksymalny czas zadania jaki można ustawić wynosi 59 minut <br>**Efekt rzeczywisty:** Na suwaku można ustawić czas większy niż 59 minut <br><br>**Załączniki:<br><https://drive.google.com/file/d/1H7qhar0VCXzSvoRV_XFqyKXjICEpYIwE/view?usp=sharing>**</p><p></p><p></p><p><br>**D3.2 -  Źle wyświetlana wartość na suwaku “Pomodoro time”<br><br>Priorytet:** Średni<br><br>**Warunki wstępne:**<br>1. Otwarte okno panelu ustawień<br>2. Zakładka Timer<br><br>**Kroki reprodukcji:**<br>1. Kursorem myszy łapiemy suwak Pomodoro time<br>2. Przesuwamy guzik i na suwaku ustawiamy czas zadania 60:15<br><br>**Efekt oczekiwany:** Wartość pomodoro time wyświetla 60:15<br>**Efekt rzeczywisty:** Wartość pomodoro time wyświetla 00:15<br><br>**Załączniki:**<br><https://drive.google.com/file/d/14lC7fWyppxoABkKHhHJhNVl30_vdd8dG/view?usp=sharing></p><p></p><p></p><p><br>**D3.3 -  Zegar źle wyświetla odmierzany czas zadania<br><br>Priorytet:** Średni<br><br>**Warunki wstępne:**<br>1. W panelu ustawień w zakładce Timer czas zadania ustawiony na maksymalną wartość tj. 60:15 (Wyświetlane 00:15)<br><br>**Kroki reprodukcji:**<br>1. Na stronie głównej klikamy kursorem myszy na Start i odpalamy odmierzanie czasu zegara<br><br>**Efekt oczekiwany:** Zegar zaczyna odliczać od 60:15<br>**Efekt rzeczywisty:** Zegar zaczyna odliczać od 00:15<br><br>**Załączniki:**<br><https://drive.google.com/file/d/1sVIEVbmfYxGWEJLxqP709A2e6OK5H5Zl/view?usp=sharing></p><p></p>|
||
||
||
||
|<p>***Dodatkowe informacje:<br><br>Uwagi:***<br>1. Nie przetestowano wszystkich opcji w panelu ustawień w zakładce Notifications. Sprawdzono dźwięki powiadomień, ale nie wiadomo czy opcje powiadomień działają prawidłowo.***<br>2. Maksymalny czas zadania. który można ustawić na suwaku pokazuje zakres od 00:15s do 00:15s, przy czym rzeczywisty maksymalny czas to 60:15s<br>3. Brak możliwości ustawienia po jakim czasie lub po którym zadaniu rozpoczyna długą przerwę.</p><p><br>***Sugestia:***<br>1. Brak możliwości edycji czasowej pojedynczego zadania. Fajnie gdyby można było edytować czas wybranego zadania. W tej chwili czas zadania jaki ustawimy odnosi się do wszystkich zadań.</p>|
|<p>**Użyte programy:** </p><p>Screenpresso (przechwytywanie ekranu)</p>|


