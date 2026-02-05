# Marketing Analytics & A/B Testing | SQL & Business Decision-Making

Proyecto de Marketing Analytics enfocado en optimización de conversión y toma de decisiones basada en datos. Incluye análisis de comportamiento de clientes, evaluación de un experimento A/B y resolución de consultas estratégicas en SQL para generar insights accionables de negocio.

---

## Tabla de contenidos
- [Business context](#business-context)
- [Objetivo](#objetivo)
- [Herramientas](#herramientas)
- [Metodología](#metodología)
- [Resultados principales](#resultados-principales)
- [Recomendaciones](#recomendaciones)
- [Dashboard (Tableau)](#dashboard-tableau)
- [Estructura del repositorio](#estructura-del-repositorio)

---

## Business context
Este proyecto simula un escenario real donde una empresa necesita optimizar desempeño operativo y validar decisiones estratégicas mediante análisis de datos.  
Se trabajó con tres casos complementarios:
1) eficiencia operativa en telecomunicaciones,  
2) evaluación de un test A/B en un funnel de conversión,  
3) consultas estratégicas mediante SQL.

---

## Objetivo
- Identificar operadores con bajo desempeño operativo y variables que explican ineficiencia.
- Evaluar estadísticamente el impacto de la variante B sobre la conversión del funnel.
- Responder preguntas estratégicas con SQL para apoyar decisiones de negocio.

---

## Herramientas
- Python (pandas, numpy, scipy, matplotlib)
- SQL
- Tableau Public
- Jupyter Notebook

---

## Metodología
**Caso Telecom**
- Limpieza y validación de registros de llamadas.
- Cálculo de métricas (llamadas perdidas, tiempos de espera, desempeño por operador).
- Segmentación por operador/cliente para detectar ineficiencias.

**Caso A/B**
- Construcción de funnel: product_page → product_card → purchase (ventana 14 días).
- Comparación de tasas de conversión entre control y variante.
- Pruebas estadísticas para validar significancia.

**Caso SQL**
- Consultas con joins y agregaciones para responder preguntas de negocio.
- Síntesis de resultados y hallazgos accionables.

---

## Resultados principales
- Se identificaron operadores con bajo desempeño que impactan la eficiencia general del servicio.
- El test A/B mostró diferencias en el funnel que permiten decidir si escalar o iterar la variante.
- Las consultas SQL entregaron insights útiles sobre catálogo/rendimiento y engagement.

---

## Recomendaciones
- Implementar monitoreo continuo de métricas operativas (pérdidas/espera) y acciones correctivas por operador.
- Si el A/B es significativo: escalar la variante ganadora; si no: iterar con nueva hipótesis y control de calidad de tráfico.
- Consolidar métricas clave en dashboards para seguimiento y toma de decisiones.

---

## Dashboard (Tableau)
🔗 https://public.tableau.com/views/DasboardCasoTelecomunicaciones/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

---

## Visualizaciones
![Dashboard](screenshots/dashboard.png)

---

## Estructura del repositorio
```bash
├── notebooks/
├── presentation/
├── dashboard/
├── data/
├── screenshots/
└── requirements.txt
