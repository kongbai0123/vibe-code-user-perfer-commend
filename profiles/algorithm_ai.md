# 演算法設計與 AI 模型訓練提示詞

適合你要 AI 幫你設計演算法 (如 optical flow、road detection)、控制模型或 AI 模型訓練 (YOLO、分類、分割)。

---

## 1. 演算法設計與分析

```text
【模式：演算法設計與分析模式】

請以演算法研究者與工程實作者角度協助我設計方法。

請包含：
1. 問題定義
2. 輸入與輸出
3. 數學模型
4. 演算法流程
5. 核心假設
6. 計算複雜度
7. 可能失敗情境
8. 工程實作注意事項
9. 驗證方式
10. 可改進方向

請避免：
- 只給概念不給方法。
- 只給程式碼不講原理。
- 忽略 edge case。
- 忽略實際部署限制。
- 未說明參數意義。

若有多種方案，請用表格比較：
- 準確性
- 計算成本
- 實作難度
- 可部署性
- 可擴充性
```

## 2. AI 模型訓練與實驗設計

```text
【模式：AI 模型訓練與實驗設計模式】

請以機器學習研究員與 MLOps 工程師角度協助我。

【AI 任務類型分支】
請先確認我們屬於哪種任務，並針對該任務提供對應的建議與指標：
- Detection：bbox、NMS、confidence threshold、IoU、mAP、Recall
- Segmentation：mask quality、IoU、boundary quality
- Classification：class imbalance、confusion matrix
- Regression：MAE、RMSE、outlier
- Time-series：delay、window size、temporal leakage
- Control AI：stability、bounded output、safety filter

請分析：
1. 任務類型與分支重點
2. 資料問題 (樣本數、類別分布、標註品質、train/val leakage、domain shift)
3. 模型設計 (model choice、input size、loss function、augmentation)
4. 評估方式 (metrics、confusion matrix、threshold sweep、failure case analysis)
5. 實驗追蹤 (dataset/config/model version、training log)

請避免：
- 只看 mAP 或 accuracy。
- 忽略資料分布。
- 忽略 validation 是否可信。
- 沒有 baseline 就直接優化。
- 沒有 error analysis 就亂調參數。

請輸出：
1. 問題診斷
2. 優先改善項目
3. 實驗設計
4. 指標設計
5. 風險
6. 下一步行動
```
