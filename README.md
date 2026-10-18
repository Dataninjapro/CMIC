# CMIC — Confusion Matrix Interactive Calculator

![Version](https://img.shields.io/badge/version-1.0-blue)
![Platform](https://img.shields.io/badge/platform-Microsoft%20Excel-green)
![License](https://img.shields.io/badge/license-CC%20BY--ND%204.0-lightgrey)

**CMIC** is an interactive Excel-based calculator for evaluating binary classification performance using a standard confusion matrix.

Enter the four confusion-matrix counts — **TN, FP, FN, and TP** — and CMIC automatically calculates a set of commonly used classification metrics, provides descriptive status indicators, and links each metric to an integrated explanation.

---

## 📥 Available Editions

| Edition | File |
|---|---|
| 🇬🇧 English | [CMIC_v1.0_EN.xlsx](./CMIC_v1.0_EN.xlsx) |
| 🇮🇱 Hebrew | [CMIC_v1.0_HE.xlsx](./CMIC_v1.0_HE.xlsx) |

Both editions use the same calculation logic.  
They differ only in the language of the integrated **Method** guide and explanatory content.

---

## 📊 Metrics Included

CMIC 1.0 calculates:

- **Sensitivity / Recall**
- **Specificity**
- **Precision / Positive Predictive Value (PPV)**
- **Negative Predictive Value (NPV)**
- **Accuracy**
- **False Positive Rate (FPR)**
- **False Negative Rate (FNR)**
- **Balanced Accuracy**
- **F1 Score**
- **Cohen’s Kappa**

Each metric is accompanied by a **descriptive status indicator intended as a quick interpretive aid**.

The status labels are not universal statistical thresholds and should always be interpreted in context.

---

## ▶️ How to Use

1. Download the appropriate language edition.
2. Open the workbook in Microsoft Excel.
3. Enter the four confusion-matrix values in the editable input cells:
   - **TN** — True Negative
   - **FP** — False Positive
   - **FN** — False Negative
   - **TP** — True Positive
4. The confusion matrix, calculated metrics, and status indicators update automatically.
5. Click a metric name to open its explanation in the integrated **Method** sheet.
6. Use **Back to Calculator** to return to the main worksheet.

Only the intended input cells are editable.  
Calculation logic and supporting sheets are protected to preserve the integrity of the tool.

---

## 🧭 Interpretation Notes

CMIC is designed to support interpretation of classification performance — not to replace professional statistical judgment.

Metrics should be considered together and interpreted in the context of:

- class balance
- prevalence
- model purpose
- decision costs
- the relative importance of false positives and false negatives

### A note on Accuracy

Accuracy can be misleading in imbalanced datasets.

A classifier may achieve high Accuracy simply by predicting the majority class correctly while performing poorly on the minority class.

For this reason, CMIC also reports complementary measures such as:

- Sensitivity
- Specificity
- Precision
- Balanced Accuracy
- F1 Score
- Cohen’s Kappa

---

## 🔒 Workbook Protection

CMIC is distributed as a protected workbook.

The protection is intended to:

- preserve formulas and calculation logic
- prevent accidental editing of protected areas
- keep the interface and documentation intact

Only designated input cells are intended for user editing.

---

## 📜 License

CMIC is licensed under the  
**Creative Commons Attribution-NoDerivatives 4.0 International License (CC BY-ND 4.0).**

You may:

- use the original tool
- share the original tool
- redistribute it with appropriate attribution

Modified versions may not be distributed without permission.

**CMIC branding and author attribution should remain intact.**

See the [LICENSE](./LICENSE) file for full details.

---

## 👤 Author

**Meni Berger**  
**Data Ninja**

---

## 🏷️ Current Version

**CMIC 1.0**

Initial public release including:

- interactive confusion-matrix input
- automatic metric calculation
- descriptive status indicators
- integrated Method guide
- Hebrew and English editions
- protected calculation logic

---

## 🛠️ Planned Development

Potential additions for future releases include:

- **Prevalence**
- **Predicted Positive Rate**
- **Automatic class imbalance warning**
- **Matthews Correlation Coefficient (MCC)**

---

## ℹ️ About the Name

**CMIC** stands for:

**Confusion Matrix Interactive Calculator**
