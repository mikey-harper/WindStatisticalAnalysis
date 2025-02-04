The code is written in R using the RMarkdown (.Rmd) format. The code and data sources are stored within this GitHub respository, and should run on any computer if you wish to repeat the analysis.

The code is broken into three main sections:

1. [**Hierarchical Model**](https://github.com/mikey-harper/WindStatisticalAnalysis/blob/master/ECOS%202017%20Conference%20Paper/02-Hierarchical%20Model/HierarchicalModel.md): Parameters are added to the model in batches
2. [**Parameter Reduction**](https://github.com/mikey-harper/WindStatisticalAnalysis/blob/master/ECOS%202017%20Conference%20Paper/03-ParameterReduction/Parameter_Reduction.md): The model from step 1 is reduced to as few predictor variables as possible
3. [**Seperating Models**](https://github.com/mikey-harper/WindStatisticalAnalysis/blob/master/ECOS%202017%20Conference%20Paper/04-NestedModels/Nested_Models.md): Seperate models are built for England, Scotland and Wales.

# Packages

The following packages are used within the analysis:

```r

# Packages used in analysis

packages <- c("bestglm" # Finding the best fitting regression model
               "caret" # Used for testing regression models
               "extrafont", # used for changing fonts of graphics
               "ggplot2", # producing graphs
               "Hmisc",
               )             

```

To avoid potential confusion or conflict with other installed packages, any package specific functions are always called with their package name e.g. `packagename::function`.


