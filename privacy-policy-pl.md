---
title: Polityka prywatności
lang: pl
---

**Spell Helper: Caster Companion** („aplikacja”), Fall In Studio. Obowiązuje od 19 listopada 2026.

## W skrócie

Dopóki nie korzystasz z drużyny online, aplikacja nie zbiera danych osobowych: wszystko, co wpisujesz, zostaje na Twoim urządzeniu, a aplikacja niczego nie wysyła ani nam, ani nikomu innemu. Aplikacja nie ma reklam, analityki ani raportowania awarii. Nigdy nie pyta o imię i nazwisko ani o e-mail i nie potrzebujesz konta.

Drużyna online to jedyna funkcja, która korzysta z naszego serwera: łączy telefony jednej drużyny przy stole. Serwer przechowuje wtedy tylko to, czego drużyna potrzebuje do działania, opisane niżej, na naszych własnych serwerach w Polsce, w UE.

## Co jest zapisywane i gdzie

Postacie z ich czarami, slotami i zasobami, dziennik, ustawienia i zaimportowane paczki są w pamięci aplikacji na Twoim urządzeniu. Tam może je odczytać tylko aplikacja. Drużyna online tego nie zmienia: karty Twoich postaci zostają na telefonie, a serwer nigdy ich nie czyta.

## Drużyna online

Ta część opisuje funkcję drużyny online w całości. Niektóre jej elementy (portrety w drużynie, wspólna kolejka inicjatywy, ukryte wpisy, kto jest przy stole, przyciski w Ustawieniach) dojdą w kolejnych wersjach aplikacji; to, co tu napisane, dotyczy ich od dnia, w którym się pojawią.

### Co przechowuje nasz serwer

- **Klucz drużyny Twojego telefonu.** Gdy pierwszy raz zakładasz drużynę albo do niej dołączasz, serwer daje aplikacji losowy numer Twojego telefonu i losowy sekret. Sekret zostaje na telefonie. Serwer przechowuje tylko jego skrót (hash), z którego nie da się odtworzyć sekretu, oraz kiedy klucz powstał i kiedy był ostatnio użyty.
- **Drużyny, w których jesteś.** Dla każdej drużyny: jej nazwa, którą wybiera gospodarz, i kto w niej jest: czy każdy członek jest gospodarzem, czy gościem, graczem, czy mistrzem gry, i kiedy dołączył.
- **Twoje postacie w drużynie, tak jak widzą je inni:** imię każdej postaci i, jeśli go jej nadałeś, jej portret. Nic więcej z postaci: ani karta, ani punkty życia, ani czary, ani dziennik. Mistrz gry bez postaci jest widoczny jako „Mistrz gry”. Pozostali członkowie widzą Twoje postacie tylko z imienia i portretu, a Ty ich postacie tak samo.
- **Portrety.** Jeśli postać w drużynie ma portret, aplikacja wysyła jego kopię na serwer, żeby telefony pozostałych członków mogły go pokazać. Serwer sprawdza tylko jego rozmiar i format. Usuwa portret kilka dni po tym, jak odejdziesz od stołu, a od razu, gdy wyjdziesz z drużyny albo usuniesz swoje dane.
- **Zaproszenia.** Link, kod QR i krótki kod zaproszenia od gospodarza, przechowywane tylko jako skróty, z datą wygaśnięcia (po 7 dniach) i liczbą użyć.
- **Gra drużyny przy stole:** wspólna kolejka inicjatywy z postaciami, przeciwnikami i innymi wpisami, ich rzuty, runda i czyja jest tura. Wpis, który mistrz gry ukryje, trafia tylko do mistrza gry (w drużynie bez mistrza gry tylko do tego, kto go dodał). Na telefony pozostałych graczy trafia dopiero wtedy, gdy zostanie odkryty.
- **Tylko u gospodarza: licencja.** Prowadzenie drużyny online jest funkcją płatną, więc serwer pyta Google Play, czy zakup gospodarza jest ważny, i zapisuje odpowiedź: który produkt, odnośnik do zakupu, czy licencja jest dożywotnia, czy to subskrypcja, do kiedy jest ważna i kiedy ją sprawdzono. Goście niczego nie kupują i serwer niczego u nich nie sprawdza.

