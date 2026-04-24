# BRAVE LEON — Tarjeta AR/XR

App de Realidad Aumentada con ARnft.js.  
Superpone un video de presentación/portafolio sobre el frente de la tarjeta de negocios.

## URL del sitio
```
https://axelgvillagomez.github.io/brave-leon
```

## Cómo usar en el celular
1. Abre **Google Chrome**
2. Entra a la URL de arriba (o escanea el QR del reverso de la tarjeta)
3. Permite acceso a la cámara
4. Apunta al **frente de la tarjeta** — el video se superpone sobre ella

## Estructura
```
brave-leon/
├── index.html              ← App AR (GitHub Pages)
├── config.json             ← Config ARnft
├── tarjeta.html            ← Tarjeta imprimible (frente + reverso)
├── brave_leon_card.jpg     ← Marcador (frente de la tarjeta)
├── portfolio.mp4           ← Video de portafolio (sin audio, loop)
├── qr_brave_leon.png       ← QR para el reverso
├── nft/                    ← Archivos de características del marcador
├── css/  js/  data/        ← Librerías ARnft + Three.js
└── README.md
```
