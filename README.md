# Matekvarázs AR

Magyar nyelvű, böngészőben futó AR matematika-játék 1–2. osztályos gyerekeknek.

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/arlinamid/MathAR-experimental)

## Funkciók

- MediaPipe kézkövetés
- ujjakkal megadható válaszok
- mutatóujjas AR választás
- karikázás, sorbarendezés és rajzolás
- 1. osztály: 20-as számkör
- 2. osztály: 100-as számkör
- gyerekbarát kézkövetési nézet csontvázrajz nélkül

## Render

A repository tartalmaz `render.yaml` Blueprint konfigurációt. A fenti **Deploy to Render** gombbal egy kattintással elindítható a telepítés. Alternatív megoldásként Renderen válaszd a **New → Blueprint** lehetőséget, csatlakoztasd ezt a repót, majd alkalmazd a Blueprintet.

A statikus oldal HTTPS-en fut, így a kameraengedély működik támogatott böngészőkben. A MediaPipe könyvtár és a Hand Landmarker modell CDN-ről töltődik be.
