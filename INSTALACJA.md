# Instalacja Well Dweller PL 1.0.0

Obsługiwana jest wersja Well Dweller na Windows ze Steam, BuildID `25633433`. Wymagana jest własna kopia gry.

1. Jeśli masz archiwum ZIP, rozpakuj je przed uruchomieniem instalatora.
2. Zamknij grę i uruchom `marko22-Instalator-Well-Dweller-PL-1.0.0.exe`.
3. Sprawdź wykryty katalog Steam lub wskaż folder gry ręcznie. Wybierz **Zainstaluj polską lokalizację** i potwierdź.
4. Uruchom grę ze Steam. Jeśli kreator wyświetli instrukcję ręcznego wyboru, otwórz **Opcje → Rozgrywka → Język → POLSKI**.

Kreator umożliwia aktualizację z RC6. Do przywrócenia uruchom ten sam instalator przy zamkniętej grze, wybierz ten sam folder i opcję **Przywróć oryginalne pliki**. Zachowaj utworzoną przez kreator kopię zapasową. Jeśli kreator zmienił język automatycznie, przywróci poprzedni wybór w tym samym profilu Windows.

Sumę kontrolną EXE podaje plik `.sha256`. W PowerShell odczytasz ją poleceniem `Get-FileHash -Algorithm SHA256 .\marko22-Instalator-Well-Dweller-PL-1.0.0.exe`.
