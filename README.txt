README:

This repository was made by: Bram Schouten, student number:6109683
For the BiBC assignment on 2020-09-16

The root directory holds the following subdirectories: R, python and data.
- The directory 'data' holds the two .csv files obtained from Kaggle, from: https://www.kaggle.com/parulpandey/palmer-archipelago-antarctica-penguin-data

penguins_size.csv and penguins_lter.csv

The penguins_size.csv is a smaller data set derived from an original, containing species: penguin species (Chinstrap, Adélie, or Gentoo), culmen_length_mm: culmen length (mm) - which is the length of the "beak-ridge"
culmen_depth_mm: culmen depth (mm) - idem dito - flipper_length_mm: flipper length (mm), body_mass_g: body mass (g), island: island name (Dream, Torgersen, or Biscoe) in the Palmer Archipelago (Antarctica) and, sex: penguin sex.

penguins_lter.csv is the original, larger data set 

- Currently, in the directory 'R' a Rmarkdown file is stored of the analysis of "penguins_lter.csv". The weight was analysed in a single boxplot according to  penguin sex, island (Dream, Torgersen, or Biscoe) where the measurement was taken and species (Gentoo penguin (Pygoscelis papua), Adélie penguin (Pygoscelis adeliae) and Chinstrap penguin (Pygoscelis antarcticus)).

- The directory 'python' holds a Jupyther notebook containing the same code (written in R) as the Rmarkdown, in directory 'R'
