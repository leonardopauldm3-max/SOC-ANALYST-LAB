Análisis de conexión sospechosa - Puerto 4444

Contexto

Se detecta una conexión hacia el puerto 4444 desde un proceso desconocido.

Indicadores de sospecha

- Puerto 4444 - comúnmente asociado a backdoors
- Proceso - randomsvc.exe - nombre no estándar
- Frecuencia - conexión periódica (posible beaconing)

---

Análisis

El puerto 4444 no es de uso común en tráfico legítimo, y suele estar relacionado con herramientas de acceso remoto malicioso.

El proceso no corresponde a un servicio estándar del sistema operativo.

La periodicidad de la conexión sugiere comportamiento automatizado.

---

Acciones recomendadas

- Verificar ubicación del proceso
- Analizar si persiste en el arranque
- Investigar reputación de la IP
- Revisar logs del sistema

---

Conclusión

Alta probabilidad de actividad maliciosa. Se recomienda tratar como incidente de seguridad.
