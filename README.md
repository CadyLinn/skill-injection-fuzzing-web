# Markdown 間接提示注入 Fuzzing 與 AI 防禦研究

<https://cadylinn.github.io/skill-injection-fuzzing-web/>

研究會載入第三方 `SKILL.md`、具備持久記憶與工具呼叫能力的 LLM Agent，將跨回合攻擊拆成 F5（惡意技能供應鏈）→ F2（記憶污染）→ F3（工具濫用）三個階段量測，並評估 Defender AI 與 gate 防禦。

頁面：`index.html` 首頁、`research.html` 研究目標與規範、`experiments.html` 系統設計與方法、`results.html` 實驗結果、`reflection.html` 進度、學習與心得。

> 全程只用 mock 工具、語料去武器化，不含真實攻擊指令或工具執行，僅供受控學術研究用途。
