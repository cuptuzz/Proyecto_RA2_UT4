# EJERCICIO 3. Seguridad, mantenimiento y validación

## 1. Revisión de Seguridad y Sistema
* **Seguridad:** Uso de Windows Defender activo y verificado con todas las protecciones en verde.
* **Diagnóstico:** Verificación de hardware mediante CPU-Z, confirmando la detección del procesador y núcleos asignados.
* **Mantenimiento:** Comprobación de Windows Update confirmando que no hay actualizaciones pendientes.

![Seguridad del sistema](../../assets/img/30-ejercicio3/01-seguridad.png)
![Diagnóstico de Hardware](../../assets/img/30-ejercicio3/02-diagnostico.png)
![Windows Update](../../assets/img/30-ejercicio3/03-updates.png)

## 2. Pruebas de funcionamiento
Se han validado las herramientas de productividad instaladas:
1. **Gestión de archivos:** Apertura correcta de documentos PDF técnicos.
2. **Compresión:** Test de extracción y compresión de archivos mediante la utilidad 7-Zip.

![Prueba de PDF](../../assets/img/30-ejercicio3/04-pruebas-pdf.png)
![Prueba de compresión](../../assets/img/30-ejercicio3/05-compresion.png)

## 3. Incidencias y resolución
* **Incidencia:** El sistema intentó forzar una cuenta Microsoft durante la instalación.
* **Solución:** Se deshabilitó el adaptador de red de la VM temporalmente para forzar la creación de la cuenta local "Admin".