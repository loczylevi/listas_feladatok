# listas_feladatok
# Python – Gyakorlófeladatok listákhoz és ciklusokhoz

## 1. feladat – Kedvenc ételek

Készíts egy programot, amely a felhasználótól kedvenc ételeket kér be!

- A program addig kérjen be újabb ételeket, amíg a felhasználó ENTER-t nem nyom.
- Az ételeket tárolja egy listában.
- A végén írja ki az összes megadott ételt!
- Írja ki azt is, hány ételt adott meg a felhasználó!

**Példa kimenet:**
```text
Adj meg egy ételt: pizza
Adj meg egy ételt: hamburger
Adj meg egy ételt: palacsinta
Adj meg egy ételt:

Megadott ételek: ['pizza', 'hamburger', 'palacsinta']
Ételek száma: 3
```

---

## 2. feladat – Három keresztnév

Készíts egy programot, amely legfeljebb három keresztnevet kér be a felhasználótól!

- A neveket tárolja egy listában.
- A harmadik név megadása után tájékoztassa a felhasználót, hogy nincs lehetőség további nevek megadására.
- Ezután jelenítse meg az összes megadott nevet.
- A program a harmadik név megadása után lépjen ki.

**Példa kimenet:**
```text
Adj meg egy keresztnevet: Anna
Adj meg egy keresztnevet: Péter
Adj meg egy keresztnevet: Gábor

Elérted a maximális névszámot!
Megadott nevek: Anna, Péter, Gábor
```

---

## 3. feladat – A betűvel kezdődő szavak

Készíts egy programot, amely szavakat kér be a felhasználótól!

- A program csak a kis `a` betűvel kezdődő szavakat tárolja.
- Ha a szó más betűvel kezdődik, hagyja figyelmen kívül.
- A bekérés ENTER lenyomásáig folytatódjon.
- A végén írja ki a tárolt szavakat.
- A program tájékoztassa a felhasználót a működéséről és az elvárt adatokról.

**Példa kimenet:**
```text
Adj meg egy a betűvel kezdődő szót: alma
Adj meg egy a betűvel kezdődő szót: körte
Adj meg egy a betűvel kezdődő szót: autó
Adj meg egy a betűvel kezdődő szót: banán
Adj meg egy a betűvel kezdődő szót:

Tárolt szavak: ['alma', 'autó']
```

---

## 4. feladat – Kis- és nagybetűs szavak

Alakítsd át a 3. feladat programját úgy, hogy a kis `a` és a nagy `A` betűvel kezdődő szavakat is elfogadja!

- A többi szó ne kerüljön a listába.
- A bekérés ENTER lenyomásáig folytatódjon.
- A végén jelenítse meg a tárolt szavakat.

**Példa kimenet:**
```text
Adj meg egy szót: alma
Adj meg egy szót: Autó
Adj meg egy szót: Körte
Adj meg egy szót: Ananász
Adj meg egy szót:

Tárolt szavak: ['alma', 'Autó', 'Ananász']
```

---

## 5. feladat – Pozitív számok gyűjtése

Készíts egy programot, amely egész számokat kér be a felhasználótól!

- A bekérés ENTER lenyomásáig folytatódjon.
- Csak a pozitív számokat tárolja egy listában.
- A nullát és a negatív számokat hagyja figyelmen kívül.
- A végén írja ki a tárolt számokat és azok darabszámát.

**Példa kimenet:**
```text
Adj meg egy egész számot: 12
Adj meg egy egész számot: -5
Adj meg egy egész számot: 0
Adj meg egy egész számot: 7
Adj meg egy egész számot:

Pozitív számok: [12, 7]
Darabszám: 2
```

---

## 6. feladat – Páros számok gyűjtése

Készíts egy programot, amely egész számokat kér be!

- A program ENTER lenyomásáig kérjen be számokat.
- Csak a páros számokat tárolja egy listában.
- A páratlan számokat hagyja figyelmen kívül.
- A végén jelenítse meg a listát és a benne található számok darabszámát.

**Példa kimenet:**
```text
Adj meg egy számot: 4
Adj meg egy számot: 7
Adj meg egy számot: 10
Adj meg egy számot: 13
Adj meg egy számot: 22
Adj meg egy számot:

Páros számok: [4, 10, 22]
Páros számok darabszáma: 3
```

