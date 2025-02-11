# 3D Topology Optimization for Structural Reinforcement

## About This Repository

This repository contains the complete LaTeX source, figures, and compiled [PDF](100_Compiled/main.pdf) of my bachelor thesis , submitted on 19.02.2019 to the Bergische Universität Wuppertal, Germany, in cooperation with BMW in Munich.

![Gradient Model 28](path_Image/pngs/Aufgabe_1/3D_Ergebnisse/canti.png)


## Thesis Overview

This bachelor thesis focuses on extending a 2D topology optimization method (Adapt) to 3D structures, enabling the optimization of complex 3D geometries for structural reinforcement.

## Key Achievements

* Extended an existing 2D topology optimization method (Adapt) to 3D structures, enabling optimization of complex 3D geometries
* Implemented features to control connection thickness, minimum distance between connections, and prevent local reinforcements in the optimized structures
* Developed method to prohibit connections at edges and corners in 3D optimized structures
* Conducted finite element reanalysis using OptiStruct to validate stiffness improvements of optimized 3D structures
* Modified the optimization method to handle slightly different load cases between the base structure and optimized reinforcements
* Implemented capability to import external 2D and 3D CAD geometries as base structures for optimization
* Integrated ParaView as a powerful open-source post-processor for visualizing and analyzing 3D optimization results
* Wrote modular, extensible code in MATLAB to enable easy addition of new dynamic systems and features
* Conducted parameter studies to evaluate the impact of different optimization parameters on results
* Demonstrated application of the extended method on multiple 2D and 3D test cases, including automotive-inspired geometries


## Repository Structure
- Inshallah [Final compiled PDF](100_Compiled/main.pdf)
- `100_Compiled/`: Contains log, auxiliary files, and the compiled PDF itself
- `2_Latex_Files/`: LaTeX source files and potentially related resources
- `path_Image/`: Figures and images used in the thesis
- `main.tex`: The main LaTeX file for the thesis
- `license.md`: License information for this project
- `README.md`: This file, providing an overview of the repository

## Note on Images

Some images were created using Inkscape, which outputs two separate files:
1. The image file itself
2. A file containing the text elements

Both types of files are included in the `path_Image/` directory for completeness.

## Important Notes

1. The PDF file in `100_Compiled/` is the original, Mistakes found post-submission have not been corrected. The reason for the latter is: the goal is to authentically show the original state that contains mistakes. Editing these mistakes afterwards would pretend to have had knowledge that I did not possess back then. All in all, it shall show that I am human, I made mistakes back then, am doing them now and will make them in upcoming projects. Inshallah I will learn from them. Acknowledging my mistakes is something I learned from the Quran and I think it is a good practice to stay honest. Only the Acknowledgement section has been slightly modified in this version. However, this modification does not affect the academic content of the thesis.
2. This repository can be used as a template for your projects.


## Compilation

To compile the thesis, ensure you have a LaTeX distribution installed on your system. Then, run the following command in the root directory of this repository:

```
pdflatex main.tex
```


You may need to run this command multiple times to resolve all references correctly. Also, ensure all necessary LaTeX packages are installed.

## License

Please refer to the `license.md` file in this repository for detailed licensing information.


## Contact

For more information or to get in touch, please visit my website: [javedab.com](https://javedab.com)


## Note on README Creation

This README was created with the assistance of an AI large language model, specifically the Claude 3.5 Sonnet model. While the content accurately reflects the thesis and repository structure, the wording and organization were enhanced through AI collaboration.

---

Feel free to explore this repository and use it as a reference for your own work. If you have any questions or feedback, please don't hesitate to reach out.
