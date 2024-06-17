## Assessment of lemon juice quality and adulteration by ultra-high performance liquid chromatography/triple quadrupole mass spectrometry with interactive and interpretable machine learning

Check the **[original article](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9261826/)** published in _Journal of Food and Drug Analysis_. 

## Abstract
A total of 81 lemon juices samples were detected using an optimized UHPLC-QqQ-MS/MS method and colorimetric assays. Concentration of 3 organic acids (ascorbic acid, malic acid and citric acid), 3 saccharides (glucose, fructose and sucrose) and 6 phenolic acids (trans-p-coumaric acid, 3-hydroxybenzoic acid, 4-hydroxybenzoic acid, 3,4-dihydroxybenzoic acid, caffeic acid) were quantified. Their total polyphenol, antioxidant activity and Ferric reducing antioxidant power were also measured. For the prediction of authentic and adulterated lemon juices and commercially sourced lemonade beverages based on the acquired metabolic profile, machine learning models including linear discriminant analysis, Gaussian naïve Bayes, lasso-regularized logistic regression, random forest (RF) and support vector machine were developed based on training (70%)-cross-validation-testing (30%) workflow. The predicted accuracy on the testing set is 73–86% for different models. Individual conditional expectation analysis (how predicted probabilities change when the feature magnitude changes) was applied for model interpretation, which in particular revealed the close association of RF-probability prediction with nuance characteristics of the density distribution of metabolic features. Using established models, an open-source online dashboard was constructed for convenient classification prediction and interactive visualization in real practice.

## Script Reference

The R script in this documentation covers data wrangling, visualization, machine learning modeling, and Shiny App construction developed in this original publication. Check [here](https://yuanbofaith.github.io/Lemon_Juice_Classification2) to find the script and associated output. 

The R code has been developed with reference to [**R for Data Science (2e)**](https://r4ds.hadley.nz/), and the official documentation of [**tidyverse**](https://www.tidyverse.org/), and [**DataBrewer.co**](https://www.databrewer.co/). See breakdown of modules below:

- **Data visualization** with **ggplot2** ([**tutorial**](https://www.databrewer.co/R/visualization/introduction) of the fundamentals; and [**data viz. gallery**](https://www.databrewer.co/R/gallery)).

- [**Data wrangling**](https://www.databrewer.co/R/data-wrangling) with the following packages:
[**tidyr**](https://www.databrewer.co/R/data-wrangling/tidyr/introduction): transform (e.g., pivoting) the dataset into tidy structure; [**dplyr**](https://www.databrewer.co/R/data-wrangling/dplyr/0-introduction): the basic tools to work with data frames; [**stringr**](https://www.databrewer.co/R/data-wrangling/stringr/0-introduction): work with strings; [**regular expression**](https://www.databrewer.co/R/data-wrangling/regular-expression/0-introduction): search and match a string pattern; [**purrr**](https://www.databrewer.co/R/data-wrangling/purrr/introduction): functional programming (e.g., iterating functions across elements of columns); and [**tibble**](https://www.databrewer.co/R/data-wrangling/tibble/introduction): work with data frames in the modern tibble structure.

## Follow me. Keep Updated with My Latest Research

<table style="border-collapse: collapse; width: 100%; border: 0; border-spacing: 0;">
  <tr>
    <td style="border: none;" align="center">
      <a href="https://medium.com/@yuanbo.faith">
        <img src="https://upload.wikimedia.org/wikipedia/commons/0/0d/Medium_%28website%29_logo.svg" alt="Medium Logo" style="height: 20px; max-width: 100px; margin: 10px;">
      </a>
    </td>
    <td style="border: none;" align="center">
      <a href="https://x.com/yuanbogeneral">
        <img src="https://upload.wikimedia.org/wikipedia/commons/c/ce/X_logo_2023.svg" alt="X Logo" style="height: 33px; max-width: 100px; margin: 10px;">
      </a>
    </td>
    <td style="border: none;" align="center">
      <a href="https://www.databrewer.co/">
        <img src="https://upload.wikimedia.org/wikipedia/commons/b/b8/DataBrewer.png" alt="DataBrewer Logo" style="height: 53px; max-width: 100px; margin: 10px;">
      </a>
    </td>
    <td style="border: none;" align="center">
      <a href="https://connects.catalyst.harvard.edu/Profiles/display/Person/193422">
        <img src="https://upload.wikimedia.org/wikipedia/en/1/18/Harvard_shield-Public_Health.png" alt="Harvard Public Health Logo" style="height: 50px; max-width: 100px; margin: 10px;">
      </a>
    </td>
    <td style="border: none;" align="center">
      <a href="https://orcid.org/0000-0003-0222-8095">
        <img src="https://upload.wikimedia.org/wikipedia/commons/0/06/ORCID_iD.svg" alt="ORCID Logo" style="height: 40px; max-width: 100px; margin: 10px;">
      </a>
    </td>
    <td style="border: none;" align="center">
      <a href="https://www.linkedin.com/in/bo-yuan-amazing/">
        <img src="https://upload.wikimedia.org/wikipedia/commons/c/ca/LinkedIn_logo_initials.png" alt="LinkedIn Logo" style="height: 33px; max-width: 100px; margin: 10px;">
      </a>
    </td>
    <td style="border: none;" align="center">
      <a href="https://harvard.academia.edu/BYuan">
        <img src="https://upload.wikimedia.org/wikipedia/commons/a/a0/Academia.edu_logo.svg" alt="Academia Logo" style="height: 15px; max-width: 100px; margin: 10px;">
      </a>
    </td>
    <td style="border: none;" align="center">
      <a href="https://scholar.google.com/citations?user=aFh0570AAAAJ&hl=en">
        <img src="https://static-00.iconduck.com/assets.00/google-scholar-icon-2048x2048-sjbhklt7.png" alt="Google Scholar" style="height: 35px; max-width: 100px; margin: 10px;">
      </a>
    </td>
  </tr>
</table>



