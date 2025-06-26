# Tutorial of IsoPairFinder

This repository contains the source files for the **Tutorial of IsoPairFinder**, an interactive and comprehensive guide for using the IsoPairFinder R package. The tutorial covers installation, data preparation, running the workflow, and interpreting results, with step-by-step instructions and example datasets.

## Features

- **Step-by-step instructions** for installing and using IsoPairFinder
- **Demo data** and case studies for hands-on learning
- **Detailed data preparation guides** for xcms, MS-DIAL, and MZmine workflows
- **References and further reading** for advanced users
- Output in both HTML and PDF formats

## Repository Structure

- `index.qmd` – Abstract and introduction
- `quick_start.qmd` – Quick start guide
- `data_preparation.qmd` – Data preparation instructions
- `isoPairFinder_running.qmd` – Running IsoPairFinder
- `caseStudy.qmd` – Case study walkthrough
- `references.qmd` – Bibliography
- `images/` – Figures and images used in the tutorial
- `docs/` – Rendered HTML output (GitHub Pages site)
- `_quarto.yml` – Quarto configuration file

## Getting Started

### Prerequisites

- [Quarto](https://quarto.org/) (v1.0 or later)
- [R](https://www.r-project.org/) (v4.0 or later)
- Required R packages (see `quick_start.qmd` for installation commands)

### Build the Book

To render the tutorial locally:

```sh
quarto render
```

The output will be generated in the `docs/` directory for HTML.

### View Online

The latest version of the tutorial is available at:  
[https://doddlab.github.io/IsoPairFinder_Tutorials/](https://doddlab.github.io/IsoPairFinder_Tutorials/)

## Citing

If you use this tutorial or IsoPairFinder in your work, please cite the relevant references listed in [references.qmd](references.qmd).

## License

This tutorial is provided for academic and educational use. See the [LICENSE](https://github.com/DoddLab/IsoPairFinder_Tutorials/blob/main/LICENSE) file for details.

## Contact

For questions or feedback, please contact:

**Zhiwei Zhou**  
Department of Pathology, Stanford University  
Email: zhouzw@stanford.edu

---

**Source code:** [https://github.com/DoddLab/IsoPairFinder_Tutorials](https://github.com/DoddLab/IsoPairFinder_Tutorials)

## License
<a rel="license" href="https://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a> 
This work is licensed under the Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)