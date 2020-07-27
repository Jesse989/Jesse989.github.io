---
layout: post
title:      "Plotting Distributions with Pandas"
date:       2020-07-27 20:37:10 +0000
permalink:  plotting_distributions_with_pandas
---


https://medium.com/@Jesse989/plotting-distributions-with-pandas-34e532d64fb

When it comes to data-science projects, there is nothing as important as knowing your data. Having a deep understanding of your data will lead to better intuition during the modeling phase of your project, resulting in better model-selection, feature-selection, and hyper-parameter tuning.
What is EDA?
Type EDA into google and it will return this definition:
In statistics, exploratory data analysis (EDA) is an approach to analyzing data sets to summarize their main characteristics, often with visual methods. A statistical model can be used or not, but primarily EDA is for seeing what the data can tell us beyond the formal modeling or hypothesis testing task.
I like this definition because it mentions that EDA’s primary purpose is to gain insights beyond what the model will predict, or whether or not to reject the null-hypothesis.
In simpler terms, EDA can be described as ‘getting to know your data’.
It is important to know your data for mean reasons, and the familiarity is important for staying focused and not getting lost when it comes time to work with the data, for example during the modeling phase.
Remember that data-science projects usually have a deadline, so even though it is important to know your data, you should be efficient and concise as well.
There are countless charts, tables, and visuals that can be created, but there is no point in creating them if they fail to provide insight.
In this article I will show how to get some very general dataset info, and then show one possible way to visualize the distributions of your data.
