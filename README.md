# Hitman 3 - Spolszczenie na PlayStation 5 (Wersja v1.10)

Spolszczenie interfejsu (LOCR) do gry *Hitman: World of Assassination (Hitman 3)* dostosowane do działania na złamanych konsolach PlayStation 5.

**Obecny stan spolszczenia:**
- **W 100% spolszczony interfejs:** Menu, ustawienia, opisy broni, cele misji, samouczki, wyzwania i powiadomienia na ekranie.
- **Angielskie napisy w cutscenkach i dialogach:** Ze względu na niekompatybilność pecetowych i konsolowych formatów binarnych silnika Glacier 2 (format `BIN1`), narzędzia moderskie nie potrafią obecnie skompilować poprawnie działających plików audio/wideo (`.DLGE` i `.RTLV`) pod konsolę PS5. Próba ich implementacji kończy się crashem gry lub czarnym ekranem, dlatego te pliki zostały intencjonalnie usunięte z łatki, aby zapewnić 100% stabilności. Gra odtworzy napisy z tych plików po angielsku.

---

## 🛠 Jak zainstalować?

Instalacja jest bardzo prosta i polega na zastąpieniu/dodaniu zmodyfikowanych plików (łatek) w folderze z grą na Twoim dysku zewnętrznym lub serwerze FTP konsoli.

1. Wypakuj grę `HITMAN 3` na swój dysk komputera lub upewnij się, że masz dostęp do plików gry przez klienta FTP (dla złamanej konsoli PS5).
2. Pobierz całe to repozytorium (np. jako plik ZIP i wypakuj).
3. Skopiuj folder **`Runtime`** z pobranego repozytorium.
4. Wklej go do głównego katalogu z grą na konsoli/dysku (tam, gdzie znajduje się już oryginalny folder `Runtime`). System zapyta, czy scalić foldery/nadpisać pliki – wyraź zgodę. Wszystkie łatki `patch300` trafią na swoje miejsce.
5. Ciesz się grą po polsku!

---

## 👥 Twórcy i podziękowania

* **Autorzy oryginalnych tekstów i tłumaczenia:** Ekipa z forum [GrajPoPolsku.pl](https://grajpopolsku.pl/forum/viewtopic.php?t=3740). Pełne zasługi za przetłumaczenie dziesiątek tysięcy linijek tekstu należą do nich!
* **Port na konsolę PS5:** Ja jedynie przygotowałem paczkę, zautomatyzowałem proces iniekcji tekstów i przekompilowałem archiwa na poprawne pliki `.rpkg` przeznaczone do odczytu przez silnik gry na PlayStation 5.
