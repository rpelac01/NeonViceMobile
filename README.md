# Neon Vice

Un simulador de vida progresivo y adictivo para navegadores móviles. Construido en una arquitectura ligera de un solo archivo (HTML5, Vanilla JS, Tailwind CSS) y renderizado táctil mediante Canvas.

## Características Implementadas

*   **Motor Móvil Nativo:** 
    *   Interfaz *Mobile-First* con barra de navegación inferior adaptada a los gestos del sistema operativo (`safe-area-inset-bottom`).
    *   Sistema de modales en pantalla completa (`100dvh`) bloqueando el scroll para una experiencia de app nativa.
    *   Persistencia de datos local mediante `localStorage` para proteger el progreso.
*   **18 Minijuegos Temáticos y Únicos:**
    *   Mecánicas táctiles diseñadas a medida para cada trabajo (gestos, sincronización, trazados).
    *   Curva de dificultad balanceada para ser accesible a jugadores jóvenes (márgenes de error generosos, eliminación de "muertes súbitas", físicas perdonables).
*   **Mercado Financiero Realista (Nivel 5):**
    *   Gráficos interactivos generados con Chart.js.
    *   Simulación de precios basada en Movimiento Browniano Geométrico (Random Walk) con diferentes perfiles de riesgo (Crypto, SP500, Meme Coins).
    *   Gestión de portafolio y cálculos de PnL en tiempo real.
*   **Casino Inmersivo (Nivel 10):**
    *   **Casino Hold'em:** Mesa 3D contra el crupier (Ante/Flop/Call/Fold) con evaluación matemática de la mejor mano.
    *   **Ruleta:** UI vertical estilo máquina de bar con visor animado de la bola y tapete completo de apuestas.
    *   **Tragaperras "Ice Queen":** Estética de neones y hielo, cuadrícula 5x3 con símbolos "Wild", líneas de pago dinámicas y animaciones de premios.
    *   **Mus:** Baraja española, enfrentamientos contra la IA y sistema de interfaz mediante bocadillos de diálogo interactivos.
*   **Negocios e Inmobiliaria (Nivel 15):**
    *   Catálogo de propiedades y negocios locales comprables.
    *   Generación de ingresos pasivos calculados por tiempo real (`marketSync`), incluyendo acumulación offline con topes máximos de horas para equilibrar la economía.

## Futuras Actualizaciones

*   **Submundo y Mafia (Nivel 20):** Implementación de la rama delictiva (`gameState.mafia`) con sistemas de dinero negro, nivel de búsqueda policial ("Heat") y operaciones de blanqueo de capitales.
*   **Sistema de Logros:** Recompensas pasivas por alcanzar hitos en los minijuegos o amasar ciertas fortunas.
*   **Eventos Aleatorios:** Sucesos dinámicos en la vida del personaje (enfermedades, crisis económicas, loterías) que obliguen a adaptar la estrategia financiera de emergencia.
