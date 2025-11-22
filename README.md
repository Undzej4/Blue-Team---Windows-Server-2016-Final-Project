# Blue-Team---Windows-Server-2016-Final-Project
Windows Server 2016

Projekt polegał na zaprojektowaniu i wdrożeniu kompletnego środowiska domenowego opartego na Windows Server 2016 oraz stacjach roboczych Windows 10. Celem było zbudowanie funkcjonalnej infrastruktury Active Directory, przygotowanie struktury organizacyjnej firmy oraz wdrożenie polityk bezpieczeństwa zgodnych z założeniami projektowymi.

W ramach projektu skonfigurowałem:
1. Active Directory Domain Services (ADDS)

-Utworzenie nowej domeny.

-Zbudowanie kompletnej struktury OU odwzorowującej działy organizacji:

-Designers

-Developers

-IT

-QA

-HR

-Dodanie użytkowników i grup zgodnie ze strukturą firmy.

Zaprojektowanie logicznego podziału z wykorzystaniem najlepszych praktyk AD.

2. Konfiguracja Group Policy Objects (GPO)

-Utworzenie i przypisanie polityk zabezpieczeń dla poszczególnych działów.

-Wdrożenie ograniczeń systemowych, m.in.:

-Blokada dostępu do Control Panel,

-Blokada dostępu do CMD,

-Zdefiniowanie ograniczeń uprawnień dla mniej uprzywilejowanych użytkowników.

-Wymuszenie firmowych tapet w zależności od działu (GPO – Wallpaper Management).

3. Środowisko klient–serwer

-Przyłączenie maszyn z Windows 10 do domeny.

-Przeprowadzenie testów logowania użytkowników domenowych.

-Weryfikacja działania polityk GPO na poszczególnych kontach użytkowników.

4. Zastosowane zasady bezpieczeństwa

-Zasada najmniejszych uprawnień (Least Privilege).

-Ograniczenie dostępu do kluczowych narzędzi administracyjnych.

-Centralne zarządzanie konfiguracją stacji roboczych.

-Podział użytkowników na role zgodne z dobrymi praktykami IT.

Efekt końcowy

-Projekt dostarczył w pełni funkcjonalne, bezpieczne i logicznie zaprojektowane środowisko Windows Server, obejmujące:

-działający kontroler domeny,

-strukturę AD z użytkownikami i grupami,

-zestaw precyzyjnie przygotowanych GPO,

-stacje robocze działające w domenie,

-kontrolowane uprawnienia i ograniczenia zabezpieczające.
