---
title: 'Interfețe computer'
id: formatting0003-ro
status: PUBLISHED
createdAt: 2025-09-03T15:00:00.388Z
publishedAt: 2025-09-03T15:00:00.388Z
firstPublishedAt: 2025-09-03T15:00:00.388Z
contentType: trackArticle
productTeam: Education
slugEN: computer-interfaces
locale: ro
trackId: 5PxyAgZrtiYlaYZBTlhJ2A
trackSlugEN: computer-interfaces
---

> ⚠️ Conținutul de mai jos explică cum se citează interfețele în tutoriale și ghiduri. Pentru a scrie texte pentru interfețe, consultați secțiunea [Texte de interfață](https://contentguide.vtex.com/ro/docs/interface-copy) din portalul Content Style Guide.

## Placeholders

Placeholder-ele indică locurile în care trebuie adăugate informații dinamice sau furnizate de utilizator. Ele ajută la claritate și consistență atunci când vă referiți la variabile, parametri sau câmpuri personalizabile. Când documentați placeholder-e, respectați regulile de formatare specifice pentru a asigura lizibilitatea și consistența.

Pentru informațiile care trebuie furnizate de utilizator, cum ar fi variabilele URL, folosiți placeholder-e între acolade.

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| <code>\{accountName\}.myvtex.com/admin</code> | <ul><li><code>\{\{accountName\}\}.myvtex.com/admin</code></li><li>`accountName.myvtex.com/admin`</li></ul> |

Când citați un placeholder într-un text continuu, formatați-l ca cod și fără acolade.

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| `accountName` trebuie înlocuit cu numele contului dvs. | <code>\{accountName\}</code> trebuie înlocuit cu numele contului dvs. |

## Etichete de acțiune

Etichetele de acțiune sunt elemente interactive care declanșează acțiuni, cum ar fi butoanele. Numele și reprezentarea lor trebuie să fie clare pentru a evita confuzia în timpul interacțiunii utilizatorului. Când citați butoane în ghiduri sau tutoriale, folosiți o formatare standardizată pentru a le diferenția de restul textului.

Când vă referiți la etichete de acțiune într-o listă, instrucțiuni numerotate, text continuu sau listă cu puncte, formatați numele butonului ca cod.

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| <ol><li>În modulul Marketplace, faceți clic pe `Integrări`.</li><li>În cardul Google Shopping, faceți clic pe `Integrare`.</li><li>Faceți clic pe `Salvare`.</li></ol> | <ol><li>În modulul `Marketplace`, faceți clic pe **Integrări**.</li><li>În cardul *Google Shopping*, faceți clic pe `Integrare`.</li><li>Faceți clic pe „Salvare configurație”.</li></ol> |

## Etichete de conținut

Etichetele de conținut, cum ar fi titlurile, meniurile și antetele coloanelor, ajută la structurarea interfeței și la ghidarea navigării. Mențineți consistența în modul în care sunt prezentate pentru a îmbunătăți experiența utilizatorului. Când le menționați în ghiduri sau tutoriale, folosiți formatarea adecvată pentru a le diferenția de textul obișnuit și pentru a face lectura mai clară.

Folosiți bold în text continuu pentru elementele interfeței, cum ar fi titlurile, numele modulelor, elementele tabelelor și secvențele care implică etichete de conținut între semnele mai mare și mai mic (>).

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| <ul><li>Selectați coloana **Status**.</li><li>Accesați pagina Admin și, în modulul **Produse**, faceți clic pe **Configurare magazin** > **inStore** > **Identificare client**.</li></ul> | <ul><li>Selectați coloana `Status`.</li><li>Accesați pagina Admin și, în modulul **Produse**, faceți clic pe `Configurare magazin` > `inStore` > `Identificare client`.</li></ul> |

## Iconițe

Iconițele reprezintă funcționalități în mod vizual și trebuie să echilibreze estetica și accesibilitatea. De aceea, este important să le folosiți cu atenție. Când le menționați în ghiduri sau tutoriale, includeți etichete descriptive și utilizați formatarea adecvată.

Iconițele sunt incluse în text pentru a reprezenta elemente ale interfeței și pentru a ajuta utilizatorul să le recunoască în timpul lecturii documentației. De fiecare dată când folosiți o iconiță, adăugați o legendă descriptivă pentru a asigura accesibilitatea.

*   Pentru documentație, preferați adăugarea iconițelor după o etichetă.
*   Iconița trebuie să fie aceeași ca în interfață. Dacă nu există iconițe în interfață, nu le folosiți.

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| Faceți clic pe butonul de căutare 🔍. | <ul><li>Faceți clic pe butonul lupa.</li><li>Faceți clic pe butonul 🔍 căutare.</li><li>Faceți clic pe butonul 🔍 lupa.</li></ul> |

Când adăugați o iconiță în HTML, includeți atributul `aria-hidden="true"` pentru ca cititoarele de ecran să ignore tagul HTML al iconiței încorporate.

> ℹ️ Iconițele încorporate cu `aria-hidden = false` pot întrerupe cititoarele de ecran, îngreunând lectura completă a propoziției.

| Corect ✅ | Incorect ❌ |
| :--- | :--- |
| Faceți clic pe butonul `` `<i class="fas fa-search" aria-hidden="true"></i>` `` de căutare. | Faceți clic pe butonul `` `<i class="fas fa-search"></i>` `` de căutare. |
