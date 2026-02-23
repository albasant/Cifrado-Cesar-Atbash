Documentación del Sistema: Cifrador César y Atbash
Este proyecto es una herramienta web diseñada para aplicar técnicas de criptografía clásica sobre un conjunto de caracteres personalizable, utilizando como estándar la tabla ASCII.

1. Documentación de Seguridad
Este software ha sido documentado de manera segura mediante este repositorio en la nube. Al utilizar un sistema de control de versiones, se garantiza que el código sea íntegro, auditable y que no sufra alteraciones no autorizadas (cumpliendo con el requisito de documentación no impresa).

2. Descripción de los Módulos
Módulo César (Desplazamiento)
Es un método de cifrado por sustitución. El programa toma cada letra del mensaje y la desplaza un número determinado de lugares (clave "n") dentro del alfabeto seleccionado. Si el desplazamiento llega al final del alfabeto, vuelve a comenzar desde el principio.

Módulo Atbash (Inversión)
Es un cifrado que no requiere clave. Funciona invirtiendo el alfabeto seleccionado: la primera letra se convierte en la última, la segunda en la penúltima, y así sucesivamente. Es un sistema recíproco, por lo que usar la misma función sirve tanto para cifrar como para descifrar.

3. Base de Datos y Caracteres (ASCII)
El programa permite al usuario definir con qué conjunto de caracteres desea trabajar. Para una compatibilidad total, se incluye la opción de cargar la base ASCII imprimible. Esto permite que el sistema pueda ocultar:

Letras mayúsculas y minúsculas.
Números.
Espacios y signos de puntuación (.,!?#).
