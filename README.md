# HealthMate-AI
結合人工智慧與檢索增強生成之智慧健康管理系統
一、專題簡介

HealthMate AI 是一套結合人工智慧與檢索增強生成（RAG）的智慧健康管理系統，目標是協助使用者記錄個人健康資料、了解健康變化趨勢，並透過 AI 提供健康資訊查詢服務。

本專題以一般健康管理為核心，機器學習模型則作為輔助分析功能，不作為醫療診斷工具。

二、主要功能規劃

健康紀錄管理： 記錄血壓、血糖、體重及 BMI 等健康資訊。

健康趨勢分析： 透過圖表呈現個人健康數據變化。

健康提醒： 協助使用者建立健康管理提醒。

AI 健康問答： 結合大型語言模型（LLM）與 RAG 技術，提供健康資訊查詢。

機器學習分析： 使用分類模型進行心臟疾病資料分析，作為輔助研究。

三、機器學習實驗

使用 UCI Heart Disease Dataset 進行心臟疾病二元分類實驗。

資料筆數：303 筆

分類模型：Logistic Regression、Decision Tree、Random Forest

評估指標：Accuracy、Precision、Recall、F1-score、AUC-ROC

四、使用技術

Python

Google Colab

Pandas、NumPy

Scikit-learn

Matplotlib、Seaborn

Large Language Model（LLM）

Retrieval-Augmented Generation（RAG）

五、資料集來源

UCI Machine Learning Repository – Heart Disease Dataset

https://archive.ics.uci.edu/dataset/45/heart+disease

六、專題開發狀態

目前已完成資料集整理、資料前處理及三種機器學習分類模型的初步比較。健康紀錄、趨勢分析、提醒與 AI 問答等系統功能仍在規劃及後續開發階段。

七、注意事項

本專題為學術研究與健康管理輔助用途，模型結果及 AI 回答不能取代醫師診斷或專業醫療建議。
