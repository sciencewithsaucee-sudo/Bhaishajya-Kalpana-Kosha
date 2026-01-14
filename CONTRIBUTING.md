# 🥣 Contributing to Bhaishajya Kalpana Kosha – Encyclopedia of Ayurvedic Formulations (Beta)

Thank you for your interest in contributing to the **Bhaishajya Kalpana Kosha** project! 🙏 This is an open, community-driven effort to digitize and organize classical Ayurvedic pharmaceutical knowledge for researchers, practitioners, and developers.

---

## 🧭 Project Overview

**Repository:** [Bhaishajya Kalpana Kosha (Beta)](https://github.com/sciencewithsaucee-sudo/Bhaishajya-Kalpana-Kosha)
**Author:** Dr. Sparsh Varshney
**License:** [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/)

This project provides structured data on classical Ayurvedic formulations in JSON format. Each entry includes ingredient lists, indications, dosage, anupana, and textual references, designed for both academic and clinical contexts.

---

## 🧩 How You Can Contribute

Contributions are welcome from students, scholars, developers, and Ayurveda enthusiasts! Here’s how you can help:

### 1. 🥣 Add or Improve Formulation Data

* Add new formulations from authoritative texts (e.g., *Sharngadhara Samhita*, *Bhavaprakasha*, *AFI*).
* Improve existing entries (correcting ingredients, Sanskrit spellings, or dosage details).
* Suggest structural improvements in the JSON schema.

### 2. 🧠 Suggest Features

Help improve the project scope by proposing new ideas such as:

* Filters (e.g., by Formulation Type: Churna, Vati, Asava).
* Search and sort algorithms for front-end application.
* Integration with AI tools for predicting potential drug interactions or equivalents.
* Cross-linking with the [Herb Database](https://github.com/sciencewithsaucee-sudo/herb-database) for ingredient analysis.

### 3. 💻 Improve Documentation

You can:

* Fix typos or grammar.
* Add missing explanations in README.
* Write tutorials or usage examples for researchers.

### 4. 🧪 Testing & Validation

* Verify data accuracy using authoritative Ayurvedic texts.
* Report inconsistencies via GitHub Issues.
* Suggest standardization (e.g., uniform unit measurements for dosage).

---

## ⚙️ Contribution Workflow

1.  **Fork** this repository
2.  **Clone** your fork

    ```bash
    git clone [https://github.com/your-username/Bhaishajya-Kalpana-Kosha.git](https://github.com/your-username/Bhaishajya-Kalpana-Kosha.git)
    ```

3.  **Create a new branch**

    ```bash
    git checkout -b feature/new-formulation
    ```

4.  **Make your changes** (edit JSON files, documentation, etc.)
5.  **Commit and push**

    ```bash
    git commit -m "Added data for [Formulation Name]"
    git push origin feature/new-formulation
    ```

6.  **Create a Pull Request** on GitHub

> 📘 **Note:** Please ensure your data sources are properly cited. Classical texts (e.g., *Bhaishajya Ratnavali*, *Chakradatta*) are the primary source of truth for this repository.

---

## 🔍 Data Format Example

```json
[
  {
    "name": "Triphala Churna",
    "type": "Churna",
    "category": "Digestive System",
    "main_ingredients": ["Haritaki", "Bibhitaki", "Amalaki"],
    "ingredients": "Haritaki (Terminalia chebula), Bibhitaki (Terminalia bellirica), Amalaki (Emblica officinalis) in equal parts.",
    "reference": "Bhavaprakasha / Sharngadhara Samhita",
    "indications": "Mild laxative (Anulomana), Eye health (Chakshushya), Rejuvenative (Rasayana), Constipation (Vibandha).",
    "dosage": "3-6 grams",
    "anupana": "Warm water or honey & ghee."
  }
]
```
---
## 🪷 Guidelines

* Maintain **accuracy** and **authenticity** based on classical texts.
* Use **IAST transliteration** or standard English spellings for Sanskrit terms where possible.
* Respect **open-data ethics** — do not plagiarize proprietary modern patent medicine data.
* Each formulation must have at least **one classical reference** mentioned.

---

## 🧾 Citation

If you use this database in your research, please cite the specific version you used.
The recommended citation for the **Beta** version is:

```bibtex
@dataset{varshney_sparsh_2025_bhaishajya,
  author       = {Varshney, Sparsh},
  title        = {{Bhaishajya Kalpana Kosha – Encyclopedia of Ayurvedic Formulations (Beta)}},
  month        = oct,
  year         = 2025,
  publisher    = {Amidha Ayurveda},
  version      = {1.0.0-beta},
  url          = {[https://www.amidhaayurveda.com/p/bhaishajya-kalpana-kosha.html](https://www.amidhaayurveda.com/p/bhaishajya-kalpana-kosha.html)}
}
```
---

## 🤝 Code of Conduct

This project follows the **Contributor Covenant Code of Conduct**. Please be respectful, inclusive, and open to discussion.

---

## 🌍 Vision

> “To create the world’s first open Ayurvedic data ecosystem — empowering research, startups, and education through open knowledge.”

---

### 💫 Join the Community

* 🌐 Website: [Amidha Ayurveda](https://amidhaayurveda.com)
* 🧵 GitHub Discussions: Use the Discussions tab for Q&A
* ✉️ Contact: For bugs, please [open an Issue](https://github.com/sciencewithsaucee-sudo/Bhaishajya-Kalpana-Kosha/issues). For questions, please [start a Discussion](https://github.com/sciencewithsaucee-sudo/Bhaishajya-Kalpana-Kosha/discussions).

---

**Together, let’s digitize Ayurveda for the future.** 🙌
