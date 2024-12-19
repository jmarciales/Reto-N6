# Reto-N6
flowchart TD
    A[ if n >= 2 ] --> B(par = n )
    B --> C(if n % 2 == 0) --> E
    B --> D(else n - 1) --> E
    E{while par >= 2}
    E -->|verdadero| F( print par )
    E -->|Falso| G[ < bloque_siquiente> ]
    F --> H[ par -= 2]
    H --> E
