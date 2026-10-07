# Mi revisión de cierre de Nómina

Revisé el código de captura, acumulados, requisitos y archivo XML antes de entregar .13. Separé la consulta documental de las operaciones que realmente modifican la nómina. No considero terminado el módulo.

## Bloque que entrego

Conservé el histórico autorizado para acumulados y rechacé huellas alteradas, empleados duplicados y revisiones incompletas. Incorporé la comparación documental por empresa, RFC y fechas sin sumar coincidencias ambiguas ni crear pagos. Las 45 pruebas focalizadas aprobaron este bloque; registro la validación del paquete en evidencias separadas.

## Trabajo que puedo continuar sin datos del usuario

- Aplicar horas dobles y triples revisadas a la captura con evidencia ligada al empleado y período, invalidación al cambiar salario/jornada y protección contra doble pago. La consulta actual aún no lo hace.
- Integrar la clasificación gravada/exenta pertinente y distinguir descanso, festivo y prima dominical sin duplicar el jornal.
- Integrar ajustes anuales autorizados, derechos y saldos de prestaciones; las consultas actuales no sustituyen ese flujo.
- Implementar control de saldos y soporte de préstamos/deducciones, operaciones masivas con resultado por empleado y conciliación central.
- Completar motores de SBC, cuotas, PTU y separación con parámetros explícitos y pruebas de límites, sin inventar parámetros patronales.
- Preparar XML de Nómina validable, catálogo vigente y flujo de respuestas y reintentos; la configuración preparatoria no constituye timbrado.

## Datos necesarios para cerrar pruebas específicas

Necesito banco y formato de dispersión por empresa para comprobar el archivo bancario. Necesito CSD y PAC configurados para comprobar timbrado real; el usuario indicó que aún no los tiene. Para cotejar SUA necesito parámetros patronales y datos revisados del ejercicio correspondiente. No detengo por esto los motores ni la interfaz independientes de esos datos.

Conservo además las pruebas físicas entre equipos y la firma compatible de la APK como pendientes de la suite. No los reduzco a un pendiente de Nómina ni presento la suite completa como certificada.
