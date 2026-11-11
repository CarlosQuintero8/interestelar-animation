# 🌌 INTERSTELLAR // Gargantua & The Tesseract (Audio-Reactive WebGL Visualizer)

> *“Do not go gentle into that good night... Rage, rage against the dying of the light.”*

Experiencia visual astrofísica en tiempo real e interactiva inspirada en **Interstellar** (Christopher Nolan, 2014) y sincronizada con la partitura original de **Hans Zimmer** (`Interstellar theme song.mp3`).

Construida íntegramente con **WebGL (GLSL Raymarching Shaders)**, **Web Audio API** y **HTML5 Canvas 2D**, sin dependencias externas.

---

## ✨ Características Principales

### 🕳️ 1. Simulación Relativista de Gargantua (WebGL Shader)
- **Raymarching Geodésico**: Curvatura gravitacional de los rayos de luz alrededor del radio de Schwarzschild ($R_s$) y la esfera de fotones.
- **Disco de Acreción Volumétrico & Efecto Doppler Relativista**: El plasma en rotación kepleriana muestra corrimiento al azul/blanco en el flanco que se aproxima al observador y corrimiento al ámbar/rojo profundo en el flanco que se aleja.
- **Anillo de Einstein & Destello Anamórfico**: Amplificación lumínica del campo estelar de fondo y destellos horizontales inspirados en la fotografía IMAX de Hoyte van Hoytema.

### 🎹 2. Sincronización Musical (Web Audio API FFT)
El motor analiza las frecuencias de `Interstellar theme song.mp3` en tiempo real y las traduce en fenómenos físicos:
- **Subgraves (`20 – 80 Hz`)**: Dilatación del horizonte de sucesos y pulsos de ondas gravitacionales.
- **Graves (`80 – 250 Hz`)**: Densidad térmica y turbulencia del disco de acreción.
- **Medios (`250 – 2000 Hz` — Órgano de Catedral)**: Iluminación de los filamentos relativistas, aceleración del anillo de la nave *Endurance* y espectro simétrico de tubos de órgano en el horizonte inferior.
- **Agudos (`2000 – 12000 Hz`)**: Centelleo estelar profundo y armónicos de la quinta dimensión.

### 🚀 3. Cuatro Modos Escénicos + Narrativa Automática
Puedes dejar que la visualización evolucione sola con la canción o alternar manualmente entre las escenas:
1. **`00 // Auto Narrativo`**: Transición progresiva automática a lo largo de la pista musical.
2. **`01 // Gargantua Singularidad`**: Vista pura del agujero negro supermasivo y su lente gravitacional.
3. **`02 // Acoplamiento (No Time For Caution)`**: Despliega los 12 módulos habitacionales de la nave **Endurance** rotando a **67.8 RPM** con retícula de acoplamiento orbital.
4. **`03 // Agujero de Gusano`**: Modula la métrica espacio-temporal hacia espectros cian e índigo.
5. **`04 // El Teseracto 5D (STAY)`**: Despliega la matriz tridimensional de cuerdas gravitacionales de la quinta dimensión y transmite la anomalía en código Morse **`S · T · A · Y`** (`··· − ·− −·−−`).

### 🛰️ 4. Telemetría de Misión NASA / Endurance
Panel HUD con lecturas dinámicas en vivo:
- **Dilatación Temporal** (*Planeta de Miller*: `1h = 7.00 Años`).
- **Reloj Terrestre Acumulado** en años transcurridos.
- **Velocidad Angular del Endurance (`RPM`)**, radio del horizonte de sucesos (`Rs`) y resonancia en decibelios (`dB`).

---

## 🎮 Controles e Interacción

| Acción | Control |
| :--- | :--- |
| **Orbitar Cámara 3D** | Clic izquierdo + arrastrar con el mouse |
| **Zoom Relativista** | Rueda del mouse (Scroll) |
| **Reproducir / Pausar** | Botón `▶ Reproducir` o tecla **`Espacio`** |
| **Modo Cine (Ocultar HUD)** | Botón `Modo Cine [C]` o tecla **`C`** |
| **Anomalía Gravitacional** | Botón `Pulso "STAY"` (emite onda espacio-temporal + Morse) |
| **Sensibilidad de Audio** | Deslizador `Reactividad` en la consola inferior |

---

## 🛠️ Ejecución Local

1. Clona este repositorio:
   ```bash
   git clone https://github.com/CarlosQuintero8/interestelar-animation.git
   cd interestelar-animation
   ```
2. Abre `index.html` usando un servidor local (por ejemplo, **Live Server** en VS Code, `npx serve .` o `python -m http.server 8000`) para permitir que `Web Audio API` analice el archivo `Interstellar theme song.mp3` sin restricciones CORS de archivos locales.

---

## 👤 Autor

Desarrollado por **[Carlos Quintero (@CarlosQuintero8)](https://github.com/CarlosQuintero8)**.
