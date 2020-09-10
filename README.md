# CCNA2020_IPC
Inter-Processes Communication in Same Host

* Pipeline, 管線（半雙工單向通訊）

  僅能在父子進程關係之間作用，且緩衝區大小受限制。
  
  特例：有名管道能允許非親緣關係的進程之間進行通訊。

* Semephore & Shared Memory, 信號與共用存儲（同步通訊）

  傳遞訊號少，有限制量。
  
  有上鎖機制。（能管理不同進程或是同一進程不同線程同時訪問同一資源時造成的進奪。）
  
* Message Queue, 訊息佇列

* Socket, 通訊端

* Signal, 訊號（Notify機制）
