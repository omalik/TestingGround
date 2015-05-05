getwd()
setwd("~/github/TestingGround")
library(knitr)

inpt <- source("README.md")
knit_print(inpt,"Testing2.md",text=TRUE)
source("README.md")
