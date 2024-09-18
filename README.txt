Science Before Statistics: Bayesian Causal Inference

# Description

Does wind make the trees sway, or do swaying trees make the wind? Statistical tools can be essential for addressing these sorts of questions, but they aren't sufficient. Statistical models are very useful for making predictions. But a causal claim is one that allows us to predict the consequences of an intervention in a system, and a scientific model in addition to one or more statistical models is always necessary for that. 

An interdisciplinary literature has developed in the previous decades that allows us to connect statistical models to scientific models of causal processes. Scientific models at different levels of description and detail can be analyzed to decide how to use available data---or whether we can use available data---to answer specific causal questions.

In the first part, I show how traditional uses of regression modeling do not automatically and appropriately answer intended causal questions. 

In the second part, I develop the causal approach at the most basic level. I begin with graphical causal models and show you how to analyze them essentially with your eyeballs to decide which variables are needed and which are harmful for making a target inference.

In the third part, I show how computational Bayesian models can naturally express scientific causal models, and so help us in the very hard work of estimation from finite and imperfect data.

# Preparation and materials

Who should attend: Researchers in academia or not who use data analysis to make causal claims. I assume a basic familiarity with multiple regression, but we won't do a lot of coding in this course. Instead I aim to motivate conceptual connections and teach you new skills for analyzing causal models. So a variety of statistical backgrounds are appropriate, Bayesian or not.

# Software

You can follow along with or later execute the examples from the course using the included R script. At the top of the script are code and instructions for installing the required R packages.

Required packages: cmdstanr, rethinking (and dependencies for both)

Here are more instructions for installing cmdstanr: https://mc-stan.org/cmdstanr/

And here is the rethinking package, with installstion instructions: https://github.com/rmcelreath/rethinking?tab=readme-ov-file#installation

