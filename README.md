<p align="center"><font size="6"><b>軟體工程 11224117 蕭冠廷 11224215 顏玉棠</b></font></p>

<p align="center">對於零基礎的人，如何利用 ChatGPT 開發出自己的 APP？</p>

有沒有想過自己製作一款手機遊戲，並生成 APK 手機應用呢？有了人工智慧，這一切都成為可能。今天，我們就要使用 ChatGPT 來建立一個簡單的井字棋遊戲（Tic-Tac-Toe），其實這個過程非常輕鬆又高效。透過 ChatGPT 自動生成網頁程式碼，並實現一些基本功能，例如更換背景顏色、顯示誰是贏家、加入重新開始按鈕等。接下來就要和大家分享詳細步驟，教你如何在幾分鐘內打造一個屬於自己的井字棋手機應用。

一、利用 ChatGPT 生成井字棋程式碼

1.確定需求

我們的目標是建立一個井字棋遊戲，並為它加入一些額外的功能，例如背景顏色漸層、勝利彈窗以及重新開始按鈕。


2.編寫提示詞

在使用 ChatGPT 時，我們可以輸入明確的提示來生成程式碼。比如：

<img width="1601" height="867" alt="題目" src="https://github.com/user-attachments/assets/45b2dd20-e403-495d-8d66-afde323c75f1" />




ChatGPT 會基於這個提示生成完整的 HTML、CSS 和 JavaScript 程式碼。這裡的 index.html 頁面是程式的前端，以網頁形式呈現；style.css 則規定網頁上各個元件的排列與樣式；JavaScript 則負責遊戲的內部邏輯，包括變色、彈窗等功能。


3.複製程式碼

一旦 ChatGPT 回傳了生成的程式碼，我們可以直接複製這些程式碼，準備貼到開發工具 CodeOpen 裡進行調試。

二、測試井字棋程式碼

1.調試程式碼

打開一個程式碼編輯工具，例如 CodeOpen，將剛剛從 ChatGPT 獲得的程式碼依照 HTML、CSS 和 JavaScript 的順序，分別貼到三個不同的框裡。接著點擊「執行」按鈕，或拖動下方頁面，看看你的井字棋遊戲是否能正常顯示與運作。



<img width="1602" height="925" alt="1" src="https://github.com/user-attachments/assets/de260648-649d-48fe-b2a4-1107c29a412a" />
<img width="1602" height="943" alt="2" src="https://github.com/user-attachments/assets/54dd8cba-6abf-4def-8986-4fbe508114d6" />
<img width="1593" height="826" alt="3" src="https://github.com/user-attachments/assets/887ca1cc-0be6-4681-877f-2c0442be4c3e" />
<img width="1590" height="936" alt="4" src="https://github.com/user-attachments/assets/e7a0ab10-ff0c-45a1-bbf3-d190dd04d206" />
<img width="1585" height="942" alt="5" src="https://github.com/user-attachments/assets/1640b4b1-ccd6-4e7b-acef-43a1e5836945" />
<img width="1588" height="847" alt="6" src="https://github.com/user-attachments/assets/84666813-5b82-4688-88e0-fbce4b7ee077" />
<img width="1917" height="943" alt="7" src="https://github.com/user-attachments/assets/11e0153f-4952-43da-b84f-9d7185ad9e63" />



2.功能新增

在執行程式碼後，若想進一步改進遊戲介面或新增功能，例如加入網頁的漸層背景顏色、在遊戲結束時顯示彈窗提示、標示出勝利者等，都可以回到 ChatGPT 的提示視窗中，繼續追加提示詞，要求它加入更多功能。

透過重新生成程式碼並替換舊程式碼，再次複製到 CodeOpen 中進行調試，就能讓新功能生效。若出現錯誤，則可以將錯誤訊息提供給 ChatGPT，它會自動進行除錯（debug），並重新生成修正版程式碼。


<img width="1912" height="970" alt="8" src="https://github.com/user-attachments/assets/33ceb890-b077-4ba7-8949-f6d94d671ed6" />



三、保存井字棋程式碼檔案

1.保存 HTML 檔案
如果調試程式碼後沒有問題，就可以保存 HTML 程式碼。我們打開一個文字編輯器（例如 Notepad），將生成的 HTML 程式碼貼上，然後將檔案的副檔名從 .txt 改為 index.html。這樣操作的目的是當訪問網站域名時，系統會自動讀取這個名為 index 的檔案，並展示程式介面。保存時要注意：格式必須正確（HTML 副檔名），且檔案編碼使用 UTF-8，以防止網頁出現亂碼。

2.保存 CSS 和 JavaScript 檔案
同樣地，你需要分別保存 CSS 和 JavaScript 程式碼，檔名分別為 style.css 和 scripts.js。注意，這三個檔案必須放在同一個目錄下，這樣不僅方便調用樣式與 JavaScript 程式碼，也能確保井字棋遊戲的外觀樣式和內部邏輯正常運作。

四、在vscode上測試


1.將檔案丟入vscode



<img width="1920" height="1080" alt="9" src="https://github.com/user-attachments/assets/06bd939e-e9d8-46f5-bb41-056c29b59036" />
<img width="827" height="947" alt="10" src="https://github.com/user-attachments/assets/64f01579-1205-4783-a641-fc9d91be8670" />
<img width="491" height="456" alt="11" src="https://github.com/user-attachments/assets/10dcd985-5ece-472a-b540-f54dbff4a874" />
<img width="855" height="967" alt="12" src="https://github.com/user-attachments/assets/775767ff-c2a8-4246-b54b-edc8cbbb568b" />
<img width="908" height="515" alt="13" src="https://github.com/user-attachments/assets/f5aaff47-172d-4aac-8cf1-a7d36e1c795d" />



2.使用livesever進行模擬


<img width="1908" height="1040" alt="14" src="https://github.com/user-attachments/assets/631520cf-f0c1-4c5d-9be4-96f6c1643864" />
<img width="1906" height="1004" alt="15" src="https://github.com/user-attachments/assets/24c3ef42-bf30-4f85-a62c-19117f899790" />
<img width="1919" height="1041" alt="16" src="https://github.com/user-attachments/assets/790e5573-ea95-45c3-9581-28cb4dc74810" />
<img width="1917" height="1045" alt="17" src="https://github.com/user-attachments/assets/bb7b3cf3-12c1-4e08-8048-e6ddc3e41662" />


五、結語


透過 ChatGPT 生成程式碼，你可以在短短幾分鐘內建立出一個簡單的井字棋網站，並將網站轉換成手機應用程式，完全不用花一毛錢就能實現全新的手機應用開發。有了 ChatGPT 等人工智慧的輔助，從程式碼生成到實際運行的每一步都變得異常簡單。無論你是程式設計新手還是有經驗的開發者，都能輕鬆上手。

現在，就動手利用 ChatGPT 製作屬於自己的小遊戲吧！如果不知道該做什麼遊戲，不妨直接問問 ChatGPT。
