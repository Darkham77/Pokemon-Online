# Pokémon Online (Versión Web)

Un simulador de combates, colección y mundo abierto basado en Pokémon, construido con HTML, CSS, JavaScript y Supabase para funciones multijugador en tiempo real.

## 🚀 Funcionalidades Principales

* **Sistema de Combate por Turnos**: Lucha contra entrenadores (NPCs), Pokémon salvajes y líderes de gimnasio usando movimientos con tipos y eficacias (súper eficaz, poco eficaz), efectos de estado (veneno, quemadura, sueño) y cambios en estadísticas.
* **Captura y Colección**: Captura Pokémon salvajes en diferentes biomas (Ruta 1, Bosque Verde, Cueva Oscura, Isla Espuma) y mételos en tu equipo de 6 o mándalos a la Caja del PC (hasta 100 Pokémon).
* **Mochila y Objetos**: Compra objetos en la Tienda (Pociones, Antídotos, Curas Totales, Revivir, Piedras Evolutivas) y úsalos en combate o desde el menú sobre tu equipo.
* **Evoluciones**: Evoluciona a tus Pokémon al alcanzar ciertos niveles de experiencia o mediante el uso de Piedras Evolutivas.
* **Sistema de Amigos**: Busca a otros entrenadores, mándales solicitud de amistad y chequeá cuándo están conectados usando el sistema de chat en vivo con Supabase (Realtime).
* **Intercambios (Trades)**: Ofrece dinero, objetos, e incluso tus propios Pokémon a tus amigos a través de un sistema de ventana de intercambio interactiva.
* **Batallas PvP en Tiempo Real**: Desafía a tus amigos a un combate 1 contra 1. La batalla se lleva a cabo directamente en tiempo real gracias a WebSockets de Supabase, respetando turnos, daño, cambios y animaciones como si estuvieras jugando contra la PC.
* **Sistema de Guardado Automático y en la Nube**: Tu progreso (dinero, inventario, equipo, Pokedex e historial) se guarda en la nube vinculado a tu usuario en Supabase, permitiendo que recuperes tu partida en cualquier momento.

## 🛠 Instalación y Uso

1. **Clonar el proyecto**
   ```bash
   git clone https://github.com/Darkham77/Pokemon-Online.git
   ```
2. **Abrir el juego**
   Simplemente tienes que abrir el archivo `index.html` en tu navegador web de preferencia (se recomienda Google Chrome, Edge o Firefox). Al usar Supabase por detrás, no se requiere ningún servidor local para que el juego y los datos de la nube funcionen.

## 🆕 Novedades de la última versión

*   **🏆 Mejora en Gimnasios**: Se han corregido los sprites de los líderes (Brock, Misty, etc.) y se ha añadido el fondo oficial `GIMNASIO.jpg` para todos los desafíos.
*   **⚔️ Batallas Premium**: Ahora los combates se muestran en una **ventana modal** más inmersiva con fondo desenfocado. Los sprites de los Pokémon son un **100% más grandes** para una mejor visualización.
*   **🌅 Fondos Dinámicos PVP**: Los combates contra otros jugadores ahora cuentan con fondos que cambian según el ciclo del día (`Mñana`, `Día`, `Noche`).
*   **🐞 Corrección de Bugs**:
    *   Se solucionó el problema donde el badge de notificaciones de amigos no se limpiaba al abrir la pestaña.
    *   Se corrigió el error de bloqueo en batalla que ocurría tras curar a todo el equipo debilitado.

---

¡Atrápalos a todos!
