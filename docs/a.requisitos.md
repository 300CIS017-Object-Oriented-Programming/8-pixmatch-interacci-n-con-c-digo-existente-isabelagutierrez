## Requisitos Funcionales y Criterios de Aceptación
### 1. Configuración de Nivel de Dificultad
**Requisito:** El sistema debe permitir a los jugadores seleccionar el nivel de dificultad antes de comenzar el juego.

**Criterios de Aceptación:**
- Opciones de dificultad fácil, medio y difícil disponibles para selección.
- La configuración de dificultad debe influir en la mecánica del juego, como la frecuencia de regeneración de imágenes y la puntuación.
- Tiempos de regeneración específicos:
  - Fácil: cada 8 segundos.
  - Medio: cada 6 segundos.
  - Difícil: cada 5 segundos.

### 2. Manejo tabla de clasificación
**Requisito:** Mostrar la clasificación de los jugadores dependiendo su puntaje total

**Criterios de aceptación:**
- Organizar en un podio a los 3 primero jugadores
- Mostrar el emoji dependiendo de la posición que ocupa
- Mostrar el puntaje que obtuvo

### 3. Comenzar juego nuevo
**Requisito:** Reiniciar el tablero del juego para que aparezcan nuevos emojis e iniciar otra vez

**Criterios de aceptación:**
- Iniciar un nuevo tablero cada que se reinicie el juego
- Colocar un tipo diferente de emojis

### 4. Representación de puntajes
**Requisitos:** Mostrar mediante emojis que tan bueno es el puntaje

**Criterios de aceptación:**
- Mostrar de manera clase al usuario el estado actual de su puntaje
- Representar mediante emojis el puntaje
  - 😐 cuando el puntaje es 0
  - 😏 cuando esta entre -5 y -1 
  - ☹️ cuando esta entre -6 y -10 
  - 😖 cuando es menor a -11 
  - 🙂 cuando esta entre 1 y 5 
  - 😊 cuando esta entre 6 y 10 
  - 😁 cuando es mayor a 10

### 5. Manejo de intentos
**Requisitos:** Delimitar un número de intentos, ya sean correctos o incorrectos para poderle dar un fin al juego

**Criterios de aceptación:**
- Restar un movimiento cada que se realiza un acierto
- Restar un movimiento cada que se comete un error
- Finalizar el juego una vez que no hayan intentos restantes

### 6. Victoria del juego
**Requisitos:** Darle a conocer al usuario que el juego ha finalizado

**Criterios de aceptación:**
- Validar cuando todas las respuestas son correctas
- Validad cuando el juego finalizo por falta de intentos
- Grafico que le indique al usuario de la victoria obtenida