### Czego nasz serwer nie przechowuje

- **Reakcje.** Podziękowania, ostrzeżenia i emotki idą na telefony pozostałych jako krótkie kody, żeby każdy telefon pokazał je w swoim języku. Są widoczne przez kilka sekund i nie są zapisywane.
- **Kto jest przy stole:** serwer wie to tylko, dopóki Twój telefon jest połączony.
- Żadnego adresu e-mail, imienia i nazwiska, konta, kontaktów, lokalizacji ani identyfikatora reklamowego.

### Adresy internetowe

Jak każdy serwer, nasz widzi adres internetowy (adres IP) telefonu, który się z nim łączy. Używa go tylko do dwóch rzeczy:

- żeby nikt nie zgadywał kodów zaproszeń ani nie zasypywał serwera: próby z jednego adresu są liczone w pamięci serwera przez minutę, a nieudane próby dołączenia, pod skrótem adresu, przez jeden dzień;
- w dziennikach technicznych serwera, które zapisują każde połączenie z jego adresem i czasem, żeby dało się znaleźć usterki i ataki. Dzienniki są usuwane po 14 dniach, a dokładniejsze ślady techniczne po 72 godzinach.

Dzienniki i ślady zostają na naszych własnych serwerach. Nigdy nie służą do ustalania, kim jesteś, do śledzenia, co robisz w aplikacji, ani do reklam.

### Po co i na jakiej podstawie

Przechowujemy te dane tylko po to, żeby działała drużyna online: żeby wpuścić Twój telefon do Twojej drużyny, pokazać członków sobie nawzajem, utrzymać grę drużyny taką samą na każdym telefonie i sprawdzić licencję gospodarza. To usługa, o którą prosisz, korzystając z tej funkcji (RODO, art. 6 ust. 1 lit. b). Adresy internetowe w dziennikach i limitach chronią serwer i graczy przed nadużyciami, co jest naszym prawnie uzasadnionym interesem (RODO, art. 6 ust. 1 lit. f).

### Gdzie

Na naszych własnych serwerach w Polsce, w Unii Europejskiej. Fall In Studio prowadzi je samo; żadna inna firma nie przechowuje danych drużyny ani ich kopii.

### Kto jeszcze bierze w tym udział

- **Cloudflare** przenosi połączenie między aplikacją a naszym serwerem i chroni serwer przed atakami. Po drodze obsługuje to, co wysyła aplikacja, i widzi adres internetowy Twojego telefonu, ale nie przechowuje danych drużyny. Cloudflare robi to dla nas na podstawie umowy powierzenia przetwarzania danych. Gdy jego sieć obsługuje połączenie poza UE, przekazanie danych zabezpieczają ramy ochrony danych UE–USA (Data Privacy Framework) i standardowe klauzule umowne Komisji Europejskiej.
- **Google Play** obsługuje zakup gospodarza według własnej polityki prywatności Google. Nasz serwer tylko pyta Google Play, czy zakup jest ważny.

Nie sprzedajemy danych i nie przekazujemy ich nikomu innemu.

### Jak długo

- Drużyna, jej członkowie, ich postacie w niej, zaproszenia i gra: dopóki członek nie wyjdzie z drużyny (jego część jest usuwana od razu), gospodarz nie usunie członka albo gospodarz nie rozwiąże drużyny (wszystko jest usuwane od razu).
- Portrety: kilka dni po tym, jak właściciel odejdzie od stołu; od razu, gdy wyjdzie z drużyny.
- Gdy licencja gospodarza wygaśnie, drużyna przestaje działać po 7 dniach, ale zostaje zachowana, żeby mogła ruszyć znowu po odnowieniu licencji. Drużyna, która nie działa od 12 miesięcy, jest usuwana.
- Klucz drużyny Twojego telefonu: usuwany, gdy nie był używany przez 12 miesięcy.
- Wszystko, razem z zapisem licencji gospodarza: usuwane od razu, gdy usuniesz swoje dane (niżej).
- Liczniki nieudanych prób dołączenia: jeden dzień. Dzienniki techniczne: 14 dni. Ślady techniczne: 72 godziny.

