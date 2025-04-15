# F5 AI Gateway - 保護、傳遞並優化 GenAI 應用程式

## 引言

人工智慧（AI）已徹底改變了我們的生活與工作方式，革新了各行各業並提升了日常生活品質。透過自動化重複性任務及促進數據驅動的決策制定，AI 解鎖了前所未有的創新力、效率與生產力。對企業而言，AI 提供了重要的競爭優勢，能簡化營運流程、增強客戶體驗並推動業務成長。然而，**機會越大，風險也越高**。AI 同時也帶來了安全性上的挑戰，包括潛在的濫用、資料外洩以及擴大的攻擊面。因此，企業必須正視這些挑戰，並採取強而有力的網路安全措施來降低風險。

此外，AI 是一項需要大量投資的技術，其投資報酬率在目前（撰文時）仍難以量化。如果缺乏適當的監管與優化，AI 預算可能迅速失控。在導入 AI 時保持負責任的態度——在其效益與風險之間取得平衡——才能確保企業在這個日益 AI 化的世界中實現可持續的成長與韌性。

在 F5，我們提供廣泛的控制工具來保護您的 AI 基礎架構，這些工具不僅適用於 AI 系統，也適用於所有 IT 環境。

本文與影片示範的重點是 AI Gateway（AI GW），它提供**執行時安全性與流量治理**。值得注意的是，像是保護 API（作為任何 AI 服務的核心）等其他控制措施同樣至關重要。

F5 AI Gateway 專為解決特定挑戰而設計，例如《OWASP Top 10 for LLM Applications》中列舉的問題。它擁有可擴展的架構，配備了專為特定目的打造的處理器與插件，並提供軟體開發套件（SDK）以因應自定義使用情境。

以下是關於 F5 AI Gateway 的示範影片。

## LLM 的流量管理與優化

AI Gateway 的功能不僅限於安全控制工具。它在成本優化與流量管理上也扮演了重要角色。此影片展示了 F5 AI Gateway 在管理與優化 LLM 流量方面的價值與能力，幫助最佳化資源使用、降低成本、提升使用者體驗並保護資料隱私。

[觀看影片：Traffic Management and Optimisation of LLM](https://www.youtube.com/watch?v=BqeL67osUBU)

## 保護 LLM 應用程式

展示 F5 AI GW 如何利用內建 AI 處理器功能，解決《OWASP TOP 10 for LLM Apps》中提出的一些關鍵安全疑慮。

[觀看影片：Securing LLM Applications](https://www.youtube.com/watch?v=5k1AwmOKxgA)

## 特定功能的示範影片

請注意，以下各個特定功能的示範影片為整體流量管理、優化與安全性示範中的摘錄片段。

### 具身分識別的模型路由（Identity Aware Model Routing）

展示 F5 AI Gateway 根據使用者身分（基於 JSON Web Token（JWT）或標頭）動態套用與導引 LLM 流量策略的能力。

[觀看影片：Identity Aware Model Routing](https://www.youtube.com/watch?v=nl0AmeaXaEY)

### 語言與程式碼偵測路由（Language and Code Detection Routing）

展示 F5 AI Gateway 偵測輸入語言類型並根據定義的語言模型導引流量，以提升使用者體驗與成本效益。同時展示其對程式碼的偵測功能，將流量導引至本地自託管模型，以避免無意中洩露程式碼至 SaaS 管理的模型。

[觀看影片：Language and Code Detection Routing](https://www.youtube.com/watch?v=ySp6EnY89PU)

### 系統提示強制（System Prompt Enforcement，Guardrail）

展示 F5 AI Gateway 的系統提示能力，確保對話內容維持在預期的語境中。AI Gateway 強制執行嚴格的使用邊界，防止使用者偏離聊天機器人的預期用途。

[觀看影片：System Prompt Enforcement](https://www.youtube.com/watch?v=ZVzeQKUhs-4)

### OWASP Top 10 LLM01 - 提示注入（Prompt Injection）

展示 Prompt Injection 處理器以解決《OWASP TOP 10 for LLM Apps》中與提示注入相關的幾項主要安全疑慮（LLM01）。

[觀看影片：Prompt Injection](https://www.youtube.com/watch?v=fXnu1JmqcgA)

### OWASP Top 10 LLM02 - 敏感資訊洩漏（PII）

展示 PII 資訊遮蔽處理器，以解決《OWASP TOP 10 for LLM Apps》中有關敏感資訊洩漏的主要問題（LLM02）。

[觀看影片：Sensitive Information Disclosure (PII)](https://www.youtube.com/watch?v=1n-du-D-4IQ)

### OWASP Top 10 LLM07 - 系統提示洩漏（System Prompt Leakage）

展示 System Prompt 處理器，以解決《OWASP TOP 10 for LLM Apps》中針對系統提示洩漏的關鍵問題（LLM07）。

[觀看影片：System Prompt Leakage](https://www.youtube.com/watch?v=gfeyP5aTdDc)

---

若需更深入的技術說明，請聯繫 F5 代表。

**版本：1.0**
