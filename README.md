# Actualizaciones AgroChek ERP

Compilación 20261006.06 disponible en [Releases](https://github.com/Djxomm/AgroChek-updates/releases/tag/v7.0.00-20261006.06).

Descargue el paquete ACTUALIZACION. Requiere AgroChek ERP ya instalado para el mismo usuario de Windows; rechaza una instalación desde cero. El instalador completo y el código permanecen en el repositorio privado.

Esta actualización conserva el fondo original de las fotografías nuevas y ofrece imprimir el gafete después de guardar el empleado o su foto. Conserva el acceso manual a gafetes.

Corrige el contador general y el resultado de Captura Nuez PC/Web. La barra verde aparece durante el proceso y desaparece al terminar; seleccione un módulo para leer su resultado completo. Si faltan tablas SQL, admin debe usar Configuración → Crear/actualizar tablas para la base conectada y volver a sincronizar. Instalar la actualización no ejecuta esa migración automáticamente.

Incluye el actualizador de Configuración para admin: descarga con porcentaje, verificación de tamaño y SHA-256 y confirmación antes de abrir el instalador. No realiza instalaciones silenciosas. Consulte LEEME.txt y manifest.json.

Continúan pendientes la impresión física remota, la firma compatible de APK y el respaldo entre equipos de todos los módulos. Nómina se conserva en su estado actual. Esta entrega no certifica el cierre integral de la suite.

Correcciones 20261006.04: estabilización del panel Captura Nuez / Sincronizar para evitar el parpadeo y las llamadas anidadas al reajustar altura. Manifiesto ordenado por calibre: JUMBO, OS1, OS2, XL, LG, MD y SM, tanto en vista previa como al imprimir. Conserva registros y totales.

Compilación 20261006.05: Impresoras y Cámara disponibles para usuarios con permiso de Configuración. El acceso se comprueba al abrir y al guardar; la configuración SQL y el mantenimiento conservan sus restricciones. Cada selección conserva las preferencias de los demás dispositivos.

Compilación 20261006.06: al guardar el Puente local en el equipo anfitrión, admin o Kevin autorizan con Windows una regla TCP entrante para el puerto seleccionado, sólo en perfil privado y desde la misma subred. Verificación posterior obligatoria; un rechazo no se presenta como puerto abierto. No abre el Firewall local al configurar un equipo remoto. Actualiza sólo la regla AgroChek-Puente-Local-TCP al cambiar puerto. No inicia el servicio ni habilita el respaldo integral entre PCs; el servicio web actual usa 8010 por defecto. Las pruebas reales de UAC/Firewall entre equipos están pendientes.

Incluye iconos de red y actualización en Puente local y Actualización en línea, con el sistema visual existente y los mismos permisos.
