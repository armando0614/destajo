# Sistema de Captura de Destajos - TODO

## Fase 1: Estructura de Base de Datos
- [x] Crear tabla de actividades (id, nombre, precio)
- [x] Crear tabla de destajistas (id, nombre, paquete_asignado)
- [x] Crear tabla de paquetes (id, nombre, manzana, lote)
- [x] Crear tabla de destajos (id, destajista_id, actividad_id, paquete_id, manzana, lotes, semana, cantidad, precio, importe, fecha_creacion)
- [x] Crear tabla de ubicaciones (id, datos_ubicacion)

## Fase 2: Backend - APIs y Procedimientos
- [x] API para obtener lista de actividades
- [x] API para obtener lista de destajistas
- [x] API para obtener lista de paquetes
- [x] API para obtener manzanas y lotes por paquete
- [x] API para crear nuevo destajo
- [x] API para obtener destajos por destajista
- [x] API para obtener destajos por semana
- [x] API para obtener resumen semanal por destajista
- [x] Implementar validación de campos obligatorios
- [x] Implementar cálculo automático de importe

## Fase 3: Frontend - Interfaz de Usuario
- [x] Crear layout principal con navegación
- [x] Crear página de inicio/dashboard
- [x] Crear formulario de captura de destajos
- [x] Implementar selector de destajista con búsqueda
- [x] Implementar selector de actividad con búsqueda
- [x] Implementar selector de paquete
- [x] Implementar selector de manzana
- [x] Implementar campo de lotes (múltiples separados por coma)
- [x] Implementar selector de semana
- [x] Implementar campo de cantidad
- [x] Mostrar cálculo automático de importe
- [x] Crear vista de hoja individual por destajista
- [x] Crear vista de resumen semanal
- [x] Crear tabla de destajos capturados

## Fase 4: Importación de Datos
- [x] Crear script de importación desde Excel
- [x] Importar actividades y precios
- [x] Importar destajistas y paquetes
- [x] Importar paquetes, manzanas y lotes
- [x] Importar ubicaciones

## Fase 5: Reportes y Exportación
- [x] Implementar generación de reporte semanal por destajista
- [x] Implementar exportación a Excel con formato original
- [x] Crear hoja de actividades en reporte
- [x] Crear hoja de resumen por destajista
- [x] Implementar descarga de archivo Excel

## Fase 6: Notificaciones y Características Avanzadas
- [x] Integrar notificaciones automáticas al administrador
- [x] Implementar envío de notificación al capturar destajo
- [x] Incluir detalles en notificación (destajista, actividad, paquete, monto)
- [x] Implementar validación de campos antes de guardar
- [x] Agregar confirmación visual de captura exitosa

## Fase 7: Pruebas y Refinamiento
- [x] Escribir pruebas unitarias para APIs
- [x] Escribir pruebas de integración
- [x] Pruebas de validación de formularios
- [x] Pruebas de cálculos de importe
- [x] Pruebas de exportación a Excel
- [x] Pruebas de notificaciones

## Fase 8: Despliegue
- [x] Revisar seguridad y permisos
- [x] Optimizar rendimiento
- [x] Crear documentación de usuario
- [x] Realizar pruebas finales
- [x] Desplegar aplicación


## Tareas Pendientes - Importación de Datos
- [x] Ejecutar script de importación de datos desde Excel
- [x] Verificar que los datos se importaron correctamente
- [x] Validar que actividades, destajistas y paquetes estén disponibles en la aplicación

## Bugs Reportados
- [x] Corregir error "paquete no encontrado" en formulario de captura
