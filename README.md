# Welcome to the GitHub repository for the RNA sequencing analysis presented in Martell et al. (Citation). 
* This repository contains the codebase used to generate all figures related to the RNAseq analysis, including gene fusions, expression profiles, outlier analysis, and other relevant visualizations.
* This has been tested on
  + R version 4.3.2 (2023-10-31)
  + Platform: x86_64-pc-linux-gnu (64-bit)
  + Running under: Ubuntu 22.04.3 LTS

## Repository Structure
* Main Script: The core of the analysis is contained in a single R Markdown (RMD) file.
* Configuration File: This file specifies paths and parameters required by the main script. All files must be present and accessible in order for the markdown to run to completion.
* Auxiliary Script: An additional R script is included, which provides extra functions necessary for the analysis.

## Important Notes
* Ensure that all paths specified in the configuration file are correct and  accessible on your system.
* Some of these files are available under the subdirectory ./inputs however 
due to certain constraints/regulations, not all files can be provided directly in this repository. For access to restricted files or further guidance, please reach out to the authors.

## Below are the minimum packages required. 

  <details>
        <summary>The following R packages </summary>
        

### Data Manipulation and Analysis
1. **tidyverse and dplyr**: Data manipulation, exploration, and transformation operations.
3. **data.table**: Similar to `dplyr` for large datasets, focusing on speed and memory efficiency.
4. **reshape2**: Designed for reshaping and pivoting data frames.
5. **stringr**:  String manipulation.
6. **openxlsx**: Tools for reading, writing, and editing Excel files.

### Statistical Methods and Parallel Computing

1. **limma and voom**: Statistical analysis for RNAseq.
2. **edgeR**: Statistical analysis for RNAseq.
3. **parallelDist**:  Computes distance matrices in parallel.
4. **dendextend**: Useful in clustering visualizations.
5. **metap**: Used for meta-analysis of data based on statistical p-values.
6. **entropy**: Functions for calculating entropy of data, used in information theory and other applications.

### Data Visualization
1. **ggplot2**: A system for creating graphics.
2. **ggbeeswarm**: Adds beeswarm plot functionality to ggplot2.
3. **ggridges**: Useful for creating ridge plots with ggplot2.
4. **treemapify**: Adds treemap capabilities to ggplot2.
5. **ggpattern**: Provides pattern fills for ggplot2 geometries.
6. **patchwork**: Facilitates combining multiple ggplot2 plots into a single plot.
7. **ComplexHeatmap**: Comprehensive tool for drawing heatmaps in R.
8. **DiagrammeR**: Creates graph and network diagrams.
9. **igraph**: Provides extensive functionality for complex network analysis.
10. **ggraph**: Builds on igraph's capabilities to make it easier to work with network data in ggplot2.
11. **ggwaffle**: Adds waffle chart capabilities to ggplot2.
12. **waffle**: Another waffle chart.
13. **ggpval**: Adds p-values and significance levels to ggplots.
14. **ggforce**: Enhancements and extensions for ggplot2.
15. **ggrepel**: Helps in adding text labels to plots in ggplot2 without them overlapping.
16. **ggpubr**: Simplifies ggplot2.
17. **RColorBrewer**: Provides color schemes for maps and other visualizations.
18. **ggsci**: Contains color palettes inspired by scientific journals.
19. **colorRamp2**: Allows the creation of custom color ramps.
20. **viridis**: Provides color maps originally created for matplotlib.
21. **grid**: Supports the creation of grid-based graphics layouts in R.
22. **VennDiagram**: Generates Venn and Euler plots.

### Report Generation
1. **knitr**: Enables dynamic report generation with R.
2. **kableExtra**: Enhances the functionality of kable() from knitr, particularly for HTML and LaTeX.

### Biological Analysis
1. **fgsea**: Provides function for GSEA.
2. **pathfindR**: An R package for pathway enrichment analysis

  </details>
