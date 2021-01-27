# sokoban2021
## A feladat leírása

A program a népszerű **Sokoban** játék egy változata, a legfontosabb különbségek, hogy ez az alkalmazás **multiplayer** (esetünkben pontosan két játékos játszhatja,) akik egymással **versenyeznek**, és akár **meg is ölhetik** egymást.

A játék egy raktárban játszódik, melynek belül is lehetnek **falai és oszlopai**, és benne **ládák** vannak, amiket **munkások** tologathatnak. A **padló blokkokból** áll, amik között találhatók **célmezők**, **lyukak**, **kapcsolók**, és **kapcsolható lyukak**. Ha munkás vagy láda **lyukra kerül, eltűnik, és elpusztul**. Kapcsolót **úgy lehet aktiválni, ha ládát tolunk rá**, és úgy lehet lekapcsolni, ha letoljuk róla a ládát. Mindegyikhez tartozik egy kapcsolható lyuk, ami akkor van nyitva és viselkedik lyukként, ha a kapcsolója aktív - egyébként egyszerű, járható mezőnek látszik és biztonságosan lehet rajta közlekedni.

Egy munkás **több objektumot is tolhat** egyszerre, ezek között ott lehet a másik munkás is. Fontos azonban, hogy a munkásoknak **véges ereje** van, amivel csak véges sok objektumot tudnak mozgatni.

Egy játékos úgy tud meghalni, ha lyukba esik vagy rátolnak egy ládát. Egy munkásra (játékosra) úgy lehet rátolni egy ládát, ha a tolás hatására nem tud a munkás is eltolódni az adott irányba.

Tehát egy   Player1 --> Láda --> Player2 --> Fal felálásban a Player2 meghal. Ugyan így belelehet tolni egy munkást egy lyukba, nyilván ezesetben is meghal.

A játékosok célja, hogy **több ládát toljon célmezőre**, mint az ellenfél. A játék véget ér, ha minden láda célmezőn van vagy többet úgy sem lehetne mozgatni.
