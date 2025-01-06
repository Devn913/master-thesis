# Hypergraph-Driven Semi-Supervised Learning Approaches for Variants of SVMs

This repository contains the LaTeX source and supporting files for my Master's thesis, **"Hypergraph-driven Semi-Supervised Learning Approaches for Variants of SVMs"**, completed at the South Asian University under the supervision of **Dr. Reshma Rastogi**.

## Thesis PDF
You can download the compiled thesis PDF [here](output/thesis.pdf).

DOI: [Research Gate](http://dx.doi.org/10.13140/RG.2.2.11547.58401)

## Project Overview

The thesis explores two novel semi-supervised frameworks:
1. **[Improved Hypergraph Laplacian Support Vector Machine (IHLSVM)]((https://doi.org/10.1007/978-3-031-78192-6_16)):** Combines Laplacian and hypergraph representations to enhance pairwise and higher-order interactions for robust pattern classification.
2. **[Hypergraph Regularized Semi-Supervised Least Squares Twin Support Vector Machine (HMLLSTSVM)](https://doi.org/10.1007/978-3-031-78383-8_15):** A multilabel learning framework leveraging hypergraph Laplacians and least-squares loss, particularly effective for sparse label scenarios.

### Applications
The proposed methods excel in real-world tasks such as:
- Medical diagnosis
- Text classification
- Image annotation

## Key Features
- **Novel Algorithms:** IHLSVM and HMLLSTSVM.
- **Benchmark Evaluations:** Validated on standard datasets like Emotions, Flags, Image, and Yeast.
- **State-of-the-Art Comparisons:** Demonstrates superior classification and multilabel learning performance.

## Repository Structure
- `disssertation_main.tex`: LaTeX source for the thesis.
- `figures/`: Figures used in the thesis.
- `bibliography.bib`: Bibliography file for references.
- `output/`: Directory for compiled PDF output.

## Prerequisites
To compile the LaTeX source, ensure you have:
- A LaTeX distribution (e.g., TeX Live, MiKTeX).
- A LaTeX editor (e.g., Overleaf, Texmaker).

## How to Compile
1. Clone the repository:
   ```bash
   git clone https://github.com/devn913/master-thesis
   cd master-thesis
   ```
2. Compile the LaTeX file:
   ```bash
   pdflatex disssertation_main.tex
   bibtex disssertation_main
   pdflatex disssertation_main.tex
   pdflatex disssertation_main.tex
   ```
3. Alternatively, use [Overleaf](https://www.overleaf.com/) for online editing and compilation.

## Publications
- R. Rastogi and Dev Nirwal, “Hypergraph Regularized Semi-Supervised Least Squares Twin Support Vector Machine for Multilabel Classification,” *Lecture Notes in Computer Science*, Dec. 2024. (ICPR)
- R. Rastogi and Dev Nirwal, “Improved Hypergraph Laplacian Based Semi-Supervised Support Vector Machine,” *Lecture Notes in Computer Science*, Dec. 2024. (ICPR)

## Results
### Multi-label Dataset Summary
| Dataset  | Instances | Features | Labels | Cardinality |
|----------|-----------|----------|--------|-------------|
| Emotions | 593       | 72       | 6      | 1.87        |
| Flags    | 194       | 19       | 7      | 3.392       |
| Image    | 2000      | 294      | 5      | 1.24        |
| Yeast    | 2417      | 103      | 14     | 4.24        |
| Birds    | 645       | 260      | 19     | 2.08        |
| CAL500   | 502       | 68       | 174    | 26.04       |
| Enron    | 1702      | 1001     | 53     | 3.38        |
| Scene    | 2407      | 294      | 6      | 1.07        |

### Performance Highlights
- **[IHLSVM](https://doi.org/10.1007/978-3-031-78192-6_16):** Outperforms existing methods for binary and multi-class classification.
- **[HMLLSTSVM](https://doi.org/10.1007/978-3-031-78383-8_15):** Achieves state-of-the-art results in multilabel learning with sparse data.

## License
This project is licensed under the **MIT**. See the `LICENSE` file for details.

## Acknowledgments
Special thanks to:
- **Dr. Reshma Rastogi**, my supervisor, for her invaluable guidance.
- My colleagues and labmates for their constant support.

## Author
**Dev Nirwal**  
[Your GitHub Profile](https://github.com/devn913)
