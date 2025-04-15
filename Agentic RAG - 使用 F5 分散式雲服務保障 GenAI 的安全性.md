# Agentic RAG - 使用 F5 分散式雲服務保障 GenAI 的安全性

在我上一篇文章《利用 Agentic RAG 與 F5 平台強化你的 GenAI 聊天機器人》中，我討論了如何利用 Agentic 檢索增強生成（RAG）和 F5 平台的力量來提升生成式 AI（GenAI）聊天機器人的效能。那篇文章提供了有關代理式 RAG（Agentic RAG）運作方式的高層次概述，並詳細說明了其背後的處理流程。本文作為後續內容，將展示如何在前述基礎概念之上，確保 Agentic RAG 的安全性。

保障 Agentic AI（或整體 GenAI）的安全，需要實施多層次的安全控制。值得注意的是，GenAI 應用屬於現代應用，採用了當代應用框架與方法論（相較於傳統的單體應用）。這些應用通常是分散式架構，經常在如 Kubernetes 等容器化平台上運行。由於其分散式、微服務導向的架構，GenAI 應用在極大程度上仰賴 API，而 API 正是 GenAI 服務的骨幹。

為了確保全面的安全性，傳統的控制措施，例如網頁應用與 API 保護（WAAP）、機器人管理、高階 API 安全措施，以及遵循安全最佳實踐，仍然是不可或缺的。然而，為應對 GenAI 應用所面臨的獨特挑戰，需採用專為此設計的解決方案，如 AI Gateway，這類工具專注於 AI 執行時的安全性與流量治理，至關重要。

在本文中，我們將探討六項關鍵的安全控制措施，這些措施旨在保障 AI 服務的安全性。如文章《F5 AI Gateway：保障、交付並優化 GenAI 應用》中所示，利用 AI Gateway 保護 AI 服務已經展現出其成效。

## 使用 F5 分散式雲服務保障 GenAI 安全（示範影片）

如需進一步深入探討，歡迎隨時聯繫 F5。

[![觀看影片](https://img.youtube.com/vi/Pwb8k3LPKgI/0.jpg)](https://www.youtube.com/embed/Pwb8k3LPKgI?si=mfTHW5qKnzwBm2G7)
