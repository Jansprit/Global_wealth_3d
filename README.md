Global Wealth 3D 🌍💰

這是一個基於 WebGL 的 3D 互動地球視覺化單頁應用程式 (SPA)，用於直觀地展示全球各國的 人均 GDP (GDP per Capita) 數據。

透過深邃的宇宙星空背景、半透明的洋藍色海洋，以及發光的大氣層邊緣，讓生硬的經濟數據化身為充滿科技感與沈浸感的互動體驗。

✨ 核心特色 (Features)

3D 互動地球：支援滑鼠拖曳旋轉、滾輪縮放。

對數尺度著色 (Logarithmic Color Scale)：由於各國財富差距極大，採用對數比例尺（深藍 < 白 < 深紅）來進行區塊上色，讓貧富差距的漸層表現更加平滑精確。

智慧視角運鏡 (Smart Camera Offset)：點擊國家後，地球會自動關閉自轉，並以平滑的 3D 運鏡將該國聚焦於畫面的「左半部」，完美避開右側彈出的資訊面板。

即時動態圖例 (Dynamic Legend Marker)：底部圖例條配有科技感發光游標，點擊國家時，游標會即時滑動到該國 GDP 對應的數值刻度上。

國際化與維基百科整合：

內建 ISO_A3 轉繁體中文對照表，確保國家名稱友善易讀。

資訊面板自動載入高品質國旗 (via flagcdn.com)。

國家名稱內建超連結，點擊即可在新視窗開啟該國的「繁體中文維基百科」介紹。

視覺優化：保留真實衛星雲圖紋理，但使用 emissive (自發光) 屬性將海洋渲染為通透的洋藍色 (#0a305e)。

🛠️ 技術堆疊 (Tech Stack)

HTML / CSS / JavaScript (ES6)

Three.js (v0.136.0) - 底層 3D 渲染引擎。

Globe.gl (v2.32.1) - 基於 Three.js 封裝的高階地球視覺化開源庫。

D3.js (v7.8.5) - 處理地理運算 (d3-geo)、對數比例尺 (d3.scaleLog)、數值格式化與動畫插值。

資料來源：Natural Earth (ne_110m_admin_0_countries.geojson)。

🚀 如何執行 (How to Run)

本專案為純前端應用程式，無需任何後端伺服器或建置步驟 (Build process)。

將 index.html 下載到您的電腦中。

直接點擊兩下，使用任何現代瀏覽器 (Chrome, Firefox, Edge, Safari) 開啟 index.html 即可流暢執行。

(備註：若要在本地端測試修改，建議使用 VS Code 的 Live Server 擴充功能，以避免瀏覽器的 CORS 跨域讀取限制。)

Created with AI Assistance
