# Formas de clasificar agentes

- por cómo piensan
- para qué sirven

# Definición y comparación conceptual de agentes(Vertical y horizontal):

- Agente horizontal: abarca múltiples dominios, entrenamiento con datos grandes y variados, despliegue rápido/menos costoso, alta adaptabilidad pero menor precisión en dominios específicos.

- Agente vertical: especializado en un dominio o flujo de trabajo, requiere datos sectoriales estructurados, ajuste profundo, mayor costo y mantenimiento, mayor precisión y trazabilidad.

- Enfoque híbrido: arquitectura que combina horizontales y verticales (no promedio), costo mayor por coordinación; recomendado cuando se requiere amplitud entre departamentos y profundidad en flujos especializados.

## Cinco elementos de comparación:

1. alcance vs profundidad
2. datos/entrenamiento
3. adaptabilidad
4. despliegue inicial
5. mantenimiento.

Ninguna opción es “mejor” universalmente; la elección depende de propósito, presupuesto y riesgos.

# Criterios para elegir tipo de agente (explicados)

Complejidad operativa: ¿el flujo atraviesa varios departamentos (ir horizontal) o exige conocimiento profundo de uno solo (ir vertical)?

Estado de los datos: ¿datos dispersos/generales o datos sectoriales estructurados y abundantes? — Un proyecto vertical falla si no hay datos de dominio.

Exigencias de la industria: regulación, auditoría, responsabilidad legal o coste del error — si la precisión demostrable y trazabilidad son críticas, optar por vertical.

Costos y mantenimiento: horizontales reducen esfuerzo de mantenimiento si el proveedor mejora el modelo; verticales requieren gobernanza, reglas y actualización continua.

Recursos técnicos y ventaja competitiva: comprar conviene si se necesita despliegue rápido y hay procesos estándar; construir (desarrollar) conviene si el proceso es ventaja competitiva, requiere control total de datos y la organización tiene equipo capaz.

# Decisión: comprar vs construir

- Comprar: cuando se necesita despliegue rápido, procesos estándar, soluciones preentrenadas disponibles y equipo técnico limitado.
- Construir: cuando el proceso es ventaja competitiva, se requiere control total sobre datos, reglas y comportamiento, y la organización puede sostener desarrollo y mantenimiento.

# Requisitos organizacionales y pasos previos a la adopción de agentes

1. Mapear procesos existentes: identificar cuellos de botella, pasos manuales y trabajo repetitivo.
2. Estandarizar y limpiar datos: homogeneizar formatos y asegurar datos completos y accesibles.
3. Elegir dónde entra el agente: priorizar procesos con volumen alto, reglas claras y resultados medibles.
4. Definir supervisión y medidas de éxito: establecer KPIs, línea base y control humano.
5. Preparar a las personas: capacitación, aclarar responsabilidades, límites y protocolos de supervisión humana antes del despliegue.

# Riesgos, gobernanza y ética

Riesgos mencionados: errores en vertical con alto coste (ej. contabilidad, salud), gasto descontrolado en consumo de tokens, adopción sin preparación que conduce a sabotaje o rechazo de la herramienta.

Gobernanza: necesidad de reglas, trazabilidad, supervisión humana y controles de presupuesto (ejemplo: Uber y consumo presupuestal).

Ética y legalidad: atención a datos sensibles, cumplimiento normativo (DOF, bloqueos a webscraping en sitios judiciales), y responsabilidad por decisiones automatizadas.

Instrucciones y fechas del trabajo integrador
