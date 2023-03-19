# 球賽約戰與聊天交友平台 Ball-Meet

## 簡介
此平台讓愛好籃球的朋友可以在上面聊天交流，且可以發布球局，呼朋引伴一起流汗，享受運動帶來的樂趣。<br/>

平台網址連結 https://jasperlee.tw<br/>
這邊提供兩個測試帳號讓大家體驗本平台 <br/>

帳號| 密碼
--------------|:-----:
123@gmail.com | 12345678
456@gmail.com | 12345678

## 開發工具介紹
本平台利用前後端分離的方式開發，並部署於 Amazon AWS 中的 EC2。</br>

前端: Angular 15</br>
前端原始碼: [Ballgame_Frontend](https://github.com/jaylee840831/Ballgame_Frontend/tree/test)</br>

後端: Spring Boot + Java 17</br>
後端原始碼: [Ballgame_Backend](https://github.com/jaylee840831/Ballgame_Backend/tree/test)</br>

資料庫: PostgreSQL</br>

雲端: Amazon AWS</br>

## 功能介紹
1. 登入<br/>
可自行註冊或使用提供的測試帳號。<br/>
<img src="https://github.com/jaylee840831/Ball-Meet/blob/master/image/%E7%99%BB%E5%85%A5.jpg" />
<img src="https://github.com/jaylee840831/Ball-Meet/blob/master/image/%E8%A8%BB%E5%86%8A.jpg" />

2. 球局資訊查詢 <br/>
這裡可以查詢到所有已建立之球局，點擊聊天室，進入與球友們聊天交流，點擊星星符號可以儲存該球局。<br/>
<img src="https://github.com/jaylee840831/Ball-Meet/blob/master/image/%E7%90%83%E5%B1%80%E6%9F%A5%E8%A9%A2.jpg" />

3. 球局聊天室<br/>
在這裡與球友們聊天交流。<br/>
<img src="https://github.com/jaylee840831/Ball-Meet/blob/master/image/%E8%81%8A%E5%A4%A9%E5%AE%A4.jpg" />

4. 使用者個人資料<br/>
建立身高、體重、場上擔任的位置等個人資訊。<br/>
<img src="https://github.com/jaylee840831/Ball-Meet/blob/master/image/%E5%80%8B%E4%BA%BA%E8%B3%87%E6%96%99.jpg" />

5. 新增球局<br/>
這裡可建立新的球局，包含時間、地點等資訊。<br/>
<img src="https://github.com/jaylee840831/Ball-Meet/blob/master/image/%E6%96%B0%E5%A2%9E%E7%90%83%E5%B1%80.jpg" />

6. 儲存球局<br/>
已儲存的球局。<br/>
<img src="https://github.com/jaylee840831/Ball-Meet/blob/master/image/%E5%84%B2%E5%AD%98%E7%90%83%E5%B1%80.jpg" />

7. 影片分析(尚未開發)<br/>
希望能整合我論文的球賽分析技術，讓使用者可以在網路上自動剪輯球賽影片等等。<br/>

8. 我的球友(尚未開發)<br/>
儲存追蹤的球友名單。<br/>