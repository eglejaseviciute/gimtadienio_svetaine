# Gimtadienio svetainė

Interaktyvi gimtadienio interneto svetainė, sukurta kaip asmeninė staigmena draugei(-ui). Svetainėje yra nuotraukų galerija, draugystės laiko skaičiuoklė, daina rodoma su žodžiais, mini žaidimas (pūzlė), viktorina ir interaktyvus gimtadienio tortas.

Svetainė sukurta naudojant **HTML, CSS ir JavaScript**, todėl jai nereikia jokio serverio ar papildomų programų. Ją galima paleisti tiesiog naršyklėje arba savo asmeniniame kompiuteryje.

---

# Apie svetainę

Tai interaktyvi gimtadienio svetainė, kurioje lankytojas nėra tiesiog nukreipiamas į paprastą tekstinį sveikinimą.

Pirmiausia reikia interaktyvei atrakinti svetainę, o vėliau lankytojas gali pasirinkti skirtingas staigmenos dalis.

Svetainėje yra:

* 🔐 interaktyvus atrakinimo ekranas;
* 👋 pradinis pasveikinimas;
* 📷 bendrų nuotraukų galerija;
* 🕰️ draugystės laiko skaičiuoklė;
* 🎵 muzikos grotuvas su sinchronizuojamu dainos tekstu;
* 🎂 interaktyvus gimtadienio tortas;
* 🧩 nuotraukos dėlionė;
* 💃 draugystės viktorina;
* 🎉 galutinis gimtadienio sveikinimas su konfeti efektu.

---

# Kaip naudotis svetaine?

## 1. Atrakinti staigmeną 🔐

Atidarius svetainę pasirodo užrakintas ekranas.

Norint tęsti reikia:

**paspausti slankiklį ir perbraukti jį į dešinę.**

Kai slankiklis pasiekia pabaigą, svetainė automatiškai pereina į pradžios ekraną.

---

## 2. Pradinis ekranas 👋

Atsidarius pradžios ekranui rodomas sveikinimas ir nuotrauka.

Norint tęsti reikia paspausti:

**„Tęsti →“**

---

# 📋 Pagrindinis meniu

Pagrindiniame meniu galima pasirinkti skirtingas svetainės dalis.

Galimi pasirinkimai:

### 📷 Nuotraukos

Čia galima peržiūrėti į svetainę įkeltas bendras nuotraukas.

Nuotraukos keičiamos naudojant:

* ◀ ankstesnė nuotrauka;
* ▶ kita nuotrauka.

Svetainėje naudojamos 19 nuotraukų, tačiau jų skaičių galima lengvai pakeisti HTML faile.

---

### ⏳ Laiko skaičiuoklė

Šioje dalyje rodoma, kiek laiko praėjo nuo nustatytos draugystės pradžios datos.

Laikas rodomas:

* metais;
* mėnesiais;
* dienomis;
* valandomis;
* minutėmis;
* sekundėmis.

Skaičiuoklė atnaujinama kiekvieną sekundę.

Pradinė data nustatyta JavaScript kode:

```javascript
const startDate = new Date("2019-09-01");
```

Jeigu reikia pakeisti datą, galima pakeisti šią eilutę, pavyzdžiui:

```javascript
const startDate = new Date("2020-05-15");
```

---

### 🎵 Muzika

Šioje skiltyje galima paleisti į svetainę įkeltą dainą.

Galimi veiksmai:

* ▶ **Groti**
* ⏸ **Sustabdyti**

Taip pat rodomas dainos tekstas.

---

### 🧩 Mini žaidimas

Mini žaidime reikia sudėti išmaišytą nuotrauką.

Nuotrauka padalinta į:

```text
3 × 3
```

tai yra 9 dalis.

Dalys gali būti perkeliamos pele.

Kai nuotrauka sudėta teisingai, pasirodo pranešimas:

> 🎉 Teisingai sudėjai!

Taip pat paleidžiamas konfeti efektas.

Norint pradėti iš naujo galima paspausti:

**🔀 Maišyti**

---

### 💃 Draugystės viktorina

Viktorinoje pateikiami klausimai apie draugystę.

Kiekvienam klausimui pateikiami keli atsakymo variantai.

Pasirinkus atsakymą:

* teisingas atsakymas pažymimas;
* neteisingas atsakymas parodomas;
* pereinama prie kito klausimo.

Baigus viktoriną parodomas rezultatas, pavyzdžiui:

```text
4 / 5
```

---

### 🎂 Gimtadienio tortas

Torto puslapyje rodomas interaktyvus gimtadienio tortas su žvakutėmis.

Paspaudus:

**💨 Užpūsk žvakutes**

žvakutės užgęsta.

---

### 🎉 Galutinis sveikinimas

Paskutiniame puslapyje rodomas pagrindinis gimtadienio sveikinimas.

Paspaudus:

**🎉 Staigmena! (PASPAUSK)**

paleidžiamas konfeti efektas.

---

# Kaip paleisti svetainę kompiuteryje naudoti GitHub?

Tai rekomenduojamas būdas, jeigu norima svetaine pasidalinti su kitu žmogumi.

### 1. Įkelti projektą į GitHub

Repositorijoje turi būti bent:

```text
index.html
```

ir visi failai, kurių reikia svetainei:

```text
car.jpg
photo1.jpg
photo2.jpg
...
photo19.jpg
song.mp3
```

### 2. Įjungti GitHub Pages

