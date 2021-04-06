# Comment on Pruitt et al (2012)

[Pruitt et al (2012)](https://doi.org/10.1086/663680) present and analyse behavioural and morphometric data on snails and their sea star predators.
This comment evaluates the snail data for evidence of data duplication that has been detected in some other papers by the same first author.

Unfortunately the raw data have been sorted. 
This complicates the checking for duplicates as methods such as [sequenceSniffer](https://github.com/alrutten/sequenceSniffer) cannot be used.
Instead, this comment looks at the similarity between the sizes in different subsets of the data and compares the results to a null model.

The comment finds that some subsets of the data are much more similar to each other than expected by chance.

To reproduce the comment, clone this repo or download it with the green "Code" button. 
Open the Rstudio project and knit the rmarkdown file "Comment_on_Pruitt_2012_Am_Nat.Rmd" with the blue knit button. 
You may need to install some packages first.
The script in the Rmd file will download the data, run all the analyses and render the manuscript.

The null models in the comment will take a few minutes to run the first time.

---

Pruitt, J. N., J. J. Stachowicz, and A. Sih. 2012. 
Behavioral types of predator and prey jointly determine prey survival: Potential implications for the maintenance of within-species behavioral variation. _The American Naturalist_ 179:217–227.
