# CSV-Workflow-Automation-v1.1.0

## 📖 **Description**  
Third release of the CSV Workflow Automation Tool, now featuring **production-ready wafermap color coding**.  
Automates semiconductor deliverables by converting CSVs to Excel, generating pivot tables, validating End Test numbers, and creating wafermap visualizations for yield and defect tracking. Built with Python, Tkinter, OpenPyXL, and xlwings, it streamlines workflows and ensures reproducible, audit‑ready insights.

---

## 🚀 Features
- **CSV → Excel Conversion**  
  Converts raw CSV deliverables into structured Excel workbooks with professional formatting.  

- **Pivot Table Generation**  
  Automates fallout analysis by filtering `C1_MARK` values and calculating End Test fallout percentages.  

- **End Test Validation**  
  Locates and validates End Test numbers against reference tables, highlighting limit conditions.  

- **Wafermap Visualization (Production Color Codes)**  
  Deterministic wafermap coloring via defined `color_map`  
  Accurate `C1_MARK` lookup for ET mapping  
  Replicates workplace wafermap references for fidelity  

- **GUI Interface**  
  Tkinter‑based interface with:  
  - Scrollable status box for long logs  
  - Title and version labels for professional branding  
  - Developer attribution displayed in the interface  

---

## 🛠️ Tech Stack 
- Python (automation & GUI)  
- Tkinter (user interface)  
- OpenPyXL (Excel file handling)  
- xlwings (pivot tables & wafermap generation)  
- CSV (data parsing)  

---

## 📂 Sample Files 
- Input: [`DEMO_WAFERMAP_08.wmap.csv` ](https://github.com/roannelafuente/CSV-Workflow-Automation/blob/main/DEMO_WAFERMAP_08.wmap.csv)
- Output: [`DEMO_WAFERMAP_08.wmap.xlsx`](https://github.com/roannelafuente/CSV-Workflow-Automation/blob/main/DEMO_WAFERMAP_08.wmap.xlsx)
- Dashboard Screenshot: `CSV Workflow Automation Dashboard v1.1.0.png`  

These files are dummy inputs included for demonstration purposes only. They are synthetic examples and do not contain any client or company data. Their purpose is to allow recruiters and collaborators to quickly test the workflow and visualize the results.

---

## 📸 Screenshots
### GUI Dashboard
![GUI Dashboard](https://github.com/roannelafuente/CSV-Workflow-Automation-v1.1.0/blob/main/CSV%20Workflow%20Automation%20Dashboard%20v1.1.0.png)

---

## 🌟 Impact
- Reduces manual effort in semiconductor deliverables preparation by automating CSV → Excel conversions and pivot table generation.
- Ensures reproducibility and audit‑ready insights with deterministic wafermap color coding.
- Improves accuracy in yield and defect tracking through validated End Test numbers and C1_MARK lookup.
- Enhances usability with a polished GUI, making engineering workflows faster and more transparent.

---

## 📦 Download
The latest release (**v1.1.0**) with production wafermap color coding is available here:  
[➡️ Download CSV Workflow Automation Tool v1.1.0](https://github.com/roannelafuente/CSV-Workflow-Automation-v1.1.0/releases/tag/v1.1.0)

▶️ **Usage**:Run the .exe to launch the dashboard and explore the features.

---

## 👩‍💻 Author
**Rose Anne Lafuente**  
Licensed Electronics Engineer | Product Engineer II | Python Automation  
GitHub: [@roannelafuente](https://github.com/roannelafuente)  
LinkedIn: [Rose Anne Lafuente](www.linkedin.com/in/rose-anne-lafuente)
