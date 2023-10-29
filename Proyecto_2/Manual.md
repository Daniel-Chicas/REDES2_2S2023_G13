<p>UNIVERSIDAD DE SAN CARLOS DE GUATEMALA</p>
<p>FACULTAD DE INGENIERIA</p>
<p>ESCUELA DE CIENCIAS Y SISTEMAS</p>
<p>LABORATORIO DE REDES Y COMPUTADORAS 2</p>
<p>SEGUNDO SEMESTRE 2023</p> 

---


---


---


---


---


---


---

<center> <h1>PROYECTO #2</h1> </center> 



---


---


---


---



| Nombre   |      Carnet      |  
|----------|:-------------:|
| Daniel Estuardo Chicas Carías    | 201807079 | 


---


---


---


---




---


---


---


---


---



<center> <h1>COMANDOS UTILIZADOS</h1> </center> 


| **Objetivo/Requerimiento** | **Comandos de Configuración** |
| --- | --- |
| **Configuración Básica** | |
| Asignar nombres a los dispositivos | `hostname <nombre_dispositivo>` |
| Configurar las interfaces | `interface <tipo> <número>`<br>`ip address <dirección_ip> <máscara>`<br>`no shutdown` |
| Configurar contraseñas | `enable password <contraseña>`<br>`enable secret <contraseña>`<br>`line console 0`<br>`password <contraseña>`<br>`login`<br>`line vty 0 15`<br>`password <contraseña>`<br>`login` |
| Configurar el reloj (opcional) | `clock set <hora>` |
| **Configuración BGP** | |
| Configurar BGP en el router de interconexión de ISPs | `router bgp <número_ASN>`<br>`neighbor <IP_vecino> remote-as <número_ASN_vecino>` |
| Configurar redes a anunciar en BGP | `network <red>` |
| **Configuración OSPF** | |
| Configurar OSPF en el router Akado | `router ospf <número_proceso>`<br>`network <red> <wildcard_mask> area <número_area>` |
| **Configuración RIP** | |
| Configurar RIP en el router Akado | `router rip`<br>`version 2`<br>`network <red>` |
| **Configuración LACP** | |
| Configurar LACP en interfaces deseadas | `interface range <tipo> <número_inicio> - <número_fin>`<br>`channel-group <número_grupo> mode active` |
| **Configuración EIGRP** | |
| Configurar EIGRP en el router Yota y Rostelecom | `router eigrp <número_proceso>`<br>`network <red>` |
| **Configuración de Subredes** | |
| Configurar subredes para Akado | `interface <tipo> <número>`<br>`ip address <dirección_ip> <máscara>`<br>`ip helper-address <IP_DHCP>` |
| **Configuración de IPv6** | |
| Configurar IPv6 en interfaces deseadas | `interface <tipo> <número>`<br>`ipv6 address <dirección_ipv6>` |
| **Configuración de Túneles IPv6 sobre IPv4** | |
| Configurar túneles IPv6 sobre IPv4 | `interface tunnel <número>`<br>`tunnel source <dirección_ipv4>`<br>`tunnel destination <dirección_ipv4_destino>`<br>`ipv6 address <dirección_ipv6>` |
| **Configuración de Comunicación entre Departamentos** | |
| Configurar rutas estáticas o protocolos de enrutamiento para la comunicación entre departamentos | `ip route <red_destino> <máscara> <próximo_salto>`<br> (o)`router rip`<br>`redistribute connected` |


<center> <h1>CAPTURAS DE PANTALLA</h1> </center> 

---
---

<p align="center">
  <a href="#"><img src="./img/TOPOLOGIA.JPEG"/></a>
</p>

---
--- 

<p align="center">
  <a href="#"><img src="./img/AVPC.JPEG"/></a>
</p>

---
---

<p align="center">
  <a href="#"><img src="./img/LACP.JPEG"/></a>
</p>

---
---
# VLAN
<p align="center">
  <a href="#"><img src="./img/VLAN.JPEG"/></a>
</p>

---
---
# ASIGNACIÓN IP A VLAN
<p align="center">
  <a href="#"><img src="./img/IPVLAN.JPEG"/></a>
</p>

---
---

# VTP
<p align="center">
  <a href="#"><img src="./img/VTP.JPEG"/></a>
</p>

---
---

# OSPF
<p align="center">
  <a href="#"><img src="./img/OSPF.PNG"/></a>
</p>

---
---