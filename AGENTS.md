# AGENTS.md

- 回應一律使用繁體中文。
- 專案語言為 Python；用 conda 管理套件，環境名稱為 `iem_python`（已驗證為 Python 3.12.13）。
- conda 不在預設 `PATH`，須用完整路徑執行：`C:\Users\user\anaconda3\Scripts\conda.exe run -n iem_python <command>`；勿用 `pip`、`uv` 或系統 Python。
- Greenfield repo — 僅有佔位 `README.md` 和 Python-template `.gitignore`，尚無原始碼、manifest、測試或 CI；新增工具鏈或進入點時在此補上確切指令。
