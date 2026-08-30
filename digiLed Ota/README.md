# digiLed OTA

Kanoniczne pliki aktualizacji OTA projektu digiLed są przechowywane wyłącznie w tym katalogu.

Dla każdego wydania:

- zapisz firmware jako `firmware-<wersja>.bin`,
- zapisz portal jako `littlefs-<wersja>.bin`,
- zaktualizuj `latest.json` i `changelog.json`,
- zachowaj zgodność wersji, rozmiarów, hashy i adresów URL,
- opublikuj katalog `digiLed Ota/` na gałęzi `main` publicznego repozytorium `kamerok89/digiLedOta`.

Nie twórz kopii manifestu ani artefaktów OTA w innych katalogach.
