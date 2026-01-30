 # Conjunto de Datos del Estudio de Self-Avatares XR Basados en Vídeo
 
## Descripción General del Estudio

Este conjunto de datos contiene los resultados de un estudio de usuarios que evalúa **avatares propios basados en vídeo** en entornos inmersivos de Realidad Extendida (XR), con un énfasis particular en **poblaciones no-WEIRD** y en la **representación del cuerpo completa**.

Los participantes experimentaron un escenario inmersivo de Realidad Virtual ambientado en el cráter de un volcán, en el que debían caminar sobre un recorrido formado por baldosas estrechas y no contiguas. La tarea requería una alta coordinación visuo-motora, conciencia corporal completa y el uso de háptica pasiva mediante pequeños escalones físicos en el suelo. Las baldosas se activaban progresivamente cuando los participantes alineaban sus manos reales con unas manos virtuales luminosas (neón) proyectadas sobre el suelo, lo que reforzaba la retroalimentación visuotáctil.

El seguimiento de manos se realizó utilizando el sistema de *hand tracking* de Meta Quest 2. Al finalizar el recorrido, los participantes eran teletransportados a un entorno virtual tranquilo y amigable, donde podían explorar libremente su representación corporal virtual sin presión ni estrés.

Cada participante experimentó el entorno bajo al menos dos de las siguientes **condiciones**:

- **Realidad Virtual (Control):** Manos virtuales por defecto proporcionadas por Meta Quest 2.
- **Chroma:** Representación basada en un algoritmo simple de segmentación por color que enmascara regiones del color de la piel. Para garantizar la visibilidad de los pies durante el trayecto, los participantes usaron cubrecalzado de color rosa.
- **Deep Learning:** Avatar propio basado en vídeo generado mediante un algoritmo de segmentación semántica basado en aprendizaje profundo (deep learning).

Tras completar todas las condiciones, los participantes rellenaron un cuestionario subjetivo destinado a evaluar el embodiment, presencia, calidad visual y aceptabilidad.


## Participantes

El estudio se llevó a cabo con dos poblaciones diferenciadas:

### Población Universitaria

- 58 participantes (54 estudiantes y 4 miembros del personal).
- Reclutados en un entorno universitario.
- Participación voluntaria, principalmente de personas interesadas en la Realidad Virtual.

### Población Local

- 33 participantes reclutados por una empresa local especializada.
- Equilibrio por edad (menores y mayores de 30 años).
- Equilibrio de género (aproximadamente 50% mujeres y 50% hombres).
- Mayor diversidad de tonos de piel, incluyendo 6 participantes de piel oscura.

---

## Contenido del Conjunto de Datos

El conjunto de datos consta de dos archivos CSV que contienen los resultados de los cuestionarios subjetivos:

- `resultados_universitypopulation.csv`  
  Resultados correspondientes a la población universitaria.

- `resultados_localpopulation.csv`  
  Resultados correspondientes a la población local.

Cada archivo incluye:

- Información demográfica:
  - Edad
  - Género
  - Experiencia previa con Realidad Virtual
- Respuestas al cuestionario:
  - 12 ítems relacionados con la **encarnación**
  - 7 ítems relacionados con la **presencia**
  - 6 ítems relacionados con la **calidad visual**
  - 4 ítems relacionados con la **aceptabilidad**

---

## Citas

Si utilizas este conjunto de datos en tu investigación, por favor cita las siguientes publicaciones:

### BibTeX

```bibtex
@inproceedings\{sosa2025evaluating,
  title=\{Evaluating XR Beyond WEIRD Population: Study Replication for Video-Based Self-Avatars\},
  author=\{Sosa, Ester Gonzalez and Perez, Pablo and Morin, Diego Gonzalez and Orduna, Marta and Villegas, Alvaro\},
  booktitle=\{2025 IEEE International Conference on Artificial Intelligence and eXtended and Virtual Reality (AIxVR)\},
  pages=\{27--34\},
  year=\{2025\},
  organization=\{IEEE\}
\}

@article\{gonzalez2023full,
  title=\{Full body video-based self-avatars for mixed reality: from e2e system to user study\},
  author=\{Gonzalez Morin, Diego and Gonzalez-Sosa, Ester and Perez, Pablo and Villegas, Alvaro\},
  journal=\{Virtual Reality\},
  volume=\{27\},
  number=\{3\},
  pages=\{2129--2147\},
  year=\{2023\},
  publisher=\{Springer\}
\}
}