# Componentes de Callouts (Notificación, Advertencia, Aviso, Recomendación)

Objetivo
- Resaltar pasos críticos, riesgos, buenas prácticas y recordatorios sin saturar.

Sintaxis GitBook
- Info: {% hint style="info" %} ... {% endhint %}
- Warning: {% hint style="warning" %} ... {% endhint %}
- Danger: {% hint style="danger" %} ... {% endhint %}
- Success: {% hint style="success" %} ... {% endhint %}

Sintaxis GitHub (GFM callouts)
> [!NOTE] Texto
> [!WARNING] Texto
> [!CAUTION] Texto
> [!TIP] Texto

Ejemplos
{% hint style="info" %}ℹ️ Notificación: Revisa AI Strategy Compass antes de continuar.{% endhint %}
{% hint style="warning" %}⚠️ Aviso: En 8 GB RAM usa modelos 3B Q4.{% endhint %}
{% hint style="danger" %}⛔ Advertencia: No indexar PII sin anonimizar.{% endhint %}
{% hint style="success" %}✅ Recomendación: Define 5 golden questions para medir precisión.{% endhint %}

> [!NOTE] Equivalente info en GitHub.
> [!WARNING] Equivalente warning en GitHub.
> [!CAUTION] Equivalente danger en GitHub.
> [!TIP] Equivalente success en GitHub.

Guía de uso
- Máx 2–3 callouts por sección.
- Usar "danger" sólo para riesgos reales (PII, pérdida de datos, sanciones legales).
- Enlazar a recursos: ROI, Compliance, Troubleshooting.
