# Time-Series-Forecasting-with-TimeGPT-and-Nixtla-API

## **Problem**

Accurate time series forecasting is critical for businesses and organizations to make data-driven decisions. In this project, we aim to forecast the Australian electricity demand and predict Amazon stock prices, leveraging the power of TimeGPT and Light Gradient-Boosting Machine (LGBM) models. The challenge lies in comparing the performance of both models to determine which one excels in predicting these time series datasets.

## **Solution**

We utilize the Nixtla API to access and fine-tune the TimeGPT model, a state-of-the-art foundational model for time series forecasting. TimeGPT is designed to handle long-term dependencies and generate accurate predictions in seconds. Additionally, we employ LGBM, a popular machine learning algorithm for regression tasks, to provide a benchmark for comparison.

## **The solution involves:**

- **Data Preprocessing:** Preparing the New South Wales electricity demand and Amazon stock price datasets.
- **TimeGPT Forecasting:** Using the Nixtla API to fine-tune and forecast future values.
- **LGBM Forecasting:** Implementing the LGBM model for comparison.
- **Model Evaluation:** Using cross-validation and evaluation metrics (MAE, RMSE, SMAPE) to assess model performance.

## **Impact**

The results demonstrate that TimeGPT is almost 5 times better than the LGBM model in terms of forecasting accuracy. This highlights the potential of TimeGPT as a superior tool for time series forecasting, especially for long-term predictions. By leveraging the Nixtla API, organizations can achieve high-quality forecasts with minimal effort, significantly reducing the need for specialized data science teams.

This project showcases the power of TimeGPT in real-world applications, from electricity demand forecasting to stock price predictions, and provides valuable insights into the future of time series modeling.

## Summary

- **Developed time series forecasting models** using the Nixtla API (TimeGPT) and Light Gradient-Boosting Machine (LGBM) to predict Australian electricity demand and Amazon stock prices.
- **Fine-tuned TimeGPT** for accurate long-term forecasting, outperforming LGBM by nearly 5x in prediction accuracy.
- **Preprocessed and prepared datasets** for New South Wales electricity demand and Amazon stock prices, ensuring data quality for model training.
- **Evaluated model performance** using metrics such as MAE, RMSE, and SMAPE to assess the accuracy and robustness of both models.
- **Leveraged the Nixtla API** for seamless integration of TimeGPT, significantly reducing the need for specialized machine learning expertise and optimizing forecasting workflows.
- **Demonstrated the power of foundational models like TimeGPT** in real-world applications, enhancing forecasting accuracy and decision-making for businesses.
