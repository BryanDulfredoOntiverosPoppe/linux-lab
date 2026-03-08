# Reporte de Analisis de Logs

**Archivo analizado:** sample.log
**Fecha del analisis:** 2026-03-08 18:35:13
**Total de entradas:** 500

---

## 1. Top 10 Direcciones IP

| Solicitudes | Direccion IP |
|-------------|--------------|
| 170 | 192.168.1.10 |
| 108 | 10.0.0.5 |
| 67 | 172.16.0.3 |
| 55 | 192.168.1.25 |
| 54 | 10.0.0.99 |
| 46 | 203.0.113.42 |

## 2. Distribucion por Severidad

| Nivel | Cantidad |
|-------|----------|
| FATAL | 68 |
| ERROR | 87 |
| WARNING | 91 |
| INFO | 254 |

## 3. Eventos por Hora

| Hora | Eventos |
|------|---------|
| 00:00 | 23 |
| 01:00 | 16 |
| 02:00 | 32 |
| 03:00 | 28 |
| 04:00 | 21 |
| 05:00 | 21 |
| 06:00 | 25 |
| 07:00 | 28 |
| 08:00 | 20 |
| 09:00 | 15 |
| 10:00 | 21 |
| 11:00 | 22 |
| 12:00 | 20 |
| 13:00 | 20 |
| 14:00 | 20 |
| 15:00 | 23 |
| 16:00 | 17 |
| 17:00 | 16 |
| 18:00 | 19 |
| 19:00 | 19 |
| 20:00 | 16 |
| 21:00 | 25 |
| 22:00 | 18 |
| 23:00 | 15 |

## 4. Top 5 Mensajes de Error

| Frecuencia | Mensaje |
|------------|---------|
| 57 | Connectiontimeoutafter30s |
| 31 | Authenticationfailedforuseradmin |
| 26 | OutofmemoryerrorinmoduleX |
| 21 | Databaseconnectionrefused |
| 20 | Failedtowritetodisk |

## 5. Resumen

- Sistema analizado con 500 eventos registrados
- 155 eventos requieren atencion (ERROR y FATAL)
- Analisis completado con herramientas UNIX estandar
