---
name: Reporte de fallo tecnico
about: Plantilla estandar para el registro, diagnostico y resolucion de fallos en la infraestructura.
title: '[INCIDENCIA]: '
labels: bug, laboratorio
assignees: 'N0EV'
---

## Descripción del Fallo
Una descripción clara y concisa de la anomalía detectada en el servicio o infraestructura.

## Entorno de Laboratorio
*   Sistemas Operativos implicados:
*   Servicios o componentes afectados:
*   Rama o versión del repositorio:

## Pasos para Reproducir el Error
1. Ejecutar el comando o script:
2. Modificar el archivo de configuración en la ruta:
3. Intentar levantar el servicio mediante:
4. Comprobar el fallo obtenido.

## Logs y Salida de Error (Troubleshooting)
Pega aquí la salida exacta de la terminal, archivos de log (`/var/log/`) o salidas de comandos de diagnóstico (`systemctl status`, `journalctl -xe`):

```bash
# Salida de error o logs
```

## Comportamiento Esperado
Descripción de cómo debería funcionar el servicio o script si la configuración fuese correcta.

## Posible Solución o Notas de Mitigación
Documentación técnica consultada o pasos previos aplicados para intentar solventar el fallo.