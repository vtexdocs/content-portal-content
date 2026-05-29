---
title: 'Formate de date'
id: ui0009-ro
status: PUBLISHED
createdAt: 2025-08-28T19:24:22.388Z
updatedAt: 2025-08-28T19:24:22.388Z
publishedAt: 2025-08-28T19:24:22.388Z
firstPublishedAt: 2025-08-28T19:24:22.388Z
contentType: trackArticle
productTeam: Localization
slugEN: data-formats
locale: ro
trackId: 5PxyAgZrtiYlaYZBTlhJ2A
trackSlugEN: data-formats
---

Formatarea datelor în mod consistent oferă clienților o experiență clară, organizată și accesibilă.

### Numere

Folosiți punct sau spațiu ca separator de mii și virgulă ca separator zecimal.

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| <ul><li>1.230</li><li>1 230</li><li>9,5</li><li>37.809.009</li><li>0,006653 RON</li></ul> | <ul><li>1,230</li><li>9.5</li><li>37,809,009</li><li>RON0.006653</li></ul> |

Folosiți maximum două zecimale. Pentru numere întregi, folosiți doar numărul, fără zecimale.

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| <ul><li>9</li><li>1,53</li></ul> | <ul><li>9,0</li><li>1,533</li></ul> |

Indicați valori nule, 0 sau goale cu o cratimă sau cu „Niciun” în text continuu.

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| <ul><li>Niciun produs de afișat</li><li>Total cheltuit din buget</li><li>-</li><li>-</li></ul> | <ul><li>0 produse de afișat</li><li>Total cheltuit din buget</li><li>Niciun</li><li>0%</li></ul> |

Folosiți formatul „[număr] rate de [valoare monetară] RON” sau „[număr]x [valoare monetară] RON” pentru a indica ratele, cu „x” (literă x mică, fără spațiu înainte, cu spațiu după) reprezentând numărul de rate.

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| 3 rate de 100 RON | <ul><li>3x</li><li>3 rate</li></ul> |

Abreviați numerele mari când spațiul este limitat, urmând standardul internațional de abrevieri numerice.

| Exemple |
| :--- |
| <ul><li>60 mii = 60K</li><li>60 milioane = 60M</li><li>60 miliarde = 60B</li><li>60 trilioane = 60T</li></ul> |

Pentru numere de telefon, folosiți formatul 07xx xxx xxx pentru contexte locale și +40 7xx xxx xxx sau +40 21 xxx xxxx pentru contexte internaționale.

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| <ul><li>0721 234 567</li><li>021 123 4567</li><li>+40 721 234 567</li><li>+40 21 123 4567</li></ul> | <ul><li>0721.234.567</li><li>40-721-234-567</li></ul> |

Folosiți % când exprimați o procentaj în sine (o proporție). Folosiți p.p. (puncte procentuale) când exprimați diferența dintre două procente, nu o singură valoare procentuală.

Pentru procente, scrieți numărul și simbolul împreună, fără spațiu. Folosiți zero sau două zecimale, în funcție de context. Pentru p.p., lăsați un spațiu între număr și abreviere.

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| <ul><li>85%</li><li>85,31%</li><li>0,56 p.p. față de ieri</li></ul> | <ul><li>85 %</li><li>85,315 %</li><li>0,56p.p. față de ieri</li></ul> |

### Monedă

Folosiți codul țării când prioritatea este claritatea și în contexte mai internaționale, iar simbolul monedei (RON sau lei) în contexte care necesită mai multă ușurință în utilizare, precum într-o vitrină.

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| <ul><li>32.540,63 USD</li><li>100 RON</li><li>61,45 lei</li></ul> | <ul><li>$ 32.540,63</li><li>61,45666 RON</li></ul> |

### Dată și oră

Sunt acceptate formele extinse și numerice, cu condiția să respecte ordinea **zi, lună și an**. Când menționați zilele săptămânii, acestea trebuie precedate de virgulă și să apară înaintea datei.

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| <ul><li>26 septembrie 2027</li><li>Luni, 21 iunie 2027</li><li>Luni, 21.06.2027</li><li>30.04.2028</li></ul> | <ul><li>26 septembrie, 2027</li><li>Luni 21 iunie</li><li>Luni, 06.21.2027</li><li>04.30.2028</li></ul> |

