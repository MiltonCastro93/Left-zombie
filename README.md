<h1 align="center">🧟‍♂️ Left Zombies</h1>

<p align="center">
  <i>Proyecto en desarrollo — Unreal Engine 5 | Blueprint System | Inspirado en el modo Zombies de Call of Duty</i>
</p>

---

## 🎮 Descripción General

**Left Zombies** es un proyecto desarrollado completamente en **Unreal Engine 5**, utilizando **Blueprints desde cero** para construir la base jugable, los sistemas de animación y la lógica del personaje principal.  
Inspirado en el clásico modo **Zombies de Call of Duty**, este prototipo busca recrear su atmósfera, pero incorporando **nuevas mecánicas de trampas, torretas y objetos de soporte**.

El objetivo final es ofrecer un sistema de supervivencia dinámico con progresión, armas y eventos aleatorios, manteniendo un equilibrio entre **acción, estrategia y recursos limitados**.

---

## 🧱 Estructura y Contenido

- ⚙️ **Motor:** Unreal Engine 5  
- 🧩 **Lógica:** 100% Blueprints (sin uso de código C++)  
- 🎮 **Protagonista:** Blueprint Character creado desde cero  
- 💥 **Armas:** Integración completa con animaciones e IK funcional  
- 🩸 **Inspiración:** Resident Evil 4 (láser clásico) + Call of Duty Zombies  

---

## 🧠 Sistemas Principales Implementados

### 🧍‍♂️ Blueprint del Personaje
- Creado **desde cero**, con control total del movimiento, cámara y animaciones.  
- Integrado con un **Blueprint Animation** dedicado para manejar el estado del personaje (idle, caminar, correr, disparar, etc.).  
- Implementación de **IK (Inverse Kinematics)** para alinear correctamente las manos con el arma.  
- Pruebas exitosas de **soldadura del arma a la mano** mediante sockets y animaciones personalizadas.

---

### 🔫 Sistema de Armas y Efectos
- Arma funcional con **efecto láser tipo Resident Evil 4 clásico**, aplicado mediante materiales y niagara VFX.  
- Sincronización del disparo, retroceso y animaciones de movimiento del personaje.  
- Preparado para soporte de múltiples armas a futuro (rifles, escopetas, armas especiales).

---

### ⚒️ Objetos Interactivos y Props
- **Baúl y cruz modelados desde cero**, con texturas originales y animaciones integradas.  
- **Baúl animado** con apertura funcional mediante Blueprint y timeline.  
- **Cruz** integrada al sistema de partículas para representar **curación o protección temporal**.  
- Sistema aleatorio de aparición de ítems al eliminar enemigos (curación o escudo extra).

---

### 💡 Sistemas planeados
El proyecto se encuentra en desarrollo activo, con los siguientes sistemas planificados:

- 🧟‍♀️ **Inteligencia artificial de zombies** (spawns, oleadas y comportamiento).  
- 💰 **Sistema de economía** para comprar armas, trampas y torretas.  
- ⚙️ **Trampas de piso y defensas automáticas** activables por el jugador.  
- 🔄 **Gestión de rondas** con dificultad progresiva y eventos dinámicos.  
- 🧍‍♂️ **HUD avanzado** con contador de zombis, salud y energía.  

---

## 🧩 Enfoque técnico

**Left Zombies** sirve como una base sólida para la implementación de mecánicas avanzadas en Unreal Engine usando únicamente Blueprints.  
Entre las áreas de aprendizaje y aplicación se destacan:

- Diseño y organización modular de Blueprints.  
- Creación de **Animation Blueprints** personalizados.  
- Aplicación práctica de **IK (Inverse Kinematics)** y sockets.  
- Integración de **VFX y partículas** con lógica de eventos.  
- Modelado básico y texturizado de assets propios (baúl y cruz).  
- Balance entre rendimiento y legibilidad visual en los gráficos.  

---

## 🖼️ Capturas del Proyecto

<p align="center">
  <img src="https://github.com/MiltonCastro93/Left-zombie/blob/main/Captura%20de%20pantalla%202025-11-11%20120200.png" width="400" style="border-radius:10px; margin:5px;"/>
  <img src="https://github.com/MiltonCastro93/Left-zombie/blob/main/Captura%20de%20pantalla%202025-11-11%20120113.png" width="400" style="border-radius:10px; margin:5px;"/>  
  <img src="https://github.com/MiltonCastro93/Left-zombie/blob/main/Captura%20de%20pantalla%202025-11-11%20120132.png" width="400" style="border-radius:10px; margin:5px;"/>
  <img src="https://github.com/MiltonCastro93/Left-zombie/blob/main/Captura%20de%20pantalla%202025-10-16%20221308.png" width="400" style="border-radius:10px; margin:5px;"/>
  <img src="https://github.com/MiltonCastro93/Left-zombie/blob/main/Captura%20de%20pantalla%202025-10-16%20221632.png" width="400" style="border-radius:10px; margin:5px;"/>  
  <img src="https://github.com/MiltonCastro93/Left-zombie/blob/main/Captura%20de%20pantalla%202025-10-16%20221650.png" width="400" style="border-radius:10px; margin:5px;"/>
  <img src="https://github.com/MiltonCastro93/Left-zombie/blob/main/Captura%20de%20pantalla%202025-11-11%20133208.png" width="400" style="border-radius:10px; margin:5px;"/>  
  <img src="https://github.com/MiltonCastro93/Left-zombie/blob/main/Captura%20de%20pantalla%202025-11-11%20133614.png" width="400" style="border-radius:10px; margin:5px;"/>
</p>

📺 Video Preview
<p align="center"> <a href="https://www.youtube.com/watch?v=ZZgoD3Js_xs&t=1s" target="_blank"> <img src="https://img.youtube.com/vi/ZZgoD3Js_xs/hqdefault.jpg" width="480" style="border-radius:10px;"/> </a> <br> <sub>👉 Click en la imagen para ver el video en YouTube</sub> </p>

---

## 🧰 Herramientas Utilizadas

- **Unreal Engine 5**
- **Blueprint Visual Scripting**
- **Audacity** (procesado de sonidos)
- **VFX Niagara** (efectos de partículas)

- **Blender**
> Baul (Modelado, Rig, Texturizado)
> Cruz (Modelado)

---

## 🚧 Estado del Proyecto

🧩 **En desarrollo (fase prototipo)**

- [x] Sistema de personaje y animaciones base  
- [x] Arma funcional con IK y efecto láser  
- [x] Props modelados y animados (baúl y cruz)  
- [ ] IA de zombies y rondas  
- [ ] Sistema de trampas y torretas  
- [ ] HUD y economía del jugador  
- [ ] Balance y optimización general  

---

## 👤 Autor

**Milton Denis Castro**  
📍 Buenos Aires, Argentina  
- 💼 [GitHub](https://github.com/MiltonCastro93)  
- 🎮 [Itch.io](https://milton93.itch.io/)  
- ✉️ [miltondeniscastro.1993@gmail.com](mailto:miltondeniscastro.1993@gmail.com)

---

## 📘 Notas Finales

**Left Zombies** representa una evolución en el uso avanzado de **Blueprints** dentro de Unreal Engine, combinando sistemas de interacción, props animados y lógica de combate.  
El proyecto continúa en desarrollo, con el foco en optimizar el rendimiento y expandir las mecánicas hacia un entorno de supervivencia completo y rejugable.

---
