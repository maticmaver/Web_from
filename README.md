# 📸 Instagram fake form (Šolski Projekt)

Enostavna spletna aplikacija, ki posnema uporabniški vmesnik za Instagram (UI) in osnovno funkcionalnost prijave, registracije ter ponastavitve gesla na socialnem omrežju Instagram. Project je nastal v okviru šolske naloge za utrjevanje znanja spletnih tehnologij.

---

## 🚀 O projektu

Namen projekta je bil ustvariti odzivno (responsive) spletno stran, ki po videzu in delovanju posnema ključne strani Instagrama:
* **Prijava (`instagramLogin.html`)**: Vstopna stran z možnostjo vnosa podatkov in preverjanjem veljavnosti.
* **Registracija (`InstagramRegister.html`)**: Obrazec za ustvarjanje računa z dinamičnim izbirnikom za datum rojstva (s preverjanjem starosti nad 13 let).
* **Ponastavitev gesla (`instagramReset.html`)**: Stran za obnovitev računa.
* **Potrditev računa (`instagramConfirm.html`)**: Stran za vnos 6-mestne potrditvene kode.

---

## 🛠️ Uporabljene tehnologije

* **HTML5**: Semantična struktura spletnih strani in obrazcev.
* **CSS3**: Stiliranje, uporaba Flexbox postavitev, modalna okna in odzivni dizajn (`@media` poizvedbe za mobilne naprave).
* **JavaScript (Vanilla JS)**: 
  * Validacija obrazcev (preverjanje formata e-pošte, telefonskih številk, dolžine gesla).
  * Dinamična modalna obvestila (namesto klasičnih `alert()` oken).
  * Dinamično generiranje letnic in dni v mesecu pri registraciji.

---

## 🔑 Demo podatki za preizkus

Za testiranje prijave in obnovitve računa lahko uporabite naslednje prednastavljene podatke:

| Polje | Testna vrednost |
| :--- | :--- |
| **Uporabniško ime / E-pošta / Telefon** | `test` **ali** `test@gmail.com` **ali** `123456789` |
| **Geslo** | `test123!` |

> 💡 **Opomba:** Pri registraciji in potrditvi se potrditvena koda izpiše v demo modalnem oknu ob kliku na povezavo *"your email address"*.

---


## 📝 Avtor

* **Dijak / Avtor:** [Matic Maver]
* **Šola:** [Elektrotehniška in računalniška šola Nova Gorica]
* **Predmet:** [Upravljanje s spletnimi vsebinami (USV)]
