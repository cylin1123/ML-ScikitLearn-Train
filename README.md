# ML-ScikitLearn-Train
Machine Learning  -ScikitLearn-Train-DigitsExample

## Package
* NumPy (>= 1.8.2)
~~~
pip install numpy
sudo apt-get install python-numpy
~~~

* SciPy (>= 0.13.3)
~~~
pip install SciPy
~~~
* [Scikit-learn](http://scikit-learn.org/stable/user_guide.html)
~~~
pip install -U scikit-learn
~~~

* Pandas
~~~
pip install pandas
~~~
* Matplotlib
~~~
# Ubuntu 
sudo apt-get install python-matplotlib
~~~
## 機器學習運作流程
* 明確定義問題 (Problem Definition)
* 獲取資料與探索性資料分析 (Get Data & Exploratory Data Analysis)
* 資料預處理與特徵工程 (Data Clean/Preprocessing & Feature Engineering)
* 訓練模型與校調 (Model Training)
* 模型驗證 (Model Predict & Testing)
* 模型優化 (Model Optimization)
~~~
分類模型優化
* 特徵工程：選擇更適合特徵值或是更好的資料清理，某種程度上很需要專業知識的協助（domain konwledge）去發現和整合出更好的 feature
* 調整模型參數：調整模型的參數
* 模型融合：結合幾個弱分類器結果來變成強的分類器
~~~
* 上線運行 (Deploy Model)

## Flow Chart
![Screenshot](http://scikit-learn.org/stable/_static/ml_map.png)

* Iris 分析模型選擇流程
Step 1. 樣本資料是否大於 50 筆：範例資料集總共有 150 筆資料，大於 50
Step 2. 是否為分類問題：Iris 花朵類別預測是多類別分類問題
Step 3. 是否有標籤好的資料：已經有 label 資料
Step 4. 樣本資料是否小於 100K：資料小於 100K
Step 5. 選擇 Linear SVC 模型（第一個選擇的模型）
Step 6. 是否是文字資料：不是
Step 7. 選擇 KNeighborsClassifier 模型（第二個選擇的模型）
Step 8. 後續優化 / SVC / Ensemble
