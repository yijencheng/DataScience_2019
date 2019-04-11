# CSXDataScience
---
### Introduce myself  

嗨，我是鄭禕仁(Ivan Cheng)，今年大三電機系的學生。  
　，我是郭庭瑞(Spark Kuo)，今年大二哲學系的學生。
_______________________
### Week1
**本組作業用資料**  
　　南山人壽保險理賠紀錄  

**本週程式碼**  
　　放置於 hw1 資料夾內  
　　使用 jupyter notebook 以便存取  

**本週進度**
* **資料整理、轉型態**  
  將資料從 csv 檔內的 column 轉換成兩種型態  
  * 一是最基礎的 list 類別  
  * 二是透過 pandas 套件將 csv 檔內容快速轉換成類似 dict 的存取方式


* **資料識別**  
  1. 針對部份欄位，透過簡單的字串處理檢查是否含有極端值或異常
  2. 思考欄位間的關係以及製表後可能會帶來的潛在資訊
  3. 若有需要，對欄位進行排序  
     多欄排序則需要用到 sorted 整理優先次序


* **製作圖表**  
  將上述資料識別中可能的欄位組合製作成二維圖表  
  若有問題則檢查欄位中數值是否有異常，抑或是程式上的錯誤  

  本週主要製作柱狀圖與圓餅圖  
  1. **客戶年資 - 人數**  
  顯示出該公司在近15~25年前加入並有理賠紀錄的客戶數較多
  ![1](/hw1/1.png)  
  2. **客戶年資 - 人均購買保單金額**   
  購買保單金額，隨客戶年資增長而提高
  ![2](/hw1/2.png)  
  3. **客戶年資 - 五年內人均理賠金額**  
  年資越高，五年內平均理賠金額越高  
  並且年資15年以上，理賠金額佔百分之七十
  ![3](/hw1/3.png)  


* **學習透過圖表觀察**  
  藉由以上做出的圖表觀察數值呈現如此的可能原因  
  嘗試找出可能特徵值  
  並且試圖藉此發現新的欄位關係


* **下週可能目標**  
  整理疾病 ID  
  尋找可能的疾病分類  
  並透過疾病類別查找與其他欄位的關係  
  試圖找出「什麼樣的人比較會買什麼類別的險」   
  向此方向靠近
