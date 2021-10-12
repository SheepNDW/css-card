# css-card

![image](https://raw.githubusercontent.com/SheepNDW/css-card/main/assets/cssCard.gif) <br>
用純 CSS 在網頁上寫一張動態卡片<br>
參考吳哲宇老師的《動畫互動網頁特效入門（JS/CANVAS）》課程中的 Project2 案例改編而來 <br>
瀏覽位置：https://sheepndw.github.io/css-card/

## Project 中使用的方法

1. 使用@keyframes 配合 transition 形成動畫互動
2. 利用:checked 來處理晝夜交替效果
3. 使用 css 預處理器 sass/scss 來編寫

   (1).使用@mixin 來達成複用功能，減少重複編寫  
   (2).使用自訂的顏色變數($colorXXX)統一管理顏色 <br>
   (3).使用 sass 迴圈 來完成星星及雲朵的呈現位置
