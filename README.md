# PteFBIC
# Exploiting Pterylotic Relationship for Fine-grained Bird Image Classification via Rachidian Orientation Learning

Fine-grained bird image classification (FBIC) plays an important role in ecological monitoring and biodiversity conservation, but it remains challenging due to camouflaged appearances, body occlusions, and diverse postures. To address these challenges, we propose **PteFBIC**, a pteryla-cue-aware framework that improves fine-grained discriminability by modeling inter-regional relationships among pteryla-related appearance cues. These cues reflect the regional organization of texture and color patterns, as well as their cross-region transitions and complementarities.
Specifically, we design a Pteryla Token Construction  module to generate pteryla-related tokens from orientation-enhanced feature representations. These tokens are then used for relationship modeling in the Pteryla Relationship Mining  module, which integrates global visual tokens and pteryla-related tokens to capture orientation-consistent texture organization, cross-region texture transitions, and complementary appearance variations. In addition, a Key Cue Extraction  module is introduced to aggregate multi-scale discriminative evidence, improving robustness to pose variations and local occlusions.

## 📌 Overview
<img width="1645" height="726" alt="image" src="https://github.com/user-attachments/assets/dd81847f-e4e9-4498-9f65-783379d5ab7d" />


## ✨ Key Contributions

- We propose **PteFBIC**, a novel framework for fine-grained bird image classification. By modeling pteryla-related appearance relationships across bird regions, PteFBIC effectively enhances discriminative representation learning and improves recognition performance. To the best of our knowledge, this is among the first attempts to introduce pteryla relationships as discriminative cues for fine-grained bird classification.

- We introduce two key modules to extract and exploit pteryla-related information from bird images. The **Pteryla Relationship Mining (PRM)** module captures regional dependencies among appearance patterns across different body regions, while the **Key Cue Extraction (KCE)** module aggregates multi-scale semantic information and identifies informative regions under the guidance of learned pteryla-related cues.

- Extensive experiments are conducted on two benchmark FBIC datasets, **CUB-200-2011** and **NABirds**. Experimental results show that PteFBIC consistently outperforms existing state-of-the-art methods. In addition, visualization analyses are provided to intuitively demonstrate the effectiveness of the learned pteryla-related appearance cues.
