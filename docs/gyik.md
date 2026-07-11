---
sidebar_position: 5
title: GyIK
description: Gyakran ismételt kérdések a MeshCore-ról — a hivatalos angol GyIK alapján.
---

# Gyakran ismételt kérdések

:::info Forrás
Ez az oldal a [hivatalos MeshCore GyIK](https://docs.meshcore.io/faq/) (MIT licenc)
szerkezetét követi. A ✍️ jellel jelölt válaszok még kidolgozásra várnak — addig
az angol eredeti a mérvadó.
:::

## 1. Bevezetés

### Mi az a MeshCore?

A MeshCore egy könnyűsúlyú, hibrid útvonalválasztású mesh protokoll LoRa
packet-rádiókhoz. Internet és mobilhálózat nélkül tesz lehetővé titkosított
üzenetküldést: a csomópontok továbbítják egymás csomagjait, így nagy területek
is lefedhetők. Nyílt forráskódú (MIT licenc).

### Mi kell a MeshCore használatához?

Egy támogatott LoRa-eszköz (lásd: [Eszközök](hardver/eszkozok.md)), rá a
Companion firmware, és a MeshCore alkalmazás a telefonodra. Részletek:
[Gyors kezdés](gyors-kezdes.md).

## 2. Első lépések

### Hány eszköz kell a kezdéshez?

Egyetlen eszközzel már tudsz csatlakozni egy meglévő hálózathoz (például a
magyar meshhez — lefedettség: [mc868.hu](https://mc868.hu)). Ha a környékeden
még nincs hálózat, legalább két eszköz kell, hogy legyen kivel kommunikálni.

### Kerül pénzbe a MeshCore?

Nem. A firmware és az alkalmazások ingyenesek, előfizetés nincs — csak az
eszközök árával kell számolni. (Az appok kínálnak opcionális támogatói
vásárlásokat, amivel a fejlesztést segítheted.)

### Milyen frekvenciákat támogat a MeshCore?

✍️ *Kidolgozandó — [eredeti válasz](https://docs.meshcore.io/faq/#23-q-what-frequencies-are-supported-by-meshcore).*
**Magyarországon a 868 MHz-es (EU868) sávot használjuk.**

### Mi az az „advert"?

✍️ *Kidolgozandó — röviden: az advert a csomópont önhirdető csomagja, ezzel
tudatja a hálózattal, hogy létezik, és így kerül fel mások kapcsolatlistájára.*

### Van hop-limit (ugráskorlát)?

✍️ *Kidolgozandó — [eredeti válasz](https://docs.meshcore.io/faq/#25-q-is-there-a-hop-limit).*

## 3. Repeater és Room Server üzemeltetés

### Hogyan konfigurálok repeatert vagy room servert?

✍️ *Kidolgozandó — lásd: [Repeater](firmware/repeater.md), [Room Server](firmware/room-server.md).*

### Be kell állítanom a repeater pozícióját?

✍️ *Kidolgozandó.*

### Mi az adminisztrációs jelszó alapértelmezetten?

✍️ *Kidolgozandó.*

### Mi a jelszó egy room serverhez való csatlakozáshoz?

✍️ *Kidolgozandó.*

### Kinyerhető / beállítható a repeater privát kulcsa?

✍️ *Kidolgozandó.*

### Mit tegyek, ha a repeaterem public key-ének első bájtja ütközik egy másikéval?

✍️ *Kidolgozandó.*

### Mit tegyek, ha a repeaterem „süket" a közeli erős interferencia miatt?

✍️ *Kidolgozandó.*

### Hogyan tehetem a repeateremet megfigyelővé (observer)?

✍️ *Kidolgozandó.*

### Mi az a multibyte támogatás (1-2-3 bájtos advert és üzenet)?

✍️ *Kidolgozandó — haladó téma, lásd az [eredeti szakaszt](https://docs.meshcore.io/faq/#39-q-what-is-multibyte-support-what-do-1-byte-2-byte-3-byte-adverts-and-messages-mean).*

## 4. T-Deck és társai

### Van felhasználói kézikönyv T-Deckhez, T-Pagerhez, T-Watch-hoz?

✍️ *Kidolgozandó.*

### Hogyan tegyem a T-Decket DFU (firmware-frissítő) módba?

✍️ *Kidolgozandó.*

### Miért nincs műholdas (GPS) fix a T-Deckemen?

✍️ *Kidolgozandó (a Plus és a sima T-Deck külön eset).*

### Mekkora SD-kártyát támogat a T-Deck?

✍️ *Kidolgozandó.*

### Hogyan kerülnek térképek a T-Deckre? Hová másoljam a csempéket?

✍️ *Kidolgozandó.*

### Hogyan halkítható / testreszabható a hangjelzés?

✍️ *Kidolgozandó.*

### Hogyan adhatok hozzá csomópontot kézzel (Import from Clipboard)?

✍️ *Kidolgozandó.*

### Hogyan készítek képernyőképet a T-Decken?

✍️ *Kidolgozandó.*

## 5. Általános kérdések

### Mit jelent a BW, SF és CR?

✍️ *Kidolgozandó — a LoRa rádióparaméterek: sávszélesség (bandwidth),
spreading factor és coding rate.*

### A kliensek (companionök) ismételnek?

✍️ *Kidolgozandó.*

### Hogyan talál útvonalat egy csomópont a célhoz? Miben más ez, mint a Meshtastic floodolása?

✍️ *Kidolgozandó — ez a MeshCore egyik legfontosabb megkülönböztető képessége.*

### Mindig floodolnak a publikus csatornák? És a privátok?

✍️ *Kidolgozandó.*

### Mi az alapértelmezett publikus csatorna kulcsa?

✍️ *Kidolgozandó.*

### Nyílt forráskódú a MeshCore?

Igen, MIT licenc alatt: [github.com/meshcore-dev/meshcore](https://github.com/meshcore-dev/meshcore).

### Hogyan támogathatom a MeshCore-t?

✍️ *Kidolgozandó.*

### Hogyan fordíthatom le a firmware-t forrásból?

✍️ *Kidolgozandó.*

### Támogatja a MeshCore az ATAK-ot?

✍️ *Kidolgozandó.*

### Hogyan kerülhet fel a csomópontom a [MeshCore térképre](https://map.meshcore.io)?

✍️ *Kidolgozandó — a magyar térképhez lásd: [mc868.hu](https://mc868.hu).*

### Van Windows/Mac kliensalkalmazás?

✍️ *Kidolgozandó.*

## 6. Hibaelhárítás

### A kliensem szerint egy csomópont „sok-sok napja" volt utoljára látható

✍️ *Kidolgozandó.*

### Nem jelenik meg egy elvárt repeater/kliens/room server a listámban

✍️ *Kidolgozandó.*

### Hogyan csatlakozzak repeaterhez Bluetooth-on (BLE)?

✍️ *Kidolgozandó.*

### Nem látszik a companionöm Bluetooth-on / mi a párosítási kód?

✍️ *Kidolgozandó.*

### A Heltec V3 folyton bontja a Bluetooth-kapcsolatot

✍️ *Kidolgozandó.*

### Hogyan törölhetem teljesen a RAK/T1000-E/XIAO nRF52 eszközömet?

✍️ *Kidolgozandó.*

### A WebFlasher Linuxon „failed to open" hibát ad

✍️ *Kidolgozandó.*

## 7. Egyéb kérdések

### Hogyan frissítsem az nRF-alapú eszközök firmware-ét OTA (DFU app)?

✍️ *Kidolgozandó.*

### Hogyan frissítsem az ESP32-alapú eszközöket OTA?

✍️ *Kidolgozandó.*

### Hogyan csökkenthető a sikertelen OTA-frissítés esélye?

✍️ *Kidolgozandó.*

### Elérhető a MeshCore logó és betűtípus?

✍️ *Kidolgozandó.*

### Mi a kontakt/csatorna QR-kód formátuma?

Lásd: [QR-kódok](referencia/qr-kodok.md).

### Hogyan csatlakozzak a companionhöz Wi-Fi-n (pl. Heltec V3)?

✍️ *Kidolgozandó.*

### Mekkora adóteljesítményt állítsak a Station G2 / Heltec V4 / EByte E22 modulos rádiókon?

✍️ *Kidolgozandó — fontos! A túl nagy beállított érték torzítást és
„süketséget" okozhat.*
