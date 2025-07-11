# 🔐 Abusive Content Analytics – Trust & Safety Intelligence

A data-driven project focused on detecting, analyzing, and predicting abusive or policy-violating content using advanced analytics and machine learning. Designed for Trust & Safety teams to proactively manage platform risk.

---

## 📌 Overview

This project tackles content moderation challenges by:

- Analyzing patterns in user-generated content
- Engineering behavioral and contextual risk indicators
- Training predictive models to classify high-risk content
- Enabling data-driven decisions for moderation pipelines and policy enforcement

---

## 🧠 Key Features

✅ **Comprehensive Dataset Profiling**  
✅ **Smart Feature Engineering** – Toxicity scores, age sensitivity, policy risk indicators, and more  
✅ **ML Classification Model** – Random Forest-based predictive analytics  
✅ **Ready for Dashboards** – Power BI/Tableau-ready metrics and flags  
✅ **Extensible Pipeline** – Structured for further model and API deployment  

---

## 🗂️ Dataset Summary

| Feature                     | Description                                                  |
|----------------------------|---------------------------------------------------------------|
| `content_type`             | Format: video, image, stream, thumbnail, etc.                 |
| `engagement_score`         | Normalized interaction metric                                 |
| `toxicity_score`           |  measure of abusive or harmful language                       |
| `misleading_title_flag`    | Binary flag for misleading metadata                           |
| `age_sensitivity_flag`     | Indicates content with potential age restrictions             |
| `upload_channel`, `device_type` | Source info for behavioral profiling                     |
| `policy_violation_risk`    | Model-generated risk score (classification output)            |

---
