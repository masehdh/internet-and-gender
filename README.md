# Accompanying R markdown and hmtl output for major research paper

The .rmd file has all code used for the quantitative analysis in _Mobile internet as a facilitator for gender attitude transformation in extremely fragile contexts: Afghanistan from 2014-2019_ In order to use this markdown file, make sure you install the following libraries:

```
install.packages(stargazer)
install.packages(caret)
install.packages(ggplot2)
install.packages(aod)
install.packages(car)
install.packages(lmtest)
install.packages(pscl)
install.packages(mfx)
```

Then, head over to the Asia Foundation’s website to get the _Survey of the Afghan People_ dataset, it's free for non-commercial purposes. The data is unfortunately unavailable due to the recent takeover, but a copy is available here(https://drive.google.com/drive/folders/1ifcY3xGGIFJ9QzRy_n9puCNnADckhsHS?usp=sharing)

It probably goes without saying, but a common cause of frustration for researchers without a programming background is figuring out imports and file directories. The file path below will be different for you.
```
afg <- readRDS(file = "C://Users//maseh//Documents//MRP//dataset_work//R-2019_data_and_codebook//2019_afghan_data_R.RDS")
```

I'm very much open to feedback and thoughts on how to add to this analysis. You can reach me at maseh46@gmail.com.
