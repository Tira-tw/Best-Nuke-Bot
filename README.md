# Best-Nuke-Bot
看別人不爽想要把他的群組炸掉嗎? <br>
你需要一個仿真保護群組的Bot? <br>
使用這個吧~ <br>
<hr>

# 安裝
<br>
1.安裝Nodejs v16 <br>
2.安裝npm :
npm install

# 修改
<br>
您需要在config/config.json修改! <br>
<br>
{ <br>
    "token": "Bot-Token", #添加Token <br>
    "prefix": "-", <br> 
    "userID": "用戶ID",  #添加您的用戶ID <br>
    "disableEveryone": true <br>
} <br>

# 功能

ℹ️ 新增頻道 <br>

-add 數量 頻道名稱 示範 : 
```
-add 1 test
```
ℹ️ 保護頻道 [添加頻道+標註+訊息] [實際上的指令 : `-pr 標註數量 頻道名稱, 訊息`] <br>
-pr 數量 頻道名稱, 原因 示範 : 
```
-pr 5 gay, Google is Good
```
ℹ️ 添加身分組 <br>

-pc 身分組數量 名稱 示範 : 
```
-pc 5 test
```
ℹ️ 刪除特定頻道 [刪除全部頻道] [只需執行`-dc`]<br>
```
-dc #頻道名稱  
```
ℹ️ 刪除特定身分組 [刪除全部身分組] [只需執行`-dr`] <br>
```
-dr @身分組
```
ℹ️ 刪除特定表情符號 [刪除全部表情符號] [只需執行`-de`] <br>
```
-de id
```
ℹ️ 刪除特定貼圖 [刪除全部貼圖] [只需執行`-ds`] <br>
```
-ds 貼圖名稱
```
ℹ️ 踢出特定用戶 [踢出全部用戶] [只需執行`-kick`] <br>
```
-kick @用戶ID
```
ℹ️ 停權特定用戶 [踢出全部] [只需執行`-ban`] <br>
```
-ban @用戶ID
```
# 優點
> ✅仿真防禦Bot <br>
> ✅開發者無需身分組權限即可使用! <br>
> ✅每10個數量標註訊息 ✅100ping 11秒達成 <br>
> ✅每100個標註訊息    ✅100ping 7秒達成 <br>
> ✅快速刪除頻道 <br>
> ✅快速刪除身分組 <br>
<img src="https://cdn.discordapp.com/attachments/1009977660061007982/1009988723426992158/unknown.png" with="600" heigh="400" alt="一張圖片">
<br>

# 缺點

> ❌除了開發者以外其他用戶以及有權限的用戶無法使用! <br>
<img src="https://cdn.discordapp.com/attachments/1009977660061007982/1009988804481925230/unknown.png" with="600" heigh="400" alt="一張圖片">

# 啟動Bot

```
node src/index.js
```

# 注意事項

> 若用戶使用了源代碼 , 我們不負責後續的處理 , 也不參與! <br>

# 源代碼

> 源代碼並不是本人製作的! , 本人只提供中文! <br>
> 作者 : [17teen](https://github.com/17teen) <br>
> 源代碼 : [Discord-Presser-Server-Nuker](https://github.com/17teen/Discord-Presser-Server-Nuker) <br>
> 翻譯作者 : [Tira-tw](https://github.com/Tira-tw)

