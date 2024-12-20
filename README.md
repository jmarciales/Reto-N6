# Reto-N6
Para los 3 primeros puntos, se realizo el diagrama de flujo teniendo en cuenta la forma de resolverlo mediante el ciclo while 
Punto 1
```mermaid
graph TD
    A[Inicio] --> B[Inicializar número en 1]
    B --> C{¿Número <= 100?}
    C -->|Sí| D[Calcular el cuadrado del número]
    D --> E[Imprimir número y su cuadrado]
    E --> F[Incrementar el número en 1]
    F --> C
    C -->|No| G[Fin del bucle]
    G --> H[Terminar]
```
