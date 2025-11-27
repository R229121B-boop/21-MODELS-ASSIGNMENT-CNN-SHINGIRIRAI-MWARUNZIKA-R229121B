# 21-MODELS-ASSIGNMENT-CNN-SHINGIRIRAI-MWARUNZIKA-R229121B
21 MODELS SUMMARY

•	FractalNet (2016): R-Squared: 0.0834 - This model showed the best performance, but with an R-squared of 0.0834, it still explains only about 8.34% of the variance in house prices. This indicates a very weak positive correlation and limited predictive power.
•	GoogLeNet / Inception-V1 (2014): R-Squared: 0.0145 - Explains about 1.45% of the variance, showing minimal predictive capability.
•	Squeeze-and-Excitation Networks (SENet) (2017): R-Squared: -0.0232 - A negative R-squared means this model performed worse than simply predicting the average house price, indicating it's not learning a useful pattern.
•	Inception-V4 (2016): R-Squared: -0.0586 - Also performed worse than a baseline average prediction.
•	HRNet-V2 (2020): R-Squared: -0.0657 - Similar to the above, it did not provide useful predictions.
•	DenseNet (2017): R-Squared: -0.2341 - Its predictions were worse than just using the mean.
•	WideResNet (2016): R-Squared: -0.2879 - Another model that performed worse than a simple average prediction.
•	Highway Networks (2015): R-Squared: -0.5135 - Demonstrates very poor predictive performance compared to the mean.
•	ResNet (2016): R-Squared: -0.7293 - Significantly worse than predicting the mean.
•	Inception-V3 (2015): R-Squared: -0.7854 - Showed poor performance.
•	NIN (Network in Network) (2013): R-Squared: -0.9679 - Closer to -1, indicating very poor model fit.
•	ZfNet (2013): R-Squared: -1.1728 - Performed worse than predicting the mean.
•	AlexNet (2012): R-Squared: -1.4269 - Very low predictive power.
•	VGG (2014): R-Squared: -1.9193 - Showed very weak or inverse correlation with the actual prices.
•	Inception-ResNet-V2 (2016): R-Squared: -5.1319 - Extremely poor performance, implying the predictions were far off from the actual values.
•	MobileNet-V2 (2018): R-Squared: -6.7093 - Another model with very low predictive accuracy.
•	CapsuleNet (2018): R-Squared: -10.1350 - Very poor fit to the data.
•	Xception (2017): R-Squared: -37.8712 - This model showed an exceptionally poor fit, suggesting its predictions were highly inaccurate and possibly systematically wrong.
•	Competitive Squeeze-and-Excitation Network (2018): R-Squared: -72.3937 - The worst performer, indicating its predictions were dramatically worse than a simple baseline, potentially due to issues in training or model suitability for this task.
Overall, the R-squared values for all models are quite low, with most being negative. This suggests that the models, under the current training conditions (e.g., limited epochs, specific hyperparameters), are not effectively learning to predict house prices from the given image data. The negative R-squared values highlight that many models perform worse than a naive predictor that always guesses the average price.
