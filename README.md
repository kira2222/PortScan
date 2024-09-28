# Port Scanner Script

Este es un script simple en Python que escanea los puertos de una dirección IP específica para identificar cuáles están abiertos.

## Descripción

El script realiza un escaneo de todos los puertos (0-65535) de una dirección IP ingresada por el usuario. Utiliza el módulo `socket` de Python para crear conexiones de prueba a cada puerto y determina si está abierto o cerrado.

## Uso

### Requisitos

- Python 3.x
- Módulo `socket` (incluido por defecto en Python)

### Ejecución

Para ejecutar el script, usa el siguiente comando en tu terminal:

```bash
python script.py

Se te solicitará que ingreses la dirección IP que deseas escanear:

Ingrese la dirección IP a escanear: <IP>

Ejemplo

Ingrese la dirección IP a escanear: 192.168.1.1
Puerto 22 abierto
Puerto 80 abierto
...
Salida
El script imprimirá una lista de puertos abiertos para la IP especificada.

Modificación del Rango de Puertos

Por defecto, el script escanea todos los puertos (0-65535). Si deseas modificar el rango de puertos a escanear, puedes cambiar la línea:

for puerto in range(0, 65535):

Advertencia
Este script debe utilizarse de forma ética y legal. Asegúrate de tener permiso para escanear los puertos de la IP especificada antes de usar el script.