GitHub repositorijos lange:

```text
Settings
→ Pages
→ Build and deployment
→ Source: Deploy from a branch
→ Branch: main
→ Folder: / (root)
→ Save
```

Po publikavimo GitHub sugeneruos svetainės adresą.

Adresas bus panašus į:

```text
https://vartotojas.github.io/repository/
```

Gautą nuorodą galima tiesiog nukopijuoti ir nusiųsti kitam žmogui.

Žmogui nereikės:

* atsisiųsti GitHub repositorijos;
* įsidiegti programavimo programų;
* turėti GitHub paskyros;
* paleisti Python;
* atidarinėti HTML failo.

Pakaks paspausti nuorodą.

---

# Kaip atsisiųsti projektą iš GitHub?

Jeigu norima turėti visą svetainę kompiuteryje, galima atsisiųsti repositoriją.

GitHub puslapyje:

```text
Code
→ Download ZIP
```

Atsisiuntus ZIP failą reikia:

1. Išskleisti ZIP failą.
2. Atidaryti atsiradusį aplanką.
3. Jame rasti `index.html`.
4. Atidaryti `index.html` su naršykle (du kartus spustelėti `index.html` failą).

Svarbu išlaikyti visus failus tame pačiame aplanke.

Negalima atsisiųsti tik `index.html`, jeigu norima, kad veiktų nuotraukos ir muzika.

---

# Kaip pakeisti nuotraukas?

Nuotraukų pavadinimai nustatyti JavaScript kode:

```javascript
const photoList = [
    "photo1.jpg",
    "photo2.jpg",
    "photo3.jpg",
    "photo4.jpg"
];
```

Jeigu norima pakeisti nuotrauką, galima tiesiog įkelti naują failą tokiu pačiu pavadinimu.

Pavyzdžiui:

```text
photo1.jpg
```

pakeisti kita nuotrauka, išlaikant tą patį pavadinimą.

Tokiu atveju HTML kodo keisti nereikia.

---

# Kaip pridėti daugiau nuotraukų?

Pavyzdžiui, jeigu norima pridėti `photo20.jpg`, reikia:

### 1. Įkelti:

```text
photo20.jpg
```

į repositoriją.

### 2. Pridėti jį į JavaScript:

```javascript
const photoList = [
    "photo1.jpg",
    "photo2.jpg",
    ...
    "photo19.jpg",
    "photo20.jpg"
];
```

Nuotraukų skaitiklis automatiškai prisitaikys prie naujo nuotraukų skaičiaus.

---

# Kaip pakeisti muziką?

Seno `song.mp3` failo vietoje galima įkelti kitą MP3 failą ir pavadinti jį:

```text
song.mp3
```

Tokiu atveju HTML kodo keisti nereikia.

Arba galima naudoti kitą failo pavadinimą ir pakeisti:

```html
<source src="song.mp3" type="audio/mpeg">
```

į:

```html
<source src="mano-daina.mp3" type="audio/mpeg">
```

---

# Kaip pakeisti tekstus?

Dauguma tekstų yra tiesiogiai `index.html` faile.

Pavyzdžiui:

```html
<h1>Liabas drauge!!!</h1>
```

galima pakeisti į:

```html
<h1>Su gimtadieniu!!!</h1>
```

Taip pat galima pakeisti galutinį sveikinimą:

```html
<h1>Su gimtadieniu,<br>nuo Eglutės!</h1>
```

ir:

```html
<p class="final-sub">
Auk didute, būk gerutė. Myliu, bučiuoju, širdelei nešioju!
</p>
```

---

# Kaip pakeisti viktorinos klausimus?

Klausimai saugomi JavaScript dalyje:

```javascript
const quizQuestions = [
    {
        q: "Kur mes pirmą kartą susipažinome?",
        answers: [
            "Universitete",
            "Gimnazijoje",
            "Per draugus",
            "Intike"
        ],
        correct: 1
    }
];
```

`correct` nurodo teisingo atsakymo numerį.

Numeracija prasideda nuo `0`.

Todėl:

```text
0 → pirmas atsakymas
1 → antras atsakymas
2 → trečias atsakymas
3 → ketvirtas atsakymas
```

Jeigu:

```javascript
correct: 1
```

teisingas yra antras atsakymas.

Specialus atvejis:

```javascript
correct: -1
```

reiškia, kad visi atsakymai laikomi teisingais.

---

# Suderinamumas

Svetainė skirta veikti šiuolaikinėse interneto naršyklėse, pavyzdžiui:

* Google Chrome
* Safari
* Microsoft Edge
* Mozilla Firefox

Kompiuteryje svetainė turėtų veikti geriausiai.

Kadangi svetainėje naudojamas pelės valdomas dėlionės mechanizmas ir gana didelis interaktyvus langas, naudojimas telefone gali būti ne toks patogus.

---

# Projekto idėja

Ši svetainė sukurta kaip asmeniška, interaktyvi gimtadienio dovana. Vietoje įprasto gimtadienio sveikinimo lankytojas turi pats „atrakinti“ staigmeną, peržiūrėti bendrus prisiminimus, pažaisti mini žaidimus, atsakyti į viktorinos klausimus, užpūsti torto žvakutes ir galiausiai pasiekti pagrindinį sveikinimą.

Visas projektas sukurtas taip, kad jį būtų galima lengvai pritaikyti kitam žmogui pakeičiant nuotraukas, muziką, tekstus, viktorinos klausimus ir datą.
