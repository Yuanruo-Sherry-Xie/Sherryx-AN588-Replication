# AN588 Replication Project: Thermal Responses to Vocalizations in Wild Chimpanzees

## Overview  

This project replicates key statistical analyses and visualizations from the paper:

-   Dezecache, G., Zuberbühler, K., Davila-Ross, M., & Dahl, C. D. (2017). Skin temperature changes in wild chimpanzees upon hearing vocalizations of conspecifics. \*Royal Society Open Science\*, 4(11), 170151. <https://doi.org/10.1098/rsos.170151>

The original study used infrared thermography (IRT) to measure facial skin temperature responses in wild chimpanzees following different types of vocalizations. This replication focuses on reproducing the main descriptive and inferential statistics as well as key figures from the published work.

## Important Files Included:  

-   Cleaned and structured versions of the publicly available dataset extracted from the original Dryad Excel file. These files correspond to Figures 3–5 in the original paper.

-   PDF copy of the original published paper.

-   R Markdown file containing all code, data analysis, figure replication, and written interpretations.

-   Knit HTML output of the \`.Rmd\` file.

## Analyses Replicated

-   Descriptive statistics\*\* (mean ± SD before vs. after vocalizations) for nose and ear regions (Figure 3).

-   Paired t-tests\*\* for before/after comparisons (Figure 3).

-   Pearson correlations\*\* between time and temperature for:

    -    Aversive vs. non-aversive vocalizations (Figure 4)

    -   Individual vocal types (bark, scream, whimper, pant-hoot) (Figure 5)

-   Visual replications of Figure 5 using \`ggplot2\`.

## Key Findings  

-   Replication confirms the major thermal trends: nose cooling and ear warming following vocalizations.

-   Temporal correlations matched published effect sizes and directions.

-   Visual replications closely aligned with original figures.

-   Some limitations exist due to missing metadata in the public dataset, but findings overall validate the original conclusions.

## How to Reproduce  

1\. Clone this repository

2\. Open \`replication.Rmd\` in RStudio

3\. Knit to HTML (\`replication.html\`)

4\. All data and figures will reproduce automatically if packages are installed.

## Required Packages  

\- \`tidyverse\`

\- \`ggplot2\`

\- \`dplyr\`

\- \`broom\`

\- \`purrr\`

\- \`scales\`
