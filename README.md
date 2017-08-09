# guide_blog
購物達人
https://cosjava26.github.io/guide_blog/index.html

## 改版過程：
<p align="center">
  <img src="http://i.imgur.com/KajoSVQ.png">
</p>  

### Step1.接收需求，發現問題：

與文章編輯者進行訪談，了解痛點與需求，以下列點說明：
  1. 希望首頁能有最新文章的區域。

  2. 在**文章內文**的部分：
    - 會使用"重點引言"，希望讓使用者看文章時，能直接看到重點。
    - 希望內文可以再集中一點。
    - 在文末區，希望能加入作者簡介，同時提供這個文章作者所寫的所有文章頁面，讓使用者持續追蹤作者的新文章。
    - 在文末區，好像沒有社群分享的按鈕。
    - 在文末區，會提供給使用者相關文章連結。

  3. 在 **wordpress** 編輯文章的部分：
    - 希望能提供文章段落主標.次標的樣式設定，文章看起來才比較井然有序。
    - 不知道要怎麼在 wordpress 加入表格的樣式，從 word 貼過來的表格，在手機上面看起來很奇怪。
    - 設定了文章分類，在前臺顯示不出來。
<br />

### Step2.解決方案：

PM整理以上需求，並討論相關解決方案，以下列點說明：
  1. 首頁版型改版，參考T客邦 https://www.techbang.com/ 等文章類的網站
  2. 文章內文格式，參考女人迷 https://womany.net/ 等文章類的網站。
  3. 與工程師＆設計師討論，制定明確的文章內文**wordpress撰寫方針**，提供給文章編輯者。
  4. 優化手機版文章瀏覽的體驗。
<br />

### Step3.解決問題：
  1.首頁：
  
  https://cosjava26.github.io/guide_blog/index.html
  - 大區塊文章露出
  - 文章排列樣式改成**左右兩則**，顯示首圖、標題文字在圖下方、文章描述、作者、發表時間、該篇文章fb分享數(social plugin)，以上全都可點擊進文章，點擊作者進入作者介紹頁!

![首頁](http://i.imgur.com/e7Sysuf.png)

  2.文章內頁：
  
  https://cosjava26.github.io/guide_blog/news_content.html
  
  - 制定文章段落標題樣式：可清楚看到文章有幾段
  - 段落裡的次標題樣式：小重點條列icon
  - 文章內容的樣式：字級、字距、行距、顏色、重點引言、表格樣式呈現、youtube RWD、相關文章連結區塊、文末作者簡介
  <br />
  
  ![文章內頁](http://i.imgur.com/Vh8YlwO.png)
  
  3.作者單頁：
  
  https://cosjava26.github.io/guide_blog/author_list.html
  
  - 與文章內頁相同作者簡介區塊。
  - 下方為該作者，所發表的文章列表，依瀏覽次數排序顯示。
  - 文章左右兩篇，顯示需求：文章縮圖、標題、文章描述、編輯名字、發佈時間以及該篇文章FB的分享數。

  <br />
  
  ![作者單頁](http://i.imgur.com/yducCZH.jpg)
