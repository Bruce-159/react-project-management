#React Project Management App  
[🔗 GitHub 部署頁面](https://bruce-159.github.io/react-project-management/)  
  
這是一個使用 React 製作的簡易專案與任務管理應用，透過本專案強化我在 Tailwind CSS、元件拆分、狀態管理、使用 Refs 以及 prop drilling 等 React 實作能力。  

狀態管理與 Component Switching
使用 useState() 控制不同畫面（No Project / New Project / Selected Project）的顯示

將畫面切換邏輯集中在 App.jsx，提高組件邏輯

Refs & Forwarded Refs
表單輸入欄位透過 useRef() 讀取資料，避免每次輸入都觸發重渲染
使用 forwardRef 傳遞 DOM 參考至自定義 Input 元件

useImperativeHandle
在錯誤提示 Modal 中使用 useImperativeHandle 暴露 .open() 方法讓父層控制開啟行為，實現主動式 API 控制

Component Composition & Reusability
將 Input、Button、Card、Modal、Sidebar 等元件模組化，並封裝樣式與邏輯
保持元件通用性與可配置性（透過 children 與 props）

Prop Drilling
從最上層 App 將資料與操作函式層層傳遞至深層元件，例如 ProjectTasks 中任務的增刪行為

Tailwind CSS
所有 UI 樣式皆透過 Tailwind CSS 撰寫
包含hover、focus、media queries、nested utility 等技巧  

  ##預覽畫面  
  ![image](https://github.com/user-attachments/assets/2f1ef538-8bce-43c6-bfcf-09195c872fcd)
  ![image](https://github.com/user-attachments/assets/41921c46-e51d-4f05-a006-c6bcaff6febb)

