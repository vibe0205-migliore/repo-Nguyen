# ⚙️ Mechanical Engineering Repository

This repository contains machine designs, the common components library, and new development projects.

---

## 🚀 Getting Started (Setup)
Before starting any design work, please follow these steps to configure your workspace:

1. **GitHub Desktop**: Download and install [GitHub Desktop](https://desktop.github.com).
2. **Git LFS**: This repository uses Git Large File Storage for CAD files. Download it [here](https://git-lfs.github.com) and run the `git lfs install` command on your machine.
3. **SolidWorks Templates**: Configure SolidWorks (*Options > File Locations*) to point to the `_TEMPLATES` folder in this repository for both Document Templates and Sheet Formats.

---

## 🛠️ Mandatory Templates
It is **mandatory** to use the following templates for every new file created:


| Document Type | Template File Name |
| :--- | :--- |
| **Assembly** | `Assieme.asmprp` |
| **Part** | `Parte.prtprp` |
| **Drawing (A0)** | `STD-A0-ISO.SLDDRT` |
| **Drawing (A3)** | `STD-A3-ISO.SLDDRT` |

---

## 📂 Folder Structure
Every project or 2026 work order must strictly adhere to the following sub-folder structure:

*   **`00_DOCS`**: Technical documentation, project briefs, review minutes, and specifications.
*   **`01_ASS`**: Assembly and sub-assembly files (`.sldasm`).
*   **`02_PRT`**: Individual part files (`.sldprt`).
*   **`03_DRW`**: Manufacturing drawings and source drawing files (`.slddrw`).
*   **`04_PDF`**: Final PDF exports for production or delivery.

---

## 🔢 Coding & Naming System
To ensure file uniqueness, use the following prefixes for naming:

- **`A31000`**: Top Level Assemblies
- **`S21000`**: Sub-assemblies
- **`P11000`**: In-house Manufactured Parts
- **`[PREFIX]-0000`**: Common Components (e.g., `MOT-0001`, `FLG-0015`)

---

## ⚠️ Workflow & Rules
*   **No In-Context References**: Avoid using external references outside the specific project folder, except for the Common Library.
*   **Custom Properties**: Always fill out the Property Tab fields (Material, Description, Weight).
*   **Commits**: Write clear and concise commit messages in GitHub Desktop (e.g., *"Added chamfer for assembly clearance on P11200"*).
*   **Drafts**: Only export to `04_PDF` once the design has been reviewed and approved.
