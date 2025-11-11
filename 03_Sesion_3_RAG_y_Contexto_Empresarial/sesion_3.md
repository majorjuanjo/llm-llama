# Sesión 3 — RAG y Contexto Empresarial

Pipeline: chunk → embed → index → retrieve → generate.
Meta: respuestas con cita y trazabilidad.

{% hint style="danger" %}⛔ Advertencia (Privacidad): No indexar PII sin anonimizar (LFPDPPP). Revisa Legal/Compliance Kit primero.{% endhint %}
{% hint style="success" %}✅ Recomendación (Calidad): Define 5–10 golden questions y mide precisión, recall y faithfulness. Objetivo inicial: >80% precisión en preguntas clave.{% endhint %}
{% hint style="warning" %}⚠️ Aviso (Chunking): Ajusta `CHUNK_SIZE` 300–800 y `CHUNK_OVERLAP` 10–80 según tipo de documento.{% endhint %}
{% hint style="info" %}ℹ️ Notificación: Usa `templates/sesion-3/rag-setup-basic.py` para una prueba guiada con Chroma + OllamaEmbeddings.{% endhint %}

> [!CAUTION] No PII sin anonimizar.
> [!TIP] Golden questions para medir progreso.
> [!WARNING] Ajusta chunk size según densidad semántica.

Se añadirá guía avanzada y métricas evaluación.
