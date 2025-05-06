# IgInterfaceAnalyzer


![IgInterfaceAnalyzer Logo](docs/logo.png)

**IgInterfaceAnalyzer** is a Python-based toolkit for identifying, comparing, and analyzing common interfaces across immunoglobulin (Ig) domains. Leveraging the **IgStrand numbering scheme** for standardized residue annotation, this project facilitates structural analysis of immunoglobulin interfaces at scale, enabling researchers to map conserved interaction patterns and assess their functional or evolutionary significance.

---

##  Motivation

Immunoglobulin (Ig) domains are central to immune system function and are widely used in therapeutic antibody engineering. However, structural variation across Ig interfaces can obscure key conserved features. **IgInterfaceAnalyzer** addresses this by:

- Standardizing residue-level annotation using **IgStrand** numbering.
- Extracting and comparing interfaces across multiple Ig-containing protein structures.
- Enabling quantitative and qualitative interface analysis to reveal conserved contact patterns.

---

## Features

- **IgStrand Numbering Integration**: Map interface residues onto the standardized IgStrand numbering system.
- **Interface Comparison**: Compare residue-level interfaces across multiple structures to identify commonalities.
- **Shared Interface Mapping**: Visualize conserved contacts across different Ig interfaces.
- **Batch Processing**: Handle large sets of structural models, such as AlphaFold2-predicted proteomes.
-  **Flexible Input Formats**: Supports PDB, mmCIF, and AlphaFold model formats.


---


---

##  Installation

```bash
git clone https://github.com/umeshkhaniya//IgInterfaceAnalyzer.git
cd IgInterfaceAnalyzer
pip install -r requirements.txt
