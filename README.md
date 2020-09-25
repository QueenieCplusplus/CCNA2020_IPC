# CCNA2020_IPC

A: Inter-Processes Communication in the Same Host

* 1. Pipeline = Channel, 管線（半雙工單向通訊，亦有全雙工）

  僅能在父子進程關係之間作用，且 Buffer 緩衝區大小受限制。
  
  特例：有名管道能允許非親緣關係的進程之間進行通訊。
  
  https://github.com/QueenieCplusplus/DataStructure_Queue/blob/master/pipeline.md (Before 2020)

* 2. Semophore（同步通訊）

  訊號量此通訊方式使用計時器的概念。

  傳遞訊號少，有限制量。
  
  有上鎖機制。（能管理不同進程或是同一進程不同線程同時訪問同一資源時造成的進奪。）
  
* 3. Signal + Shared Memory , 訊號（Notify機制）與共享內存

  複製內存，由進程創建內存此共享內存，讓進程間相互共用此內存，藉由信號通知，防止資源上鎖。
  
  傳遞量少，有限制量。
 
* 4. Message Queue, 訊息佇列 (非同步通訊，尚有發布與訂閱的通訊方式)

  無 訊號與管線的缺點。
  
  https://github.com/QueenieCplusplus/DataStructure_Queue (Before 2020)
  
  https://github.com/QueenieCplusplus/DataStructure_Queue#qmq-zero-mq (Java)
  
  https://github.com/QueenieCplusplus/DataStructure_Queue/blob/master/PubSub.js (發布與訂閱)
  
---------------------------------------------------------------------------------------------

B: Inter-Processes Communication in Different Hosts

* Socket Stream, 通訊端串流 (全雙工雙向通訊)

  常發生於不同機器間的進程通訊。
  
  https://github.com/QueenieCplusplus/DataStructure_Queue/blob/master/server_in_python.py (Python)
  
  https://github.com/QueenieCplusplus/DataStructure_Queue/blob/master/server_in_NodeJs.js (Nodejs)
  
  https://github.com/QueenieCplusplus/DataStructure_Queue/blob/master/server_in_php.php (PHP)
  
  https://github.com/QueenieCplusplus/DataStructure_Queue/blob/master/server_in_C%2B%2B.cpp (C++)
  





