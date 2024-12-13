# 【LLM API】實作串接 OpenAI
本專案介紹兩種串接 OpenAI API 的方法：使用官方 Python 套件，以及通過 HTTP 請求(利用 requests 套件)來直接發送請求，並比較不同版本 (v0.28 與 v1.57.3) 的程式碼差異。

# 主要功能
- 利用 OpenAI 官方 Python 套件調用 API。
- 實作 HTTP 請求，直接調用 OpenAI API。
- 比較 v0.28 與 1.57.3 版本程式碼的差異。

# 專案結構
llm-api-openai/
├── llm-api-openai.ipynb   # 主程式碼檔案
├── .env                   # 環境變數檔案
└── README.md              # 專案說明文件