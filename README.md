📸 Instagram UI Clone (Šolski Projekt)Enostavna spletna aplikacija, ki posnema uporabniški vmesnik (UI) in osnovno funkcionalnost prijave, registracije ter ponastavitve gesla na socialnem omrežju Instagram. Project je nastal v okviru šolske naloge za utrjevanje znanja spletnih tehnologij.🚀 O projektuNamen projekta je bil ustvariti odzivno (responsive) spletno stran, ki po videzu in delovanju posnema ključne strani Instagrama:Prijava (instagramLogin.html): Vstopna stran z možnostjo vnosa podatkov in preverjanjem veljavnosti.Registracija (InstagramRegister.html): Obrazec za ustvarjanje računa z dinamičnim izbirnikom za datum rojstva (s preverjanjem starosti nad 13 let).Ponastavitev gesla (instagramReset.html): Stran za obnovitev računa.Potrditev računa (instagramConfirm.html): Stran za vnos 6-mestne potrditvene kode.🛠️ Uporabljene tehnologijeHTML5: Semantična struktura spletnih strani in obrazcev.CSS3: Stiliranje, uporaba Flexbox postavitev, modalna okna in odzivni dizajn (@media poizvedbe za mobilne naprave).JavaScript (Vanilla JS):Validacija obrazcev (preverjanje formata e-pošte, telefonskih številk, dolžine gesla).Dinamična modalna obvestila (namesto klasičnih alert() oken).Dinamično generiranje letnic in dni v mesecu pri registraciji.📂 Struktura datotek.
├── html/
│   ├── instagramLogin.html      # Stran za prijavo
│   ├── InstagramRegister.html   # Stran za registracijo
│   ├── instagramReset.html      # Stran za pozabljeno geslo
│   └── instagramConfirm.html    # Stran za potrditveno kodo
├── css/
│   ├── styleLogin.css           # Slogi za prijavo
│   ├── styleRegister.css        # Slogi za registracijo
│   ├── styleReset.css           # Slogi za ponastavitev
│   └── styleConfirm.css         # Slogi za potrditev
└── images/
    └── logo.png                 # Logotip in slike
🔑 Demo podatki za preizkusZa testiranje prijave in obnovitve računa lahko uporabite naslednje prednastavljene podatke:PoljeTestna vrednostUporabniško ime / E-pošta / Telefontest ali test@gmail.com ali 123456789Geslotest123!💡 Opomba: Pri registraciji in potrditvi se potrditvena koda izpiše v demo modalnem oknu ob kliku na povezavo "your email address".💻 Kako pokreneti projektKlonirajte repozitorij na svoj računalnik:git clone https://github.com/uporabnisko-ime/ime-repozitorija.git
Odprite mapo projekta.V brskalniku odprite datoteko html/instagramLogin.html.📝 AvtorDijak / Avtor: [Tvoje Ime]Šola: [Ime Srednje Šole]Predmet: [Ime Predmeta, npr. Spletne tehnologije / Računalništvo]
