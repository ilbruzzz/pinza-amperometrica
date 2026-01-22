# pinza-amperometrica
Energy Monitor IoT open source. Stack: ESP8266, sensore CT, ESPHome e Home Assistant. Repository con codice sensore e interfaccia grafica per la visualizzazione del consumo istantaneo, totale giornaliero e costo in tempo reale.

## Necessario
- 1 ESP8266
- 1 condensatore 10μF (Elettrolitico)
- 2 resistenze 10kΩ
- Pinza amperometrica YHDC SCT-013
- Cavi jumper

## Scelta della pinza ampeometrica
Il dimensionamento del sensore di corrente è stato effettuato cercando il miglior compromesso tra range di misurazione e risoluzione. Per un'utenza domestica standard con contratto di fornitura da 3 kW, le correnti in gioco raramente superano i 16-20 Ampere. L'utilizzo di un sensore con fondo scala a 100A avrebbe ridotto la sensibilità ai bassi carichi. Pertanto, la scelta è ricaduta sul modello SCT-013-030 (range 0-30A, output 0-1V), che garantisce un'elevata accuratezza nella lettura dei consumi ridotti tipici dell'abitazione, mantenendo comunque un margine di sicurezza per carichi fino a circa 6,9 kW.

