# Lab3StatCaminsEng
StatCamins Lab3 package

# First steps to activate the tutorial
Let's install the packages that we need. Installation is only done once. Package will be installed for next tutorials

install.packages("learnr") 
install.packages("devtools")

# We activate the package (once per sessio if needed)

library("learnr") 
library("devtools")

# Download the tutorial from the repository:

devtools::install_github("MaribelOrtego/Lab3StatCaminsEng")

# Execute the tutorial:

learnr::run_tutorial("Lab3StatCaminsEng", "Lab3StatCaminsEng")

# And now follow the tutorial. ( Always follow the Next Page buttons)
