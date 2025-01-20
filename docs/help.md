Amennyiben szeretnéd, hogy bővüljön az általunk lefedett szolgáltatások listája, van lehetőséged, hogy segíts nekünk!

A segítség legkényelmesebb módja az [anyagi támogatás](../support).

## Alapvető hibakeresés
Felmerülhet az igény, hogy betegyünk egy új szolgáltatást, függetlenül attól, hogy régi vagy akár új felhasználó vagy. Ilyenkor hasznos, ha meg tudod nekünk mutatni, hogy az adott szolgáltatásnak mi az ip címe, milyen szervereken megy keresztül, mekkora válaszidővel.

!!! INFO

    Ez a tudás akkor is hasznos, ha ellenőrizni szeretnéd, hogy a VPN működik-e vagy kíváncsi vagy, hogy támogatjuk-e az adott szolgáltatást!

### Ping parancs
A válaszidőnek, illetve a csomagvesztésnek mérésének a legalapvetőbb módja a **ping**.

=== "Windows"

    Az alábbi parancs a válaszidőt (ping), illetve a csomagvesztést (packet loss) méri a megadott ip cím felé 10 csomagon keresztül.    

    ```title="ping"
    ping -n 10 1.1.1.1
    ```
    
    ![](../../assets/ping1.png)    

=== "Linux"

    Az alábbi parancs a válaszidőt (ping), illetve a csomagvesztést (packet loss) méri a megadott ip cím/webcím felé 10 csomagon keresztül.    

    ```title="ping"
    ping -c 10 1.1.1.1
    ```
    
    ![](../../assets/ping2.png)    

### Tracert/Traceroute parancs
Mikor csatlakozol az internetre, valójában több szerveren mész keresztül, míg eléred uticélod, ezt az útvonalat hívjuk a gépedtől az uticélig **route**-nak. Ezen útvonal ismerete a mi szempontunkból kimondottan fontos, de sebaj, nagyon egyszerűen megtekinthető.

=== "Windows"

    Az alábbi parancs megmutatja, hogy milyen utat jársz be, mielőtt eléred uticálod.

    ```title="tracert"
    tracert 1.1.1.1
    ```
    ![](../../assets/trace1.png)

=== "Linux"

    Az alábbi parancs megmutatja, hogy milyen utat jársz be, mielőtt eléred uticálod.

    ```title="traceroute"
    traceroute 1.1.1.1
    ```
    ![](../../assets/trace2.png)

