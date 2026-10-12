# chromecast-cardputer


### Etapy
1. Habitat TV Standalone
   - Osobny testowy APK widoczny na ekranie głównym Android TV.
   - Interfejs TV będzie zapakowany wewnątrz APK, a nie pobierany z PC.
   - Uruchomi się również przy wyłączonym komputerze.
   - Obecny APK pozostanie nietknięty jako stabilny fallback.
2. TV LAN Relay
   - Chromecast udostępni w LAN ograniczony endpoint dla Cardputera i telefonu.
   - Lokalna baza/cache, outbox, Device ID i obecność urządzeń.
   - Tylko allowlistowane akcje, bez shella, ADB i uprawnień Core.
   - Parowanie sześciocyfrowym kodem wyświetlanym bezpośrednio na TV.
3. Aplikacja Cardputer Direct
   - Dodamy ją jako kolejną pozycję w głównym menu przerobionej MicroHydry.
   - Automatyczne wykrywanie TV w LAN, bez ręcznego wpisywania IP.
   - Jednorazowe parowanie, później zapis ograniczonego tokenu.
   - Zadania, status urządzeń, powiadomienia i sterowanie widokiem TV.
4. Telefon jako pilot
   - TV pokaże kod lub QR.
   - Telefon otworzy lokalny pilot i połączy się bezpośrednio z Chromecastem.
   - PC nie będzie pośrednikiem.
5. Synchronizacja z Core
   - Po ponownym uruchomieniu PC dane zostaną dosynchronizowane przez istniejący Sync v1.
   - Docelowo podmienimy lokalny relay na Hub 24/7 bez przebudowy aplikacji.




