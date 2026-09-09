# Fortes Huang

**Staff 級前端架構師｜即時系統與 AI 輔助交付**

[fortes1219@gmail.com](mailto:fortes1219@gmail.com)｜+886 931 711 229｜台灣，可接受全球／遠端工作  
[LinkedIn](https://linkedin.com/in/fortes-huang)｜[GitHub](https://github.com/fortes1219)｜[HackMD](https://hackmd.io/@FortesHuang)

## 個人摘要

專注於高併發即時平台的 Staff 級前端架構師。我將前端架構視為系統成本與交付風險問題：分頁、Socket 與重新抓取在負載下的行為，決定了產品的營運成本。我負責 Vue 3／TypeScript 平台的即時資料流協調，以及多租戶白標系統的交付；同時設計 AI 輔助交付流程，確保正確性與責任歸屬仍由團隊掌握。我也將產品、設計與 QA 納入這些流程，讓 AI 導入提升真正的交付吞吐量，而不只是增加程式碼產量。

## 代表性成果

- **即時系統成本治理模型**：將高頻資料平面（市場行情串流）與低頻控制平面（領導者選舉、快照、加入抖動的重新抓取）分離，使同時開啟的 N 個分頁與視窗共同選出單一即時連線擁有者，避免每個分頁各自建立 Socket 並引發重新抓取風暴。藉此將每位客戶端造成的即時負載，從 SRE／雲端帳單問題重新定義為前端協調問題。
- **跨職能推行的 AI 交付治理框架**：以「AI 能提高生產產能，但不會提高審查或驗證產能」為核心前提，將其制度化為契約／實作／交付關卡、Agent 護欄與技能，以及可追溯的交接流程；再包裝成課程與可重複使用的工具套件，推廣至產品、設計、QA 與工程團隊。
- **廣受引用的技術文章**：關於工程團隊導入 AI 的文章，在 Google 搜尋「AI 導入工程」時名列前茅；其他主題涵蓋前端架構、AbortController 與 TanStack Query。

## 核心能力

- **前端平台與架構**：多租戶／白標系統、設計 Token 主題化、建置階段的品牌樣式隔離、動態路由、RBAC 權限引擎。
- **即時資料流與成本治理**：資料平面／控制平面分離、BroadcastChannel 領導者選舉、跨分頁協調、重新抓取風暴控制、Socket 生命週期。
- **AI 輔助交付治理**：契約優先流程、審查／交付關卡、驗證產能設計、Agent 護欄與技能、跨職能賦能。
- **效能與正確性**：Heap 分析與預算、非同步更新策略、金額精度、時區與報表正確性。
- **工程領導力**：工程標準、人才培育，以及與 Backend／SRE／Design／PM／QA 的跨團隊協作。
- **技術棧**：Vue 3、TypeScript、Vite、Pinia、TanStack Query、Zod + ts-rest；Rust（支援服務與工具）；Markdown + Mermaid 文件即程式碼。

## 工作經歷

### Staff／Lead Frontend Engineer・Frontend Architect｜XIHUI Co., Ltd.

**2024 年 9 月－2026 年 4 月**  
白標加密貨幣交易所｜百萬級流量、高併發工作負載

- 擔任前端架構負責人，負責平台的系統設計、技術決策與長期演進。
- 設計核心前端基礎設施，包括 Permission Engine（RBAC）、動態路由、QuerySync、Time Engine 與 Precision Engine。
- 建立即時協調層，導入資料平面／控制平面分離、BroadcastChannel 領導者選舉與加入抖動的重新抓取；消除多分頁／多視窗工作階段中的重複 Socket 與重新抓取風暴，控制大規模即時系統的成本。
- 規劃多租戶交付系統（動態打包 + 設計 Token 主題化），並建立可自動產生設計 Token 的 Figma Design-to-Code MCP 流程，縮短設計與實作之間的落差。
- 建立架構藍圖、工程標準及契約優先的 API 流程（Zod + ts-rest），降低整合錯誤與長期耦合。
- 重新設計權限資料模型，並透過多次 Heap Snapshot 分析驗證，使 JavaScript Heap 使用量降低約 40%。
- 主導 AI 輔助交付治理：調校 Agent 規則與技能（contract-review、phase-verify、pr-review、security-boundary-review、handoff-maintainer），使其在有界情境中運作；透過護欄及契約／實作／交付關卡，要求每項 AI 產出都必須聲明正確性定義、負責人與出貨證據。
- 推動 PM、設計與 QA 的跨職能導入：將工作流程包裝成課程與可重複使用的工具套件（Claude／Codex 配對範例、Linear 交接流程），並以生產／審查／驗證產能為框架，確保驗證速度跟得上 AI 加速後的產出。

### Senior Frontend Engineer｜Tianxin Technology Co., Ltd.

**2023 年 11 月－2024 年 6 月**  
消費者生活風格平台（Wota Lifestyle）

- 在既有程式碼庫中交付核心使用者功能並穩定關鍵流程；擴充功能的同時，維持與既有架構模式的一致性。
- 與設計及後端團隊共同解決跨流程整合問題與邊界情境，在上線前改善可用性與交付可靠度。

### Senior Frontend Engineer｜Ascella Technology Co., Ltd.

**2023 年 3 月－2023 年 9 月**  
Design System 實作

- 主導 Design System 的實際落地，將設計原則轉化為可重複使用的元件與 Token，使規範能在程式碼庫中確實執行，而不只停留在概念層次。
- 與設計主管合作，使設計意圖符合工程現實，並為元件結構、樣式與使用方式建立基礎規範。

### Senior Frontend Engineer｜Vinnovation Network Co., Ltd.

**2022 年 7 月－2023 年 3 月**  
大型內容平台

- 建置及維護具複雜使用者互動的內容平台前端。
- 設計客戶端圖片快取／交付機制（IndexedDB），整合 CDN 圖片訂閱與 Base64 轉換，使低頻寬及不穩定裝置也能進行適合離線使用的循序閱讀器式渲染。

### Senior Frontend Engineer｜Hlwtech Co., Ltd.

**2021 年 6 月－2022 年 5 月**  
線上遊戲平台｜多語系系統

- 建置線上遊戲平台的使用者介面及多語系管理系統。
- 推動 Git 工作流程（在 CentOS 7 上自架 GitLab，取代舊有 SVN）；設計以 JSON 為基礎的 i18n 架構，以及 CSV ↔ JSON 工具流程，降低翻譯錯誤與迭代成本。

## 寫作、演講與社群

- **Vue Taiwan Meetup 講者（2026）**：「即時連線的責任歸屬：控制平面、領導者選舉，以及馴服重新抓取風暴。」開源參考實作：[Frontend](https://github.com/fortes1219/socket-meetup-frontend)・[Backend](https://github.com/fortes1219/socket-meetup-backend)・[Slides](https://drive.google.com/file/d/1PDq8JyvRjnvsZlmJ-Ay3bA9Dflw9FsdA/view)・[現場指南](https://meetup.akasa-lab.dev/)
- **精選文章**：[〈工程團隊導入 AI：真正的瓶頸是 PR 審查與驗證責任〉](https://hackmd.io/@FortesHuang/HJnWgQGJMx)——在 Google 搜尋「AI 導入工程」時名列前茅。更多文章請見 [hackmd.io/@FortesHuang](https://hackmd.io/@FortesHuang)。

## 學歷

**Tungnan University（東南科技大學）｜資訊管理系**  
2006
