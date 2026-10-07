# Revisión del impuesto patronal de Sonora

Integré en Nómina el acceso **Impuesto patronal Sonora**, disponible con el permiso de precálculo. La consulta solicita empresa, mes de 2026, remuneraciones efectivamente pagadas, exclusiones estatales revisadas y trabajadores registrados en todo el estado. Revalido el permiso al calcular y rechazo una empresa cambiada desde la apertura del formulario.

Utilicé el [criterio publicado por Hacienda Sonora](https://hacienda.sonora.gob.mx/component/content/article/que-es-el-isrtp?Itemid=101&catid=22): 3% general sobre la base mensual y cuota adicional de 1% cuando el patrón tiene más de 100 trabajadores registrados en Sonora. Separé ambos importes y redondeé cada uno a centavos. No tomé automáticamente los exentos del ISR federal como exclusiones estatales.

El resultado es una consulta antes de estímulos. Dejé pendiente su aplicación hasta acreditar las condiciones de cada patrón. Hacienda describe el [estímulo para el sector primario](https://hacienda.sonora.gob.mx/contribuyentes/impuesto-sobre-remuneracion-al-trabajo-personal-isrtp); el giro agrícola por sí solo no sustituye la revisión de transformación de productos y cumplimiento fiscal.

Conservé las fórmulas de pago existentes: este impuesto corresponde al patrón y la consulta no descuenta al empleado, no aplica importes a un período, no conserva una declaración y no envía datos a Hacienda. El cálculo exige revisar explícitamente la base y plantilla. Si se cambia cualquier entrada, descarto el resultado anterior.

Validé el límite 100/101, cero, redondeo, año y mes, importes negativos y no finitos, exclusiones excesivas, revisión incompleta, cambio de empresa y revocación de permisos. Esta incorporación no completa CFDI/PAC, conciliación bancaria, SUA, estímulos ni la clasificación automática de todos los conceptos.
