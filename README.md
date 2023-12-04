# AI-Voice-accounting
AI語音記帳(AI模型容量過大 故無法上傳)
摘要:
身在大消費時代，每日都有許多消費行為，大家都知道記帳可以掌握個人財務支出，但要如何在現今忙碌生活中持之以恆紀錄便是一大考驗，因此我們的目標是建立一個語音記帳系統，來達到以下目的。

1.簡化記帳流程：可直覺地語音輸入內容，提高記帳效率以及使用者黏著度。

2.提升內容準確率：語音辨識並自動分類，減少手動輸入錯誤的機會。

3.提供財務洞察：供使用者分析其相關數據，檢視個人消費狀況。

本專題使用 Bert 模型進行微調，對記帳資料進行分類共7類，分為：食、衣、住、行、育、樂、其他。利用Web Speech API 接收使用者語音輸入，系統將口語內容轉為文字。使用 llama2 中文模型提取項目及金額，將其儲存至資料庫中。最後應用 Flask 建構後端網站提供使用者可從前端介面檢視支出狀況。
