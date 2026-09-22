# El Rastro de Casiopea

Entrega de la práctica de **Realidad y Accesibilidad Aumentadas** — Universidad de Oviedo, curso 2025/2026.

> Una aventura espacial de tres mundos para recomponer una constelación perdida, estrella a estrella.

## 📖 Descripción

En algún punto del espacio, la constelación de Casiopea ha desaparecido del cielo nocturno. Como astronauta encargado de investigar, junto a tu compañero Ori emprenderás un viaje por tres mundos para descubrir qué ha ocurrido y devolverle su luz al firmamento.

Comienza la misión en la **Luna**, donde conocerás la historia detrás de la desaparición. Continúa en **Marte**, sorteando un recorrido de rocas flotantes y poniendo a prueba tus conocimientos ante los NPCs alienígenas del planeta rojo. Termina el viaje en el gélido **Neptuno**, explorando entre el hielo para recuperar los 5 fragmentos dispersos de Casiopea, antes de devolverle por fin su brillo al cielo en la escena final.

Juego desarrollado en **Delightex (CoSpaces)**, programado íntegramente con **CoBlocks**.

## 🎮 Jugar

**URL del proyecto:** https://edu.delightex.com/GKU-YBS

**Código QR:**

![QR del proyecto](qr.png)

Para jugar en modo **Realidad Aumentada (RA)** o **Realidad Virtual (RV)**, abre la URL o escanea el QR desde la app móvil **Delightex** (disponible en iOS y Android) y selecciona el modo correspondiente desde el propio visor.

## 🌌 Estructura del juego

| Escena | Tipo | Contenido |
|---|---|---|
| Luna | Narrativa | Introducción a la historia, animaciones ambientales en paralelo |
| Marte | Exploración / reto | Parkour sobre rocas flotantes, NPCs alienígenas con panel de preguntas |
| Neptuno | Recolección | Búsqueda de los 5 fragmentos de Casiopea, contador y diálogo final |
| Victoria | Cinemática | Escena sin intervención del jugador, con cambios de cámara, que cierra la historia |

## 🧩 Aspectos técnicos (CoBlocks)

- Animaciones ambientales simultáneas mediante bloques de ejecución en paralelo.
- Variable/contador compartido para la mecánica de recolección de fragmentos, con comprobación condicional que desencadena el diálogo final.
- Diálogos programados entre personajes (Ori, Casiopea, NPCs de Marte) con paneles de interacción.
- Escena cinemática final con múltiples cámaras y cambios de plano, sin intervención del jugador.
- Sonidos y música ambiente diferenciados por escena.

## 🎬 Vídeo de la entrega

Gameplay completo + explicación del diseño y la programación:

**(pendiente — se añade el enlace de YouTube aquí)**

## 📂 Contenido de este repositorio

- `qr.png` — código QR del proyecto Delightex.
- `capturas-diseño/` — capturas del diseño narrativo en papel (si aplica).
- Este `README.md`.

## 👤 Autor

*(tu nombre)* — Grado en Ingeniería Informática del Software, Universidad de Oviedo.
