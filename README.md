# Bayesian-survival-analysis
Bayesian models were implemented for the survival analysis of patients with breast cancer. To evaluate the effect of covariates on survival time, Exponential, Weibull, and Log-Normal models with fixed effects were estimated, as well as Weibull and Log-Normal models with random effects.
## Overview

Survival analysis is a set of essential statistical techniques used to study the time between a starting point such as the beginning of a clinical study and the occurrence of an event of interest, such as a patient’s death or the recurrence of a disease. This type of analysis is widely applied in biomedical, epidemiological, and biological research.

The primary goals of survival analysis are to describe the distribution of time-to-event in the population under study and to quantify the impact of explanatory variables on survival.

Traditionally, survival analysis has relied on frequentist approaches such as the Cox proportional hazards model and classical parametric distributions. While these methods are powerful, they often face limitations when dealing with the structural complexity of real-world data.

In recent decades, Bayesian methods have gained increasing attention. By explicitly incorporating prior distributions and updating prior beliefs through the posterior distribution, Bayesian approaches offer a more transparent handling of uncertainty and greater flexibility in model specification.

In this analysis, three Bayesian parametric models and one semiparametric model are presented. The differences between these models are explored, the effects of covariates on event time are interpreted, and their predictive performances are compared.
