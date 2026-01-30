 # XR Video-Based Self-Avatar User Study Dataset
 
## Overview of the Study

This dataset contains the results of a user study evaluating **video-based self-avatars** in immersive Extended Reality (XR) environments, with a particular focus on **non-WEIRD populations** and full-body embodiment.

Participants experienced an immersive VR scenario set on the crater of a volcano, where they were required to walk along a path of narrow, non-contiguous tiles. The task involved demanding visuomotor coordination, full-body awareness, and passive haptics through physical floor steps. Tiles were progressively activated by matching the users' real hands with virtual neon hand cues placed on the ground, enhancing visuotactile feedback. Hand tracking was performed using Meta Quest 2. At the end of the path, participants were teleported to a calm and friendly virtual environment to freely explore their virtual body representation.

Each participant experienced the environment under two of the following **embodiment conditions**:

- **Virtual Reality (Control):** Default Meta Quest 2 virtual hands.
- **Chroma:** A color-based segmentation approach masking skin-colored regions; participants wore pink booties to ensure visibility of the feet.
- **Deep Learning:** A video-based self-avatar generated using a semantic segmentation algorithm.

After completing all conditions, participants filled in a subjective questionnaire assessing embodiment, presence, visual quality, and acceptability.

---

## Participants

The study was conducted with two distinct populations:

- **University Population:**  
  58 participants (54 students and 4 staff members), recruited from a university environment. Participation was voluntary and mainly attracted individuals interested in VR.

- **Local Population:**  
  33 participants recruited by a specialized local company, balanced by age (below and above 30 years old) and gender (approximately 50% female, 50% male). This group included participants with a wider range of skin tones, including 6 participants with black skin color.

---

## Dataset Contents

The dataset consists of two CSV files containing the subjective questionnaire results:

- `resultados_universitypopulation.csv`  
  Results from the university population study.

- `resultados_localpopulation.csv`  
  Results from the local population study.

Each file includes:
- Demographic information (age, gender, previous VR experience)
- Questionnaire responses:
  - 12 items related to **embodiment**
  - 7 items related to **presence**
  - 6 items related to **visual quality**
  - 4 items related to **acceptability**

---

## Citation

If you use this dataset, please cite the following publications:

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