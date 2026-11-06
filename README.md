[Versión 0.6.2]: #
# cuentaAtras - Cuentra atrás diginal por CLI

Es una cuenta atras CLI que al llegar a 0 empieza a contar hacia adelante para ver cuanto tiempo te has pasado.

---
## Estado del proyecto
Estructura del la cuenta atrás funcional

Actualmente TIEMPO IMPRECISO, se ha usado sleep para el desarrollo de la estructura del reloj en terminal.

---
## Instalación
No requiere instalación

### Lenguaje
- Bash
### Dependencias
No tiene dependencias
### Sistemas operativos compatibles
Probado en:
- Debian

---
## Uso
Para usarlo solamente hay que llamar al script y añadirle 3 argumentos: horas, minutos y segundos respectivamente.

### Ejemplo de uso

- Se deben definir los 3 argumentos, usando ceros en los que no queramos usar.
```bash
        ./cuentaAtras 1 6 23
```
- Ejecutará una cuenta atrás de 1 hora, 6 minutos y 23 segundos.
```bash
        ./cuentaAtras 0 6 0
```
- Ejecutará una cuenta atrás de 0 horas, 6 minutos y 0 segundos.

---
## Recomendación
Para un uso mas ágil se puede crear una carpeta para script de forma que todos los que se añadan se puedan llamar desde la propia terminal como cualquier otro comando.

Esto se puede conseguir añadiendo a ~/.bashrc la línea:

>export PATH=$PATH:/ruta/a/carpeta/con/scripts

---
## Licencia
Este proyecto está licenciado bajo GPLv2 - consulta el archivo LICENSE para más detalles.

---
## Autor
>[Alex](github.com/4lexKy)
---
