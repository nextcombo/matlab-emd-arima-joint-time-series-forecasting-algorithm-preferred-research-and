# [MATLAB] EMD-ARIMA Joint Time Series Forecasting Algorithm, Preferred Research and Innovation Algorithm

1. EMD Signal Decomposition Algorithm
EMD, also known as Empirical Mode Decomposition, is an algorithm for signal decomposition. It breaks down a signal into a sum of finite number of Intrinsic Mode Functions (IMF), each of which represents a localized vibration mode with its own characteristic. The main steps of EMD decomposition are as follows:
1. Connect the local maxima and minima of the signal to form some local extrema envelopes.
2. For each local extremum envelope, linear interpolation is used to obtain a smooth envelope. Subtract this envelope from the original signal to obtain a residual signal with localized oscillations.
3. Repeat steps 1 and 2 until no new localized oscillation modes can be identified.
4. Add up all the localized oscillation modes to obtain the original signal's EMD decomposition.
The advantage of EMD decomposition is that it can effectively handle nonlinear and non-stationary signals without the need for predefined basis functions. Therefore, EMD decomposition has been widely applied in fields such as signal processing, image processing, and pattern recognition.
To use EMD decomposition in MATLAB, you first need to install the EMD decomposition toolkit.
Installation of EMD Toolkit: Open the package_emd folder in MATLAB, run install_emd. M and index_emd. M as shown in the figure below to complete the installation of the toolkit.
MATLAB Signal Decomposition First Session - EMD:
For detailed information on signal decomposition, please refer to:
2. ARIMA Time Series Forecasting Algorithm
The ARIMA (Autoregressive Integrated Moving Average) model is a predictive model based on time series analysis, suitable for analyzing and forecasting data with both temporal dependence and randomness. The ARIMA model was first proposed by Box and Jenkins in 1976 and has since become a widely used time series model for data prediction in production and finance sectors. The core idea of the ARIMA model is to differentiate the time series data to make it stationary, then establish the model through the combination of autoregression (AR) and moving average (MA), and use this model for forecasting. In the ARIMA model, "AR" stands for autoregression, indicating that current data are related to the data from several previous moments; "I" stands for differencing, which means to differentiate the data to make it stationary; "MA" stands for moving average, indicating that current data are related to the errors from several previous moments. The establishment process of the ARIMA model includes three steps: model identification, parameter estimation, and model verification. In the model identification stage, the order of the ARIMA model and the number of differencing times need to be determined; in the parameter estimation stage, the model needs to be estimated; in the model verification stage, the model needs to be verified and judged whether the prediction accuracy meets the requirements. The ARIMA model has the advantage of fully utilizing the historical information of time series data for prediction, can adapt to various types of time series data, and has good explanatory power. However, there are some disadvantages to the ARIMA model, such as the need to differentiate non-stationary time series data, and the process of parameter estimation is relatively complex.
MATLAB | Time Series Forecasting | ARIMA Forecasting Model:
For more details about the five time series forecasting schemes, please refer to:
3. EMD-ARIMA Joint Time Series Forecasting Algorithm Next, we will introduce in detail the principle and thought behind the latest EMD-ARIMA joint time series forecasting algorithm.
Signal decomposition can break down raw data into N layers of imf components. In this study, we expand the ARIMA time series prediction for each layer's imf component and then reconstruct the predicted imf components to obtain the EMD-ARIMA joint time series prediction values. 

We compare the EMD-ARIMA joint time series prediction values with the pure ARIMA time series prediction values against the true values. The results show that the EMD-ARIMA joint time series prediction algorithm has a good predictive effect. The reason is that signal decomposition breaks down the raw data into different frequency components, meaning that the frequencies of each imf component are roughly the same. This makes the data have good periodicity and regularity. Therefore, when using the ARIMA time series prediction algorithm to predict each imf component, its predictive effect will be closer to the true value. 

Below is a brief video tutorial on how to perform this operation. 

To view this video please enable JavaScript, and consider upgrading to a web browser that supports HTML5 video. 

Video Player is loading. 
Play VideoPauseMute  
Current Time 0:21  
/  
Duration 1:42  
Loaded: 57.34%  
0:21  
Stream Type LIVE
Seek to live, currently behind liveLIVERemaining Time -1:21  
1x  
Playback Rate  
ChaptersChapters  
Descriptionsdescriptions off, selected  
Subtitlessubtitles settings, opens subtitles settings dialog  
subtitles off, selected  
Audio Track  
Picture-in-PictureFullscreen  
This is a modal window.  
Beginning of dialog window. Escape will cancel and close the window.  
TextColorWhiteBlackRedGreenBlueYellowMagentaCyanTransparencyOpaqueSemi-TransparentBackgroundColorBlackWhiteRedGreenBlueYellowMagentaCyanTransparencyOpaqueSemi-TransparentTransparentWindowColorBlackWhiteRedGreenBlueYellowMagentaCyanTransparencyTransparentSemi-TransparentOpaque  
Font Size50%75%100%125%150%175%200%300%400%Text Edge StyleNoneRaisedDepressedUniformDropshadowFont FamilyProportional Sans-SerifMonospace Sans-SerifProportional SerifMonospace SerifCasualScriptSmall Caps  
Reset restore all settings to the default valuesDone  
Close Modal DialogEnd of dialog window.  

## Images

![(MATLAB)EMD-ARIMA Joint Time Series Forecasting Algorithm, Preferred Research and Innovation Algorithm](cover.jpg)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
