# Awesome-Time-Series-Forecasting-Platform

## Top Time-Series Forecasting Platform Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Demand Prediction, Anomaly Detection & Self-Hosted Forecasting Libraries*  

**Last updated: October 2026**



This repository tracks notable **commercial time-series forecasting platforms** and **open-source projects** that predict future values from historical data. These tools range from fully managed AutoML services to open-source Python libraries for statistical and deep learning forecasting.



**Examples** include Amazon Forecast, DataRobot Time Series, Google Cloud Vertex AI Forecasting, Anodot, Pecan AI, Dataiku DSS, Nixtla TimeGPT, Tangent Works, H2O Driverless AI, and Azure Automated ML Forecasting (the category leaders).



**Open-source emphasis**: Time-series forecasting has a rich open-source ecosystem. **Nixtla's StatsForecast, NeuralForecast, and MLForecast** provide production-grade libraries, while **FELITS** offers end-to-end pipelines with XAI, **Omnicast** delivers automatic statistical forecasting, and **TSFM** wraps foundation models (Moirai, Chronos) with a consistent API. **sktime** and **Prophet** remain foundational. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Amazon Forecast](https://aws.amazon.com/forecast/)**  

  **AWS's fully managed time-series forecasting service** — uses the same technology as Amazon.com for demand prediction, inventory planning, and resource forecasting . **No ML experience required** — automatically inspects data, selects algorithms, and trains custom models . Supports **state-of-the-art algorithms** including DeepAR+, CNN-QR, and Prophet. **Note**: Amazon Forecast is no longer available to new customers; existing customers can continue using the service . **Best for AWS-centric organizations** with existing Forecast deployments.



