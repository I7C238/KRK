## **A rendszer célja és nem célja**

Ennek a projektnek az a célja, hogy egy olyan felületet biztosítson két játékos számára akik egymás ellen tudnak játszani 3x3-as vagy 4x4es pályán. Az lesz a győztes aki víszintesen vagy függőlegesen 3 ugyan olyan szimbólumot sikerül kiraknia. Ha sikerül, még a tervünk az, hogy mesterséges inteligenciát használva akár a gép ellen is tudjunk játszani. A játéknak nem célja az, hogy ha gép ellen játszunk mindig veszítsünk, hanem törekszünk egy kiegyensúlyozott játékot létrehozni.

## **Üzleti folyamatok modellje**

### Üzleti Szereplők

Játékosok: Két játékos, akik egymás ellen játszanak

## **Üzleti folyamat**

* 1.Az induláshoz az egyik játékos egy táblát rajzol, létrehozva egy rácsnyi négyzetet, általában 3 x 3 vagy 4 x 4.
* 2.A játékos, aki "X" -t játszik, mindig először megy.
* 3.A játékosok váltakoznak az Xs és Os helyezést a táblán, amíg egyik játékosnak nincs három sorban, vízszintesen, függőlegesen vagy átlósan; vagy mind a kilenc négyzet be van töltve. 
* 4.Ha egy játékos három egymás utáni X-ből vagy három O-rájából húzható ki, akkor a játékos nyer. 
* 5.Ha mind a kilenc négyzet be van töltve, és egyik játékos sem három egymás után, a játék egy sorsolás.
* 6.A játékmenet ugyanaz, ha 4 x 4-es rácson játszik. Az "X" játékos megy először. És a játékosok váltakoznak az Xs és Os helyezésével a táblán, amíg egy sor vízszintesen, függőlegesen vagy átlósan nem lesz, vagy mind a 16 négyzet be van töltve. Ha mind a 16 négyzet be van töltve, és egyik játékos sem négy egymás után, a játék egy sorsolás. 

## **Követelmények**
Funkcionális követelmények:

- Könnyű kezelhetőség
- Áttekinhető és felhasználó barát felület
- Optimalizálás különböző böngészőkre
- Optimalizálás telefonos böngészőkre

Karbantartási terv

A játék a jövőben nem igényel nagy karbantartásokat, a szükséges karbantartások az alábbi egységekből állnak:

    Frissebb verziójú böngészőkben történő tesztelés, hiba észlelése esetén azoknak javítása.
    A kiszolgáló szerver státuszának ellenőrzése, offline szerver esetén újraindítás.
    Igény esetén új funkciók implementálása.
