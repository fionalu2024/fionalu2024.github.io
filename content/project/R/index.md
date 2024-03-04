---
title: Fitting Models for Energy Appliances Dataset
summary: This project works with a modified dataset of energy use of appliances in a low-energy house. It aims to find out the best performance model and use it for prediction, by using R.
tags:
  - R
date: 2023-08-01
# xternal_link:
---

⭐ **Project Goal**

The given dataset provides the energy use of Appliances using 671 samples, 340 samples are required to be randomly generated for this project. It comprises 5 variables, and has been used to create models of energy use of appliances in a low-energy house. Find out the best fitting model and use it for prediction, by using R. 

❗ **Challenges**

Which way of data transformation and which fitting model is the most appropriate to predict need to be considered, and there are also outliers need to be dealt with before data transformation.

💪 **Strategies**

By understanding the relationship between each variable and the variable interest and relevant data distribution, as well as handling with outliers (with winsorized method), I then apply the corresponding data transformation. 

Different models are introduced to compare the performance to understand the importance of each variable, as well as finding out the best performance model. Models including a Weighted arithmetic mean (WAM), a Weighted power means (WPM) with p = 0.5, a Weighted power means (WPM) with p = 2, an Ordered weighted averaging function (OWA), and the Choquet integral, Finally, the Choquet Integral model fits the best.
