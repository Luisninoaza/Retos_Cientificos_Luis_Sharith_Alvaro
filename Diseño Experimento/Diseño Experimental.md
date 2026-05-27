## Montaje Experimental

### 1. Descripción General del Sistema
El montaje experimental consiste en un sistema electromecánico diseñado para estudiar el movimiento de una partícula desde perspectivas inerciales y no inerciales. El diseño integra una plataforma giratoria de velocidad controlada, una rampa con un mecanismo de liberación automatizado para garantizar la repetibilidad de los lanzamientos, y una estructura aérea para capturar el movimiento en video de forma cenital.

### 2. Componentes del Montaje y Especificaciones
* **Base y Plataforma Giratoria:** Se utilizó un disco principal de madera de 30 cm de diámetro que sirve como superficie de rodamiento para la partícula, acoplado concéntricamente sobre una base de soporte de 20 cm.
* **Sistema de Propulsión:** El giro de la plataforma es impulsado por un motorreductor metálico N20 de 12 V y 60 RPM, encargado de mantener la rotación del disco.
* **Mecanismo de Lanzamiento Automático:** Sobre el disco se fijó una rampa de cartón piedra de 5.5 cm de altura y 10 cm de largo. En la parte superior de la rampa se instaló un servomotor SG90 que funciona como compuerta automatizada, liberando una canica cada 4 segundos para asegurar que las condiciones iniciales de cada lanzamiento sean reproducibles.
* **Estructura de Captura de Video:** Se construyó un soporte externo utilizando tubería de PVC fijada firmemente al suelo. Esta estructura sostiene un dispositivo móvil en posición cenital, asegurando una toma perpendicular al plano de rotación.

### 3. Precisión e Incertidumbres Instrumentales
* **Resolución Temporal:** El registro cinematográfico del movimiento se realizó con una tasa de muestreo de **60 fotogramas por segundo (fps)**, lo que otorga una precisión temporal de aproximadamente 0.0167 segundos por fotograma en el análisis posterior en Tracker.
* **Precisión Espacial:** La calibración de distancias en el software de seguimiento se realizó tomando como referencia el diámetro conocido del disco de madera (30 cm), permitiendo una escala de medición con precisión milimétrica.

### 4. Limitaciones del Montaje y Errores Procedimentales
Durante el diseño, ensamble y ejecución del experimento, se identificaron factores físicos e imperfecciones mecánicas que limitaron la precisión ideal del sistema:

* **Desniveles en la Transición de la Rampa:** Debido a las propiedades del material y al corte del cartón piedra, se presentaron sutiles desniveles geométricos en el punto terminal donde la rampa se conecta con la superficie de la plataforma de madera. Esta discontinuidad introdujo pequeñas perturbaciones en la trayectoria de la canica e inestabilidad en el instante exacto en que abandonaba la rampa, afectando levemente la uniformidad de la velocidad inicial.
* **Movimiento de Precesión en el Motor:** El acople y la fijación del eje vertical del motorreductor N20 presentaron una alta complejidad técnica debido a que el bálsamo (soporte/buje) del motor es de dimensiones muy reducidas. Al no lograr un aseguramiento completamente rígido, se generó una holgura mecánica que derivó en un ligero **movimiento de precesión** en el eje durante la marcha. Esto provocó sutiles oscilaciones e inclinaciones en el plano del disco giratorio en lugar de una rotación perfectamente plana.
