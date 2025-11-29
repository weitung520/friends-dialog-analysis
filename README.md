
# 🎬 Friends Dialogue Text Analysis  
課程：碩一 - 社群媒體分析
目標：分析《Friends 六人行》全季全集數的56,329 筆對白資料的自然語言處理專案

## 📁 Project Overview  
本專案以美國情境喜劇 **《Friends》**（六人行）之 56,329 筆 Kaggle 對白資料為研究對象，透過多項 NLP 技術進行情緒分析、實體識別、關鍵詞特徵抽取與主題模型分析，並視覺化角色互動與台詞資訊。本專案適合作為文本探勘、情緒分析與主題探索的教學示例或作品集展示。

---

## 📌 Summary（中文摘要）
本研究從《Friends》的大量對白資料中，分析角色互動、情緒變化與主題內容。首先透過 **Stanza 與 CoreNLP** 完成實體識別與詞性標註，並以 **LIWC 字典** 執行情緒分類，觀察不同季與集數的情緒分布情形。接著以 **TF-IDF 與 2/3-gram** 萃取重要詞彙，並使用 **LDA 與 BERTopic 模型** 探索劇中主題變化。研究也生成 **文字雲（WordCloud）** 來呈現高頻詞彙。本專案建構完整的 NLP 分析流程，有效揭示角色關係、情緒傾向以及劇情主題演進。

---

## 🛠️ Methods & Techniques（方法與技術）
### 🔹 NLP 前處理
- Tokenization（斷詞）
- POS Tagging（詞性標註）
- NER（實體識別）
- Stopwords removal
- Word frequency statistics

### 🔹 情緒分析
- **LIWC 英文字典**
- Sentiment distribution across seasons/episodes

### 🔹 特徵抽取
- **TF-IDF**
- **2-gram / 3-gram** 特徵建構

### 🔹 主題模型
- **LDA（Latent Dirichlet Allocation）**
- **BERTopic（搭配 Transformer 嵌入）**

### 🔹 視覺化
- WordCloud（文字雲）
- Matplotlib 圖表呈現

### 🔹 使用套件
- Python
- pandas / numpy
- scikit-learn
- stanza
- CoreNLP
- wordcloud
- matplotlib
