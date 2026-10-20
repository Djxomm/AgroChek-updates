# Actualizaciones AgroChek ERP

## Windows: compilación 20261020.01

[Descargar actualizador](https://github.com/Djxomm/AgroChek-updates/releases/download/v7.0.00-20261020.01/AgroChek_ERP_7.0.00_20261020_01_ACTUALIZACION.exe) · [Notas de la versión](https://github.com/Djxomm/AgroChek-updates/releases/tag/v7.0.00-20261020.01)

Requiere una instalación existente de AgroChek ERP 7.0.00 para el mismo usuario de Windows. Guarde sus capturas y cierre AgroChek antes de ejecutar el paquete. El instalador conserva bases y configuración y realiza la copia local previa a actualizar.

Edición del registro seleccionado en Pallets y Papeletas. Permisos independientes por usuario: Editar pallets y Editar papeletas, comprobados al abrir y al guardar. Las filas con conflicto se marcan en naranja y el detalle del error se muestra en rojo. Conserva la identidad del registro y los datos existentes al corregirlo. Los permisos nuevos deben asignarse expresamente en Administración de usuarios y requieren volver a iniciar sesión.

SHA-256 del actualizador: `019c2d0813caa131c7a4781c12941b5ca43eb2e67e91f970f4347959a27e21aa`.

Validación local: 15 pruebas con código del producto final, tres recorridos del ejecutable de prueba y arranque normal en un perfil vacío. El instalador fue comprobado por extracción estática. No se ha instalado en el equipo de Alma ni se declara validado el servidor SQL de producción.

El canal de actualización de Windows está en [manifest.json](manifest.json). Las versiones anteriores de los paquetes de Windows se retiraron de las descargas. El actualizador requiere una instalación existente; no sustituye al instalador completo.

Los canales de [Android](android.json) y [Linux](manifest-linux.json) se conservan por separado.
