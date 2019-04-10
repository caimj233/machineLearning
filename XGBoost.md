
# XGBoost

全稱為extreme gradient boosting，是陳天奇Tianqi Chen發明并實現的，在[xgboost開源庫](https://github.com/dmlc/xgboost)。

## 算法原理

xgboost也是一個基於決策樹的集成算法，集成方式是gradient boosting，即梯度提升。

其中boosting是將弱學習器的結果纍加，使損失函數（分類可能用交叉熵，回歸可能用平方誤差）最小；
gradient boosting是在添加新個體學習器的時候使用梯度下降法計算使損失最小化的參數，且擬合的是當前集成學習器的殘差，
最終的結果一定比單個個體學習器要好。

### 損失函數
xgboost和gbdt在損失函數的定義上有比較大的不同。

### 分裂節點算法
### 正則化
## 對缺失值的處理
## 優缺點

\+ 計算速度比一般的gradient boosting算法要快，有并行化和分佈式計算。

\+ 模型表現好。
##  應用場景

一般分類問題和回歸問題都能使用

## sklearn參數

## 參考資料
1. [寫得很清晰](https://www.jianshu.com/p/7e0e2d66b3d4)
2. [寫得很清晰且有數學公式](https://blog.csdn.net/a819825294/article/details/51206410)

