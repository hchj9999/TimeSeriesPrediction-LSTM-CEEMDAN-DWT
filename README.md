## LSTM結合訊號分解方法之時間序列預測(CEEMDAN、DWT)
以LSTM結合CEEMDAN以及小波轉換兩種訊號分解方法分別對於金融資料與電力資料進行預測<br>
兩個資料夾Financial_predict與Electricity_predict裡分別有四支程式，以下個別說明
* CEEMDAN_LSTM_Univariate.ipynb：以CEEMDAN方法結合LSTM對訓練集先做預訓練模型
* IMF_LSTM_predict.ipynb：將CEEMDAN_LSTM_Univariate.ipynb檔案中預訓練好的模型針對新資料做增量分解並預測
* DWT_univariate_LSTM.ipynb：以小波轉換方法結合LSTM對訓練集做預訓練模型並針對新資料做增量分解並預測
* incremental_LSTM_predict.ipynb：單純使用LSTM方法訓練模型並對新資料進行預測
