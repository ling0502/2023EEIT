# 2023 EEIT project


## 🎯 Frontend web project 前端網頁專案(靜態)

是一款飲料訂購網頁，實現RWD技術，消費者在小設備中也能有非常好的體驗。

* **以Html5、CSS為基礎，搭配Boostrape設計出網頁畫面。**
* **加入JavaScript、JQuery增加與使用者互動。**
* **利用localstorage實現購物車存取功能。**

#

## 🎯 Backend web project 全端網頁專案(JAVA - SpringBoot)

一個客製化餐廳系統，可以提供消費者點餐及店家設置餐點、活動、查看訂單、數據分析等功能，以JAVA為基礎搭配mySQL存取相關資訊。

負責功能
#### :shopping_cart: 消費者端
* RWD官網設計，以Html5、CSS為基礎，搭配Boostrape框架。
* JavaScript、JQuery控制與使用者互動行為。
* 搭配AJAX技術，向後端發送資料請求。
* 以ngrok架設本地伺服器，使用Node.js與MySQL連接，搭配Dialogflow處理自然語言，在網站上提供智慧客服機器人及連動lineBot。

#### :computer: 店家後臺
* 以Html5、CSS為基礎，搭配Boostrape框架設計操作頁面，及側邊導覽列。
* 以JAVA為基礎，使用Spring MVC、Spring Boot框架。
* 使用Tomcat作為伺服器連接，搭配MySQL資料庫存取相關資訊。
* 透過Spring Security驗證發送請求是否為經授權的管理者，否則拒絕訪問後台系統。
* 管理者在後台可新增【輪播圖】，同步顯示在官網首頁。
* 管理者在後台可新增【活動】，讓消費者在下訂單時，自動帶入最優惠的活動折扣。
* 管理者在後台可操作【訂單結帳】，輸入收款的金額，回寫結單時間及訂單狀態至資料庫。

