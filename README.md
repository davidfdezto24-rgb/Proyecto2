# Proyecto2
# Proyecto #2 – Máquina de Turing “Tic-Tac-Toe Analyzer”

---

## 1. **Nombre del proyecto**
**Máquina de Turing para la validación de estados del juego Tic-Tac-Toe (Gato)**  
Desarrollado utilizando **JFlap**, con el objetivo de simular un autómata capaz de determinar el resultado de una partida de Tic-Tac-Toe/Gato a partir de una secuencia de entrada.

---

## 2. **Descripción del problema que se resuelve**
El proyecto tiene como propósito construir una **Máquina de Turing** que reciba una cadena de **nueve símbolos** representando el estado de un tablero de Tic-Tac-Toe (por ejemplo: `XOOOOXXOX`), y que determine de forma automática si existe un **ganador**, un **empate** o si el **juego está incompleto**.

La máquina analiza la secuencia según las siguientes reglas:

- Cada símbolo de entrada pertenece al conjunto `{O, X, -}`.  
- Evalúa las combinaciones **horizontales**, **verticales** y **diagonales** para detectar una victoria.  
- En caso de empate, imprime `EMPATE`.  
- Si el juego no está terminado, imprime `INCOMPLETO`.  
- Cuando existe un ganador, muestra el mensaje correspondiente junto con las coordenadas de las posiciones ganadoras.  
  ```
  Ganador: Jugador 1 - (0,1), (1,1), (2,1)
  ```

Además, la máquina implementa un **modo ayuda**, que sugiere posibles jugadas en caso de partida incompleta.

En resumen, el proyecto aplica los fundamentos de la **Teoría de la Computación** y el modelo de **Máquina de Turing** para resolver un problema cotidiano del razonamiento lógico: la detección de patrones y la validación de estados finitos en un sistema de símbolos.

---

## 3. **Retos afrontados**
Durante el desarrollo del proyecto se enfrentaron diversos desafíos, entre ellos:

- **Diseño lógico del autómata:** fue necesario descomponer el juego en una secuencia lineal de símbolos y definir transiciones precisas para evaluar cada posible línea ganadora.  
- **Gestión del alfabeto y la cinta:** decidir qué símbolos adicionales utilizar sin sobrecargar el diseño de la máquina.  
- **Limitaciones de JFlap y turingmachine.io:** ambas herramientas exigen precisión absoluta en los estados y direcciones de movimiento, lo cual implicó un extenso proceso de depuración y pruebas.  
- **Validación de entradas:** garantizar que la cadena tuviera exactamente 9 posiciones válidas y que representara un juego completo o incompleto de manera coherente.  
- **Impresión estructurada del resultado:** implementar la salida con el formato exacto solicitado (mensaje y coordenadas) dentro de las restricciones de la herramienta.

Estos retos fortalecieron la comprensión del funcionamiento interno de las máquinas de Turing y resaltaron la importancia de la planificación previa del conjunto de estados y transiciones.

---

## 4. **Integrantes del grupo**
Jeymskell Pinnock Venegas - 2025068225
David Fernández Torres - 2025087292 


## 5. **Conclusiones sobre el trabajo realizado**
El desarrollo de esta máquina de Turing permitió:

- Aplicar de forma práctica los **conceptos teóricos** vistos en clase sobre autómatas, lenguajes formales y máquinas deterministas.  
- Comprobar la **potencia de la Máquina de Turing** como modelo de cómputo universal, capaz de resolver incluso problemas lúdicos como el Tic-Tac-Toe.  
- Desarrollar **habilidades colaborativas**, tanto en la planificación del proyecto como en la gestión del repositorio y los commits.  
- Valorar la **importancia del diseño estructurado**, ya que una buena organización de estados reduce la complejidad del sistema y facilita el mantenimiento del diagrama.

En conclusión, este trabajo demuestra que incluso un juego tan simple como el Gato puede convertirse en un ejercicio de lógica computacional, donde cada transición representa un paso hacia la automatización del pensamiento.
