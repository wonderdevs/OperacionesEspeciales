El combate en éste sistema se desarrolla sobre una cuadrícula. Tienes una cantidad de movimiento determinada por tus stats y una acción por tu turno.

Cada cuadrícula mide 1m * 1m.

## Turnos
Cada turno esta dividido en dos fases.
Movimiento y Accion.

### Movimiento 
Te puedes mover la cantidad de cuadriculas que este marcada por la velocidad de tu personaje.

###### Movimiento en diagonal
El movimiento el diagonal sigue la regla 1-2 es decir que el primer movimiento en diagonal solo cuenta como una casilla. pero la siguiente que te muevas cuenta como 2.


## Acciones

- Disparar
	Formula: `(Cadencia * (cs Prof >= Esquiva)) * Daño – Armadura`
	
	Digamos que la cadencia del arma son 4 tienes una proficiencia de 1d6, tu modificador de daño es 2. Y el enemigo tiene una esquiva de 3, y una armadura de 1.
	
	Tienes que tirar 4d6. Y por cada dado que supere la esquiva enemiga (3), Se lleva el daño (2) menos su armadura (1)
- Recargar
	Todas las armas tienen un cargador. Este cargador indica por cuantas rondas puede ser usada hasta quedarse sin municion, una vez se acabe esa municion, resta un cargador del arma de tu inventario y el arma volvera a tener la municion maxima
- Combate cuerpo a cuerpo
	El combate cuerpo a cuerpo es como una tirada de disparo pero usas tu modificador de [[Características#Resistencia - RES (Aguante / estamina):|RES]] (Añadimos VOL o AGI como posibles modificadores?)
- Planear
	Gastando tu turno, puedes planear una estrategia sencilla (lo que te de tiempo a decir en 1min en la mesa) con tus compañeros.
- Esprintar
	Duplicas tu velocidad de movimiento durante este turno.
- Coger cobertura
	Usando esta accion te pones en cobertura, esto te impide tomar daño enemigo siempre que este al otro lado de la cobertura. (TODO esto puede romper bastate el juego habra que hacer un poco de testeo)
- Lanzar
	Te permite lanzar un objeto *como una granada.*  Tu personaje puede lanzar objetos a 5 casillas por cada punto en [[Características#Resistencia - RES (Aguante / estamina):|RES]] Aunque a partir de 12 casillas puede haber penalizacion de precision
- Usar objeto
	Te permite usar un objeto durante use turno (duh)
