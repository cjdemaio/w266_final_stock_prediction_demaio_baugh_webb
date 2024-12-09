# w266_final_stock_prediction

filter_news.ipynb - cuts news from 2018 to 2023 for S&P 100 stocks

pull_stock_data.ipynb - pulls OHLCV for S&P100 from 2018 to 2023 for S&P 100 stocks

arima_baseline.ipynb - calculates ARIMA baseline

EDA_stock_news.ipynb - EDA for news data

EDA_EDT_data.ipynb - EDA on Business Event labeled data

FinBERT_sentiment_classifier - Leverages pre-trained FinBERT to rate article as negative to positive sentiment

BusinessEventFinBERT_finetune_266.ipynb - Traditional fine-tuning on FinBERT to extract business events

LORA_BusinessEvent_FinBERT_finetune_266.ipynb - LoRA adapter fine-tuning on FinBERT to extract business events

Business_event_prediction - Applies Fine-tuned FinBERT to FNSPID news articles

Business_event_prediction_LORA.ipynb - Applies LoRA-adapted FinBERT to FNSPID news articles

merge_ohlcv_news.ipynb - Merges OHLCV, News Sentiment and Business events from Fine-Tune and LoRA

lstm_predict.ipynb - LSTM network predictions for Stock data and news sentiment only

lstm_predict_events.ipynb - LSTM network predictions for Stock data, news sentiment & Fine-tuned Events

lstm_predict_events_lora.ipynb - LSTM network predictions for Stock data, news sentiment & LoRA-adapted Events
