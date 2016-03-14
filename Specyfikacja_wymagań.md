#Projekt na język skryptowy w Pythonie
###Dziennik rowerzysty
###Tobiasz Dobrowolski
####1. Wstęp
Podstawowym celem aplikacji jest zapisywanie, przetrzymywanie, obliczanie oraz wyświetlanie danych powiązanych z jazdą na rowerze. Program składa się z 4 odzielnych sekcji do których dostać się można przez górne menu. Kliknięcie w interesujący użytkownika tytuł sekcji przenosi go na odpowiednią stronę.

Aktualności - Sekcja domyślna - 
Strona aktualności jest miejscem w którym pojawia się użytkownik przy uruchomieniu aplikacji. Składa się z 3 kart, dwóch małych i jednej większej.

- Karta "Witaj!" - Przedstawia wybrany cel oraz jego postęp wraz z ikoną.
- Karta "Porady" - Wyświetla jedną, losową poradę z 20.
- Karta "Ostatni trening" - Pokazuje dane ostatniego treningu.

![GitHub Logo](/images/interface1c.png)

Mój dziennik - 
Miejsce w którym użytkownik może przeglądać i dodawać treningi. Może on również podglądnać swoje postępy.

- Karta "Moje treningi" - Lista zapisanych treningów, po kliknięciu w wybraną aktywność pojawi się okno ze szczegółami na jego temat. W dolnym, prawym rogu karty widnieje przycisk FAB (Floating Action Button), który umożliwia dodanie nowego treningu. Po jego wciśnięciu pojawi się okno z pustymi polami do uzupełnienia.
- Karta "Postęp" - Wykaz danych pokazujących postęp użytkownika do osiągnięcia wybranego celu. Pod kartą widnieje pasek postępu z tekstem informującym użytkownika czy jest na dobrej drodze do wykonania celu. Program przewiduje czy tempo osiagania kolejnych postępów jest odpowiednie.

Moje dane - 
Sekcja wyświetlająca wszystkie dane jakie użytkownik wpisał oraz dodatkowe dane które program oblicza.

- Karta "Wpisane dane" - Dane wpisane przez użytkownika w sekcji Ustawienia
- Karta "Obliczone dane" - Dane obliczone przez program na podstawie wpisanych danych. Użytkownik może tu zaspokoić swoją ciekawość i dowiedzieć się jak pracował do tej pory.

Ustawienia - 
Sekcja umożliwiająca wpisanie danych użytkownika oraz wyzerowanie wszystkich wpisanych i obliczonych danych.

- Karta "Moje dane" - Umożliwia wpisanie danych lub ich poprawę. Można wpisać tylko jedną wartość w wybranym miejscu a tylko ona zostanie zmieniona. Można również usunąć wszystkie dane przyciskiem "Wyzeruj dane".
- Dodatkowa karta - Informacje na temat programu i jego autora. Karta pokazuje również logo programu.

Program umożliwia wybranie jednego z 3 celów. Jego wybór ma wpływ na wymagania jakie stawiać nam będzie program.

Dostępne cele:
- Popraw sylwetkę
- Popraw kondycję
- Popraw samopoczucie

####2. Opis programu
Interfejs systemu jest utrzymany w zmodyfikowanym stylu Google Material Design. Styl różni się od wytycznych Google brakiem cieni oraz brakiem zaokrąglonych rogów kart. Przewodnim kolorem interfejsu jest niebieski. Zastosowanie stylu Material wpływa pozytywnie na czytelność programu oraz daje możliwość łatwego przeportowania systemu na tablety z systemem Android. Biblioteka użyta do stworzenia interfejsu to Tkinter. Program działa w rozdzielczości 800x600 w okienku. Zapobiega to "rozjeżdżaniu się" interfejsu. Dane użytkownika przetrzymywane są w bazie danych. Program pobiera z niej potrzebne wartości do obliczania kolejnych oraz zapisuje tam te, które już przetworzył. Nie istnieją żadne ograniczenia nałożone na grupę docelową aplikacji, z programu może korzystać każdy. UI/UX zostało zaprojektowane tak aby każdy mógł w szybki i przystępny sposób dotrzeć do interesujących go danych.
