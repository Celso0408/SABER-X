# Open Experimental X-ray Datasets & Portals (Synchrotron + Benchtop)

A compact, curated list of **open-access** datasets/portals for experimental X-ray data.
Sections are split into **synchrotron** sources and **benchtop** (lab) X-ray collections.

---

## Synchrotron data (multi-facility portals)

* **PaNOSC Open Data Portal** – federated search across major European photon/neutron facilities (ESRF, MAX IV, PSI/SLS, SOLEIL, etc.); find XRD, PDF/total scattering, XAS, GI(W)AXS datasets with DOIs. ([data.panosc.eu][1])
* **ESRF & partner ICAT portals (via PaNOSC)** – facility landing pages and DOIs reachable from the PaNOSC search. ([data.panosc.eu][1])
* **Canadian Light Source (CLS) – FRDR collections** – public records for CLS datasets (XAS, XRD, etc.), including bulk downloads (Globus). ([frdr-dfdr.ca][3])
* **MDF (Materials Data Facility) – APS HEDM / diffraction** – e.g., SrTiO₃ high-energy X-ray diffraction microscopy datasets from APS 1-ID. ([acdc.alcf.anl.gov][4])

## Synchrotron XAS (reference spectrum libraries)

* **RefXAS (DAPHNE4NFDI)** – open database with QC’d XANES/EXAFS + metadata; actively maintained with FAIR principles. ([xafsdb.ddns.net][5])
* **CLS XASDB** – Canadian Light Source’s open XAS database (periodic-table browser; batch plotting & downloads). ([xasdb.lightsource.ca][6])
* **SSRL XAFS Library** – long-standing reference library (mostly transmission EXAFS/XANES). ([www-ssrl.slac.stanford.edu][7])
* **IXAS / Farrel Lytle EXAFS archive** – historical EXAFS scans curated by IXAS. ([ixs.iit.edu][8])

## Synchrotron diffraction / total scattering (examples & portals)

* **PaNOSC portal** – find HR-XRD, GI(W)AXS, and **PDF** (total scattering) datasets across facilities via a single search. ([data.panosc.eu][1])
* **MDF example** – SrTiO₃ 3D microstructure (HEDM) datasets from APS (with metadata & access instructions). ([acdc.alcf.anl.gov][4])

## Combined XAS + XRD datasets (same specimens)

* **Arsenic minerals (28 species)** – CLS **XAS (As K)** + **XRD** reference set (open via FRDR; described in Data in Brief). Ideal for LCF and cross-technique validation. ([frdr-dfdr.ca][9])
* **Molybdenum minerals (15 species)** – CLS **XAS (Mo K & LIII)** + **XRD** dataset (open via FRDR; Data in Brief). ([frdr-dfdr.ca][10])

---

## Benchtop (lab) X-ray datasets

* **opXRD – Open Experimental Powder X-ray Diffraction Database** – the largest open collection of **experimental** pXRD diffractograms (single/multiphase; powders & some thin films). Great for ML benchmarking and reference matching. ([advanced.onlinelibrary.wiley.com][11])
* **Materials Cloud Archive (selected records)** – many community-contributed archives include **lab XRD** alongside synchrotron data; searchable by material (e.g., SrTiO₃). ([archive.materialscloud.org][12])
* **NOMAD Repository (experimental domain)** – FAIR repository hosting **experimental** materials data (including XRD/XPS etc.) with structured metadata and search. ([nomad-lab.eu][13])

---

### Notes

* Most portals above provide **DOIs**, standardized **metadata**, and bulk download options (e.g., **Globus** for FRDR). ([frdr-dfdr.ca][3])
* For pipeline building (e.g., Rietveld + PDF + EXAFS), a good pattern is: **PaNOSC** for synchrotron raw data → **opXRD** for benchtop references → **RefXAS/XASDB** for reference spectra. ([data.panosc.eu][1])

---

*PRs welcome:* If you know other **open** X-ray datasets (synchrotron or benchtop) with persistent identifiers and redistribution rights, add them here.

[1]: https://data.panosc.eu/?utm_source=chatgpt.com "Open Data Portal · PaNOSC"
[2]: https://www.youtube.com/watch?v=mawSWk1ZHrU&utm_source=chatgpt.com "The RefXAS database: Current Status and Future Plans ..."
[3]: https://www.frdr-dfdr.ca/repo/dataset/3b13c7b1-8845-45d6-b1e9-1c4613205461?utm_source=chatgpt.com "Canadian Light Source XAS Database Data | FRDR-DFDR"
[4]: https://acdc.alcf.anl.gov/mdf/detail/12b54dfc-0584-4665-9a56-595ec6dcac85-1.0/?utm_source=chatgpt.com "Grain Growth Study of SrTiO3: 3D Microstructure Datasets ..."
[5]: https://xafsdb.ddns.net/?utm_source=chatgpt.com "RefXAS - Home"
[6]: https://xasdb.lightsource.ca/?utm_source=chatgpt.com "XAS Database"
[7]: https://www-ssrl.slac.stanford.edu/mes/spectra/index.html?utm_source=chatgpt.com "MEIS - Spectra Library"
[8]: https://ixs.iit.edu/database/?utm_source=chatgpt.com "IXAS XAFS database"
[9]: https://www.frdr-dfdr.ca/repo/dataset/019dd0ba-de36-4d92-be04-e560f7ae1abf?utm_source=chatgpt.com "X-ray absorption spectroscopy and X-ray diffraction data for ..."
[10]: https://www.frdr-dfdr.ca/repo/dataset/45a70a9c-3869-4245-a070-1aae83a319c1?utm_source=chatgpt.com "X -ray absorption spectroscopy and X-ray diffraction data ..."
[11]: https://advanced.onlinelibrary.wiley.com/doi/10.1002/aidi.202500044?utm_source=chatgpt.com "opXRD: Open Experimental Powder X‐Ray Diffraction Database"
[12]: https://archive.materialscloud.org/?utm_source=chatgpt.com "Materials Cloud Archive"
[13]: https://nomad-lab.eu/?utm_source=chatgpt.com "NOMAD"
