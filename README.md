# 🔒 Práctica de Firewall: Simulador de Filtrado de IP en Python

Este repositorio contiene un script básico en Python que simula la lógica de un Firewall, evaluando direcciones IP de origen mediante una lista negra para autorizar o denegar el tráfico de red.

## 🚀 Instrucciones de Ejecución

1. Clona este repositorio o descarga el archivo fuente:

git clone

https://github.com/jonathangiovannyvz-ai/simulador-firewall-python

2. Ejecuta el script en tu terminal:

python3 simulador_firewall.py

También se puede ejecutar en el compilador en línea de Programiz.

Casos de prueba

- simular_firewall("203.0.113.5", 80) — IP en lista negra (bloqueada).
- simular_firewall("192.168.1.50", 443) — IP segura (permitida).

Resultado esperado

- La IP 203.0.113.5 muestra [BLOQUEADO] Tráfico denegado por reglas del Firewall.
- La IP 192.168.1.50 muestra [PERMITIDO] Conexión establecida exitosamente.

Archivos

- simulador_firewall.py — Código fuente del simulador.
- README.md — Documentación del proyecto.
```bash