## Pliki, które sam przenosisz

- **Kopie zapasowe.** Gdy robisz kopię, aplikacja zapisuje plik i przekazuje go do okna udostępniania Androida. Gdzie trafi dalej (folder, dysk w chmurze, wiadomość), decydujesz Ty, a od tej chwili zajmuje się nim wybrana aplikacja lub usługa na własnych zasadach.
- **Paczki i kopie, które otwierasz.** Aplikacja czyta tylko plik wybrany przez Ciebie w oknie wyboru plików Androida i tylko po to, żeby go zaimportować.

## Kopia zapasowa Androida

Jeśli w ustawieniach urządzenia kopia zapasowa jest włączona, Android może kopiować dane aplikacji na Twoje konto Google, tak jak robi to z innymi aplikacjami, i przywrócić je na nowym urządzeniu. Tą kopią zajmuje się Google według własnej polityki prywatności, a my jej nigdy nie dostajemy. Możesz ją wyłączyć w ustawieniach urządzenia. Klucz drużyny Twojego telefonu nigdy nie trafia do tej kopii ani do kopii zapasowych samej aplikacji.

## Usuwanie danych

Usuń postacie i paczki w aplikacji, wyczyść pamięć aplikacji w ustawieniach Androida albo odinstaluj aplikację. Każdy z tych sposobów usuwa dane z urządzenia.

W drużynie online:

- **Wyjdź z drużyny** w aplikacji albo **Wyjdź ze wszystkich drużyn** w Ustawieniach: Ty, Twoje postacie i ich portrety w tych drużynach są od razu usuwane z serwera. Klucz drużyny Twojego telefonu i licencja zostają, więc możesz znowu dołączyć do drużyny albo ją założyć.
- **Rozwiąż drużynę** (gospodarz): drużyna, jej członkowie, zaproszenia, gra i portrety są od razu usuwane z serwera.
- **Usuń moje dane** w Ustawieniach: wszystkie Twoje dane online są od razu usuwane z serwera: klucz drużyny Twojego telefonu, zapis licencji, Twoje miejsce w każdej drużynie oraz dodane przez Ciebie zaproszenia, wpisy i portrety. Drużyny, które prowadzisz, są przy tym rozwiązywane.
- **Jeśli nie możesz już użyć aplikacji** (na przykład ją odinstalowałeś), klucza drużyny na serwerze nie da się już użyć, a po 12 miesiącach bez użycia jest usuwany. Żeby usunąć wszystko wcześniej, napisz do nas na adres niżej, a usuniemy to w ciągu miesiąca. Możemy zapytać o nazwę Twojej drużyny albo imiona Twoich postaci, żeby to znaleźć.

Pisząc na ten sam adres, możesz też zapytać, co o Tobie przechowujemy, poprosić o poprawienie tych danych, ograniczenie lub zaprzestanie ich używania albo o ich kopię. Możesz też złożyć skargę do Prezesa Urzędu Ochrony Danych Osobowych (UODO).

## Dzieci

Aplikacja nie jest skierowana do dzieci poniżej 13 lat.

## Zmiany

Jeśli aplikacja zacznie kiedyś inaczej obchodzić się z danymi, najpierw zmieni się ta polityka, z nową datą na górze.

## Kontakt

Administratorem opisanych tu danych jest Fall In Studio Jakub Leśniak, Polska.

Fall In Studio — spellhelper.fallin@gmail.com
