## O projekcie

Ta organizacja stanowi zbiór repozytoriów tworzących projekt stanowiska badawczego do analizy działania stacji uzdatniania wody, stworzonego na potrzeby edukacyjne dla Wydziału Inżynierii Środowiska i Energetyki Politechniki Poznańskiej. 

Stanowisko składa się między innymi z części mechaniczno-elektronicznej (opisanej w repozytorium `hardware`), oprogramowania niskopoziomowego (`firmware`), oprogramowania stanowiącego trzon logiki aplikacji i zarządzania przepływem danych (`backend`), łącznika między tymi dwiema warstwami (`connector`) oraz aplikacji internetowej służącej celom edukacyjno-eksperymentalnym, pozwalającej zgłębić wiedzę na temat analizowanych procesów oraz obsługiwać stanowisko z poziomu przeglądarki (`webapp_frontend`).

Aplikacja wykorzystuje dwie bazy danych - [InfluxDB](https://www.influxdata.com/) do przechowywania metryk w postaci przebiegów czasowych oraz [PostgreSQL](https://www.postgresql.org/). W obecnej wersji stanowisko laboratoryjne wykorzystuje Raspberry Pi 3B jako komputer pokładowy.

Każde z repozytoriów zostało opisane w taki sposób, by opisy tworzyły spójną dokumentację techniczną stanowiska pozwalającą na przeanalizowanie jego budowy i sposobu działania.
