---
title: 'Proceduri'
id: formatting0004-ro
status: PUBLISHED
createdAt: 2025-12-27T15:00:00.388Z
publishedAt: 2025-12-27T15:00:00.388Z
firstPublishedAt: 2025-12-27T15:00:00.388Z
contentType: trackArticle
productTeam: Education
slugEN: procedures
locale: ro
trackId: 5PxyAgZrtiYlaYZBTlhJ2A
trackSlugEN: procedures
---

Procedurile includ o secvență de pași pentru a realiza o sarcină.

## Propoziții introductive

Începeți o procedură cu o propoziție introductivă pentru a oferi contextul care nu se regăsește în titlul secțiunii. Propozițiile introductive ajută cititorul să înțeleagă obiectivul, domeniul de aplicare și cerințele preliminare ale unei proceduri înainte de a începe.

> ⚠️ Dacă titlul explică procedura și nu este necesar niciun context suplimentar, introducerea poate fi omisă.

| Corect ✅ | Incorect ❌ |
| :---- | :---- |
| Înainte de a începe, asigurați-vă că aveți acces la panou ca administrator. | Această secțiune explică cum se configurează panoul. |
| Urmați instrucțiunile de mai jos pentru a remedia erorile din fluxul de plată. | În continuare, prezentăm etapele fluxului de plată. |
| Instalați VTEX IO CLI pentru a gestiona și dezvolta proiectul magazinului dvs. | Această secțiune explică cum se instalează CLI. |

Când explicați un pas cu pas, folosiți imperativul pentru a oferi instrucțiuni clare și pentru a ajuta utilizatorul să identifice acțiunile. Evitați să începeți cu o propoziție incompletă care depinde de etapele ulterioare pentru a fi finalizată.

| Corect ✅ | Incorect ❌ |
| :---- | :---- |
| Pentru a personaliza butoanele, urmați instrucțiunile de mai jos: | Pentru a personaliza butoanele: |
| Înainte de a face deploy, asigurați-vă că aplicația a fost deja publicată și testată. | Pași pentru deploy: |

Propoziția poate să se încheie cu două puncte sau cu punct final.

* Folosiți două puncte dacă propoziția introductivă precede imediat pașii.
* Folosiți punct final dacă există mai mult conținut (de exemplu: un callout sau o captură de ecran) între introducere și pași.

| Corect ✅ | Incorect ❌ |
| :---- | :---- |
| Pentru a gestiona categoriile de produse ale magazinului, urmați acești pași: | Pași pentru gestionarea categoriilor de produse ale magazinului dvs. |
| 1. Accesați Admin VTEX. | Mai întâi, accesați Admin VTEX. |
| 2. ... | 2. ... |
| Instalați dependențele proiectului pentru a-l rula local, urmând instrucțiunile de mai jos. | Instalați dependențele proiectului: |
| ⚠️ Asigurați-vă că proiectul dvs. are toate cerințele preliminare descrise în secțiunea [Înainte de a începe]. | ⚠️ Asigurați-vă că proiectul dvs. are toate cerințele preliminare descrise în secțiunea [Înainte de a începe]. |
| 1. Deschideți terminalul și executați `yarn install`. | Executați `yarn install`. |
| 2. ... | 2. ... |

## Conținut

Fiecare linie a pașilor trebuie să corespundă unei acțiuni pe care utilizatorul trebuie să o realizeze.

| Corect ✅ | Incorect ❌ |
| :---- | :---- |
| 1. Adăugați numele categoriei. | 1. Adăugați numele categoriei, faceți clic pe „Salvare” și reveniți la pagina **Categorii**. |
| 2. Faceți clic pe `Salvare`. |  |
| 3. Reveniți la pagina **Categorii**. |  |

Explicați conceptele separat (de exemplu: în callout-uri sau în introducere) și evitați să folosiți pașii exclusiv pentru a explica concepte.

| Corect ✅ | Incorect ❌ |
| :---- | :---- |
| Workspace-urile de dezvoltare vă permit să asociați, să publicați și să instalați aplicații. Pentru a crea un workspace de dezvoltare, urmați pașii de mai jos: | 1. Workspace-urile de dezvoltare vă permit să asociați, să publicați și să instalați aplicații. Pentru a crea un workspace de dezvoltare, autentificați-vă într-un cont VTEX. |
| 1. Autentificați-vă în contul VTEX dorit. | 2. Creați un workspace de dezvoltare executând comanda `vtex use {workspaceName}`. |
| 2. Creați un workspace de dezvoltare executând comanda `vtex use {workspaceName}`. | |

