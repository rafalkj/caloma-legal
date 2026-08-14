# Polityka Prywatności aplikacji Caloma

**Data ostatniej aktualizacji:** 14.08.2026 r.

---

## 1. Administrator danych

Administratorem danych osobowych jest Rafał Kidaj — indywidualny twórca aplikacji mobilnych.

**Adres korespondencyjny:** ul. Tumidajskiego 16/88; 20-247 Lublin

**Kontakt:** calomamacrotracker@gmail.com

---

## 2. O aplikacji

Caloma to aplikacja mobilna do śledzenia spożycia kalorii i makroskładników. Aplikacja działa w trybie offline — nie wymaga rejestracji ani logowania. Dane wprowadzone przez użytkownika przechowywane są wyłącznie lokalnie na urządzeniu i nie są nigdy wysyłane na serwery administratora.

---

## 3. Dane przechowywane lokalnie na urządzeniu

Następujące dane przechowywane są wyłącznie na urządzeniu użytkownika:
- spożyte posiłki, produkty, ilości i makroskładniki,
- wpisy w dzienniku wagi,
- cele kaloryczne i makroskładnikowe,
- dane antropometryczne wykorzystywane do automatycznego wyliczenia zapotrzebowania kalorycznego: wzrost, wiek, płeć, poziom aktywności fizycznej, waga docelowa, wybrany cel (redukcja/utrzymanie/masa),
- opcjonalna nazwa użytkownika,
- ustawienia aplikacji, status subskrypcji Pro i data jej wygaśnięcia.

Dane przechowywane są do czasu odinstalowania aplikacji. Użytkownik może usuwać poszczególne wpisy (produkty, szablony posiłków) bezpośrednio w aplikacji. Aplikacja tworzy również automatyczną, lokalną kopię zapasową danych w prywatnym katalogu aplikacji na urządzeniu — plik ten nie jest nigdzie przesyłany ani udostępniany. Jeśli na urządzeniu włączona jest funkcja kopii zapasowej systemu Android, dane aplikacji mogą być objęte automatycznym backupem Google — zarządzanie nim odbywa się w ustawieniach systemu Android.

**Podstawa prawna:** art. 6 ust. 1 lit. b RODO (świadczenie usługi).

---

## 4. Automatyczne wyliczanie zapotrzebowania kalorycznego

Na podstawie danych antropometrycznych podanych przez użytkownika (waga, wzrost, wiek, płeć, poziom aktywności) aplikacja może automatycznie wyliczyć orientacyjne dzienne zapotrzebowanie kaloryczne i makroskładnikowe. Wyliczenia opierają się na standardowych wzorach (np. Mifflin-St Jeor) i mają charakter wyłącznie szacunkowy — nie stanowią porady medycznej ani dietetycznej. Zasady odpowiedzialności za wykorzystanie tych wyliczeń określa Regulamin aplikacji.

**Podstawa prawna:** art. 6 ust. 1 lit. b RODO (świadczenie usługi).

---

## 5. Dane przekazywane do usług zewnętrznych

### 5.1 Sentry — raportowanie błędów

Aplikacja korzysta z Sentry.io w celu wykrywania awarii. W przypadku błędu automatycznie przekazywane są:
- informacje o błędzie i ślad stosu wywołań (stack trace),
- podstawowe dane urządzenia (model, wersja systemu Android),
- wersja aplikacji,
- próbka danych o wydajności (20% sesji).

Dane nie zawierają informacji żywieniowych użytkownika. Dane przetwarzane są na serwerach w Unii Europejskiej. Administrator zawarł z Sentry umowę powierzenia przetwarzania danych (DPA) zgodnie z art. 28 RODO.

**Cel:** zapewnienie stabilności i jakości aplikacji.  
**Podstawa prawna:** art. 6 ust. 1 lit. f RODO (uzasadniony interes administratora).  
**Polityka prywatności Sentry:** https://sentry.io/privacy/

### 5.2 Open Food Facts — baza produktów

Podczas wyszukiwania produktów aplikacja wysyła zapytanie do publicznej bazy Open Food Facts:
- kod kreskowy produktu (przy skanowaniu),
- wyszukiwana fraza tekstowa (przy wyszukiwaniu po nazwie).

Open Food Facts to organizacja non-profit z siedzibą we Francji.

**Cel:** pobranie wartości odżywczych produktu.  
**Podstawa prawna:** art. 6 ust. 1 lit. b RODO (świadczenie usługi).  
**Polityka prywatności Open Food Facts:** https://world.openfoodfacts.org/privacy

### 5.3 Google Play Billing — zakupy w aplikacji

Wersja Caloma Pro udostępniana jest w modelu automatycznie odnawiającej się subskrypcji, w wariancie miesięcznym lub rocznym, obsługiwanej w całości przez Google Play. Administrator otrzymuje wyłącznie:
- identyfikator produktu subskrypcyjnego,
- token potwierdzający zakup/odnowienie subskrypcji.

