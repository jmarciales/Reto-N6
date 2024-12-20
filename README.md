# Reto-N6
Para los 3 primeros puntos, se realizo el diagrama de flujo teniendo en cuenta la forma de resolverlo mediante el ciclo while <br>
Punto 1
```mermaid
flowchart TD
    A[Inicio] --> B[Inicializar i en 1]
    B --> C{¿i<= 100?}
    C -->|Sí| D[Calcular el cuadrado de i]
    D --> E[Imprimir i y su cuadrado]
    E --> F[Incrementar el i en 1]
    F --> C
    C -->|No| G[Fin]
    G --> H[Terminar]
```
Punto 2
```mermaid
flowchart TD
    A[Inicio] --> B[Inicializar impar = 1]
    B --> C{¿impar <= 999?}
    C -->|Sí| D{¿El numero es impar?}
    D -->|Sí| E[Imprimir numero]
    D -->|No| G[Pasar al listado de pares]
    E --> F[Incrementar impar en 1]
    F --> B
    C -->|No| G[Pasar al listado de pares]
    G --> H[Inicializar par = 2]
    H --> I{¿par <= 1000?}
    I -->|Sí| J{¿El numero es par?}
    J -->|Sí| K[Imprimir numero]
    K --> L[Incrementar par en 1]
    L --> H
    J -->|No| B[Inicializar impar = 1]
    I -->|No| M[Fin]
    

```
Punto 3 

```mermaid
flowchart TD
    A[Inicio] --> B[Solicitar un número natural y almacenarlo en 'num']
    B --> C{¿num es impar?}
    C -->|Sí| D[Restar 1 a num ]
    C -->|No| E[Continuar con el valor de num]
    D --> F[ Establecer el rango y restarle 2 progresivamente]
    E --> F
    F --> G{¿Quedan valores en el rango?}
    G -->|Sí| H[Imprimir el valor actual de i]
    H --> I[Pasar al siguiente valor en el rango]
    I --> G
    G -->|No| J[Fin del bucle]
    J --> K[Terminar]

```
