# EJERCICIO 1. Entorno virtual e instalación de Windows

## 1. Configuración de la Máquina Virtual
* **Hipervisor:** VirtualBox
* **Recursos:** 8GB RAM, 4 Núcleos CPU, 50GB Disco.
* **Justificación:** Se han asignado estos recursos para garantizar un rendimiento óptimo del sistema operativo Windows 10 en un entorno de oficina, permitiendo la ejecución fluida de aplicaciones de ofimática y navegación sin comprometer el equipo anfitrión.

![Resumen de configuración](../../assets/img/10-ejercicio1/01-config.png)
![Configuración de hardware](../../assets/img/10-ejercicio1/01-config-hardware.png)
![Configuración de red](../../assets/img/10-ejercicio1/03-config-red.png)
![Configuración de pantalla](../../assets/img/10-ejercicio1/04-config-pantalla.png)

## 2. Proceso de instalación
1. **Arranque:** Inicio de la máquina virtual mediante la ISO oficial de Windows 10.
2. **Particionado:** Selección de instalación personalizada utilizando el espacio total del disco (50GB) para una partición primaria.
3. **Instalación:** Ejecución del copiado y preparación de archivos del sistema.
4. **Optimización (Guest Additions):** Instalación de los controladores de VirtualBox para mejorar la resolución, integración del ratón y habilitar funciones avanzadas como carpetas compartidas, portapapeles compartido y arrastrar y soltar.

![Particionado de disco](../../assets/img/10-ejercicio1/05-particionado.png)
![Progreso de instalación](../../assets/img/10-ejercicio1/05-proceso-instalacion.png)
![Instalación de Guest Additions](../../assets/img/10-ejercicio1/07-instalacion-tools.png)

## 3. Usuarios y Sistema Operativo
* **Sistema Operativo:** Windows 10 Pro / Home.
* **Usuarios configurados:** * **Admin:** Cuenta de administrador local para tareas de gestión.
    * **Empleado:** Cuenta de usuario estándar para el trabajo diario.

![Creación de usuario Admin](../../assets/img/10-ejercicio1/02-usuarios-admin.png)
![Panel de gestión de usuarios](../../assets/img/10-ejercicio1/02-usuarios.png)
![Escritorio del sistema operativo](../../assets/img/10-ejercicio1/06-sistema-operativo.png)