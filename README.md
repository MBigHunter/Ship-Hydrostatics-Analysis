# 🚢 Ship Hydrostatics & Hull Surface Modeling (Maxsurf + SolidWorks + Excel)

[![Discipline](https://img.shields.io/badge/Discipline-Naval%20Architecture-0b7285?style=flat-square)](#)
[![Tools](https://img.shields.io/badge/Tools-Maxsurf%20%7C%20SolidWorks%20%7C%20Excel-364fc7?style=flat-square)](#)
[![Language](https://img.shields.io/badge/Report-Persian-7950f2?style=flat-square)](#)
[![Docs](https://img.shields.io/badge/Docs-English%20README-343a40?style=flat-square)](#)

A complete end-to-end naval architecture workflow developed at **Sharif University of Technology** under the supervision of **Dr. Khorasanchi**.  
This project reconstructs a full-scale hull from an **offset table**, generates a **faired NURBS surface**, performs **hydrostatic & intact stability analyses**, and **numerically validates** key outputs using independent **Excel-based calculations**.

> Technical report: **Persian** (PDF)  
> Repository documentation: **English** (this README)

---

## 📌 Highlights
- Converted **non-dimensional offsets → full-scale (1:1) hull geometry**
- Performed **curve fairing** and created a **high-quality NURBS surface** in **Maxsurf**
- Computed **hydrostatics** across drafts (e.g., displacement, KB, BM, GM, LCB)
- Verified results using **independent Excel numerical models**
- Generated **GZ curves** (intact stability) and **Bonjean curves** for longitudinal assessment

---

## 🧭 Table of Contents
- [Project Scope](#-project-scope)
- [Methodology](#-methodology)
- [Results](#-results)
- [Tools](#-tools)
- [Repository Structure](#-repository-structure)
- [How to Reproduce](#-how-to-reproduce)
- [Notes](#-notes)
- [Future Work](#-future-work)
- [Contact](#-contact)

---

## 🎯 Project Scope
This repository bridges:
1) classical **hydrostatics & stability theory**, and  
2) practical **computer-aided hull modeling** and **software verification**.

The core goal is not only producing a hull model, but also demonstrating **engineering integrity** through **cross-validation**.

---

## 🧪 Methodology
1. **Offset Processing (Scaling & Reconstruction)**
   - Non-dimensional offset tables converted to full-scale coordinates
   - Station/section curves reconstructed and checked for consistency

2. **Hydrostatic Analysis (Maxsurf Stability)**
   - Hydrostatic parameters computed across multiple drafts

3. **Numerical Verification (Excel)**
   - Independent hydrostatic computations implemented in Excel
   - Cross-check with Maxsurf outputs (error/consistency evaluation)

4. **Stability & Longitudinal Assessment**
   - Intact stability: **GZ curve**
   - Longitudinal assessment: **Bonjean curves**

---

## 📊 Results
### Key Plots (examples)
**3D Hull Geometry**
- `Media/Hull Design.png`  
![Hull Design](Media/Hull%20Design.png)

**Bonjean Curves**
- `Media/Bonjean Curve.png`  
![Bonjean Curve](Media/Bonjean%20Curve.png)

**Stability (GZ) Curve**
- `Media/Stability Curve 3.png`  
![GZ Curve](Media/Stability%20Curve%203.png)


---

## 🛠 Tools
- **Maxsurf Modeler & Stability**: Hull surface modeling + hydrostatics/stability
- **SolidWorks**: CAD refinement + `.STEP` export
- **MS Excel**: Offset conversion + numerical verification models

---

## 📂 Repository Structure
* **/Documents**: Project brief and the final Technical Report (PDF).
* **/Models**: Original Maxsurf (`.msd`) and SolidWorks (`.SLDPRT`, `.step`) files.
* **/Calculations**: Excel workbooks containing offset conversions and hydrostatic tables.
* **/Media**: Body plans, sheer plans, and high-resolution stability plots.
 
---

## 🔁 How to Reproduce
1) **Open the hull model**
- Maxsurf: `Models/*.msd`

2) **Run hydrostatics & stability**
- Use Maxsurf Stability (draft range / loading condition as defined in your report)

3) **Export CAD (optional)**
- SolidWorks: open `Models/*.SLDPRT`
- Export `.STEP` for interoperability

---

## 📝 Notes
- Reports and detailed derivations are provided in **Persian** under `/Documents`.
- Repository documentation is designed for international review and academic evaluation.
- If you use this repository for learning or extension, please cite or reference it appropriately.

---

## 🔭 Future Work
Potential extensions (research-oriented):
- CFD-based resistance prediction
- Seakeeping analysis
- Coupled hydrostatic–structural workflow
- Automation with Python/MATLAB for hydrostatics & plotting

---

## 📬 Contact
**Mohammad Aldaghi**  
Marine Engineering Student | Sharif University of Technology  
- Email: `Aldaghi34@gmail.com`  
- Email: `Moh.aldaghi84@sharif.edu`
