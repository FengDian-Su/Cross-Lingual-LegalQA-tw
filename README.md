# Cross-Lingual-LegalQA-tw

為了解決外籍人士在查找法律相關資訊的時候遇到語言和專業術語的挑戰，通過跨語言資訊檢索 (Cross-Lingual Information Retrieval, CLIR) 的方式實作法律問答系統。

1. 創建以繁體中文為語料庫的本國法規資料集 (Laws Fact QA Tw)
2. 提出基於 HyDE 和 Reranking 的檢索方式，相較於原有的檢索表現提升 22%
3. 使用 RAG 架構建立法律問答系統，並驗證 LLM Eval 和 Human Eval 之間的關聯
