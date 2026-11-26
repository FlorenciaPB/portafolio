# 📱 Portafolio Digital — Taller de Interfaces

Portafolio web interactivo diseñado con la estética retro metálica de un **Nokia 6630** para reunir y presentar las entregas del curso **Taller de Interfaces** de la carrera de **Ingeniería Civil en Diseño** en la **Universidad Adolfo Ibáñez (UAI)**.

---

## 🎮 Funcionamiento e Interfaz

La navegación del portafolio replica la interacción física de un teléfono móvil clásico:

- **Teclado Numérico (`1` al `0`):** Cada tecla muestra en la pantalla digital la ficha técnica de una entrega (número, título y breve descripción).
- **Botón Central (`OK`):** Abre el proyecto seleccionado dentro de un visor integrado a pantalla completa con permisos para cámara, micrófono, Web Serial y WebXR.
- **Barra de Retorno (`← Volver al Celular`):** Permite regresar directamente al teléfono desde cualquier entrega abierta (también disponible mediante la tecla `Esc` o apertura en pestaña externa).
- **Teclas Especiales:**
  - `*`: Vuelve a la pantalla principal de bienvenida del portafolio.
  - `#`: Despliega el índice rápido de entregas asignadas.
- **Soporte de Teclado Físico y Sonido:** Compatible con teclas numéricas (`0`–`9`), `Enter` / `Espacio` para confirmar, `Esc` para cerrar el visor y tonos retro generados en tiempo real mediante **Web Audio API**.

---

## 🗂️ Mapa de Teclas y Entregas

| Tecla | Entrega | Proyecto | Enlace / Ruta |
| :---: | :--- | :--- | :--- |
| **1** | Entrega N° 1 | **Lámina de Análisis de Interfaces** — Identificación y clasificación visual de entradas (*inputs*) y salidas (*outputs*) de un electrodoméstico cotidiano (Tostadora). | `entrega1/index.html` |
| **2** | Entrega N° 2 | **Edición de Sonido & Web Interactiva** — Experiencia web lúdica donde el sonido procesado en DAW actúa como eje central de interacción. | `entrega2/index.html` |
| **3** | Entrega N° 3 | **Síntesis y Control Sonoro en Max/MSP** — Parche de síntesis de audio y manipulación de muestras en tiempo real configurado en *Presentation Mode*. | `entrega3/index.html` |
| **4** | Entrega N° 4 | **Sonificación de Datos e Imágenes** — Traducción de información visual (RGB / píxeles) a parámetros sonoros mediante HTML5 Canvas y Web Audio API. | `entrega4/index.html` |
| **5** | Entrega N° 5 | **Controlador Físico en Arduino** — Controlador impreso en 3D con potenciómetro y pulsador conectado vía Web Serial a un juego musical web. | [Ver proyecto](https://florenciapb.github.io/Entrega1ControladorFisico/) |
| **6** | Entrega N° 6 | **Sistema Interactivo: Faro de Alertas en Morse** — Traducción de reconocimiento de voz a código Morse mediante Web Serial y tira LED WS2812 en Arduino Uno. | [Ver proyecto](https://florenciapb.github.io/Entrega2SistemaInteractivo/) |
| **7** | Entrega N° 7 | **Realidad Virtual & Paisajes 360°** — Experiencia inmersiva WebXR en A-Frame con teletransportadores activados por mirada (*gaze*). | [Ver proyecto](https://florenciapb.github.io/realidadvirtualpaisajes/) |
| **8** | Entrega N° 8 | **Cortadora de Fruta con MediaPipe** — Juego web controlado por detección de movimiento y gestos corporales en tiempo real mediante cámara. | [Ver proyecto](https://florenciapb.github.io/cortadoradefruta.medipipe/) |
| **9** | Entrega N° 9 | **Concurso Chile Re-descubre (Memorice Chinchorro)** — Juego educativo interactivo sobre la cultura Chinchorro y patrimonio arqueológico. | [Ver proyecto](https://florenciapb.github.io/concursoChileRe-descubre/) |
| **0** | Entrega N° 10 | **Realidad Aumentada con AR.js** — Superposición de contenido 3D en tiempo real sobre marcador NFT personalizado en A-Frame y AR.js. | [Ver proyecto](https://florenciapb.github.io/Ar.js/) |

---

## 🛠️ Tecnologías Utilizadas

- **Estructura y Estilos:** HTML5, CSS3 (degradados metálicos, sombras en relieve y diseño responsivo) y tipografía *Fredoka*.
- **Interactividad y Audio:** JavaScript (ES6+) y **Web Audio API** para síntesis de tonos DTMF/retro sin archivos externos.
- **Integración de Entregas:** Visor `<iframe>` con atributos `allow="camera; microphone; serial; xr-spatial-tracking; fullscreen"` para ejecutar proyectos de hardware, visión artificial y WebXR dentro del mismo entorno.
- **Despliegue:** GitHub Pages.

---

## 📁 Estructura del Repositorio

```text
├── index.html          # Interfaz principal del Nokia 6630 y lógica de navegación
├── entrega1/           # Archivos de la Entrega N° 1 (Lámina de Análisis)
├── entrega2/           # Archivos de la Entrega N° 2 (Edición de Sonido)
├── entrega3/           # Archivos de la Entrega N° 3 (Max/MSP)
├── entrega4/           # Archivos de la Entrega N° 4 (Sonificación)
└── README.md           # Documentación del portafolio
