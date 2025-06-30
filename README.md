Simulación Básica de Interacción de Agujeros Negros

Este proyecto presenta una simulación sencilla y con fines educativos de la interacción gravitacional entre dos agujeros negros. La visualización se realiza en un entorno 3D, mostrando las órbitas y la eventual fusión de los cuerpos.

El objetivo principal es demostrar visualmente los principios de la mecánica orbital utilizando un método numérico para resolver las ecuaciones de movimiento.

Características Principales

    Visualización 3D: Utiliza la librería VPython para renderizar los dos agujeros negros como esferas y mostrar sus trayectorias en tiempo real.

    Modelo Físico Simplificado: La interacción se basa exclusivamente en la Ley de Gravitación Universal de Newton. Es una aproximación clásica y no incluye efectos de la Relatividad General.

    Integración Numérica: Las posiciones y velocidades de los cuerpos se actualizan en cada paso de tiempo utilizando el método de Runge-Kutta de 4º orden (RK4), que ofrece una buena precisión para este tipo de problema.

    Detección de Fusión: La simulación detecta cuando los dos cuerpos se acercan a una distancia predefinida, cambiando su color para representar una "fusión" de manera simbólica.

    Conservación de Energía: El script calcula e imprime la energía total del sistema en cada paso, lo que sirve como una comprobación de la estabilidad y precisión de la simulación.

Limitaciones

Es importante destacar que esta es una simulación muy básica y no representa un modelo astrofísico preciso. Las principales simplificaciones son:

    No es Relativista: Ignora por completo los complejos efectos de la Relatividad General, como la curvatura del espacio-tiempo, la emisión de ondas gravitacionales, la dilatación del tiempo o el horizonte de sucesos.

    Fusión Simbólica: La "fusión" es solo una representación visual y no simula la física real de la fusión de agujeros negros.

Tecnologías Utilizadas

    Python 3

    VPython: Para la creación de la escena y los objetos 3D.

    NumPy: Para el manejo de vectores y operaciones numéricas de manera eficiente.
