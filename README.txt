CONTROL DE MATERIALES - PROYECTO ANDROID

Incluye:
- Inventario de materiales: unidades, peso promedio por unidad (kg), precio promedio por unidad (COP).
- Edición y eliminación de materiales.
- Registro de pedidos con nombre, cédula, teléfono y varios materiales.
- Cálculo de peso y valor estimado del pedido.
- Descuento automático de inventario al guardar.
- Validación para impedir pedidos por encima de las existencias.
- Historial de pedidos.
- Datos locales en el almacenamiento del WebView; no requiere internet.

IMPORTANTE SOBRE LOS DATOS:
Los datos se guardan localmente en el almacenamiento de la aplicación. No borres los datos de la app ni la desinstales sin exportar/respaldar primero; esta primera versión todavía no incluye copia de seguridad.

CÓMO GENERAR EL APK:
1. Instala Android Studio en un computador.
2. Abre la carpeta ControlMateriales con Android Studio.
3. Espera la sincronización de Gradle. Se requiere conexión la primera vez para descargar el complemento de Android.
4. Selecciona Build > Build Bundle(s) / APK(s) > Build APK(s).
5. Android Studio mostrará la ubicación del APK generado (normalmente app/build/outputs/apk/debug/app-debug.apk).
6. Copia el APK al teléfono Android e instálalo. Puede pedir autorización para instalar apps de esa fuente.

SUPUESTOS DE ESTA VERSIÓN:
- El peso promedio se registra en kg por unidad.
- El precio promedio se registra en COP por unidad.
- El pedido usa esos promedios para calcular peso y valor estimado.
