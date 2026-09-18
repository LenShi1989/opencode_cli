# opencode_cli

## OpenCode 指令大全

## 最常用指令

```sh
opencode                           # 開啟目前目錄
opencode .                         # 開啟目前專案
opencode D:\Gitlab\benton_system   # 指定工作目錄
opencode --help                    # 查看說明
opencode --version                 # 查看版本
opencode run "分析這個專案"         # 非互動執行
opencode mini                      # 啟動簡易介面
opencode upgrade                   # 更新 OpenCode


opencode session list                                # Session 管理
opencode session list --max-count 20               # 限制數量
opencode session list --format json                 # JSON
opencode session export <SESSION_ID>                 # Export
opencode session export <SESSION_ID> --sanitize     # 安全處理敏感資料
opencode session import session.json               # Import

opencode agent --help          # 查看
opencode agent create           # 建立 Agent

建立 Agent




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
