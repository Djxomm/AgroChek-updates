# AgroChek 7.0.00 · Compilación 20261005.07

Separé Guardar e Imprimir en Captura de papeleta de recepción. Guardar conserva la captura sin generar PDF ni iniciar impresión; el formulario queda abierto para imprimir o continuar con Nueva papeleta. Guardar nuevamente actualiza el mismo registro y no duplica la captura.

Imprimir requiere una papeleta guardada. Si cambia datos, debe guardarlos antes de imprimir. Mantengo el bloque y mecanismo de impresión existentes. La corrección conserva Guardar corrección. Eliminé el fondo gris de las seis acciones del historial, conservando iconos, títulos y funciones.

Actualizar historial primero envía pendientes de Captura Nuez y del puente web mediante el servicio existente; después consulta papeletas del servidor y agrega las ausentes por identidad y folio. Ordené toda la lista por folio ascendente, sin limitarla a las últimas 500. Conservé las capturas locales y señalé conflictos cuando un folio tiene datos distintos; no los reemplazo ni elimino automáticamente. Las recepciones del servidor quedan auditadas y no generan una nueva cola de envío. Si faltan tablas o falla la conexión, conservo los registros locales. No crea tablas en el servidor.

Incorporé barras animadas durante la sincronización del ERP, toda la suite, el envío web y el historial. La ventana de toda la suite informa cada módulo; Nómina, cierres y adjuntos siguen locales. No presento un porcentaje ficticio ni certifico timbrado o pagos con esta acción.

Preparé dos paquetes: instalación completa y actualización exclusiva. El segundo exige registro de instalación para el usuario de Windows, ejecutable y marca de AgroChek ERP; revalida el destino antes de copiar. Sin instalación previa se detiene, incluso en ejecución silenciosa. Conservo el respaldo anterior. Publiqué el canal público separado AgroChek-updates; el instalador completo se distribuye desde el repositorio privado. Buscar nueva versión abre el canal público; la instalación automática aún no está habilitada.

Probé el código del instalador con identidad QA distinta y archivos de prueba: instalación nueva, actualización, rechazo sin instalación y conservación de datos. Comprobé que no cambió el registro de producción. Este ensayo no reemplaza una prueba del producto en otra computadora. No conecté SQL real ni imprimí físicamente.
