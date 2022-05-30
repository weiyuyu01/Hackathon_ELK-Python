# Hackathon_ELK-Python

數據驅動與集先鋒科技共同主辦的黑客松競賽
Accupass競賽資訊 : https://www.accupass.com/event/2204061448029829370060  

題目
1. 將所提供的2天份Apache log檔,依照以下四點指示進行計算(必須用PYTHON!!)後各自產生一份CSV檔  
計算每小時 404-500 數量  
統計 觸發 404-500 的 IP (天)  
同 IP 觸發 404-500 今天與昨天的差異比例 ((今天值-昨天值)/昨天值)  
同 IP 觸發 404-500 今天與昨天的差異比例 與 200-299 今天與昨天的差異比例 (404-500 差異比例) / (200-299差異比例)  

2. 通過logstash將4個csv寫入Elasticsearch  
時間欄位轉換  
數字欄位轉換  

成果文章 : https://blog.bimap.com.tw/2022/04/11/bimap-elk-%E9%BB%91%E5%AE%A2%E6%9D%BE
