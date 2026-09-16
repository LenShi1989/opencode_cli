# opencode_cli

## OpenCode 指令大全

## 最常用指令

| 指令                 | 用途          | 範例                               |
| -------------------- | ------------- | ---------------------------------- |
| `opencode`           | 開啟目前目錄  | `opencode`                         |
| `opencode .`         | 開啟目前專案  | `opencode .`                       |
| `opencode <路徑>`    | 指定工作目錄  | `opencode D:\Gitlab\benton_system` |
| `opencode --help`    | 查看說明      | `opencode --help`                  |
| `opencode --version` | 查看版本      | `opencode --version`               |
| `opencode run "..."` | 非互動執行    | `opencode run "分析這個專案"`      |
| `opencode mini`      | 啟動簡易介面  | `opencode mini`                    |
| `opencode upgrade`   | 更新 OpenCode | `opencode upgrade`                 |

## ⭐ OpenCode TUI 內建 / 指令

| TUI 指令     | 功能                    |
| ------------ | ----------------------- |
| `/help`      | 顯示說明                |
| `/init`      | 建立 / 更新專案 AI 規則 |
| `/new`       | 建立新 Session          |
| `/clear`     | `/new` 的 Alias         |
| `/sessions`  | 查看 / 切換 Session     |
| `/resume`    | 繼續 Session            |
| `/continue`  | 繼續 Session            |
| `/compact`   | 壓縮目前 Context        |
| `/summarize` | `/compact` Alias        |
| `/models`    | 查看模型                |
| `/themes`    | 查看 Theme              |
| `/editor`    | 開啟外部編輯器          |
| `/export`    | 匯出對話                |
| `/details`   | 顯示 / 隱藏工具執行細節 |
| `/undo`      | Undo                    |
| `/redo`      | Redo                    |
| `/share`     | 分享 Session            |
| `/unshare`   | 取消分享                |
| `/exit`      | 離開                    |
| `/quit`      | 離開                    |
| `/q`         | 離開                    |
