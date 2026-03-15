# Reto 01 - RA2 - UT4: Preparación de Equipo de Oficina

**Módulo:** Fundamentos de Hardware (FHW)  
**Alumno:** Ugo Pérez Ruiz  
**Fecha:** 15 Marzo 2026  
**Enlace al repositorio:** https://github.com/cuptuzz/Proyecto_RA2_UT4

---

# EJERCICIO 1. Entorno virtual e instalación de Windows

## 1. Configuración de la Máquina Virtual
* **Hipervisor:** VirtualBox
* **Recursos:** 8GB RAM, 4 Núcleos CPU, 50GB Disco.
* **Justificación:** 
- Se asignan 8GB de RAM y 4 núcleos para garantizar un rendimiento fluido en multitarea.
 
- Los 50GB cubren de sobra el sistema operativo y el software base sin quitarle espacio innecesario al PC anfitrión.

![Configuración VM](../../assets/img/10-ejercicio1/01-config.png)

## 2. Instalación y Usuarios
* **Sistema Operativo:** Windows 10 Home.
* **Usuarios creados:** "Admin" (Administrador) y "Empleado" (Estándar).

![Usuarios creados](../../assets/img/10-ejercicio1/02-usuarios.png)

---

## EJERCICIO 2. Software de Oficina

| Herramienta | Función | Motivo de elección | Ventaja en la oficina |
| :--- | :--- | :--- | :--- |
| **Google Chrome** | Navegador | Integración nativa con el ecosistema Google. | Acceso rápido y sin fallos a Docs, Drive y Gmail. |
| **Sumatra PDF** | Lector PDF | Extremadamente ligero y de código abierto. | Abre documentos al instante sin consumir RAM. |
| **7-Zip** | Compresor | Open Source, soporta todos los formatos. | Gratuito, seguro y sin publicidad intrusiva. |
| **Google Drive** | Nube | App de escritorio oficial. | Sincronización directa desde el explorador de archivos. |

### Evidencias de instalación
![Chrome y Google Workspace](../assets/img/20-ejercicio2/01-chrome.png)
![7-Zip y Sumatra](../assets/img/20-ejercicio2/02-herramientas.png)

---

## EJERCICIO 3. Seguridad, Diagnóstico y Pruebas

### 1. Mantenimiento y Seguridad
* **Antivirus:** Windows Defender. *Justificación:* Integrado en el sistema, no requiere licencias extra y es suficiente para ofimática básica.
* **Diagnóstico:** CPU-Z. *Justificación:* Permite verificar rápidamente que la VM detecta el hardware asignado.
* **Actualizaciones:** Windows Update verificado al 100%.

### 2. Pruebas de funcionamiento
* [x] Acceso correcto a Gmail y Google Docs.
* [x] Archivo PDF abierto sin errores.
* [x] Archivo comprimido y descomprimido con 7-Zip.
* [x] Análisis rápido de antivirus completado.

### Evidencias
![Análisis Defender](../assets/img/30-ejercicio3/01-defender.png)
![Pruebas funcionales](../assets/img/30-ejercicio3/02-pruebas.png)

---

## EJERCICIO 4. Incidencias y Conclusión Final

### Incidencias encontradas
* **Problema:** [Ej: La máquina virtual no tenía conexión a Internet al arrancar].
* **Solución:** [Ej: Apagar la VM, ir a Red en VirtualBox y cambiar de NAT a Adaptador Puente].

![Solución incidencia](../assets/img/40-incidencias/01-incidencia.png)

### Conclusión
El equipo ha sido configurado con éxito. Se encuentra operativo, actualizado y con las medidas de seguridad básicas activadas. Las herramientas seleccionadas garantizan un entorno de trabajo rápido y sin distracciones, listo para ser entregado al usuario final.