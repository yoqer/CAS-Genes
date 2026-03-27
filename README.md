# CAS-Genes
El Plegamiento de Proteinas con los modelos basicos del comienzo de Alphafold. 

[Genes](https://github.com/yoqer/CAS-Genes/blob/main/Estudio_Gen%C3%B3mico_y_Modelos_de_Aprendizaje_Autom%C3%A1ti.md)


______________________________________________________________________________________________________________________________________

                      - 

# GUIA BASICA:



Tenga en cuenta que para realizar experimentos reales, necesitará formación especializada y *seguir las regulaciones de bioseguridad pertinentes.*

**Manual Básico de Diseño Genético con CRISPR-Cas9**

**1. Comprensión de CRISPR-Cas9:**
CRISPR-Cas9 es un sistema de edición genética que permite a los científicos alterar el ADN de organismos. Funciona cortando el ADN en un lugar específico, permitiendo así la edición del genoma.

**2. Identificación del Objetivo:**
- Determina el gen o secuencia de ADN que deseas modificar.
- Utiliza herramientas bioinformáticas para identificar una secuencia de ADN de 20 nucleótidos que sea única para el gen objetivo y seguida por una secuencia PAM (protospacer adjacent motif), típicamente NGG para el Cas9 de Streptococcus pyogenes.

**3. Diseño de la Guía de ARN (gRNA):**
- Diseña una secuencia de ARN guía (gRNA) complementaria a la secuencia objetivo.
- Utiliza herramientas en línea como CRISPR Design, [CHOPCHOP](https://chopchop.cbu.uib.no/). o [CRISPOR](https://crispor.tefor.net/) para ayudar en el diseño y evaluar la especificidad del gRNA.

  

**4. Construcción del Vector CRISPR:**
- Clona la secuencia del gRNA en un vector plasmídico que contenga el gen Cas9.
- Asegúrate de que el vector tenga un promotor adecuado para la expresión del gRNA y Cas9 en la célula objetivo.

**5. Preparación de las Células:**
- Selecciona las células que deseas modificar.
- Prepara las células para la transfección o transducción, siguiendo los protocolos estándar de cultivo celular.

**6. Entrega del Sistema CRISPR:**
- Introduce el vector CRISPR en las células utilizando métodos como la transfección liposómica, electroporación o virus.
- Optimiza las condiciones de entrega para maximizar la eficiencia y minimizar la toxicidad.

**7. Selección y Validación:**
- Selecciona células que han incorporado el vector CRISPR, si es necesario, utilizando marcadores de selección.
- Valida la edición genética mediante técnicas como PCR, digestión con enzimas de restricción, secuenciación del ADN o análisis de Western blot para proteínas.

**8. Análisis de las Modificaciones:**
- Analiza las modificaciones genéticas para confirmar que se ha producido el cambio deseado.
- Evalúa los efectos fenotípicos de la edición genética.

**9. Consideraciones Éticas y de Seguridad:**
- Asegúrate de cumplir con todas las regulaciones éticas y de bioseguridad aplicables.
- Considera los posibles efectos no deseados y las implicaciones éticas de la edición genética.

**10. Documentación y Reporte:**
- Documenta todos los pasos del experimento y los resultados obtenidos.
- Reporta los hallazgos siguiendo las normas de publicación científica.

Recuerda que este es un resumen muy básico y que la edición genética con CRISPR-Cas9 es una técnica compleja que requiere un conocimiento profundo de biología molecular y genética. Además, es importante estar al tanto de las regulaciones locales e internacionales que rigen la investigación con CRISPR.

