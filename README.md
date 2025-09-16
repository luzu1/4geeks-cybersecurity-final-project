# 4geeks-cybersecurity-final-project

# 🛡️ Proyecto Final – Pentesting & SGSI (4Geeks Academy)

 Fecha: Febrero 2025  
 Autor: Luciano Matias Zuccardi  
 Curso: 4Geeks Academy – Ciberseguridad  

---

##  Descripción
Este proyecto final integra un **ejercicio práctico de Pentesting** con el diseño de un  
**Sistema de Gestión de Seguridad de la Información (SGSI)** y un  
**Plan de Recuperación y Backup** para la academia **4Geeks**, basado en estándares:  

- **ISO/IEC 27001**  
- **NIST Cybersecurity Framework**  
- **CIS Controls**  
- **OWASP Testing Guide**  

---

##  Contenido
##  Contenido
-  [Informe de Pentesting](docs/Informe_Pentesting.pdf) → Análisis de vulnerabilidades en FTP, SSH, WordPress.  
-  [Plan de Recuperación y Backup](docs/Plan_Recuperacion_Backup.pdf) → Continuidad y respaldos, RTO/RPO, incident response.  
-  [Proyecto Final](docs/Proyecto_Final.pdf) → Resumen de vulnerabilidades críticas y mitigación.  
-  [SGSI 4Geeks](docs/SGSI_4Geeks.pdf) → Modelo SGSI con matriz de riesgos y políticas de seguridad.  
-  [Topología de Red](images/topologia.png) → Diagrama del entorno atacado y defendido.  

---

##  Principales Vulnerabilidades
- FTP con credenciales predeterminadas.  
- SSH con contraseñas débiles (fuerza bruta).  
- HTTP sin configuración segura (falta de HTTPS).  
- MySQL con credenciales inseguras.  
- WordPress con mala configuración en `wp-config.php`.  

---

##  Controles aplicados
- Configuración segura de servicios (FTP, SSH, HTTPs).  
- Políticas de contraseñas y autenticación robusta (2FA).  
- Actualización y parches en servidores.  
- Implementación de SIEM (Wazuh/ELK).  
- Plan de continuidad y respaldo (copias cifradas, restauración probada).  

---

##  Resultados
Este proyecto permitió:  
1. Identificar y explotar vulnerabilidades reales en un entorno controlado.  
2. Aplicar medidas correctivas y documentarlas en un **SGSI alineado con ISO 27001 y NIST**.  
3. Proponer un plan de continuidad para asegurar la **Confidencialidad, Integridad y Disponibilidad (CID)**.  

---


