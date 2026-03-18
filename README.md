# SOC Analyst Journey 🚀

## Sobre mí
Abogado en transición hacia ciberseguridad (Blue Team).

## Objetivo
Convertirme en analista SOC en 9 meses.

## Primer análisis de tráfico

### Caso:
Conexión detectada:

TCP    172.16.29.47:64871     13.69.116.105:443      ESTABLISHED     17344

### Análisis:

- IP local: 172.16.x.x → red privada
- IP externa: 13.69.116.105
- Puerto: 443 → HTTPS (normal)
- Estado: ESTABLISHED → conexión activa

### Proceso asociado:
msedge.exe

### Conclusión:
Tráfico normal asociado al navegador.


## 📈 Aprendizajes

- Identificación de IPs privadas vs públicas
- Interpretación de puertos
- Relación proceso → conexión
