Ronin Simulator VR

Proyecto: Experiencia VR interactiva de un samurái forjando y usando su katana.

Tecnologías utilizadas:

HTML5

A-Frame 1.5.0
 (WebVR/WebXR)

Modelos GLTF (.gltf) para el samurái, katana y escenarios

Sonidos en formato .mp3

Estructura del proyecto
/ (raíz)
│─ index.html                  # Página principal
│─ escena-360.html              # Escena de la aldea 360º
│─ escena-proceso.html          # Escena del proceso de forja
│─ escena-resultado.html        # Escena final del samurái con katana
│─ assets/
│   ├─ 360/
│   │   └─ fondo360.jpg         # Imagen 360 del fondo
│   ├─ models/
│   │   ├─ samurai/
│   │   │   └─ scene.gltf
│   │   ├─ katana/
│   │   │   └─ scene.gltf
│   │   └─ dojo/
│   │       └─ scene.gltf
│   └─ sounds/
│       ├─ ambient.mp3
│       ├─ epic.mp3
│       └─ hit.mp3

Cómo usarlo

Abre index.html en un navegador compatible con WebVR/WebXR (Chrome, Edge, Firefox).

Navega por las escenas:

Escena 1 (Aldea 360º) → portal hacia el dojo

Escena 2 (Forja - Proceso) → interactúa con la katana y prueba efectos

Escena 3 (Samurái - Producto) → observa al samurái con la katana y animación de ataque

Interactúa con los botones:

Golpear metal → activa animaciones y efectos de chispas/onda

Ver producto → lleva a la escena del samurái final

Mostrar ataque → hace que el samurái realice un movimiento de ataque

Notas

La experiencia funciona tanto en navegador de escritorio como en gafas VR compatibles con WebXR.

Todos los modelos deben estar en la carpeta assets/models/ con la misma estructura para que los enlaces funcionen.

Los sonidos deben estar en assets/sounds/ con los nombres indicados.

Ajusta posiciones/rotaciones/escala si tus modelos no se alinean perfectamente en la escena.

Autores

Plácido Chinchilla
Borja Serrano
Antonio Morales