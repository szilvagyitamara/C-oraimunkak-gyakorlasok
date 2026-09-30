 # Rövid osszefoglaló vázlat


##  1. PROGRAM – Gyümölcsök kezelése

###  Mit tartalmaz?
- `Gyumolcs` osztály (név, szín)
- Objektumok létrehozása
- Kiírás metódussal
- Tömb használata
- Lista használata
- Ciklusok (for, foreach)

###  Mit csinál?
- Létrehoz 4 gyümölcsöt (alma, szilva, barack, banán)
- Kiírja a gyümölcsök adatait
- 5× kiírja az alma nevét
- Tömbben tárolja a gyümölcsöket és kiírja:
  - neveket
  - neveket + színeket
- Listában is tárolja őket és kiírja:
  - for ciklussal
  - foreach ciklussal

###  Mit tanít?
- Osztályok, objektumok
- Tömbök és listák használata
- Ciklusok bejárása

---

##  2. PROGRAM – Kutya osztály

###  Mit tartalmaz?
- `Kutya` osztály (név, életkor)
- 3 különböző konstruktor
- `Kiir()` metódus
- Kutyák létrehozása és kiírása
- Külső függvény a kiíráshoz

###  Mit csinál?
- Létrehoz 4 kutyát (Abby, Lisa, Jinn, BbokAri)
- Kiírja a kutyák nevét és életkorát
- Meghívja a `Kiir()` metódust minden kutyára
- Külső `Kiir(Kutya kutya)` függvény is kiírja az adatokat

###  Mit tanít?
- Konstruktorok működése
- Objektumok többféle létrehozása
- Metódusok osztályon belül és kívül

---

##  3. PROGRAM – Macska osztály

###  Mit tartalmaz?
- `Macska` osztály (név, életkor)
- Automatikus property-k (`get; set;`)

###  Mit csinál?
- Létrehoz két macskát (Cili, Panni)
- Kiírja a macskák nevét és életkorát
- Javít egy hibát: macska2 értéke rossz objektumra lett beállítva

### Mit tanít?
- Property-k használata
- Egyszerű objektumok létrehozása
- Adatok kiírása

---

# Összefoglaló táblázat

| Program   | Osztály   | Mit tanít? |
|----------|-----------|------------|
| Gyümölcs | Gyumolcs  | objektumok, tömb, lista, ciklusok |
| Kutya    | Kutya     | konstruktorok, metódusok, objektumkezelés |
| Macska   | Macska    | property-k, egyszerű objektumok |

---
# Fogalmak 

## Osztály (class)
Az osztály egy **sablon**, amely meghatározza, hogy egy objektumnak milyen adatai (property-k) és műveletei (metódusok) vannak.  
Példa: `Gyumolcs`, `Kutya`, `Macska`.

---

## Objektum (object)
Az osztály **példánya**, egy konkrétan létrehozott adat.  
Példa:  
`Gyumolcs alma = new Gyumolcs("alma", "piros");`

---

## Konstruktor (constructor)
Egy speciális metódus, amely **az objektum létrehozásakor fut le**, és beállítja az induló értékeket.  
Példa:  
`public Gyumolcs(string nev, string szin) { ... }`

---

## Property (get; set;)
Olyan változó, amelyhez szabályozott módon férünk hozzá.  
A `get` visszaadja az értéket, a `set` beállítja.  
Példa:  
`public string Nev { get; set; }`

---

## Metódus (method)
Az osztályon belüli függvény, amely valamilyen műveletet végez.  
Példa:  
`public void Kiir() { ... }`

---

## Tömb (array)
Rögzített méretű adatszerkezet, amely több elemet tárol.  
Példa:  
`Gyumolcs[] gyumolcsok = { gy1, gy2, gy3 };`

---

## Lista (List<T>)
Rugalmas méretű gyűjtemény, amelyben elemeket lehet hozzáadni, törölni.  
Példa:  
`List<Gyumolcs> lista = new List<Gyumolcs>();`

---

## for ciklus
Ismétlődő művelet, amely **meghatározott számú alkalommal** fut.  
Példa:  
`for (int i = 0; i < 5; i++) { ... }`

---

## foreach ciklus
Végigmegy egy gyűjtemény **minden elemén**, és sorban elérhetővé teszi őket.  
Példa:  
`foreach (Gyumolcs g in lista) { ... }`

---

## Metódus hívása
Egy objektumhoz tartozó metódus futtatása.  
Példa:  
`kutya1.Kiir();`

---

## Namespace
Logikai csoportosítás, amely segít rendszerezni az osztályokat.  
Példa:  
`namespace ConsoleApp31 { ... }`

---




