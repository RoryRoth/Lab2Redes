# Lab2
Construcción, simulación y configuración de Redes VLAN

OBJETIVOS:

 - Construir una red LAN simulada en Cisco Packet Tracer.
 - Configurar VLAN y protocolo Spanning Treed en switches.
 - Analizar el tráfico dentro de una red LAN.
 - Diagnosticar la conexión entre PC's y su enlace mediante gateway

PASOS:

1. Se inicia el desarrollo en la modalidad de configuración física, agregando 3 racks. Cada uno con un router, un switch y un patch panel.

![image](https://cdn.discordapp.com/attachments/1006269019646603349/1022549629058945054/unknown.png)

2. Configuración de los tres switches y el router principal.
 
![image](https://cdn.discordapp.com/attachments/1006269019646603349/1022549629058945054/unknown.png)

3. Conexión de cables de consola de un PC a el router o a los switches y configuración básica (host, contraseña).

![image](https://cdn.discordapp.com/attachments/1006269019646603349/1022550970669989939/Untitled.png)
![image](https://cdn.discordapp.com/attachments/1006269019646603349/1022550970309292062/Untitled2.png)

4. Configuración de VLAN en switches y los routers.

![image](https://cdn.discordapp.com/attachments/1006269019646603349/1022551480911282316/unknown.png)
![image](https://cdn.discordapp.com/attachments/1006269019646603349/1022551487697653791/unknown.png)

5. Configuración de las IP's de las interfaces NIC en los PC's.

6. Verificaciones de las IP's en cada una de las PC´s del espacio de trabajo.

![image](https://cdn.discordapp.com/attachments/1006269019646603349/1022552065039405096/unknown.png)
![image](https://cdn.discordapp.com/attachments/1006269019646603349/1022552200716767343/unknown.png)

7. Verificación de las VLAN estén correctamente creadas y asignadas.

![image](https://cdn.discordapp.com/attachments/1006269019646603349/1022552524135342080/unknown.png)

8. Verificación de las IP's en los PC's.

![image](https://cdn.discordapp.com/attachments/1006269019646603349/1022553527190569121/unknown.png)

![image](https://cdn.discordapp.com/attachments/1006269019646603349/1022553574988861461/unknown.png)

![image](https://cdn.discordapp.com/attachments/1006269019646603349/1022553924605050992/unknown.png)

![image](https://cdn.discordapp.com/attachments/1006269019646603349/1022553932947529830/unknown.png)

CONCLUSIONES:

1. La conexión de los diferentes VLAN se realiza mediante el comando ping.

3. Se usa el comando show spanning-tree para verificar el protocolo STP.

![image](https://cdn.discordapp.com/attachments/1006269019646603349/1022558365282472016/unknown.png)

4. El comando telnet permite configurar los switches y el router sin la necesidad de un cable de consola.

![image](https://cdn.discordapp.com/attachments/1006269019646603349/1022555652628959343/unknown.png)

5. Haciendo referencia a la conexión VLAN y la comuniación entre os PC's; esta conexión envía paquetes aleatorios que vuelven al mismo punto, esto para buscar la ruta más rápida a todos los host.

6. Cuando esta red se conecta a una diferente VLAN, esta realiza diferentes procesos con el fin de determinar la IP, el default gateway y la ruta más rápida hacia el PC al cual se le va a enviar el paquete final.

![image](https://cdn.discordapp.com/attachments/1006269019646603349/1022558631222321287/unknown.png)
