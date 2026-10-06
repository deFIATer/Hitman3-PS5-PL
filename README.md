# Hitman 3 - Spolszczenie na PlayStation 5 (Wersja v1.10)

Spolszczenie interfejsu (LOCR) do gry *Hitman: World of Assassination (Hitman 3)* dostosowane do działania na złamanych konsolach PlayStation 5.

**Obecny stan spolszczenia:**
- **W 100% spolszczony interfejs:** Menu, ustawienia, opisy broni, cele misji, samouczki, wyzwania i powiadomienia na ekranie.
- **Angielskie napisy w cutscenkach i dialogach:** Ze względu na niekompatybilność pecetowych i konsolowych formatów binarnych silnika Glacier 2 (format `BIN1`), narzędzia moderskie nie potrafią obecnie skompilować poprawnie działających plików audio/wideo (`.DLGE` i `.RTLV`) pod konsolę PS5. Próba ich implementacji kończy się crashem gry lub czarnym ekranem, dlatego te pliki zostały intencjonalnie usunięte z łatki, aby zapewnić 100% stabilności. Gra odtworzy napisy z tych plików po angielsku.

---

## 🛠 Jak zainstalować?

Instalacja jest bardzo prosta i polega na zastąpieniu/dodaniu zmodyfikowanych plików (łatek) w folderze z grą na Twoim dysku zewnętrznym lub serwerze FTP konsoli.

1. Wypakuj grę `HITMAN 3` na swój dysk komputera lub upewnij się, że masz dostęp do plików gry przez klienta FTP (dla złamanej konsoli PS5).
2. Otwórz folder z wypakowaną grą i przejdź do podfolderu **`Runtime`**. Powinieneś tam widzieć ogromne archiwa o nazwach takich jak `chunk0.rpkg`, `chunk1.rpkg` itd.
3. Skopiuj **wszystkie pliki `.rpkg`** z tego repozytorium (zaczynające się od `chunkXpatch300.rpkg`) i wklej je bezpośrednio do folderu **`Runtime`** na konsoli/dysku z grą.
4. Zbuduj ponownie pakiet gry na PS5 (jeśli uruchamiasz z pendrive'a/dysku zewnętrznego) lub po prostu uruchom grę, jeśli wklejałeś pliki bezpośrednio "w locie". Silnik sam zauważy pliki `patch300`, nada im najwyższy priorytet i nadpisze domyślny język angielski.
5. Ciesz się grą po polsku!

---
*Bazuje na oryginalnym spolszczeniu PC od społeczności Hitmana. Architektura PS5 przeliczona automatycznie.*
