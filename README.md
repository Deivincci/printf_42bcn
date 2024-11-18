# ft_printf - Implementación propia de la función printf

`ft_printf` es una implementación personalizada de la famosa función `printf` de C, que permite imprimir en pantalla textos con formato. Esta versión incluye funciones auxiliares como `ft_itoa`, `ft_base10`, entre otras, necesarias para su funcionamiento correcto.
Se incluye Makefile para compilar el paquete completo.

## Características:

- Implementa conversiones estándar de `printf`, como `%d`, `%s`, `%c`, etc.
- Soporta flags como `-`, `+`, `#`, `0`, y la precisión en los formatos.
- Maneja diferentes tipos de datos, incluyendo enteros, caracteres y cadenas.
- Incluye funciones auxiliares como `ft_itoa`, `ft_base10`, entre otras.

## Instalación y Uso:

1. Clona el repositorio:


   git clone https://github.com/Deivincci/printf_42bcn.git


Usa la función ft_printf en lugar de printf en tu código para probar su funcionamiento.

ft_printf("Hola, mi número es: %d\n", 42);