- **[DataRobot Time Series](https://www.datarobot.com/)**  

  **Enterprise AutoML with comprehensive time-series capabilities** — automated feature derivation, backtesting, and model selection . Supports **multiseries modeling**, known-in-advance features, and event calendars . **Best for enterprises** wanting governed, automated forecasting.



- **[Google Cloud Vertex AI Forecasting](https://cloud.google.com/vertex-ai)**  

  **Google's AutoML forecasting** — supports ARIMA+ and hierarchical aggregation for consistent forecasts across product categories . **Best for Google Cloud users** wanting AutoML forecasting.



- **[Anodot](https://www.anodot.com/)**  

  **AI-powered anomaly detection and forecasting** for business metrics. **Best for real-time anomaly detection**.



- **[Pecan AI](https://www.pecan.ai/)**  

  **Predictive AI for business outcomes** — demand forecasting, churn prediction, and LTV modeling without a data science team. **Best for CRM-integrated predictive analytics**.



- **[Dataiku DSS](https://www.dataiku.com/)**  

  **Collaborative data science platform with visual time-series forecasting** — supports statistical, deep learning, and baseline algorithms . Handles multiple time series with identifier columns and automatic resampling . **Best for enterprise data science teams**.



- **[Nixtla TimeGPT](https://www.nixtla.io/)**  

  **The first foundation model for time-series forecasting** — production-ready generative pretrained transformer for retail, electricity, finance, and IoT . **Zero-shot inference** out of the box, fine-tuning for custom scenarios, and multivariate support in TimeGPT 2.1 . **Closed source** but accessible via hosted API or self-hosted deployment . **Best for enterprises wanting foundation model forecasting**.



- **[Tangent Works](https://www.tangent.works/)**  

  Automated time-series forecasting and anomaly detection for industrial and business applications.



- **[H2O Driverless AI](https://h2o.ai/)**  

  **Enterprise AutoML with time-series forecasting** — automatic feature engineering and model selection.



- **[Azure Automated ML Forecasting](https://azure.microsoft.com/en-us/products/machine-learning/)**  

  **Microsoft's AutoML for time-series** — automated forecasting with Azure Machine Learning.



## Open-Source GitHub Projects



- **[StatsForecast (Nixtla)](https://github.com/Nixtla/statsforecast)**  

  **The leading open-source statistical forecasting library**, Apache-2.0 licensed. **Blazing fast implementations of ARIMA, ETS, CES, and Theta** — scales to millions of series. **The foundation for production forecasting pipelines** — used by Nixtla's own TimeGPT. **Best for high-performance statistical forecasting**.



- **[NeuralForecast (Nixtla)](https://github.com/Nixtla/neuralforecast)**  

  **Deep learning forecasting library**, Apache-2.0 licensed. **Implements N-BEATS, N-HiTS, TFT, and other neural architectures** — GPU-accelerated. **Best for deep learning-based forecasting**.



- **[MLForecast (Nixtla)](https://github.com/Nixtla/mlforecast)**  

  **Machine learning forecasting with LightGBM, XGBoost, and scikit-learn**, Apache-2.0 licensed. **Feature engineering for lag features, rolling statistics, and date features**. **Best for ML-based forecasting**.



- **[FELITS](https://github.com/felits/felits)**  

  **End-to-end time-series analysis and forecasting library**, open-source with INIC01-6 research funding . **Complete pipeline**: signal cleaning, feature engineering, feature selection, predictive modelling, and **explainable AI (XAI)** . **Models**: XGBoost, RandomForest, LSTM/GRU/BiLSTM with Bahdanau attention . **XAI**: LIME, SHAP, and Deep SHAP for feature elimination . **Dual API** for pandas and polars . **Best for research and explainable forecasting**.



- **[Omnicast](https://github.com/afraz496/omnicast)**  

  **Automatic statistical forecasting for Python with one consistent, interval-aware API**, open-source (v0.1 alpha) . **Models**: Naive, Seasonal Naive, Mean, Drift, Theta, ETS, ARIMA, AutoARIMA, and LSTM . **Backtesting with expanding windows** and model selection via `AutoForecaster` . **Prediction intervals** with configurable coverage . **Best for automatic model selection with statistical foundations**.



- **[TSFM (Time Series Forecasting Models)](https://github.com/tsfmecb/tsfmecb)**  

  **Wrapper for foundation models with consistent API**, open-source . **Models**: Salesforce **Moirai 1.1 and 2.0**, Amazon **Chronos and Chronos 2.0**, and ARModel . **Frequency-aware** with automatic detection . **Quantile forecasts** for probabilistic predictions . **Best for experimenting with foundation models**.



- **[Prophet (Meta)](https://github.com/facebook/prophet)**  

  **The most widely used open-source forecasting library**, MIT licensed. **Decomposable time series model** with trend, seasonality, and holidays. **Best for business forecasting with interpretable components**.



- **[sktime](https://github.com/sktime/sktime)**  

  **Unified framework for time-series machine learning**, BSD-3-Clause licensed. **Forecasting, classification, and regression** with a consistent API. **Best for comprehensive time-series ML**.



- **[Darts](https://github.com/unit8co/darts)**  

  **User-friendly forecasting library**, Apache-2.0 licensed. **Statistical and deep learning models** with a scikit-learn-like API. **Best for quick prototyping**.



- **[GluonTS](https://github.com/awslabs/gluonts)**  

  **Probabilistic time-series modeling from AWS**, Apache-2.0 licensed. **The foundation for Amazon Forecast algorithms**. **Best for probabilistic forecasting research**.



- **[PyTorch Forecasting](https://github.com/jdb78/pytorch-forecasting)**  

  **Deep learning forecasting with PyTorch**, MIT licensed. **Implements TFT, N-BEATS, and DeepAR** with Lightning integration. **Best for PyTorch users**.



- **[Kats (Meta)](https://github.com/facebookresearch/kats)**  

  **Toolkit for time-series analysis**, MIT licensed. **Forecasting, detection, and feature extraction**. **Best for time-series analysis**.



### Additional Strong Open-Source Options



- **AutoTS** — Automated time-series forecasting with model selection .

- **PyCaret** — Low-code ML with time-series module .

- **Merlion (Salesforce)** — Time-series intelligence library .

- **Orbit (Uber)** — Bayesian time-series forecasting .

- **pmdarima** — ARIMA modeling for Python .

- **arch** — Financial time-series modeling .

- **tsfresh** — Feature extraction for time series .

- **sktime** — Unified time-series ML framework .

- **Pandas Profiling** — Automated EDA with time-series support .



**Frameworks for building custom time-series forecasting solutions**: Combine **StatsForecast** for fast statistical baselines with **MLForecast** for ML-based improvements and **NeuralForecast** for deep learning . Use **FELITS** for explainable forecasting with XAI . Deploy **Omnicast** for automatic model selection with interval-aware predictions . Experiment with **TSFM** for foundation model forecasting (Moirai, Chronos) . Integrate **Prophet** for business-friendly interpretable forecasts . Note that true enterprise forecasting platforms with governed AutoML, CRM integration, and business-outcome predictions (DataRobot, Dataiku, Nixtla TimeGPT) remain primarily commercial territory; open-source stacks provide strong statistical, ML, and deep learning forecasting foundations that require integration for complete enterprise deployment.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Time-series forecasting platforms handle sensitive business data. **Review data privacy policies** — cloud platforms store data on their servers. Self-hosted solutions require proper security hardening.

- **Forecasting accuracy depends on data quality** — missing values, irregular timestamps, and insufficient history degrade predictions . Preprocessing is critical.

- **Amazon Forecast is no longer available to new customers** — existing customers can continue using the service . Consider alternatives like DataRobot or open-source libraries for new deployments.

- **TimeGPT is closed source** — while accessible via API or self-hosted deployment, the model weights are not publicly available . Open-source alternatives like StatsForecast, NeuralForecast, and FELITS provide transparency and control .

- The open-source ecosystem provides strong statistical, ML, and deep learning forecasting foundations, but **governed AutoML, CRM integration, and business-outcome predictions** remain primarily commercial offerings.



---



**Made for data scientists, demand planners, and organizations seeking forecasting sovereignty.**  

Let's make time-series forecasting more open, transparent, and accessible.
