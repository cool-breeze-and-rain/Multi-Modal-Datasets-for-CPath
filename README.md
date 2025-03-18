# Multi-Modal-Datasets-for-CPath
This repository provides a comprehensive list of multi-modal datasets for computational pathology (CPath). The datasets are categorized based on their data type, description, staining, data source, and other attributes. Staining type: H: H&E, I: IHC, O: Others.

## Table of Contents

- [Image-Text Pair Datasets](#image-text-pair-datasets)
- [Multi-Modal Instruction Datasets](#multi-modal-instruction-datasets)
- [Acknowledgements](#acknowledgements)

---
<a id="image-text-pair-datasets"></a>
## Image-Text Pair Datasets

### 1. **QUILT**

- **Data Type:** Tile-Caption Pair
- **Description:** 437,878 tiles paired with 802,404 captions extracted from 4,475 videos.
- **Staining:** H, I, O
- **Data Source:** YouTube
- **Public/Private:** Public
- **Method:** QUILT-1M
- **LLM Assisted:** ❌

---

### 2. **PathCap**

- **Data Type:** Tile-Caption Pair
- **Description:** 208k pathology tile-caption pairs.
- **Staining:** H, I, O
- **Data Source:** PubMed
- **Public/Private:** Public
- **Method:** PathCLIP
- **LLM Assisted:** ❌

---

### 3. **OpenPath**

- **Data Type:** Tile-Caption Pair
- **Description:** 208,014 tile-caption pairs.
- **Staining:** I, O
- **Data Source:** WSI-Twitter, Repositories, Internet
- **Public/Private:** Public
- **Method:** PLIP
- **LLM Assisted:** ❌

---

### 4. **CONCH**

- **Data Type:** Tile-Caption Pair
- **Description:** 1,170,674 tile-caption pairs.
- **Staining:** H, I,
- **Data Source:** PMC-OA
- **Public/Private:** Public
- **Method:** CONCH
- **LLM Assisted:** ❌

---

### 5. **HistGen**

- **Data Type:** WSI-Report Pair
- **Description:** A WSI-report dataset with 75,723 pairs.
- **Staining:** H,
- **Data Source:** PMC-OA
- **Public/Private:** Public
- **Method:** HistGen
- **LLM Assisted:** ❌

---

### 6. **Mass-3QK**

- **Data Type:** WSI
- **Description:** 335,665 WSIs across 20 organs.
- **Staining:** H, M, I
- **Data Source:** GTEx
- **Public/Private:** Private
- **Method:** TITAN
- **LLM Assisted:** ❌

---

### 7. **CAPTION-PATCH CAPTION**

- **Data Type:** Tile-Caption Pair
- **Description:** 10.5 million tile-caption pairs from diverse datasets.
- **Staining:** H, I, O
- **Data Source:** TCGA
- **Public/Private:** Public
- **Method:** PathGen-CLIP
- **LLM Assisted:** ❌

---

### 8. **MUNICH**

- **Data Type:** WSI-Report Pair
- **Description:** 15,129 paired WSIs and pathology reports from 6,705 patients.
- **Staining:** I
- **Data Source:** TCGA
- **Public/Private:** Public
- **Method:** HistGenGPT
- **LLM Assisted:** ❌

---

### 9. **PCAPTION-C**

- **Data Type:** Tile-Caption Pair
- **Description:** 1,409,058 tile-caption pairs, removing non-human pathology data and filtering out pairs with <20 words.
- **Staining:** H, I, O
- **Data Source:** PMC-OA, QUILT-1M
- **Public/Private:** Public
- **Method:** PA-LaVA
- **LLM Assisted:** ✅

---

### 10. **ARCHI**

- **Data Type:** Bag-Caption Pair
- **Description:** 21,186 bags and 15,164 images, each bag containing multiple tiles. Diverse dataset of 33,480 tile-caption pairs.
- **Staining:** H, I, O
- **Data Source:** PubMed
- **Public/Private:** Public
- **Method:** PathBench
- **LLM Assisted:** ❌

---

### 11. **MI-ZERO**

- **Data Type:** Tile-Caption Pair
- **Description:** Tile-caption pairs from educational resources.
- **Staining:** H, I, O
- **Data Source:** ARCHI
- **Public/Private:** Public
- **Method:** ARCHI
- **LLM Assisted:** ❌

---
<a id="multi-modal-instruction-datasets"></a>
## Multi-Modal Instruction Datasets

### 1. **PathInstrucT**

- **Data Type:** Tile-Level Instruction
- **Description:** 180k pathology multi-modal instruction-following samples.
- **Staining:** H, I, O
- **Data Source:** YouTube
- **Public/Private:** Public
- **Method:** PathInstrucT
- **LLM Assisted:** ❌

---

### 2. **CAPTION-PATCH Instruction**

- **Data Type:** Tile-Level Instruction
- **Description:** 351,871 tile-level samples, including tile-caption pairs, VQA pairs, and instructions for classification and prompting tasks.
- **Staining:** H
- **Data Source:** CAPTION-VQA, PathGen, CAPTION-PATCH
- **Public/Private:** Public
- **Method:** CPath-Omni
- **LLM Assisted:** ✅

---

### 3. **CAPTI-WSI Instruction**

- **Data Type:** WSI-Level Instruction
- **Description:** 7,312 WSI-level samples, including captioning, VQA, and classification.
- **Staining:** H
- **Data Source:** HistGen
- **Public/Private:** Public
- **Method:** CAPTI
- **LLM Assisted:** ❌

---

### 4. **QUILT-Instruct**

- **Data Type:** VQA Pair
- **Description:** 107,131 question/answer pairs.
- **Staining:** H
- **Data Source:** YouTube
- **Public/Private:** Public
- **Method:** QUILT-Instruct
- **LLM Assisted:** ❌

---

### 5. **PathCapQ&A Bench**

- **Data Type:** Tile-Level Instruction
- **Description:** 456,916 instructions with 999,022 question-and-answer pairs.
- **Staining:** H
- **Data Source:** PMC-OA, TCGA
- **Public/Private:** Public
- **Method:** PathCapBench
- **LLM Assisted:** ✅

---

### 6. **CLOVER**

- **Data Type:** Instruction
- **Description:** 45k question-and-answer instruction pairs.
- **Staining:** I
- **Data Source:** PathVQA
- **Public/Private:** Public
- **Method:** CLOVER
- **LLM Assisted:** ❌

---
<a id="acknowledgements"></a>
## Acknowledgements

This repository was curated based on datasets used in computational pathology research. Thank you to the respective authors and contributors for making these datasets available.

For any questions, feel free to raise an [issue](https://github.com/cool-breeze-and-rain/Multi-Modal-Datasets-for-CPath/issues/new) or contact us.

---

Happy coding! 🚀