Dacă trebuie să abreviați numele lunii, folosiți primele trei litere cu minusculă, urmate de punct. Singura excepție este luna mai, care nu are formă abreviată.

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| <ul><li>22 oct. 2021</li><li>mai/2016</li></ul> | <ul><li>22/octombrie</li><li>22 oct</li><li>Mai/2016</li></ul> |

La abrevierea zilelor săptămânii, folosiți primele trei litere, urmate de punct. În contexte cu restricții de spațiu, este acceptabil să folosiți doar inițiala, dacă sensul este clar (precum în calendare).

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| <ul><li>lun.</li><li>mar.</li><li>M</li><li>V</li></ul> | <ul><li>lun</li><li>mar</li><li>M.</li><li>V.</li></ul> |

În formulare și selectoare de dată, folosiți formatul DD.MM.AAAA sau DD.MM.AA. Nu folosiți formatul nord-american pentru date.

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| 30.05.25 | 05.30.25 |

Folosiți preferabil formatul de 24 de ore, conform standardului localei `ro-RO` ([CLDR](https://www.unicode.org/cldr/charts/47/summary/ro.html)): ore și minute separate prin două puncte (`HH:mm`), cu minutele zero incluse când este necesar pentru claritate.

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| <ul><li>14:30</li><li>16:00</li><li>09:00</li></ul> | <ul><li>14h30</li><li>16H</li><li>2:30 PM</li></ul> |

Pentru formatul de 12 ore, folosiți abrevierea cu litere mici și puncte. Adăugați un spațiu între oră și abreviere. Minutele zero nu sunt necesare.

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| <ul><li>Promoția va începe la 9:00 a.m.</li><li>Promoția va începe la 9 a.m.</li></ul> | Promoția va începe la 9:00 AM |

Pentru a indica timpul rămas sau parcurs, folosiți formatul 00z 00h 00m 00s, incluzând doar unitățile de timp necesare.

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| <ul><li>2z 5h 30m</li><li>45m 10s</li><li>10s</li></ul> | <ul><li>2:5:30</li><li>45' 10"</li><li>00:00:10</li></ul> |

Pentru a indica timpul scurs, precum data creării sau ultimei modificări, folosiți structura „acum x [unitate de timp]”.

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| <ul><li>acum 3 zile</li><li>acum 2 ore</li><li>acum 15 minute</li></ul> | <ul><li>Acum 3 zile</li><li>În urmă cu 2 ore</li><li>De acum 15 minute</li></ul> |

### Unități de măsură

Folosiți spațiu între număr și unitatea de măsură.

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| <ul><li>10 kg</li><li>50 cm</li><li>3 m²</li><li>100 km/h</li></ul> | <ul><li>10kg</li><li>50cm</li><li>3m²</li><li>100km/h</li></ul> |

La checkout, plasați semnul plus (+) sau minus (–) înaintea simbolului monedei (RON) fără spațiu între ele.

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| <ul><li>+100 RON</li><li>−6,99 RON</li></ul> | <ul><li>+ 45,00</li><li>− RON 6,99</li></ul> |

Nu folosiți niciodată plural la abrevierile unităților de măsură; acestea rămân la singular chiar și când valoarea este mai mare decât unu.

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| <ul><li>7 kg</li><li>60 m</li><li>1 cm</li></ul> | <ul><li>7 kgs</li><li>60 mts</li><li>7 cms</li></ul> |

Pentru prețuri pe unitate de măsură, nu folosiți spațiu înainte sau după bară (/).

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| <ul><li>2,99 RON/m</li><li>5,50 RON/kg</li><li>3,00 RON/buc</li></ul> | <ul><li>2,99 RON / m</li><li>5,50 RON/ kg</li><li>3,00 RON /buc</li></ul> |

Folosiți întotdeauna numere și unități când indicați cantități.

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| <ul><li>5 m</li><li>50 cm</li></ul> | <ul><li>cinci metri</li><li>cincizeci de centimetri</li></ul> |

Folosiți întotdeauna kilometri ca unitate de măsură pentru distanță.

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| <ul><li>10 km</li><li>0,5 km</li></ul> | <ul><li>6,21 mi</li><li>0,3 mi</li></ul> |

### Intervale

Folosiți întotdeauna cratima medie (en dash –) cu spațiu înainte și după pentru a indica intervale.

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| <ul><li>1 – 30 rezultate căutare</li><li>1 kg – 4 kg</li><li>4 aprilie – 6 iunie 2026</li><li>71601 – 72999</li></ul> | <ul><li>1 - 30 rezultate căutare</li><li>1 kg - 4 kg</li><li>4 aprilie - 6 iunie 2026</li><li>71601-72999</li></ul> |

> Notă: cratima medie este o liniuță scurtă (–) și diferă de cratima (-) și de liniuța de dialog (—).

### Adrese

Formatul standard de adresă în România include numele destinatarului, urmat de strada cu tip (str., bd., etc.), nume, număr și apartament, când este cazul. Urmează localitatea, județul (sau sectorul, în București) și codul poștal din șase cifre.

Exemplu:

```
Maria Popescu
Str. Victoriei, nr. 10, ap. 5
Sector 1
București 010101
```

Folosiți virgulă între localitate și județ. Dacă adresa este scrisă pe o singură linie, puneți virgulă după numele străzii și după localitate.

| Exemplu |
| :--- |
| Str. Victoriei, nr. 10, București, Sector 1 |

Pentru cazuri speciale, urmați orientările [Poștei Române](https://www.posta-romana.ro/). Pentru adrese din alte țări, urmați directivele serviciului poștal oficial al fiecărei țări.

Corect ✅
```
Bd. Unirii, nr. 15 – Centru
Cluj-Napoca, Cluj 400001
```

Incorect ❌
```
Bd. Unirii, nr. 15- Cluj-Napoca,
400001
```

Când indicați o locație aproximativă, puteți folosi codul poștal din șase cifre, localitatea sau ambele. Dacă folosiți localitatea și codul poștal împreună, separați-le prin virgulă.

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| <ul><li>010101</li><li>București, 010101</li></ul> | <ul><li>01010</li><li>București - 010101</li></ul> |

### Nume de țări

Pentru numele țărilor, urmați normele oficiale ale Institutului Național de Statistică sau standardele internaționale ISO 3166-1 adaptate în limba română.

| Exemple |
| :--- |
| <ul><li>Statele Unite</li><li>Regatul Unit</li><li>US</li><li>GB</li></ul> |

### Locale

Pentru a identifica localități (limbă + țară), folosiți o subtag de limbă din două litere cu minusculă, urmată de o subtag de țară din două litere cu majuscule, separate prin cratimă. Această practică urmează standardul [IETF BCP 47](https://www.rfc-editor.org/rfc/rfc5646#ref-ISO639-3), care combină normele ISO.

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| <ul><li>ro-RO</li><li>en-US</li><li>en-GB</li></ul> | <ul><li>ro_RO</li><li>En-US</li><li>RO</li></ul> |

### Documentație

Scrieți cu litere numerele mai mici decât 10 (unu, doi, trei etc.). Folosiți cifre de la 10 în sus, cu excepția cazurilor în care numărul nu indică o valoare specifică. Excepție: în tabele, deoarece cifrele îmbunătățesc lizibilitatea.

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| Acest filtru depășește intervalul maxim de șase luni. | Acest filtru depășește intervalul maxim de 6 luni. |

Când un eveniment sau o acțiune are loc la o anumită oră locală, includeți orașul și fusul orar UTC corespunzător. Dacă nu este un eveniment fizic și nu are o locație specifică, menționați doar UTC-ul corespunzător.

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| <ul><li>Evenimentul va avea loc în București la 10:30 (UTC+2)</li><li>Ultima actualizare: 06:42 (UTC+2)</li></ul> | <ul><li>Evenimentul va avea loc la 15h (GMT+2).</li><li>Ultima actualizare: 6h42 (UTC+2)</li></ul> |

#### Monede

Folosiți simbolul monedei, urmat de spațiu. Pentru numere întregi, folosiți preferabil doar numărul, fără zecimale.

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| Vom folosi ca exemplu un preț de 100 RON. | Vom folosi ca exemplu un preț de 100,00 RON. |

### Interfețe de utilizator

#### Monede

La checkout, folosiți simbolul monedei, întotdeauna cu un spațiu între simbol și valoare și cu două zecimale, chiar și pentru numere întregi.

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| <ul><li>55,90 RON</li><li>100,00 RON</li></ul> | <ul><li>55,9 RON</li><li>100 RON</li></ul> |

În storefront, folosiți simbolul monedei, urmat de spațiu. Pentru numere întregi, folosiți doar numărul, fără zecimale.

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| <ul><li>55,90 RON</li><li>80 RON</li></ul> | <ul><li>55,9 RON</li><li>80,00 RON</li></ul> |
