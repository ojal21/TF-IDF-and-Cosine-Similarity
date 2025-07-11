## 🎬 Movie Plot Search Engine — TF-IDF & Cosine Similarity

**Databricks Notebook Link:** [View Project](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/2750839131378492/2703843189920629/8689822275567822/latest.html)

---

### 📌 Overview

A text-based movie search engine built using **PySpark** and **Databricks**, leveraging **TF-IDF vectorization** and **Cosine Similarity** to rank plot summaries by relevance to user queries. The project processes a large-scale dataset from the **Carnegie Movie Summary Corpus**.

---

### 🔧 Tools & Technologies

* **Platform:** Databricks
* **Processing:** PySpark, MapReduce
* **Text Vectorization:** TF-IDF
* **Similarity Metric:** Cosine Similarity
* **Dataset:** Carnegie Mellon Movie Summary Corpus

---

### ⚙️ Key Features

* Cleaned and preprocessed movie plot data using **PySpark**.
* Generated a **TF-IDF matrix** to represent document-term relevance.
* Implemented **Cosine Similarity** to compare user queries with plot vectors.
* Enabled flexible search with both **single-term and multi-term queries**.
* Returned the **Top 10 most relevant movie plots** per search query.

---

### 🧠 Enhancements

* Mapped **Wikipedia movie IDs** to human-readable names using metadata, improving usability.
* Designed the pipeline with modular MapReduce-style transformations for scalability.

---

### 🔍 Example Output

**Query:** `space exploration mission`

**Top Result:** *Interstellar*

**Matched Terms:** space, exploration, mission, wormhole

---
Note: This project was originally created during academic coursework using public datasets and entirely self-written code. It is shared solely for skill demonstration and not intended for academic reuse.


