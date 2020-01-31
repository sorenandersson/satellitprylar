# Satellitprylar

Lathund för Fossasat.
En groundstation för Fossasat är busenkel att bygga. En ESP32, en OLED samt en LORA krets. Allt kopplas ihop med 8 trådar. Komplettera med några avkopplingskondingar sen är det klart.
Programvaran finns här: https://github.com/G4lile0/ESP32-OLED-Fossa-GroundStation.

På samma plats finns  också info om hur man konfigurerar och får inloggningsuppgifter till MQTT server för satellitdata.
Bygger man enligt schemat nedan ska man under konfigurationen välja ”Heltec LORA 32 V1”.

Tyvärr fungerar inte Fossasat-1 som tänkt utan vi får vänta till framåt sommaren då Fossasat-1B och Fossasat-2 skjuts upp. Under tiden kan man testa sin konstruktion med en simulator.
Den är ännu enklare att bygga. En Arduino328P en LORA och 6 trådar.
Programvaran till simulatorn finns här: https://github.com/FOSSASystems/FOSSASAT-1/tree/master/Code/Simulator.
Varför ska man då bygga allt detta? Ingen aning egentligen annat än att det är kul. Man får en liten kick när man ser att ens simulerade data dyker upp i flödet på servern med Fossasat data.
Registrerade groundstations kan man se här: https://fossa.apaluba.com/worldmap/

Så här kan en groundstation se ut.

<img src="https://github.com/sorenandersson/satellitprylar/blob/master/Groundstation.jpg" width="75%" height="75%" />

Simulatorn

<img src="https://github.com/sorenandersson/satellitprylar/blob/master/Simulator.jpg" width="75%" height="75%" />


