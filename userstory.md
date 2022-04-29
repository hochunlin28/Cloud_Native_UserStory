User Story:

    疫情日漸嚴重，身為一個使用者，需要Uber提供「防疫uber」的選擇，讓使用者能夠安全不接觸人群前往醫院檢測

Acceptance Criteria 1:

    Given 隔離使用者一個 app 能夠叫車
  
    When 隔離使用者打開 app 介面
  
    Then 系統會提供一個防疫專車給使用者選擇

    Given 隔離使用者勾選「自行叫車」
  
    When 隔離使用者選擇防疫專車
  
    Then app 提供使用者填入目前地址，或是用google地圖導入
  
    When 隔離使用者填完資料完成
  
    Then app 輸出預計抵達時間、預計前往醫院，並且通知醫院準備

Acceptance Criteria 2:

    Given 衛生局人員使用 app 能夠幫隔離者叫車

    When 衛生局人員打開 app 介面

    Then 系統會提供一個防疫專車給使用者選擇

    Given 衛生局人員勾選「替人叫車」
    
    When 衛生局人員選擇防疫專車

    Then app 提供衛生局人員填寫乘坐人電話、地址

    When 衛生局人員填寫資料完成

    Then app 利用手機簡訊通知乘坐人預計抵達時間、預計前往醫院，並且通知醫院準備
    


