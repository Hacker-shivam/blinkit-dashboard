# Blinkit Sales Dashboard (Power BI)

An interactive Power BI dashboard analyzing Blinkit's sales and operations KPIs.
This repository contains the `.pbix` file, documentation, and placeholders for data and screenshots.

## 📦 Repository Structure

```
Blinkit-Dashboard/
├─ Blinkit_Dashboard.pbix           # Power BI file
├─ README.md                        # You are here
├─ .gitattributes                   # Enables Git LFS for .pbix
├─ .gitignore
├─ LICENSE
├─ data/                            # Put sample or anonymized data (optional)
│  └─ .gitkeep
└─ screenshots/                     # Export dashboard images here
   └─ .gitkeep
```

## 🧰 Requirements
- **Power BI Desktop** (May 2023 or later recommended)

## 🚀 How to Use
1. Download this repository or the `Blinkit_Dashboard.pbix` file.
2. Open the `.pbix` in Power BI Desktop.
3. If your report uses local data, update file paths in **Transform Data ➜ Data source settings**.
4. Refresh the report and explore!

## 📸 Screenshots (Add later)
Export images from **File ➜ Export ➜ Export to PDF** or take PNGs and place them in `/screenshots`, then reference them below:
```
![Overview](screenshots/overview.png)
![Filters](screenshots/filters.png)
```

## 🗃️ Dataset
- Source: _Add public link or state "Proprietary dataset (not included)"._
- If sharing data is not allowed, include a small **sample** in `/data` and note the fields.

## 🧮 DAX / Power Query
If you want to document key measures or transformations, add them here or in a separate `docs/` folder.

## ⚠️ Large File Note (Git LFS)
Power BI files are large. GitHub blocks files **> 100 MB** unless you use **Git LFS**.
This repo is pre-configured to track `*.pbix` with LFS via `.gitattributes`.
On your machine, run once per machine (before your first commit):

```bash
git lfs install
git lfs track "*.pbix"
git add .gitattributes
git add Blinkit_Dashboard.pbix
git commit -m "Add PBIX tracked with LFS"
```

## 📄 License
This project is released under the MIT License. See `LICENSE` for details.
