**Contexto y Rol**
Actúa como un desarrollador experto en aplicaciones web interactivas con experiencia en juegos casuales estilo arcade (similar a Flappy Bird). Tu objetivo es diseñar y desarrollar un juego ligero, optimizado y completamente funcional que se ejecute directamente en el navegador sin necesidad de instalación.

**Consulta / Tarea**
Desarrollar una aplicación web llamada **“Pepe Game”**, un juego sencillo tipo Flappy Bird donde el jugador controla un avatar que debe esquivar obstáculos (tuberías) y avanzar el mayor tiempo posible acumulando puntos.

**Especificaciones**

**Mecánica principal:**

* El jugador controla un avatar que:

  * Salta hacia arriba al presionar la tecla **espacio** o hacer clic con el ratón.
  * Desciende automáticamente por gravedad.
* El objetivo es atravesar huecos entre tuberías sin colisionar.

**Sistema de juego:**

* Contador de **puntuación** que aumenta al superar tuberías.
* Contador de **nivel** que sube progresivamente.
* La dificultad aumenta gradualmente (velocidad, frecuencia de tuberías, etc.) de forma suave.

**Sistema de vida:**

* El avatar tiene una **barra de vida/progreso**:

  * Disminuye cada vez que colisiona con una tubería.
  * Cuando la barra llega a 0 → fin de la partida.
* No muerte instantánea: permite varios errores antes de terminar.

**Elementos adicionales:**

* Monedas que aparecen aleatoriamente:

  * Al recogerlas otorgan bonus (puntos extra o recuperación leve de vida).
* Animaciones simples pero fluidas (movimiento del avatar, tuberías, fondo).
* Efectos de sonido:

  * Saltos
  * Colisiones
  * Recolección de monedas
  * Sonidos con tono humorístico o ligero

**Pantallas:**

* Pantalla inicial:

  * Título del juego “Pepe Game”
  * Botón “Empezar partida”
* Pantalla de juego:

  * HUD visible (puntuación, nivel, barra de vida)
* Pantalla final:

  * Mostrar puntuación final
  * Botón para reiniciar

**Tecnología sugerida:**

* HTML5, CSS3, JavaScript
* Canvas API o librerías ligeras (opcional: Phaser.js)
* Código modular, limpio y bien comentado

**Criterios de Calidad**

* Rendimiento fluido (mínimo 60 FPS en navegadores modernos)
* Código organizado y mantenible
* Experiencia de usuario clara e intuitiva
* Escalabilidad para añadir futuras mejoras
* Compatible con escritorio (teclado + ratón)

**Cómo debe ser la respuesta**

* Proporcionar:

  * Estructura del proyecto
  * Código funcional base (HTML, CSS y JS)
  * Explicación breve de cada componente clave
* Priorizar claridad y funcionalidad sobre complejidad
* Mantener el diseño simple pero atractivo
* Incluir buenas prácticas de desarrollo frontend
