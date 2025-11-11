# Sesión 2 — Instalación y Agente Local

Objetivo: Ejecutar Llama local (Ollama/LM Studio) y estabilizar prompt v1.5.
Entregables: agente corriendo, medición de latencia, automatización básica (Make/n8n/Zapier).

{% hint style="warning" %}⚠️ Aviso (Hardware): Con 8 GB RAM usa modelos 3B Q4 y cierra apps pesadas. Si hay congelamientos, migra temporalmente a Cloud (Together/Groq/Colab).{% endhint %}
{% hint style="success" %}✅ Recomendación: Ejecuta `install-ollama.sh` (Mac/Linux) o `install-ollama.bat` (Windows) y valida con `test-llama.py`. Registra latencia en `log-iteraciones.csv`.{% endhint %}
{% hint style="info" %}ℹ️ Notificación: Antivirus corporativo bloqueando binarios → usa LM Studio GUI o ruta Cloud.{% endhint %}
{% hint style="danger" %}⛔ Advertencia: Evita descargar modelos grandes en red móvil (costos y cortes).{% endhint %}

> [!WARNING] 8 GB RAM = preferible modelo 3B Q4.
> [!TIP] Mide latencia y tokens para baseline.
> [!CAUTION] No descargas pesadas en datos móviles.

Secciones siguientes: Verificación, Parámetros, Troubleshooting (ver `templates/sesion-2/*`).
