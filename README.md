<div align="center">

# Elder Care During COVID-19

**A machine-learning model to predict how severe COVID-19 is likely to be in older adults, built as a supporting task for my thesis.**

![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Machine learning](https://img.shields.io/badge/ML-severity%20prediction-blueviolet)
![Year](https://img.shields.io/badge/year-2021-lightgrey)
[![License: MIT](https://img.shields.io/badge/license-MIT-yellow)](LICENSE)

</div>

---

## About

Older people were among the most vulnerable to COVID-19, and early action made a big difference. My thesis proposed a **monitoring framework for elder care during the pandemic**. One of its features was a model that predicts how severe an infection is likely to be, so an older person or their caregiver can be **alerted to get tested early** and take steps toward treatment.

This repository was set up for that severity-prediction task.

```mermaid
flowchart LR
    D["Health and symptom data<br/>of an older person"] --> M["Severity prediction<br/>model"]
    M --> R{"Predicted<br/>risk"}
    R -- "high" --> A["Alert: get tested<br/>and seek care"]
    R -- "low" --> W["Keep monitoring"]
    A --> F["Elder-care monitoring<br/>framework"]
    W --> F
```

## Status

> **The notebook isn't published here.**
> `elder_care_during_covid-19_main.ipynb` is a placeholder. The notebook used in the final thesis paper was a newer version that couldn't be shared at the time, because the paper was still awaiting publication.

## License

[MIT](LICENSE) © 2026 tarekFerdous
