# 血染鐘樓《規則怪談》RAG 對話機器人（第七週作業）

| 檔案 | 說明 |
|---|---|
| `rules_horror_rag-data.zip` | 69 個 TXT chunk 資料集（RAG01 從這裡自動下載） |
| `rules_horror_rag-data/` | 同上，解壓縮後的內容，方便直接瀏覽 |
| `rules_horror_vector_db.zip` | RAG01 匯出的 FAISS 向量資料庫（RAG02 從這裡自動下載） |
| `規則怪談_RAG01_建立向量資料庫.ipynb` | 讀取資料、EmbeddingGemma 2 向量化、建立 FAISS 索引 |
| `規則怪談_RAG02_祭司對話機器人.ipynb` | 「鴉木布拉夫小鎮的祭司」RAG 問答 + Gradio |
| `build_chunks.py` | 把 PDF 內容切成 chunk 的腳本 |

資料來源：鐘樓劇本博物館〈【染鐘樓】劇本社群—第332期《規則怪談》〉，劇本作者：星火樂。僅供課程作業使用。
