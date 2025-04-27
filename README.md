# Multimodal NER for Quantitative Recognition

This project focuses on extracting **measurement-related entities** such as weight, dimensions, and other quantities from images by combining **text** and **visual** information.

The system uses **OCR** to extract text from images, applies **entity recognition** using the **BIO tagging** scheme, and then refines the outputs using **regular expressions** to ensure consistent formatting and unit standardization.

---

## 📂 Project Overview

- **OCR Preprocessing**: Extract text from images.
- **Entity Recognition**: Identify measurement entities using BIO tagging.
- **Postprocessing**: Clean and standardize measurements using regex (e.g., normalize units like "kg", "g", "lb").

---

##  How It Works

1. Perform OCR on input images to extract text.
2. Apply entity recognition to label measurements within the text.
3. Use regex-based cleaning to standardize and refine the extracted measurement entities.
