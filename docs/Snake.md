# Historia del juego Snake

El juego “Snake” apareció originalmente en 1976 bajo el nombre “Blockade”, creado por Gremlin Industries para arcade. El objetivo era controlar una línea que crecía evitando chocar con otras o con las paredes. Sin embargo, la versión más reconocida es la que fue incluida en los teléfonos Nokia en 1997, desarrollada por Taneli Armanto. Este sencillo juego venía preinstalado en más de 350 millones de teléfonos Nokia y se convirtió en un fenómeno cultural mundial, reviviendo la popularidad de su mecánica entre todas las generaciones de jugadores[web:2][web:3][web:5][web:7][web:9].

# Reglas y mecánicas del juego

- Controlas una “serpiente” que se desplaza por la pantalla, creciendo cada vez que come un elemento (normalmente una manzana o punto).
- Si la serpiente choca contra una pared o contra sí misma, el juego termina.
- El objetivo es lograr la mayor longitud posible y puntaje antes de perder.
- Cuanto más come la serpiente, más difícil se vuelve el juego, ya que aumenta su velocidad y es más complicado evitar colisiones.
- Solo puedes moverte en cuatro direcciones: arriba, abajo, izquierda y derecha.
- Ganas si llenas completamente el espacio con la serpiente, aunque la mayoría de las versiones simplemente continúan hasta perder[web:10].

# Algoritmo del juego Snake (básico)

El algoritmo general para una versión simple de Snake puede estructurarse en estos pasos:

1. **Inicialización:**

   - Definir una matriz o cuadrícula para representar el campo de juego.
   - Iniciar la serpiente con una longitud inicial y una posición específica.
   - Colocar la “comida” aleatoriamente en una celda vacía de la cuadrícula[web:10].

2. **Loop principal:**
   - Leer la entrada del usuario para cambiar la dirección de la serpiente.
   - Mover la cabeza de la serpiente un “paso” en la dirección actual.
   - Añadir la nueva posición de la cabeza al principio de la lista/cuerpo de la serpiente.
   - Si la serpiente encuentra comida:
     - Deja la nueva celda añadida y genera una nueva comida aleatoriamente.
   - Si no hay comida:
     - Quita la última celda del cuerpo de la serpiente (simula movimiento).
   - Si la nueva posición de la cabeza está fuera de límites o colisiona con el cuerpo:
     - Termina el juego (game over)[web:10][web:6].

![Foto](/assets/diagramasnake.png)

# Promt

Puedes crear una version del juego de snake en la web usando java script para poder jugarlo desde la pagina web del github

[Conversacion con IA](https://www.perplexity.ai/search/estoy-haciendo-una-practica-y-Vx6TKvO5TJ2iXn0R2g8hSw#0)
