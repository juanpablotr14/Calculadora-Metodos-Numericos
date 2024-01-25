# Proyecto de Métodos Numéricos en Python

Este proyecto implementa diversos métodos numéricos en Python, permitiendo a los usuarios calcular derivadas y encontrar raíces de funciones de forma eficiente y precisa.


## Funcionalidades principales

### Derivadas

1. #### Derivada de una función: 
Permite hallar la derivada exacta de una función matemática dada.

2. #### Derivadas usando diferencias finitas:
- Diferencia central.
- Diferencia hacia adelante (derecha).
- Diferencia hacia atrás (izquierda).


### Busqueda de Raíces

1. #### Método de Bisección: 
Divide el intervalo en dos subintervalos y selecciona el subintervalo en el que la función cambia de signo, garantizando así la presencia de una raíz.

2. #### Método de Punto Fijo: 
Itera la función hasta hallar un punto que no varíe significativamente entre iteraciones.

3. #### Método de Newton-Raphson: 
Usa tangentes para encontrar la raíz de la función de forma iterativa.

4. #### Método de la Falsa Posición:
Similar al método de bisección, pero se aproxima mediante una línea recta.

5. #### Método de la Secante: 
Usa secantes para aproximar la raíz de la función.


## Cómo Empezar

Clona el proyecto del repositorio

```bash
  git clone https://github.com/Numerical-Methods-App/numericalmethods_app.git
```

Ve hacia el directorio donde se encuentra el proyecto

```bash
  cd numericalmethods_app
```

Para empezar a usar el programa, simplemente ejecute el archivo main.py:

```bash
  python3 main.py
```

Asegúrese de tener todas las dependencias necesarias instaladas antes de ejecutar el programa.


## Contribuciones y soporte

Si tiene alguna sugerencia o encuentra algún error, no dude en abrir un `issue` en el repositorio del proyecto. Las contribuciones son bienvenidas, simplemente realice un `fork` del proyecto y envíe un `pull request`.