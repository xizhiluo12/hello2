# modSaRa2
Although it has been shown that the widely used change-point based methods can increase statistical power to identify variants, it remains challenging to effectively identify CNVs with weak signals due to the noisy nature of genotyping intensity data. modSaRa2 is a novel improvement of our previously developed method modified Screening and Ranking algorithm (modSaRa) by integrating the relative allelic intensity with prior information of statistics. modSaRa2 markedly improved both sensitivity and specificity over existing methods. The improvement for weak CNV signals is the most substantial, while simultaneously improving stability when CNV size varies. 
## Getting Started
The source package needs to be compiled first with the Rtools on Windows. 
## Installing
```
install.packages("devtools")
library(devtools)
install_github("xizhiluo12/hello2",subdir="modSaRa2")
```
## Reference Manual
*[Reference Manual](https://github.com/xizhiluo12/hello2/blob/master/modSaRa2-manual.pdf)
