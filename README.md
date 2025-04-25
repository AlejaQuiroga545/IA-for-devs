# Desafío IA: Transformando un proceso tradicional

## 1. Introducción

En este documento se analiza cómo el proceso de reclutamiento de personal a través de plataformas de empleo puede optimizarse mediante el uso de inteligencia artificial (IA). Se ha seleccionado como caso de uso la **revisión y filtrado de currículums (CVs)**, una etapa clave pero tradicionalmente lenta y propensa a sesgos humanos en el área de recursos humanos.

## 2. Descripción del proceso tradicional

**Situación actual:**  
En muchas empresas, los reclutadores reciben cientos o miles de CVs para cada vacante publicada en plataformas de empleo como LinkedIn, Indeed o Computrabajo. El proceso habitual implica que una persona revise manualmente cada currículum, buscando coincidencias con los requisitos del puesto.

**Problemas o limitaciones del método tradicional:**
- **Tiempo elevado de revisión**, especialmente en vacantes con alta demanda.
- **Sesgos subjetivos** en la selección (edad, género, universidad, etc.).
- **Inconsistencia** en los criterios de evaluación entre diferentes reclutadores.
- **Dificultad para identificar talento oculto** o no evidente a simple vista.
- **Poca trazabilidad** de decisiones de rechazo o preselección.

## 3. Propuesta de solución con IA

**Objetivo de la solución:**  
Implementar un sistema de revisión automatizada de CVs utilizando IA, que permita clasificar, filtrar y priorizar candidatos de forma rápida, objetiva y eficiente.

**Descripción de la solución IA:**  

- **Tecnología empleada:**  
  - **Procesamiento de lenguaje natural (NLP):** Para analizar el contenido de los CVs.
  - **Modelos de clasificación y scoring predictivo:** Para asignar un puntaje a cada CV según su compatibilidad con el perfil buscado.
  - **Algoritmos de detección de sesgos:** Para mitigar decisiones discriminatorias.

- **Integración en el flujo:**  
  1. La plataforma de empleo recibe los CVs.
  2. El sistema de IA analiza automáticamente cada documento:
     - Extrae información clave: experiencia, educación, habilidades técnicas, idiomas, etc.
     - Evalúa la compatibilidad con la vacante.
     - Asigna una puntuación y ordena los CVs por relevancia.
  3. El reclutador recibe una lista priorizada con los mejores perfiles.
  4. Se habilita revisión manual para casos especiales o finales.

**Beneficios esperados:**  
- **Reducción del tiempo de revisión** en más del 70%.  
- **Mayor objetividad y transparencia** en la selección.  
- **Identificación de talento más relevante**, incluso si no usa las palabras clave exactas.  
- **Trazabilidad de decisiones** con reportes generados automáticamente.  
- **Escalabilidad:** puede aplicarse simultáneamente a múltiples vacantes.

## 4. Comparativa entre procesos

| Aspecto                    | Proceso Tradicional              | Solución con IA                          |
|----------------------------|----------------------------------|------------------------------------------|
| Tiempo de revisión         | Lento y manual                   | Rápido y automático                      |
| Criterios de selección     | Subjetivos y variables           | Uniformes y basados en datos             |
| Costo operativo            | Elevado                          | Bajo                                     |
| Escalabilidad              | Limitada a la capacidad humana   | Alta, sin necesidad de escalar personal  |
| Sesgo en decisiones        | Frecuente                        | Mitigado mediante algoritmos específicos |
| Precisión en filtrado      | Media, propensa a errores        | Alta, basada en modelos entrenados       |

## 5. Reflexión personal

Este ejercicio pone en evidencia cómo los procesos de selección de talento pueden beneficiarse enormemente del uso de la inteligencia artificial. No solo mejora la **eficiencia** y **objetividad**, sino que también permite **descubrir talento oculto** al que los métodos tradicionales no llegan. Sin embargo, la implementación ética de la IA es clave. Es fundamental entrenar los modelos con datos diversos, auditar periódicamente los resultados y siempre mantener la supervisión humana en decisiones críticas para evitar consecuencias discriminatorias o injustas.