Pełne dane płatności (karta, adres) oraz zarządzanie subskrypcją (w tym jej anulowanie) przetwarzane są wyłącznie przez Google i nie są dostępne dla administratora. Subskrypcją można zarządzać oraz ją anulować bezpośrednio w aplikacji Google Play na urządzeniu.

**Cel:** realizacja i weryfikacja subskrypcji Pro.
**Podstawa prawna:** art. 6 ust. 1 lit. b RODO (wykonanie umowy).
**Polityka prywatności Google:** https://policies.google.com/privacy

### 5.4 Expo — aktualizacje aplikacji

Aplikacja korzysta z Expo Updates w celu dostarczania aktualizacji. Przekazywane są wyłącznie metadane techniczne:
- identyfikator projektu,
- wersja aplikacji.

**Cel:** dostarczanie poprawek bez pośrednictwa sklepu.  
**Podstawa prawna:** art. 6 ust. 1 lit. f RODO (uzasadniony interes administratora).  
**Polityka prywatności Expo:** https://expo.dev/privacy

---

## 6. Aparat i skaner kodów kreskowych

Aplikacja może używać aparatu wyłącznie do skanowania kodów kreskowych produktów żywnościowych. Obraz z kamery przetwarzany jest lokalnie na urządzeniu — nie jest zapisywany ani przesyłany na zewnątrz. Dostęp do aparatu wymaga zgody użytkownika i może być cofnięty w ustawieniach systemu.

---

## 7. Eksport danych

Aplikacja umożliwia eksport danych żywieniowych (m.in. dziennika, produktów własnych, szablonów posiłków i pomiarów wagi) do pliku JSON (Profil → Eksport danych). Plik zapisywany jest lokalnie na urządzeniu i udostępniany wyłącznie na żądanie użytkownika za pomocą systemowego mechanizmu udostępniania. Aplikacja umożliwia również import danych z wcześniej wyeksportowanego pliku JSON (Profil → Import danych), w trybie połączenia z istniejącymi danymi lub ich zastąpienia. Import odbywa się wyłącznie lokalnie na urządzeniu — wybrany plik nie jest przesyłany do administratora ani do żadnych usług zewnętrznych.

---

## 8. Zautomatyzowane podejmowanie decyzji i profilowanie

Administrator nie stosuje zautomatyzowanego podejmowania decyzji ani profilowania w rozumieniu art. 22 RODO.

---

## 9. Minimalny wiek użytkownika

Aplikacja przeznaczona jest dla osób, które ukończyły 18 lat, w szczególności ze względu na dostępną w Aplikacji płatną subskrypcję. Z uwagi na to, że Aplikacja działa w pełni offline i nie wymaga rejestracji, Administrator nie posiada możliwości identyfikacji użytkowników ani zdalnego dostępu do ich danych. Jeżeli rodzic lub opiekun prawny stwierdzi, że z Aplikacji korzysta osoba niepełnoletnia, może samodzielnie odinstalować Aplikację.

---

## 10. Prawa użytkownika (RODO)

Przysługują Ci następujące prawa:

- **Prawo dostępu, sprostowania i usunięcia danych** — z uwagi na to, że Aplikacja działa w pełni offline i nie przekazuje danych lokalnych do Administratora, Administrator nie ma do nich dostępu ani możliwości ich zdalnej modyfikacji lub usunięcia. Powyższe prawa realizujesz samodzielnie bezpośrednio w Aplikacji — poprzez edycję lub usunięcie poszczególnych wpisów, eksport danych (Profil → Eksportuj dane) lub odinstalowanie Aplikacji.
- **Prawo do przeniesienia danych** — dane lokalne możesz wyeksportować bezpośrednio w aplikacji (Profil → Eksportuj dane).
- **Prawo do sprzeciwu** — wobec przetwarzania danych na podstawie uzasadnionego interesu administratora (dotyczy Sentry i Expo Updates). Z uwagi na brak identyfikacji użytkowników w Aplikacji, Administrator nie ma możliwości wyłączenia tego przetwarzania dla pojedynczego użytkownika na jego żądanie — jedynym sposobem rezygnacji z tego przetwarzania jest zaprzestanie korzystania z Aplikacji.
- **Prawo do skargi** — możesz złożyć skargę do Prezesa Urzędu Ochrony Danych Osobowych (UODO), ul. Stawki 2, 00-193 Warszawa, www.uodo.gov.pl.

W sprawach, w których Administrator ma faktyczną możliwość podjęcia działania (np. pytania dotyczące przetwarzania danych przez Sentry lub Expo), skontaktuj się: calomamacrotracker@gmail.com

---

## 11. Zmiany polityki prywatności

Administrator zastrzega sobie prawo do zmiany niniejszej polityki. Data ostatniej aktualizacji widnieje na górze dokumentu. O istotnych zmianach użytkownicy będą informowani poprzez aktualizację aplikacji.

---

## 12. Kontakt

**Email:** calomamacrotracker@gmail.com
