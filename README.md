# QuantitaTIMM
Collection of slides and resources for QuantitaTIMM

## Technical Skills

### GitHub

I think GitHub has a massive learning curve and feels like an unnecessarily nit-picky way to share files compared to, say, Dropbox. Its design makes more sense when you consider the [problem it's trying to solve](https://betterexplained.com/articles/a-visual-guide-to-version-control/). Here's an intro to GitHub ["vocabulary"](https://medium.com/crowdbotics/a-dead-simple-intro-to-github-for-the-non-technical-f9d56410a856).

GitHub has a few "portions." There is Git, which is the tool itself; GitHub, which is a storage website that you interact with using Git; and GitHub Desktop, an app that helps you interact with GitHub using Git. You can also use Git without GitHub Desktop - RStudio and other apps also fill this role or you can type commands in the Command Line/Terminal - I just find GitHub Desktop easiest for me.

Here are tutorials on [GitHub, the website](https://lgatto.github.io/github-intro/) and [using Git with RStudio](https://jennybc.github.io/2014-05-12-ubc/ubc-r/session03_git.html). [GitHub Desktop](https://desktop.github.com/) has a built-in tutorial when you open the app.

### Coding

[R and Python](https://towardsdatascience.com/from-r-vs-python-to-r-and-python-aa25db33ce17) are both good options. R might be a better fit for biology, since many biologists use R and there are a lot of R packages for biology on [Bioconductor](http://bioconductor.org/).

[DataCamp](datacamp.com] can be a good resource for getting started, though I personally did not find it very helpful. There are a number of free courses. DataCamp did have problems with [sexual harassment](https://www.datacamp.com/community/blog/working-ideal-independent-third-party-review-of-datacamp) last year.

Please do not use Excel for anything but data entry! Analysis in Excel is bad because a number of the statistical tests have [errors in the math](http://biostat.mc.vanderbilt.edu/wiki/pub/Main/TheresaScott/StatsInExcel.TAScott.slides.pdf)... It's graphing software is not very customizable and doesn't look good when compared to other options. Fixing data input errors in Excel is problematic because it doesn't leave a trackable and reproducible record of what was changed - doing so in RMarkdown leaves a trail you can follow if something goes wrong. Even clicking around in Excel can be scary - there are stories of retracted papers because one cell was accidentally deleted without the researcher realizing.

#### R

I'd highly recommend learning to work with data using [Tidyverse](https://www.analyticsvidhya.com/blog/2019/05/beginner-guide-tidyverse-most-powerful-collection-r-packages-data-science/). It is a set of packages in R that all share the same philosophy and work well together. It's played a huge role in making R accessible, readable, and effective. 

[R for Data Science](https://r4ds.had.co.nz/index.html) is a great introductory open-source book written by Hadley Wickham, who built Tidyerse. All the packages listed in the survey I sent are in Tidyverse (data transformation with dplyr, visualization with ggplot2) or follow the Tidyverse mentality (machine learning with tidymodels.) Tidymodels is a recent improvement over R's previous machine-learning package, caret.

You should definitely be coding in RStudio (an app that helps you code in R, the language) and using RMarkdown (a way to keep track of your code so it is reproducible.) RMarkdown also allows you to write non-code (normal things) and LaTeX (to type math) in the same document as code, so you can write reminders of what your code is doing to your future self or create [PDF reports](https://miro.medium.com/max/2920/1*6Y0XxQynWWUNTPUOAOhl6g.png).

RMarkdown lets you reproduce, organize, and present your work. Here is a [presentation](https://apreshill.github.io/rmd4cdc/) with a lot of information on the philosophy of RMarkdown and all the cool things you can do with it.

There are a number of [cheatsheets](https://rstudio.com/resources/cheatsheets/) available so you don't have to memorize all the functions, formatting, and syntax. The cheatsheets on [RMarkdown](https://github.com/rstudio/cheatsheets/raw/master/rmarkdown-2.0.pdf), [RStudio IDE](https://github.com/rstudio/cheatsheets/raw/master/rstudio-ide.pdf), [visualization with ggplot2](https://github.com/rstudio/cheatsheets/raw/master/data-visualization-2.1.pdf), and [data transformation with dplyr](https://github.com/rstudio/cheatsheets/raw/master/data-transformation.pdf) might be particularly helpful.
