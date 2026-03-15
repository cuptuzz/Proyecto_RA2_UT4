# Reto 01 - RA2 - UT4: Preparación de Equipo de Oficina

**Módulo:** Fundamentos de Hardware (FHW)  
**Alumno:** Ugo Pérez Ruiz  
**Fecha:** 15 Marzo 2026  
**Enlace al repositorio:** [github.com/cuptuzz/Proyecto_RA2_UT4](https://github.com/cuptuzz/Proyecto_RA2_UT4)

![Portada del Proyecto](../assets/img/portada.png)

<div style="page-break-after: always;"></div>

# EJERCICIO 1. Entorno virtual e instalación de Windows

## 1. Configuración de la Máquina Virtual
* **Hipervisor:** VirtualBox
* **Recursos:** 8GB RAM, 4 Núcleos CPU, 50GB Disco.
* **Justificación:** Se han asignado estos recursos para garantizar un rendimiento óptimo del sistema operativo Windows 10 en un entorno de oficina.

![Resumen de configuración](../assets/img/10-ejercicio1/01-config.png)
![Configuración de hardware](../assets/img/10-ejercicio1/01-config-hardware.png)
![Configuración de red](../assets/img/10-ejercicio1/03-config-red.png)
![Configuración de pantalla](../assets/img/10-ejercicio1/04-config-pantalla.png)

## 2. Proceso de instalación
1. **Arranque:** Inicio de la VM mediante la ISO oficial de Windows 10.
2. **Particionado:** Selección de instalación personalizada (50GB).
3. **Instalación:** Ejecución del copiado y preparación de archivos.
4. **Optimización:** Instalación de **Guest Additions** para resolución y fluidez.

![Particionado de disco](../assets/img/10-ejercicio1/05-particionado.png)
![Progreso de instalación](../assets/img/10-ejercicio1/05-proceso-instalacion.png)
![Instalación de Guest Additions](../assets/img/10-ejercicio1/07-instalacion-tools.png)

## 3. Usuarios y Sistema Operativo
* **Admin:** Cuenta de administrador local.
* **Empleado:** Cuenta de usuario estándar.

![Creación de usuario Admin](../assets/img/10-ejercicio1/02-usuarios-admin.png)
![Panel de gestión de usuarios](../assets/img/10-ejercicio1/02-usuarios.png)
![Escritorio del sistema operativo](../assets/img/10-ejercicio1/06-sistema-operativo.png)

<div style="page-break-after: always;"></div>

# EJERCICIO 2. Selección e instalación de software

## 1. Relación de software instalado
| Programa | Tipo | Justificación técnica para oficina |
| :--- | :--- | :--- |
| **Google Chrome** | Navegador | Estándar de compatibilidad para herramientas SaaS. |
| **7-Zip** | Compresor | Software ligero para gestionar archivos adjuntos. |
| **SumatraPDF** | Visor PDF | Consumo mínimo de RAM para apertura instantánea. |
| **CPU-Z** | Diagnóstico | Identificación rápida de hardware ante incidencias. |
| **Guest Additions** | Herramientas | Optimización de drivers y fluidez en la VM. |

## 2. Evidencia de instalación
![Software instalado](../assets/img/20-ejercicio2/01-software-instalado.png)

<div style="page-break-after: always;"></div>

# EJERCICIO 3. Seguridad, mantenimiento y validación

## 1. Revisión de Seguridad y Sistema
![Seguridad del sistema](../assets/img/30-ejercicio3/01-seguridad.png)
![Diagnóstico de Hardware](../assets/img/30-ejercicio3/02-diagnostico.png)
![Windows Update](../assets/img/30-ejercicio3/03-updates.png)

## 2. Pruebas de funcionamiento
![Prueba de PDF](../assets/img/30-ejercicio3/04-pruebas-pdf.png)
![Prueba de compresión](../assets/img/30-ejercicio3/05-compresion.png)

<div style="page-break-after: always;"></div>

# EJERCICIO 4. Incidencias y Conclusión Final

## Incidencias encontradas
* **Problema:** El instalador de Windows 10 forzaba la creación de una cuenta Microsoft.
* **Solución:** Se deshabilitó el adaptador de red en VirtualBox para forzar la creación de la cuenta local "Admin".

![Solución incidencia](../assets/img/10-ejercicio1/02-usuarios-admin.png)

## Conclusión
El equipo ha sido configurado con éxito. Se encuentra operativo, actualizado y con las medidas de seguridad básicas activadas, listo para ser entregado al usuario final.