---

## 7. feladat – Véletlenszámok listája

Készíts egy programot, amely tíz véletlenszámot generál a `[0; 50]` intervallumban!

- A generált számokat tárolja egy listában.
- A végén írja ki a teljes listát.
- Jelenítse meg a lista hosszát is.

**Példa kimenet:**
```text
Generált számok: [12, 4, 35, 8, 19, 0, 41, 22, 6, 50]
A lista hossza: 10
```

---

## 8. feladat – Néggyel osztható véletlenszámok

Készíts egy programot, amely tíz véletlenszámot generál a `[0; 50]` intervallumban!

- Csak a néggyel osztható számokat tárolja egy listában.
- A végén jelenítse meg a tárolt számokat.
- Írja ki, hány szám került a listába.

**Példa kimenet:**
```text
Generált számok: [12, 7, 20, 33, 8, 14, 40, 5, 16, 29]
Néggyel osztható számok: [12, 20, 8, 40, 16]
Darabszám: 5
```

---

## 9. feladat – Hárommal osztható számok

Készíts egy programot, amely 15 véletlenszámot generál a `[10; 100]` intervallumban!

- Csak a hárommal osztható számokat tárolja egy listában.
- A végén írja ki a listát.
- Jelenítse meg a lista hosszát.
- Írja ki a lista legnagyobb elemét is, ha a lista nem üres.

**Példa kimenet:**
```text
Generált számok: [12, 17, 30, 44, 63, 81, 25, 99, 56, 72, 14, 36, 48, 91, 60]
Hárommal osztható számok: [12, 30, 63, 81, 99, 72, 36, 48, 60]
Darabszám: 9
Legnagyobb elem: 99
```

---

## 10. feladat – Szavak és azok hossza

Készíts egy programot, amely szavakat kér be a felhasználótól ENTER lenyomásáig!

- Minden olyan szót tároljon, amely legalább öt karakter hosszú.
- A rövidebb szavakat hagyja figyelmen kívül.
- A végén írja ki a tárolt szavakat.
- Írja ki a tárolt szavak számát is.

**Példa kimenet:**
```text
Adj meg egy szót: alma
Adj meg egy szót: informatika
Adj meg egy szót: körte
Adj meg egy szót: programozás
Adj meg egy szót:

Tárolt szavak: ['informatika', 'programozás']
Darabszám: 2
```

---

## 11. feladat – A lista elemeinek kiíratása

Készíts egy programot, amely ENTER lenyomásáig egész számokat kér be!

- A számokat tárolja egy listában.
- A bekérés végén írja ki a lista elemeit vesszővel elválasztva.
- Írja ki az első és az utolsó elemet.
- Jelenítse meg a lista hosszát.
- Ha a felhasználó nem ad meg egyetlen számot sem, a program ne hibásodjon meg.

**Példa kimenet:**
```text
Adj meg egy számot: 12
Adj meg egy számot: 5
Adj meg egy számot: 23
Adj meg egy számot: 8
Adj meg egy számot:

Lista: 12, 5, 23, 8
Első elem: 12
Utolsó elem: 8
Lista hossza: 4
```

---

## 12. feladat – Összetett gyakorlófeladat

Készíts egy programot, amely tíz véletlenszámot generál a `[0; 100]` intervallumban!

A program feladatai:

1. Generáljon tíz véletlenszámot.
2. Minden generált számot írjon ki a képernyőre.
3. Csak a páros számokat tárolja egy listában.
4. A végén írja ki a páros számokat tartalmazó listát.
5. Jelenítse meg, hány páros szám került a listába.
6. Számítsa ki a tárolt számok összegét.
7. Írja ki a legnagyobb tárolt számot, ha van ilyen.

**Példa kimenet:**
```text
Generált szám: 12
Generált szám: 7
Generált szám: 40
Generált szám: 33
Generált szám: 8
Generált szám: 15
Generált szám: 22
Generált szám: 51
Generált szám: 64
Generált szám: 9

Páros számok: [12, 40, 8, 22, 64]
Darabszám: 5
Összeg: 146
Legnagyobb páros szám: 64
```
