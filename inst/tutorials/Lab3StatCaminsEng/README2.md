# Lab2StatCamins

StatCamins Lab2 Package. Download and install it

# First steps to activate the tutorial

## Let's install the packages that we need. Installation is only done once. Package will be installed for next tutorials

install.packages("learnr")
install.packages("devtools")

## We activate the package (once per sessio if needed)
library("learnr")
library("devtools")

## Download the tutorial from the repository:
devtools::install_github("MaribelOrtego/Lab2StatCaminsCat")
## Execute the tutorial:
learnr::run_tutorial("Lab2StatCaminsCat", "Lab2StatCaminsCat")

### And now follow the tutorial. ( Always follow the Next Page buttons) 
