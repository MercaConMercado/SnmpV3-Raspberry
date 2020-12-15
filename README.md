# SnmpV3-Raspberry
Modulo integrado con lenjuage pyton , php, c para lectura y escritura de señales SNMPv3 relacionada a un HARDWARE de una maquina industrial de control de aire acondicionado.

- OJO: Tener encuenta la GPIO de la raspberry, sus puertos y en la creacion de usuario y clave para acceso a SNMPv3 crearlo con permisos de lectura y escritura

- Integracion de una RASPBERRYPI con Raspbian con servidor APACHE para interfaz visual e interfaz de conexion remota

- las señales y programas en ejecucion se corren bajo un Crontab para inicializarse en cunato el modulo encienda.

- El snmp v3 permite autenticacion segura MD5 para interactuar con las señales que se enrrutan por medio de una MIB que se podra leer e interactuar por cualquier escaneador de señales SNMP como MIB Browser y ManageEngine MibBrowser por medio del archivo de TEXTO donde se programo la MIB
