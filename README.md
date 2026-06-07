# Gruvor och bergrum i Uppland

Interaktiv karta över gruvor, bergrum, bunkrar och mineralrättigheter i Uppland.
Kartan är en helt fristående HTML-fil ([`index.html`](index.html)) byggd med [Leaflet](https://leafletjs.com/) – ingen server eller installation behövs, öppna filen i en webbläsare.

## Innehåll

| Lager | Antal | Källa |
|---|---|---|
| Malmgruvor (nedlagda) | ~700 | SGU |
| Kalk-/industrimineralbrott (nedlagda) | ~250 | SGU |
| Stenbrott & täkter (nedlagda) | ~150 | SGU |
| Gruvor/täkter i drift | 49 | SGU |
| Gruvor enligt OSM | ~20 | OpenStreetMap |
| Bergrum & underjordsanläggningar | ~15 | OpenStreetMap + egna efterforskningar |
| Bunkrar & fort | ~50 | OpenStreetMap |
| Skyddsrum | ~25 | OpenStreetMap |
| Mineralrättigheter (polygoner) | 10 | Bergsstaten/SGU |

Funktioner: tändbara lager, sökruta, tre bakgrundskartor (OSM, OpenTopoMap, Esri flygfoto), popup med detaljer och källa för varje objekt.

## Datakällor och licenser

- **SGU – Mineralresurser**: hämtat via [SGU:s öppna data-API](https://api.sgu.se/oppnadata/mineralresurser/ogc/features/v1/collections) (OGC API Features). Licens: [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
- **OpenStreetMap** (bunkrar, fort, bergrum, gruvobjekt): hämtat via Overpass API. © OpenStreetMap-bidragsgivare, licens [ODbL](https://www.openstreetmap.org/copyright).
- **Bergsstaten/SGU – Mineralrättigheter**: undersökningstillstånd och bearbetningskoncessioner, ur SGU:s nedladdningsbara GPKG (urklipp för Uppland i [`mineralratt_uppland.json`](mineralratt_uppland.json)).
- **Kurerade bergrum** (SFR Forsmark, Lurbo, Bålsta, Arlanda): egna efterforskningar utifrån bl.a. [SGU:s sidor om efterbehandling av oljelager](https://www.sgu.se/samhallsplanering/fororenade-omraden/efterbehandling-av-oljelager/). Lägen markerade som ungefärliga där exakt position inte är offentlig.

Bakgrundskartor laddas från respektive tjänst (OSM, OpenTopoMap, Esri) och kräver internetuppkoppling.

## Förbehåll

Datat är ett ögonblicksavläst utdrag (juni 2026) och kan innehålla fel. Gamla gruvhål kan vara farliga – besök på egen risk och respektera privat mark. Kartan är ett hobbyprojekt och inte en officiell produkt från SGU eller Bergsstaten.

## Licens

Kod: MIT. Data: enligt respektive källas licens ovan.