| Corect ✅ | Incorect ❌ |
| :---- | :---- |
| 1. Deschideți un terminal. Porniți un server de dezvoltare local pentru a găzdui site-ul executând `faststore dev`. | 1. Deschideți un terminal. |
| ℹ️ Comanda `faststore dev`, parte din [FastStore CLI](https://developers.vtex.com/docs/guides/faststore/getting-started-3-faststore-cli), actualizează proiectul magazinului cu pachetul `@faststore/core`. | 2. Porniți un server de dezvoltare local pentru a găzdui site-ul executând `faststore dev`. |
|  | 3. Comanda `faststore dev`, parte din [FastStore CLI](https://developers.vtex.com/docs/guides/faststore/getting-started-3-faststore-cli), actualizează proiectul magazinului dvs. cu pachetul `@faststore/core`. |

Includeți toate acțiunile necesare. Nu omiteți etape și nu presupuneți că utilizatorul cunoaște deja un anumit pas.

| Corect ✅ | Incorect ❌ |
| :---- | :---- |
| Tastați **install**. Faceți clic pe `Enter` pentru a începe instalarea. | 1. Tastați **install**. *(Se presupune că utilizatorul știe că trebuie să apese `Enter`)* |

Dacă un pas este prea lung, împărțiți-l în mai mulți pași. De asemenea, puteți combina acțiuni mici într-un singur pas folosind paranteze unghiulare (>) pentru selecții secvențiale din meniu.

| Corect ✅ | Incorect ❌ |
| :---- | :---- |
| 1. Accesați **Catalog > Atribute personalizate produs > Tipuri de serviciu**. | 1. Accesați **Catalog**. |
|  | 2. Mergeți la **Atribute personalizate produs**. |
|  | 3. Apoi, mergeți la **Tipuri de serviciu**. |

Mențineți forma verbală consistentă pe parcursul pașilor.

| Corect ✅ | Incorect ❌ |
| :---- | :---- |
| 1. Configurați inventarul. | 1. Configurând inventarul. |
| 2. Introduceți numele dvs. | 2. Completarea numelui dvs. |
| 3. Faceți clic pe `Salvare`. | 3. Faceți clic pe `Salvare`. |

Indicați obiectivul acțiunii și locul unde trebuie realizată înainte de a o indica.

| Corect ✅ | Incorect ❌ |
| :---- | :---- |
| Pentru a crea un document nou în software, faceți clic pe **Fișier > Nou > Document**. | Faceți clic pe **Fișier > Nou > Document** pentru a crea un document nou în software. |

Dacă există mai multe moduri de a realiza o sarcină, procedați astfel:

* Scrieți pașii care sunt cei mai accesibili pentru toți utilizatorii.
* Dacă toți pașii trebuie documentați, clarificați pentru cititor că aceasta este o modalitate alternativă de a realiza aceeași sarcină.
* Folosiți titluri, pagini sau ghiduri separate pentru a diferenția pașii alternativi.

<details>

<summary><b>✅ Corect</b></summary>

```md  
## Trimitere fișiere

1. Faceți clic pe **Trimitere**.  
2. Selectați fișierul.  
3. …

### Metodă alternativă: Trimitere fișiere (CLI)

1. Deschideți terminalul.  
2. Executați `upload --file=<path>`.  
3. …
```

</details>

<details>

<summary><b>❌ Incorect</b></summary>

```md  
## Trimitere fișiere

1. Faceți clic pe Trimitere sau executați `upload --file=<path>` în terminal.  
//(Amestecă metode fără o diferențiere clară.)
```

</details>

Pentru un pas opțional, adăugați (*Opțional*) la începutul propoziției.

| Corect ✅ | Incorect ❌ |
| :---- | :---- |
| (Opțional) Șir arbitrar. | (Opțional): Șir arbitrar. |

Evitați limbajul direcțional care face referire la aspectul vizual al layout-ului (de exemplu: „deasupra”, „dedesubt”, „în dreapta”) pentru a ghida cititorul. Acest tip de limbaj nu este eficient pentru accesibilitate sau localizare, deoarece depinde de vedere și de un layout specific al ecranului. În schimb, folosiți text descriptiv care numește elementele interfeței după funcția sau titlul lor.

| Corect ✅ | Incorect ❌ |
| :---- | :---- |
| 1. Faceți clic pe meniul ☰. | 1. Faceți clic pe butonul cu trei linii. |
| 2. În diagrama următoare, ... | 2. În diagrama de mai jos, ... |

> ⚠️ Când menționați elemente ale interfeței Admin care conțin text, transcrieți textul așa cum apare în Admin, păstrând literele mari și mici. Pentru mai multe informații, accesați [Interfețe computer](https://contentguide.vtex.com/ro/docs/formatting/computer-interfaces).

### Pași secundari în instrucțiuni numerotate

Pașii secundari împart instrucțiunile complexe în acțiuni mai mici și secvențiale care trebuie finalizate într-o anumită ordine. Ei folosesc o distincție ierarhică (litere, cifre romane) pentru a arăta dependența dintre acțiuni, ghidând utilizatorii prin etape dependente și clare.

#### Ierarhie și punctuație

* Pași principali: numere (`1.`, `2.`).
* Pași secundari: litere mici (`a.`, `b.`).
* Subpași: cifre romane mici (`i.`, `ii.`)
* Dacă un pas introduce pași secundari, încheiați-l cu două puncte (`:`).
* Dacă este un pas independent, folosiți punct final (`.`).

| Corect ✅ | Incorect ❌ |
| :---- | :---- |
| 1. Pentru a adăuga o instanță VM, procedați astfel: | 1. Pentru a adăuga o instanță VM, procedați astfel: |
| a. Faceți clic pe `Creare instanță`. | a. Faceți clic pe `Creare instanță`. |
| b. Introduceți un *Nume* pentru instanța VM și apoi: | b. Introduceți un *Nume* pentru instanța VM și apoi: |
| i. Selectați *Regiunea* în care doriți să faceți deploy instanței VM. | c. Selectați *Regiunea* în care doriți să faceți deploy instanței VM. |
| ii. Selectați *Tipul mașinii*. | d. Selectați *Tipul mașinii*. |
| c. Faceți clic pe `Creare`. | e. Faceți clic pe `Creare`. |
| 3. Pentru a vă conecta la instanța VM folosind SSH, faceți clic pe `SSH`. | 2. Pentru a vă conecta la instanța VM folosind SSH, faceți clic pe `SSH`. |

#### Acțiuni nesevențiale

Pentru elemente independente care nu necesită o secvență specifică, folosiți o listă cu puncte.

| Corect ✅ | Incorect ❌ |
| :---- | :---- |
| 1. Mergeți la **Setări**. | 1. Mergeți la **Setări**. |
| 2. Completați câmpurile de pe ecran listate mai jos, după cum este necesar. | 2. Completați câmpurile de pe ecran listate mai jos, după cum este necesar. |
| • ... | a. ... |
| • ... | b. ... |
| • ... | c. ... |
| 3. Faceți clic pe `Salvare`. | 3. Faceți clic pe `Salvare`. |

### Formatare

Când creați instrucțiuni, este esențial să mențineți o numerotare continuă. Aceasta înseamnă că etapele trebuie să curgă fără întreruperi (exemplu: 1., 2., 3. etc.).

Pentru a asigura claritatea și a menține fluxul, verificați întotdeauna dacă conținutul inserat — cum ar fi capturi de ecran, diagrame sau note — nu întrerupe progresia logică a etapelor. Inserarea incorectă a acestor elemente poate reporni accidental lista numerotată, făcând să pară că o procedură nouă începe de la `1.`, chiar dacă intenționați să continuați aceeași secvență de instrucțiuni.

| Corect ✅ | Incorect ❌ |
| :---- | :---- |
| 1. Deschideți Admin VTEX. | 1. Deschideți Admin VTEX. |
| 2. Accesați **Catalog > Produse și SKU-uri**. | 2. Accesați **Catalog > Produse și SKU-uri**. |
| `Captură de ecran a interfeței Produse și SKU-uri.` | `Captură de ecran a interfeței Produse și SKU-uri.` |
| 3. Faceți clic pe `Adăugare produs`. | 1. Faceți clic pe `Adăugare produs`. |
