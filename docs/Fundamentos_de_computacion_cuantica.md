# Fundamentos de Computación Cuántica

Imagina que tienes un computador tan potente que puedes explorar miles de posibilidades al mismo tiempo, en lugar de hacerlo una por una.
Eso es lo que permite la computación cuántica: aprovechar las leyes de la mecánica cuántica (la rama de la física que describe el comportamiento de las partículas más pequeñas del universo) para procesar información de formas que los computadores tradicionales no pueden.

Mientras que un computador clásico usa bits (que solo pueden ser 0 o 1), un computador cuántico utiliza qubits, que pueden ser 0 y 1 al mismo tiempo.
Esta propiedad, conocida como superposición, es lo que da a la computación cuántica su enorme poder de procesamiento paralelo.
>En lugar de probar una sola solución por vez, un computador cuántico puede explorar muchas posibilidades simultáneamente.

---

## Conceptos clave

### 1. Qubit
Un qubit es la unidad básica de información cuántica, equivalente al bit en la computación clásica.
Pero con una gran diferencia:

- Un bit clásico solo puede ser 0 o 1.
- Un qubit puede ser una mezcla de ambos estados al mismo tiempo.

Ejemplo sencillo:
Piensa en una moneda girando en el aire. Mientras está girando, no es cara ni cruz, sino una combinación de ambas. Solo cuando la detienes (la “mides”) se convierte en una de las dos. 

### 2. Superposición
Es la capacidad de un qubit para estar en varios estados simultáneamente.
Gracias a esto, un computador cuántico puede realizar muchos cálculos al mismo tiempo, lo que lo hace clave para tareas como simulaciones científicas o búsquedas complejas.

Ejemplo:
Si quisieras encontrar la combinación correcta en una cerradura con 1000 opciones, un computador clásico probaría una por una.
Un computador cuántico, en cambio, podría analizar todas las combinaciones al mismo tiempo.

### 3. Entrelazamiento 
El entrelazamiento cuántico es una conexión misteriosa entre qubits.
Cuando dos qubits están entrelazados, lo que le pasa a uno afecta instantáneamente al otro, incluso si están a kilómetros de distancia.

Ejemplo:
Como si tuvieras dos dados mágicos: no importa dónde estén, si lanzas uno y sale 3, el otro automáticamente también mostrará 3.

### 4. Puertas cuánticas
Las puertas cuánticas son operaciones que transforman los estados de los qubits, como los interruptores lógicos en un computador clásico, pero con una flexibilidad mucho mayor.
Al aplicar diferentes puertas, puedes crear efectos de superposición o entrelazamiento.

Ejemplos de puertas:

- **Puerta X**: Esta puerta invierte el valor del qubit.

      - Si el qubit está en 0, pasa a 1.
      - Si el qubit está en 1, pasa a 0.
      - Es como un interruptor de luz: si está apagado, lo enciende; si está encendido, lo apaga.

- **Puerta Hadamard**: Es una de las más importantes, porque convierte un estado fijo (0 o 1) en una superposición.

      - Si aplicas la puerta Hadamard a |0⟩, el qubit pasa a ser mitad 0 y mitad 1 al mismo tiempo.
      - Es como poner una moneda a girar: mientras gira, no es cara ni cruz, sino una mezcla de las dos.
      - Esto permite que los computadores cuánticos procesen muchas posibilidades simultáneamente.

- **Puerta CNOT**:Esta puerta trabaja con dos qubits:
  
      - El primero es el qubit de control.
      - El segundo es el qubit objetivo.
      - La regla es simple:
  
          - Si el qubit de control está en 0, no pasa nada.
          - Si el qubit de control está en 1, el qubit objetivo cambia de estado (de 0 a 1 o de 1 a 0).
  
      - ¿Por qué es importante?
       Porque permite entrelazar dos qubits, es decir, crear una conexión entre ellos donde lo que le pase a uno afecta al otro.
       Ejemplo cotidiano: imagina dos interruptores conectados mágicamente: cuando activas uno, el otro cambia instantáneamente sin importar la distancia.

### 5. Medición y colapso
En el mundo cuántico, medir algo cambia su estado.
Cuando observas un qubit, este “colapsa” a uno de sus posibles valores (0 o 1), rompiendo la superposición.

Ejemplo:
Es como si la moneda girando (superposición) se detuviera: al mirarla, forzosamente se convierte en cara o cruz.

### ¿Cual es la imporatancia de todo esto?
Estas propiedas (Superposicion , entrelazamiento y puertas cuanticas) son base de el poder que tiene la computacion cuantica, gracias a ellas es que se dice que los computadores cuanticos prometen revolucionar campos como:

- Descubrimiento de nuevos medicamentos.
- Optimizar las inversiones y finanzas.
- La inteligencia artficial y el aprendizaje automatico.
- Simulacion de materiales y sistemas completos.

---

## Recursos recomendados para ti
- [Introducción a la computación cuántica (IBM Qiskit)](https://qiskit.org/textbook)  
- Video: [Quantum Computers Explained (Kurzgesagt)](https://www.youtube.com/watch?v=JhHMJCUmq28)  
- [¿Qué es un qubit? – IBM Think](https://www.ibm.com/think/topics/qubit)
- [4 preguntas clave para entender la Computación Cuántica(Luciana Gutsztat)](https://stayrelevant.globant.com/es/technology/data-ai/4-preguntas-clave-para-entender-la-computacion-cuantica-una-tendencia-tecnologica-en-el-horizonte/?) 
---

Este módulo busca que comprendas las bases esenciales de la computación cuántica antes de conectar estos conceptos con el aprendizaje automático.
