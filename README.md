# Final Project
### PH 464

## Reference Papers
[Contents of the R directory] K. Hamidieh, _A Data-Driven Statistical Model for Predicting the Critical Temperature of a Superconductor_. arXiv: 1803.10260v2 [stat.AP] 12 Oct 2018.

V. Stanev, C. Oses, et al., _Machine learning modeling of superconducting critical temperature_. arXiv: 1709.02727v2 [cond-mat.supr-con] 6 Oct 2017.

## Data Source
From Hamidieh: https://github.com/khamidieh/predict_tc

## Guenter's Specs
+ Visualize data (take inspiration from 2017 paper)
	+ Which are the most important predictors?
+ Use a Random Forest model to predict semiconductor temp
	+ Find all superconductors
	+ HTC: Contain `Cn` and `O` and Tc > 10K
		+ Optional: Ratio Cn:O roughly 1:2
	+ Fe-based SC: Contain `Fe`
	+ Conventional SC: Tc < 10K
