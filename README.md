# opencode_cli

# 安裝指令

```sh
curl -fsSL https://opencode.ai/install | bash
npm i -g opencode-ai
```

## OpenCode 指令大全

## 最常用指令

```sh
opencode                                          # 開啟目前目錄
opencode .                                        # 開啟目前專案
opencode D:\Gitlab\benton_system                  # 指定工作目錄
opencode --help                                   # 查看說明
opencode --version                                # 查看版本
opencode --continue                               # 繼續上次工作
opencode run "分析這個專案"                        # 非互動執行
opencode mini                                     # 啟動簡易介面
opencode upgrade                                  # 更新 OpenCode

opencode session list                             # Session 管理
opencode session list --max-count 20              # 限制數量
opencode session list --format json               # JSON
opencode session export <SESSION_ID>              # Export
opencode session export <SESSION_ID> --sanitize   # 安全處理敏感資料
opencode session import session.json              # Import

opencode agent --help                             # 查看
opencode agent create                             # 建立 Agent

opencode models                                   # 查看模型
opencode models --refresh                         # 刷新 Provider Model
opencode --model ollama/qwen3.5:9b                # 指定模型

opencode serve                                    # 啟動 OpenCode Server
opencode serve --port 4096                        # 指定 Port
opencode serve --hostname 0.0.0.0 --port 4096     # 允許其他網路介面
opencode serve --cors https://example.com         # 設定 CORS

opencode service start                            # 背景服務
opencode service status                           # 查看
opencode service restart                          # 重啟
opencode service stop                             # 停止

opencode debug agents                             # 這幾個很適合遇到 OpenCode 問題時使用
opencode debug config                             # 查看設定來源
opencode debug paths                              # 查看 OpenCode 路徑
opencode debug paths db                           # 查看 DB 路徑

opencode uninstall --dry-run                      # 預覽
opencode uninstall                                # 完整移除
opencode uninstall --keep-config                  # 保留設定
opencode uninstall --keep-data                    # 保留資料
```

## ⭐ OpenCode TUI 內建 / 指令

| TUI 指令   | 功能                    |
| ---------- | ----------------------- |
| /help      | 顯示說明                |
| /init      | 建立 / 更新專案 AI 規則 |
| /new       | 建立新 Session          |
| /clear     | /new 的 Alias           |
| /sessions  | 查看 / 切換 Session     |
| /resume    | 繼續 Session            |
| /continue  | 繼續 Session            |
| /compact   | 壓縮目前 Context        |
| /summarize | /compact Alias          |
| /models    | 查看模型                |
| /themes    | 查看 Theme              |
| /editor    | 開啟外部編輯器          |
| /export    | 匯出對話                |
| /details   | 顯示 / 隱藏工具執行細節 |
| /undo      | Undo                    |
| /redo      | Redo                    |
| /share     | 分享 Session            |
| /unshare   | 取消分享                |
| /exit      | 離開                    |
| /quit      | 離開                    |
| /q         | 離開                    |
