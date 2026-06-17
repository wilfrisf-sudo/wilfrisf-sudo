<div align="center">
<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=28&duration=3000&pause=1000&color=FF4500&center=true&vCenter=true&width=500&lines=wilfrisf-sudo;Seguridad+Inform%C3%A1tica;Scapy+%2B+GNS3+%2B+Kali+Linux" alt="Typing SVG" />

**Seguridad Informática · ITLA · Matrícula `2024-2364`**

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white&style=flat-square)](https://python.org)
[![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?logo=linux&logoColor=white&style=flat-square)](#)
[![Scapy](https://img.shields.io/badge/Scapy-Framework-009688?style=flat-square)](#)
[![GNS3](https://img.shields.io/badge/GNS3-Simulator-FF6D00?style=flat-square)](#)
[![Cisco IOU](https://img.shields.io/badge/Cisco_IOU-Layer_2-1BA0D7?style=flat-square)](#)
</div>

---

## 👤 Acerca de mí

Soy **Wilfri Solano Frías**, estudiante de Seguridad Informática en el **ITLA**. Este perfil documenta laboratorios de seguridad ofensiva, análisis de protocolos y scripting automatizado, con un fuerte enfoque en la evaluación de infraestructura de red (**Capa 2 y Capa 3**) mediante herramientas desarrolladas en **Python + Scapy** sobre entornos virtualizados distribuidos (**GNS3 / Cisco IOU**).

> 🔒 *"Entender el ataque es el primer paso para construir la defensa."*

---

## 🧪 Laboratorios de Seguridad Ofensiva — Capa 2 (Data Link)

| # | Laboratorio | Vector de Ataque | Impacto | Mecanismo de Mitigación |
|---|-------------|------------------|---------|-------------------------|
| 🔴 1 | [STP Root Claim](https://github.com/wilfrisf-sudo/stp-claim-root) | Topology Hijack | Re-convergencia forzada e intercepción | Spanning-Tree BPDU Guard |
| 🟠 2 | [DHCP Spoofing](https://github.com/wilfrisf-sudo/DHCP-SPOOFING) | Man-in-the-Middle | Asignación de falso Gateway / DNS | IP DHCP Snooping |
| 🟡 3 | [DHCP Starvation](https://github.com/wilfrisf-sudo/DHCP_STARVING) | DoS (Agotamiento) | Denegación de IPs a hosts legítimos | Port Security (Max MACs) |
| 🟢 4 | [ARP MitM](https://github.com/wilfrisf-sudo/MiTM-Arp) | Cache Poisoning | Intercepción silenciosa de tráfico unicast | Dynamic ARP Inspection (DAI) / Amarrado Estático |
| 🔵 5 | [MAC Flooding](https://github.com/wilfrisf-sudo/ataque_mac_flood) | CAM Table Overflow | Falla de switch → Comportamiento de Hub | Port Security Statics / Violation Restrict |
| 🟣 6 | [CDP Flood](https://github.com/wilfrisf-sudo/ataque_cdp_flood) | CPU/Memory Exhaustion | Congestión del plano de control del switch | Deshabilitar CDP global/interfaz (`no cdp enable`) |
| 🟤 7 | [DTP VLAN Hopping](https://github.com/wilfrisf-sudo/DTP-VLAN-Hopping) | Dynamic Trunking Hijack | Salto de VLAN e interfección de tráfico nativo | `switchport mode access` / `switchport nonegotiate` |

---

## 🌐 Ataques de Red Avanzados y Utilidades (Capas Superiores / Criptografía)

Proyectos enfocados en la manipulación de servicios de resolución de nombres y algoritmos para el procesamiento seguro/ofuscado de datos.

* 📡 **[DNS Spoofing](https://github.com/wilfrisf-sudo/DNS-Spoofing-)** * **Vector:** Envenenamiento de respuestas DNS en tránsito (*Man-in-the-Middle*).
  * **Impacto:** Redirección de nombres de dominio legítimos hacia servidores maliciosos (Phishing / Desviación de tráfico).
  * **Mitigación:** Implementación y validación estricta de extensiones de seguridad **DNSSEC** y uso de servidores DNS confiables con filtrado.

* 🧮 **[Cifrado ROT13.py](https://github.com/wilfrisf-sudo/cifrado_ROT13.py)** * **Categoría:** Criptografía Básica / Utilidad en Python.
  * **Descripción:** Script funcional para aplicar cifrado por sustitución de tipo César (desplazamiento de 13 posiciones). Diseñado como recurso educativo para comprender la transformación elemental de cadenas y la ofuscación de datos antes de avanzar a criptografía moderna simétrica/asimétrica.

---

## 🔧 Stack Técnico

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=for-the-badge)
![Scapy](https://img.shields.io/badge/Scapy-009688?style=for-the-badge)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?logo=linux&logoColor=white&style=for-the-badge)
![GNS3](https://img.shields.io/badge/GNS3-FF6D00?style=for-the-badge)
![Cisco](https://img.shields.io/badge/Cisco_IOU-1BA0D7?style=for-the-badge)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?logo=wireshark&logoColor=white&style=for-the-badge)

</div>

---

## 📚 Estructura de Mis Repositorios

* 🔐 **Laboratorios de Seguridad** - Scripts automatizados para auditorías de infraestructura en Capa 2 y Capa 3.
* 🛡️ **Herramientas de Mitigación** - Configuración de contramedidas robustas en entornos Cisco IOS / Linux hardening.
* 📖 **Documentación Técnica** - Reportes detallados, análisis de tramas en Wireshark y topologies de red en GNS3.

---

<div align="center">
**Wilfri Solano Frías** · Matrícula `2024-2364`  
🔒 [wilfrisf-sudo](https://github.com/wilfrisf-sudo) · Estudiante de Seguridad Informática · ITLA
</div>
