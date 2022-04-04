# 2022-04-02-SQL-uzduotis
Instructions
1. Susikurti duomenų bazę "duomenubazesvaldymas".
2. Duomenų bazėje susikurti lentelę Clients:
id - primary, key, bigInteger(10), unsigned, autoIncrement
name - varchar, 120 simbolių
description - text
3. Pasinaudojant duomenų bazės užpildymo skriptu(https://github.com/motiejus1/duomenu_bazes_uzpildymas-22gr-php) užpildyti duomenų bazę 4000 klientų.
4. Papildyti duomenų lentelę Clients stulpeliu:
company_id - bigInteger(10)
internal_id - bigInteger(10)
5. Su SQL užklausa UPDATE, kiekvienam klientui sugeneruoti atsitiktinį company_id nuo 1 iki 4,
internal_id - nuo 1 iki 10000.
6. Sukurti SELECT užklausą, kuri atfiltruotų klientus, kurių company_id = 4 ir išrikiuotų pagal name mažėjimo tvarka.
7. Sukurti SELECT užklausą, kuri suskaičiuotų, kiek klientų priklauso 2 kompanijai.
8. Sukurti DELETE užklausą, kuri ištrintų klientus, kurių internal id lygus 958, 1414.

P.S. Užklausas tiesiog prikabinkite prie Assignmento kaip tekstinį failą.
My work
