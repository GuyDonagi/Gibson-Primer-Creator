# 🧬 Gibson Assembly Automator
https://gibson-primer-creator.streamlit.app/

Made by Guy Donagi for the Toporik lab. A streamlined automation tool designed to eliminate the manual bottleneck of PCR primer design for Gibson Assembly. 

This tool automates the entire pipeline of copying and pasting between Benchling, NEBuilder, and the NEB Tm Calculator. It parses annotated GenBank files, interacts with web-based assembly tools headlessly, verifies primer parameters, and outputs a formatted `.xlsx` order sheet ready for Sigma-Aldrich.

## 🛠️ Tech Stack
* **UI & Framework:** Streamlit
* **Browser Automation:** SeleniumBase
* **Data Manipulation:** Pandas
* **Bioinformatics:** Biopython
* **Excel Generation:** OpenPyXL

## 📖 Usage
* **Design in Benchling:** Assemble and annotate your plasmid in Benchling.
* **Export:** Click the ⓘ icon in the right-hand panel, scroll down, and export the file as .gb.
* **Upload:** Drag and drop the .gb file into the Gibson Assembly Automator interface.
* **Generate & Download:** Click "Generate Primers," review the diagnostic table for any Tm warnings, and download the .xlsx order form.

## 👨‍🔬 Author
Guy Donagi

M.Sc. Student in Plant Sciences and Genetics

Let's connect on [LinkedIn](https://www.linkedin.com/in/guy-donagi-47691522a)
