# Actualizaciones AgroChek ERP

## Windows: compilación 20261020.02

[Descargar actualizador](https://github.com/Djxomm/AgroChek-updates/releases/download/v7.0.00-20261020.02/AgroChek_ERP_7.0.00_20261020_02_ACTUALIZACION.exe) · [Notas de la versión](https://github.com/Djxomm/AgroChek-updates/releases/tag/v7.0.00-20261020.02)

Requiere una instalación existente de AgroChek ERP 7.0.00 para el mismo usuario de Windows. Guarde sus capturas y cierre AgroChek antes de ejecutar el paquete. El instalador conserva bases y configuración y realiza la copia local previa a actualizar.

Corrige el bloqueo de admin al editar pallets y papeletas. Root y admin activos con nivel Administrador conservan ese acceso; los demás usuarios requieren los permisos de edición asignados. Los perfiles protegidos se muestran para consulta, sin permitir un guardado que sería rechazado. Conserva las comprobaciones de sesión, cuenta activa y permisos al guardar, y mantiene los colores de conflicto de la versión anterior.

SHA-256 del actualizador: `9530c7a26f1cf1973f7e628678ebc13c8a655a85cddee3465b9e760eb3addc87`.

Validación local: 64 pruebas con código del producto final, tres recorridos del ejecutable de prueba y arranque normal en un perfil vacío. El instalador fue comprobado por extracción estática. No se ha instalado en los equipos remotos ni se declara validado el servidor SQL de producción.

El canal de actualización de Windows está en [manifest.json](manifest.json). Las versiones anteriores de los paquetes de Windows se retiraron de las descargas. El actualizador requiere una instalación existente; no sustituye al instalador completo.

Los canales de [Android](android.json) y [Linux](manifest-linux.json) se conservan por separado.
