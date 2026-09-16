
# Caso 3 - Control de frecuencia del transporte público

Recorrido de un GPS hasta la alerta

```text
GPS del bus
   ↓
Simulador agrega ruido / rebote / desorden / silencio
   ↓
Web Worker
   ↓
Rejilla espacial (RF-1)
   ↓
Candidatos de segmentos
   ↓
Programación dinámica simple:
distancia al segmento + transición de avance (RF-2)
   ↓
posición en metros / progreso monótono (RF-3)
   ↓
orden de buses por ruta (RF-5)
   ↓
intervalo vs frecuencia programada
   ↓
< 40%  → bunching
>160%   → hueco
   ↓
alerta temprana
   ↓
propuesta de retención (RF-6)
```

