# An-Analysis-of-the-Great-Diesel-Dupe-Scandal
I analyze the causal impact of Volkswagen's EPA Scandal in 2015 using time-series financial data.

In September of 2015, Volkswagen's scandalous behavior was published by the Environmental Protection Agency and a number of Media conglomerates. 
In particular, Volkswagen's vehicles were found to have a "defeat device" installed in them, which changed their emissions behavior during testing. 

I wanted to analyze the impact of this real historical event.

To do so, I first approached the problem in an experimental framework that included 
a difference-in-difference regression approach using historical stock price data of Volkswagen. However, this framework was giving me strange errors
& poor results.

I had to rethink my strategy; in doing so, I created a structual Bayesian time-series model using the Causal Impact package in R. 

After getting the model to run correctly, I performed a variety of statistical tests to validate my findings as well as produced some visualizations
that help tell the story of the data. 

Ultimately, I found that Volkswagen's stock price dropped by 30% over the next four months after the scandal was publicized. Moreover, their stock
never recovered. 

For full information, please refer to my write-up from the Word Document in this Repository. Obviously, you can also reproduce my findings using the 
same R code provided as well. 
