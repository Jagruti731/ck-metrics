# CK Metrics – Object-Oriented Software Metrics and Fault Prediction

A research companion website for the **CS6081 – Research Methods** module at the University of Limerick.

This project explores whether Chidamber–Kemerer (CK) object-oriented design metrics can help identify fault-prone software classes, and whether their predictive value remains after controlling for class size.

## 🌐 Live Website

**Main Website:**  
https://jagruti731.github.io/ck-metrics/

**Evidence Companion:**  
https://jagruti731.github.io/ck-metrics/ck_metrics_evidence_companion.html

**Detailed Literature Review:**  
https://jagruti731.github.io/ck-metrics/ck_metrics_detailed_literature_review.html

## 📚 Research Overview

The project reviews empirical research on CK metrics and their relationship with software defects.

The literature review follows the development of evidence across five key studies:

1. **Chidamber & Kemerer (1994)** – Introduced the CK metrics suite and examined its theoretical properties.
2. **Basili et al. (1996)** – Investigated whether object-oriented design metrics could predict faulty classes.
3. **El Emam et al. (2001)** – Examined the confounding effect of class size on metric validity.
4. **Subramanyam & Krishnan (2003)** – Investigated metric relationships with software defects across C++ and Java.
5. **Gyimóthy et al. (2005)** – Evaluated object-oriented metrics using a large open-source software system.

## 🔍 Key Research Finding

CK metrics can help identify fault-prone classes, but class size explains part of their apparent predictive power.

Coupling Between Objects (CBO) shows promising results in some studies, including evidence that remains after controlling for size in the C++ data examined by Subramanyam and Krishnan.

However, results vary across programming languages, datasets, fault definitions and research methods.

## 🧪 Proposed Research Direction

**Research Question:**

Does coupling (CBO) still predict faults once class size is controlled, across programming languages?

The proposed study considers:

- Six or more open-source projects.
- Java and C++ systems.
- All six CK metrics and Lines of Code (LOC).
- Bug-fix commits linked to individual classes.
- Regression analysis controlling for class size.

## 📂 Repository Structure

```text
ck-metrics/
│
├── index.html
├── ck_metrics_evidence_companion.html
├── ck_metrics_detailed_literature_review.html
└── README.md
```

## 🛠️ Technologies

- HTML5
- CSS3
- JavaScript
- GitHub Pages

The website is designed to be responsive and accessible through desktop and mobile browsers.

## 🚀 Deployment

This project is published using **GitHub Pages**.

To deploy updates:

1. Open the repository.
2. Upload or update the required files.
3. Commit changes to the `main` branch.
4. Ensure GitHub Pages is configured to deploy from the `main` branch and root folder.
5. Access the published website using the links above.

## 👥 Contributors

CS6081 – Research Methods

- Jagruti Badgujar
- Chirag Aggarwal
- Dhruv Punj
- Snehal Patil

## 📖 References

- Basili, V.R., Briand, L.C. and Melo, W.L. (1996).
- Chidamber, S.R. and Kemerer, C.F. (1994).
- El Emam, K., Benlarbi, S., Goel, N. and Rai, S.N. (2001).
- Gyimóthy, T., Ferenc, R. and Siket, I. (2005).
- Subramanyam, R. and Krishnan, M.S. (2003).

---

*Academic research project developed as part of CS6081 – Research Methods, University of Limerick.*
