# coding-camp-25-public

# Shortcuts & Cool Features
## Pipe
Mac: Cmd + Shift + M 
Windows: Ctrl + Shift + M 

## Code Block
Mac: Option + Cmd + I
Windows: Ctrl + Alt + I

## Rainbow parentheses
It's a nice way to keep track of parentheses and make sure each pair is complete. 
Tools --> Global Options --> Code --> Display --> Rainbow Parentheses

# FAQs - I assume
## Quarto vs. R Markdown
R/Posit (the parent company) has been making a ton of changes since I (Libby) started learning R in 2018. Quarto notebooks are one of those changes. For all intensive purposes, they're very similar to R Markdown files. I suggest choosing a Quarto Document over R Markdown. R Markdown has some templates to choose from, but I am under the impression that Quarto documents are likely the future of R so I suggest using those. (I could possibly be wrong, but we shall see.)

That said, you will likely encounter files that are just .R. These are scripts where you can only have code, and any text will need to be commented out. You can run the code line by line. If you use Python, the difference between R Script and Notebooks are essentially the same between .py files and Jupyter Notebooks. 

## Pipes
R/Posit (the parent company) has been making a ton of changes since I (Libby) started learning R in 2018. A pipe like this |> rather than %>% is one of those changes. I suggest using this pipe. 

A pipe in R essentially means "and then do this." You tell your dataframe/variable to then go through this. 

## Tidyverse & dplyr
Dplyr is a package within the tidyverse. It contains functions that are powerful for data manipulation. The tidyverse itself contains multiple packages that make data analysis simple. Referring to dplyr is like referring to one drawer among a chest of 10+ drawers.  

## ggplot uses + signs?
ggplot was created before tidyverse, and the developer used + signs rather than pipes. But it became such an integral part of R that nobody bothers to switch it. 

# Set up R & Git
See this [textbook](https://happygitwithr.com/)
