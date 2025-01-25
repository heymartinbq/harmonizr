# Harmonizer 🌟

[![License: MIT](https://img.shields.io/badge/License-MIT-gold.svg)](https://opensource.org/licenses/MIT)
![Neuroceptive Engine](https://img.shields.io/badge/Dynamics-Emotional_Resonance-38BDF8.svg)
![Fractal Versioning](https://img.shields.io/badge/Release-Φ1.618-9cf.svg)

**Sistema de Visualización de Emociones Dinámicas**  
*Interfaz Neuroceptiva basada en Principios Áureos*

```bash
    git clone https://github.com/heymartinbq/harmonizr.git
    <img src="preview.gif" width="100%" alt="Dynamic Emotion Interface">
```

##🌈 Características Principales
Mapa Emocional Cuántico
Estructura Holográfica (JSON Multidimensional)

### 4 Dimensiones Emocionales:

- 🌿 Protección (Mecanismos adaptativos)
- 🌈 Conexión (Estados positivos)
- ⚡ Alerta (Respuestas inmediatas)
- 🌫️ Mixtas (Transiciones emocionales)

### Parámetros por Emoción:

- Frecuencia de resonancia (0.3Hz - 10.0Hz)
- Color HSL dinámico
- Patrón cardíaco (Sístole/Diástole)
- Parámetros neuroceptivos (Tono vagal, Coherencia cortical)

## Sistema de Renderizado Dinámico

- Motor CSS Cuántico:
- Variables basadas en Φ (1.618)
- Transformaciones 3D fractales
- Animaciones fluidas con curvas de Bezier dinámicas
- Efectos de partículas cuánticas

## Neurocepción Interactiva

### Clases Principales:

- **NeuroceptiveManager:** Carga y normaliza el mapa emocional
- **EmotionalHarmonizer:** Control central de armonización
- **CardioSystem:** Simulación de ritmo cardíaco adaptativo

## Modos de Operación:

- Auto-resonancia emocional
- Selección manual de estados
- Modo de baja energía


## 🚀 Instalación
```bash
    npm install @heymartinbq/harmonizer
```

### Requisitos:
- Node.js 18+
- Navegadores modernos con WebGL 2.0

###💡 Uso Básico

```javascript
    import { NeuroceptiveManager, EmotionalHarmonizer } from '@heymartinbq/harmonizer';

    // Inicialización del sistema
    const emotionLoader = new NeuroceptiveManager();
    await emotionLoader.loadEmotionalMap();

    const harmonizer = new EmotionalHarmonizer(emotionLoader);

    // Activar estado de conexión
    harmonizer.setQuantumEmotion('euforia', {
    intensity: 0.9,
    coherence: 1.618
    });

    // Conectar a elementos del DOM
    document.querySelector('#emotionSelector')
    .addEventListener('change', (e) => {
        harmonizer.setQuantumEmotion(e.target.value);
    });
```

## 🎨 Selector de Emociones 

```html
    <select id="emotionSelector">
    <optgroup label="🌈 Conexión">
        <option value="euforia">🎊 Euforia (9.5Hz)</option>
        <option value="gratitud">🙏 Gratitud (5.0Hz)</option>
        <option value="intimidad">💞 Intimidad (4.8Hz)</option>
    </optgroup>
    <optgroup label="🚀 Energía Vital">
        <option value="entusiasmo">🚀 Entusiasmo (7.2Hz)</option>
        <option value="inspiracion">💡 Inspiración (5.5Hz)</option>
    </optgroup>
    <optgroup label="🌟 Asombro">
        <option value="maravilla">🌠 Maravilla (5.8Hz)</option>
        <option value="esperanza">🕊️ Esperanza (1.5Hz)</option>
    </optgroup>
    </select>
```

## 🧠 Fundamentos Científicos

### El sistema implementa:

- **Modelo de Resonancia Cardíaca** (Proporción áurea sístole/diástole)
- **Teoría Polivagal** (Parámetros neuroceptivos)
- **Dinámica Fractal** (Patrones de transformación CSS)
- **Psicofísica del Color** (Mapeo HSL de frecuencia emocional)
- **Ecuación principal de resonancia:**

```math
    H(t) = A ⋅ e^{-βt} ⋅ sin(2πft + ϕ)
```

### Donde:

- **A = ** intensidad ⋅ Φ
- **f = ** frecuencia emocional
- **ϕ = ** fase neuroceptiva

## 📚 Estructura del Proyecto

```bash
    Harmonizer/
    ├── data/
    │   └── emotionMap.json       # Mapa emocional completo
    ├── docs/
    │   └── neuroception.md       # Documentación técnica
    ├── src/
    │   ├── NeuroceptiveManager.js # Cargador de emociones
    │   ├── EmotionalHarmonizer.js # Núcleo de armonización
    │   └── CardioSystem.js       # Simulación cardíaca
    └── examples/
        └── basic-interface.html  # Demo interactivo
```

## 🤝 Contribución

- Clona el repositorio
- Crea una rama para tu feature:

```bash

    git checkout -b feature/nueva-emocion
    Añade emociones al JSON siguiendo el esquema:
```

```json
    {
        "id": "conexion",
        "name": "🌈 Conexión",
        "subcategories": [
          {
            "id": "celebracion",
            "name": "🎉 Celebración",
            "emotions": [
              {
                "id": "euforia",
                "name": "Euforia",
                "function": "Éxtasis por metas alcanzadas",
                "intensity": "alta",
                "frequency": "9.5Hz",
                "colorHue": 342,
                "resonance": {
                  "systole": 1.618,
                  "diastole": 1.0
                },
                "neuroception": {
                  "dopaminergicFlow": 0.9,
                  "vagalBoost": 0.7,
                  "corticalCoherence": 0.8
                },
                "ariaLabel": "euforia",
                "icon": "🎊"
              },
              {
                "id": "gratitud",
                "name": "Gratitud",
                "function": "Reconocimiento de lo recibido",
                "intensity": "media",
                "frequency": "5.0Hz",
                "colorHue": 180,
                "resonance": {
                  "systole": 1.0,
                  "diastole": 1.618
                },
                "neuroception": {
                  "vagalTone": 0.8,
                  "thalamicSynchronization": 0.6,
                  "corticalIntegration": 0.7
                },
                "ariaLabel": "gratitud",
                "icon": "🙏"
              }
            ]
          },
        ]
    }
```
Envía un Pull Request

📄 Licencia
MIT License - Ver LICENSE para más detalles.

### Contacto

- **Autor**: Martín Batalla
- **Alias**: [@heymartinbq](https://github.com/heymartinbq)
- **Título**: Creative Developer
- **Bio**: *"Mi forma de vida: IMAGINACIÓN, ¿hay algún límite?"*
- **Contacto**:
  - 📧 Email: [themartinbq@gmail.com](mailto:themartinbq@gmail.com)
  - 🧵 Threads: [@heymartinbq](https://www.threads.net/@heymartinbq)
- **☕ Invítame un café**: [buymeacoffee.com/heymartinbq](https://www.buymeacoffee.com/heymartinbq)
