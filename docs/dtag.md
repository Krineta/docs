# Információk a problémáról
Ha itt vagy bizonyára tapasztaltad, hogy Telekom hálózaton rengeteg oldal elérése, illetve jó pár játék is problémás. Bizonyára hallottál a hírekről is, miszerint a DTAG, vagyis a Német Telekom évek óta nem tud megegyezni a Cloudflare-el, vagy arról, hogy a Meta levált a hálózatukról.

## A probléma gyökere
Az előbb említett dolgok azért történnek, mert a DTAG üzleti kérdést csinált abból, hogy egyéb szolgáltatók közvetlenül összeköttetésben legyenek-e a hálózatukkal, ezáltal azok a szolgáltatások, melyek nem kerülnek be, többnyire használhatatlanok lesznek Telekom hálózatról, mindez azért, mert a DTAG egy előfizetéses modellből több pénzt tud kivenni, mint az elégedett ügyfelekből. Egy gigavállalatnak sokszor a számok jobban számítanak, mint a megteremtett érték.

## Hol a megoldás?
Korábban volt már rá példa, hogy beperelték a céget, valamint folyamatosan mennek a lakossági panaszok is, de ez nem minősül sikeresnek, ugyanis pénzzel minden megoldható, ami pedig a DTAG-nak van :slight_smile:.

Természetesen, ha akarnák, akkor simán megoldanák, viszont nem akarják, így nem maradt más, mint a közösségi megoldás, erre törekszünk mi is.

Mint a bevezetőbben olvashattad: ez egy VPN. Felmerül a kérdés, hogy más VPN-ek megoldhatják-e a problémát. A válasz igen. Amennyiben rendelkezel a szükséges tudással, kereshetsz egy VPS-t, ami bent van a DTAG hálón, és készíthetsz magadnak. Az üzleti VPN-ek, mint például a Proton vagy a Nord, nem fognak működni, mert az M247 hostingnál vannak, ez igaz a legtöbb VPN-re, ezért érdemes olyan VPN szolgáltatót keresni ami Datapacket-et használ, mivel hozzájuk jó a kapcsolat. Sok helyen írnak a Cloudflare WARP-ról, mint lehetséges megoldás, régen mi is javasoltuk, de nem megbízható már az sem, tehát a jelenlegi helyzet szerint a legkézenfekvőbb megoldás mi vagyunk!
