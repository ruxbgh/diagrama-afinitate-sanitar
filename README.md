# Diagrama afinității – Managementul calității în sistemul sanitar

Aplicație web live pentru exercițiul **Diagrama afinității**, destinată studenților de la masterul *Managementul calității în sistemul sanitar* (ASE București).

**Link:** https://ruxbgh.github.io/diagrama-afinitate-sanitar/
**Zona formatorului:** https://ruxbgh.github.io/diagrama-afinitate-sanitar/?prof

## Cum funcționează
1. **Pregătire** – formatorul creează sesiunea (cod de 5 caractere), participanții intră cu numele.
2. **Scriere individuală** – fiecare notează cauze pe bilețele, cu cronometru (ideile celorlalți sunt ascunse).
3. **Grupare împreună** – toată echipa grupează bilețelele în categorii și le denumește, în timp real.
4. **Rezultat** – diagrama finală, export CSV (Excel).

Studiul de caz implicit: *Investigarea unui caz de malpraxis – compresă chirurgicală uitată în abdomenul pacientului după o operație de urgență* – poate fi modificat la crearea sesiunii.

Datele sunt stocate în Firebase Realtime Database, sub `afinitate-sanitar/`, separat de aplicația pentru SMC.
