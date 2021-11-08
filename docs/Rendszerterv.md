# WEATHER FORECAST
## 1. A Rendszer célja
A project célja, hogy egy neurális háló, ami Pythonban van megírva, megtudja jósolni az időjárási adatokat. Például hőmérséklet, esőzés, páratartalom.
Ezeket az adatokat a program egy adatbázisból szerzi(az átlag hőmérsékletet, az átlag esőzést). A program tartalmazni fog egy egyszerűbb GUI-t is. Így jobban átláthatóbb lesz.

## 2. Követelmények
* Funkcionális
    -Kapcsolat teremtése az adatbázissal,illetve szükséges információk megszerzése az adatbázisból.
    -A szükséges adatok megszerzése után az adatok átadása egy képi tanuló algoritmusnak.
    -Neurális háló segítségével a megszerzett információk alapján előrejelzés készítése.
### Nem Funkcionális 
    -Az alkalmazásnak (viszonylag) pontos,reális előrejelzést kell adni a felhasználó számára.

## 3. Funkcionális terv
* Rendszerszereplő:
    -Felhasználó
### Rendszerhasználati esetek:
* Felhasználó tudjon a programmal:
    -Pontos előrejelzés alapján információkat szerezni az időjárással (hőmérséklet, csapadék, páratartalom) kapcsolatban.

### Menü-hierarchia:
    -Legördülő lista, melyben a városnevek találhatók.
    -Gomb, amely megerősíti a várost,és elindítja az előrejelzést
    -Táblázat, melyben az adatok megjelennek,a gomb megnyomása után.

## 4. Fizikai környezet

* Fejlesztői környezet:
    -Python

## 5. Architekturális terv
Az alkalmazás a felhasználó szamítógépén fog futni.
* Specifikáció:
    - Szükséges egy megfelelő specifikációval rendelkező számítógép.
	- Szükség hogy a számítógépen telepítve legyen megfelelő futtató program (python).

## 6. Adatbázis terv
Az adatbázis tartalmaz egy városnevet,valamint a hozzá tartozó időjárási adatokat( hőmérséklet, csapadék, páratartalom, szélerősség )

## 7. Implementációs terv
Az alkalmazás a felhasználó gépén fog futni python segítségével.

## 8. Tesztterv

## 9. Karbantartási terv
