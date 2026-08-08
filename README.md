# Matekvarázs AR

Magyar nyelvű, böngészőben futó AR matematika-játék 1–2. osztályos gyerekeknek.

## Funkciók

- MediaPipe kézkövetés
- ujjakkal megadható válaszok
- mutatóujjas AR választás
- karikázás, sorbarendezés és rajzolás
- 1. osztály: 20-as számkör
- 2. osztály: 100-as számkör
- gyerekbarát kézkövetési nézet csontvázrajz nélkül

## Render

A repository tartalmaz `render.yaml` Blueprint konfigurációt. Renderen válaszd a **New → Blueprint** lehetőséget, csatlakoztasd ezt a repót, majd alkalmazd a Blueprintet. A statikus oldal HTTPS-en fog futni, ezért a kameraengedély működik támogatott böngészőkben.

A MediaPipe könyvtár és a Hand Landmarker modell CDN-ről töltődik be.
