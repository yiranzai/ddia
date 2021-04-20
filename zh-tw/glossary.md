<!--ts-->
   * [術語表 【DRAFT】](./zh-tw/glossary.md#術語表-draft)
         * [非同步（asynchronous）](./zh-tw/glossary.md#非同步asynchronous)
         * [原子（atomic）](./zh-tw/glossary.md#原子atomic)
         * [背壓（backpressure）](./zh-tw/glossary.md#背壓backpressure)
         * [批處理（batch process）](./zh-tw/glossary.md#批處理batch-process)
         * [邊界（bounded）](./zh-tw/glossary.md#邊界bounded)
         * [拜占庭故障（Byzantine fault）](./zh-tw/glossary.md#拜占庭故障byzantine-fault)
         * [快取（cache）](./zh-tw/glossary.md#快取cache)
         * [CAP定理（CAP theorem）](./zh-tw/glossary.md#cap定理cap-theorem)
         * [因果關係（causality）](./zh-tw/glossary.md#因果關係causality)
         * [共識（consensus）](./zh-tw/glossary.md#共識consensus)
         * [資料倉庫（data warehouse）](./zh-tw/glossary.md#資料倉庫data-warehouse)
         * [宣告式（declarative）](./zh-tw/glossary.md#宣告式declarative)
         * [非規範化（denormalize）](./zh-tw/glossary.md#非規範化denormalize)
         * [衍生資料（derived data）](./zh-tw/glossary.md#衍生資料derived-data)
         * [確定性（deterministic）](./zh-tw/glossary.md#確定性deterministic)
         * [分散式（distributed）](./zh-tw/glossary.md#分散式distributed)
         * [持久（durable）](./zh-tw/glossary.md#持久durable)
         * [ETL（Extract-Transform-Load）](./zh-tw/glossary.md#etlextract-transform-load)
         * [故障切換（failover）](./zh-tw/glossary.md#故障切換failover)
         * [容錯（fault-tolerant）](./zh-tw/glossary.md#容錯fault-tolerant)
         * [流量控制（flow control）](./zh-tw/glossary.md#流量控制flow-control)
         * [追隨者（follower）](./zh-tw/glossary.md#追隨者follower)
         * [全文檢索（full-text search）](./zh-tw/glossary.md#全文檢索full-text-search)
         * [圖（graph）](./zh-tw/glossary.md#圖graph)
         * [雜湊（hash）](./zh-tw/glossary.md#雜湊hash)
         * [冪等（idempotent）](./zh-tw/glossary.md#冪等idempotent)
         * [索引（index）](./zh-tw/glossary.md#索引index)
         * [隔離性（isolation）](./zh-tw/glossary.md#隔離性isolation)
         * [連線（join）](./zh-tw/glossary.md#連線join)
         * [領導者（leader）](./zh-tw/glossary.md#領導者leader)
         * [線性化（linearizable）](./zh-tw/glossary.md#線性化linearizable)
         * [區域性性（locality）](./zh-tw/glossary.md#區域性性locality)
         * [鎖（lock）](./zh-tw/glossary.md#鎖lock)
         * [日誌（log）](./zh-tw/glossary.md#日誌log)
         * [物化（materialize）](./zh-tw/glossary.md#物化materialize)
         * [節點（node）](./zh-tw/glossary.md#節點node)
         * [規範化（normalized）](./zh-tw/glossary.md#規範化normalized)
         * [OLAP（Online Analytic Processing）](./zh-tw/glossary.md#olaponline-analytic-processing)
         * [OLTP（Online Transaction Processing）](./zh-tw/glossary.md#oltponline-transaction-processing)
         * [分割槽（partitioning）](./zh-tw/glossary.md#分割槽partitioning)
         * [百分位點（percentile）](./zh-tw/glossary.md#百分位點percentile)
         * [主鍵（primary key）](./zh-tw/glossary.md#主鍵primary-key)
         * [法定人數（quorum）](./zh-tw/glossary.md#法定人數quorum)
         * [再平衡（rebalance）](./zh-tw/glossary.md#再平衡rebalance)
         * [複製（replication）](./zh-tw/glossary.md#複製replication)
         * [模式（schema）](./zh-tw/glossary.md#模式schema)
         * [次級索引（secondary index）](./zh-tw/glossary.md#次級索引secondary-index)
         * [可序列化（serializable）](./zh-tw/glossary.md#可序列化serializable)
         * [無共享（shared-nothing）](./zh-tw/glossary.md#無共享shared-nothing)
         * [偏斜（skew）](./zh-tw/glossary.md#偏斜skew)
         * [腦裂（split brain）](./zh-tw/glossary.md#腦裂split-brain)
         * [儲存過程（stored procedure）](./zh-tw/glossary.md#儲存過程stored-procedure)
         * [流處理（stream process）](./zh-tw/glossary.md#流處理stream-process)
         * [同步（synchronous）](./zh-tw/glossary.md#同步synchronous)
         * [記錄系統（system of record）](./zh-tw/glossary.md#記錄系統system-of-record)
         * [超時（timeout）](./zh-tw/glossary.md#超時timeout)
         * [全序（total order）](./zh-tw/glossary.md#全序total-order)
         * [事務（transaction）](./zh-tw/glossary.md#事務transaction)
         * [兩階段提交（2PC, two-phase commit）](./zh-tw/glossary.md#兩階段提交2pc-two-phase-commit)
         * [兩階段鎖定（2PL, two-phase locking）](./zh-tw/glossary.md#兩階段鎖定2pl-two-phase-locking)
         * [無邊界（unbounded）](./zh-tw/glossary.md#無邊界unbounded)

<!-- Added by: runner, at: Tue Apr 20 03:41:49 UTC 2021 -->

<!--te-->
# 術語表 【DRAFT】

> 請注意，本術語表中的定義簡短而簡單，旨在傳達核心思想，而不是術語的完整細微之處。 有關更多詳細資訊，請參閱正文中的參考資料。



[TOC]



### 非同步（asynchronous）

不等待某些事情完成（例如，將資料傳送到網路中的另一個節點），並且不會假設要花多長時間。請參閱第153頁上的“同步與非同步複製”，第284頁上的“同步與非同步網路”，以及第306頁上的“系統模型與現實”。



### 原子（atomic）

1.在併發操作的上下文中：描述一個在單個時間點看起來生效的操作，所以另一個併發程序永遠不會遇到處於“半完成”狀態的操作。另見隔離。

2.在事務的上下文中：將一些寫入操作分為一組，這組寫入要麼全部提交成功，要麼遇到錯誤時全部回滾。參見第223頁的“原子性”和第354頁的“原子提交和兩階段提交（2PC）”。



### 背壓（backpressure）

接收方接收資料速度較慢時，強制降低傳送方的資料傳送速度。也稱為流量控制。請參閱第441頁上的“訊息系統”。



### 批處理（batch process）

一種計算，它將一些固定的（通常是大的）資料集作為輸入，並將其他一些資料作為輸出，而不修改輸入。見第十章。



### 邊界（bounded）

有一些已知的上限或大小。例如，網路延遲情況（請參閱“超時和未定義的延遲”在本頁281）和資料集（請參閱第11章的介紹）。



### 拜占庭故障（Byzantine fault）

表現異常的節點，這種異常可能以任意方式出現，例如向其他節點發送矛盾或惡意訊息。請參閱第304頁上的“拜占庭故障”。



### 快取（cache）

一種元件，透過儲存最近使用過的資料，加快未來對相同資料的讀取速度。快取中通常存放部分資料：因此，如果快取中缺少某些資料，則必須從某些底層較慢的資料儲存系統中，獲取完整的資料副本。



### CAP定理（CAP theorem）

一個被廣泛誤解的理論結果，在實踐中是沒有用的。參見第336頁的“CAP定理”。



### 因果關係（causality）

事件之間的依賴關係，當一件事發生在另一件事情之前。例如，後面的事件是對早期事件的迴應，或者依賴於更早的事件，或者應該根據先前的事件來理解。請參閱第186頁上的“發生之前的關係和併發性”和第339頁上的“排序和因果關係”。



### 共識（consensus）

分散式計算的一個基本問題，就是讓幾個節點同意某些事情（例如，哪個節點應該是資料庫叢集的領導者）。問題比乍看起來要困難得多。請參閱第364頁上的“容錯共識”。



### 資料倉庫（data warehouse）

一個數據庫，其中來自幾個不同的OLTP系統的資料已經被合併和準備用於分析目的。請參閱第91頁上的“資料倉庫”。



### 宣告式（declarative）

描述某些東西應有的屬性，但不知道如何實現它的確切步驟。在查詢的上下文中，查詢最佳化器採用宣告性查詢並決定如何最好地執行它。請參閱第42頁上的“資料的查詢語言”。



### 非規範化（denormalize）

為了加速讀取，在標準資料集中引入一些冗餘或重複資料，通常採用快取或索引的形式。非規範化的值是一種預先計算的查詢結果，像物化檢視。請參見“單物件和多物件操作”（第228頁）和“從同一事件日誌中派生多個檢視”（第461頁）。



### 衍生資料（derived data）

一種資料集，根據其他資料透過可重複執行的流程建立。必要時，你可以執行該流程再次建立衍生資料。衍生資料通常用於提高特定資料的讀取速度。常見的衍生資料有索引、快取和物化檢視。參見第三部分的介紹。



### 確定性（deterministic）

描述一個函式，如果給它相同的輸入，則總是產生相同的輸出。這意味著它不能依賴於隨機數字、時間、網路通訊或其他不可預測的事情。



### 分散式（distributed）

在由網路連線的多個節點上執行。對於部分節點故障，具有容錯性：系統的一部分發生故障時，其他部分仍可以正常工作，通常情況下，軟體無需瞭解故障相關的確切情況。請參閱第274頁上的“故障和部分故障”。



### 持久（durable）

以某種方式儲存資料，即使發生各種故障，也不會丟失資料。請參閱第226頁上的“永續性”。



### ETL（Extract-Transform-Load）

提取-轉換-載入（Extract-Transform-Load）。從源資料庫中提取資料，將其轉換為更適合分析查詢的形式，並將其載入到資料倉庫或批處理系統中的過程。請參閱第91頁上的“資料倉庫”。



### 故障切換（failover）

在具有單一領導者的系統中，故障切換是將領導角色從一個節點轉移到另一個節點的過程。請參閱第156頁的“處理節點故障”。



### 容錯（fault-tolerant）

如果出現問題（例如，機器崩潰或網路連線失敗），可以自動恢復。請參閱第6頁上的“可靠性”。



### 流量控制（flow control）

見背壓（backpressure）。



### 追隨者（follower）

一種資料副本，僅處理領導者發出的資料變更，不直接接受來自客戶端的任何寫入。也稱為輔助、僕從、只讀副本或熱備份。請參閱第152頁上的“領導和追隨者”。



### 全文檢索（full-text search）

透過任意關鍵字來搜尋文字，通常具有附加特徵，例如匹配類似的拼寫詞或同義詞。全文索引是一種支援這種查詢的次級索引。請參閱第88頁上的“全文搜尋和模糊索引”。



### 圖（graph）

一種資料結構，由頂點（可以指向的東西，也稱為節點或實體）和邊（從一個頂點到另一個頂點的連線，也稱為關係或弧）組成。請參閱第49頁上的“和圖相似的資料模型”。 



### 雜湊（hash）

將輸入轉換為看起來像隨機數值的函式。相同的輸入會轉換為相同的數值，不同的輸入一般會轉換為不同的數值，也可能轉換為相同數值（也被稱為衝突）。請參閱第203頁的“根據鍵的雜湊值分隔”。



### 冪等（idempotent）

用於描述一種操作可以安全地重試執行，即執行多次的效果和執行一次的效果相同。請參閱第478頁的“冪等”。



### 索引（index）

一種資料結構。透過索引，你可以根據特定欄位的值，在所有資料記錄中進行高效檢索。請參閱第70頁的“讓資料庫更強大的資料結構”。



### 隔離性（isolation）

在事務上下文中，用於描述併發執行事務的互相干擾程度。序列執行具有最強的隔離性，不過其它程度的隔離也通常被使用。請參閱第225頁的“隔離”。



### 連線（join）

彙集有共同點的記錄。在一個記錄與另一個記錄有關（外來鍵，文件參考，圖中的邊）的情況下最常用，查詢需要獲取參考所指向的記錄。請參閱第33頁上的“多對一和多對多關係”和第393頁上的“減少端連線和分組”。



### 領導者（leader）

當資料或服務被複制到多個節點時，由領導者分發已授權變更的資料副本。領導者可以透過某些協議選舉產生，也可以由管理者手動選擇。也被稱為主人。請參閱第152頁的“領導者和追隨者”。



### 線性化（linearizable）

表現為系統中只有一份透過原子操作更新的資料副本。請參閱第324頁的“線性化”。



### 區域性性（locality）

一種效能最佳化方式，如果經常在相同的時間請求一些離散資料，把這些資料放到一個位置。請參閱第41頁的“請求資料的區域性性”。



### 鎖（lock）

一種保證只有一個執行緒、節點或事務可以訪問的機制，如果其它執行緒、節點或事務想訪問相同元素，則必須等待鎖被釋放。請參閱第257頁的“兩段鎖（2PL）”和301頁的“領導者和鎖”。



### 日誌（log）

日誌是一個只能以追加方式寫入的檔案，用於存放資料。預寫式日誌用於在儲存引擎崩潰時恢復資料（請參閱第82頁的“使二叉樹更穩定”）；結構化日誌儲存引擎使用日誌作為它的主要儲存格式（請參閱第76頁的“有序字串表和日誌結構的合併樹”）；複製型日誌用於把寫入從領導者複製到追隨者（請參閱第152頁的“領導者和追隨者”）；事件性日誌可以表現為資料流（請參閱第446頁的“分段日誌”）。



### 物化（materialize）

急切地計算並寫出結果，而不是在請求時計算。請參閱第101頁的“聚合：資料立方和物化檢視”和419頁的“中間狀態的物化”。



### 節點（node）

計算機上執行的一些軟體的例項，透過網路與其他節點通訊以完成某項任務。



### 規範化（normalized）

以沒有冗餘或重複的方式進行結構化。 在規範化資料庫中，當某些資料發生變化時，您只需要在一個地方進行更改，而不是在許多不同的地方複製很多次。 請參閱第33頁上的“多對一和多對多關係”。



### OLAP（Online Analytic Processing）

線上分析處理。 透過對大量記錄進行聚合（例如，計數，總和，平均）來表徵的訪問模式。 請參閱第90頁上的“交易處理或分析？”。



### OLTP（Online Transaction Processing）

線上事務處理。 訪問模式的特點是快速查詢，讀取或寫入少量記錄，這些記錄通常透過鍵索引。 請參閱第90頁上的“交易處理或分析？”。



### 分割槽（partitioning）

將單機上的大型資料集或計算結果拆分為較小部分，並將其分佈到多臺機器上。 也稱為分片。 見第6章。



### 百分位點（percentile）

透過計算有多少值高於或低於某個閾值來衡量值分佈的方法。 例如，某個時間段的第95個百分位響應時間是時間t，則該時間段中，95％的請求完成時間小於t，5％的請求完成時間要比t長。 請參閱第13頁上的“描述效能”。



### 主鍵（primary key）

唯一標識記錄的值（通常是數字或字串）。 在許多應用程式中，主鍵由系統在建立記錄時生成（例如，按順序或隨機）; 它們通常不由使用者設定。 另請參閱二級索引。



### 法定人數（quorum）

在操作完成之前，需要對操作進行投票的最少節點數量。 請參閱第179頁上的“讀寫的法定人數”。



### 再平衡（rebalance）

將資料或服務從一個節點移動到另一個節點以實現負載均衡。 請參閱第209頁上的“再平衡分割槽”。



### 複製（replication）

在幾個節點（副本）上保留相同資料的副本，以便在某些節點無法訪問時，資料仍可訪問。請參閱第5章。



### 模式（schema）

一些資料結構的描述，包括其欄位和資料型別。 可以在資料生命週期的不同點檢查某些資料是否符合模式（請參閱第39頁上的“文件模型中的模式靈活性”），模式可以隨時間變化（請參閱第4章）。



### 次級索引（secondary index）

與主要資料儲存器一起維護的附加資料結構，使您可以高效地搜尋與某種條件相匹配的記錄。 請參閱第85頁上的“其他索引結構”和第206頁上的“分割槽和二級索引”。



### 可序列化（serializable）

保證多個併發事務同時執行時，它們的行為與按順序逐個執行事務相同。 請參閱第251頁上的“可序列化”。



### 無共享（shared-nothing）

與共享記憶體或共享磁碟架構相比，獨立節點（每個節點都有自己的CPU，記憶體和磁碟）透過傳統網路連線。 見第二部分的介紹。



### 偏斜（skew）

1.各分割槽負載不平衡，例如某些分割槽有大量請求或資料，而其他分割槽則少得多。也被稱為熱點。請參閱第205頁上的“工作負載偏斜和減輕熱點”和第407頁上的“處理偏斜”。

2.時間線異常導致事件以不期望的順序出現。 請參閱第237頁上的“快照隔離和可重複讀取”中的關於讀取偏斜的討論，第246頁上的“寫入偏斜和模糊”中的寫入偏斜以及第291頁上的“訂購事件的時間戳”中的時鐘偏斜。



### 腦裂（split brain）

兩個節點同時認為自己是領導者的情況，這種情況可能違反系統擔保。 請參閱第156頁的“處理節點中斷”和第300頁的“真相由多數定義”。



### 儲存過程（stored procedure）

一種對事務邏輯進行編碼的方式，它可以完全在資料庫伺服器上執行，事務執行期間無需與客戶端通訊。 請參閱第252頁的“實際序列執行”。



### 流處理（stream process）

持續執行的計算。可以持續接收事件流作為輸入，並得出一些輸出。 見第11章。



### 同步（synchronous）

非同步的反義詞。



### 記錄系統（system of record）

一個儲存主要權威版本資料的系統，也被稱為真相的來源。首先在這裡寫入資料變更，其他資料集可以從記錄系統衍生。 參見第三部分的介紹。



### 超時（timeout）

檢測故障的最簡單方法之一，即在一段時間內觀察是否缺乏響應。 但是，不可能知道超時是由於遠端節點的問題還是網路中的問題造成的。 請參閱第281頁上的“超時和無限延遲”。



### 全序（total order）

一種比較事物的方法（例如時間戳），可以讓您總是說出兩件事中哪一件更大，哪件更小。 總的來說，有些東西是無法比擬的（不能說哪個更大或更小）的順序稱為偏序。 請參見第341頁的“因果順序不是全序”。



### 事務（transaction）

為了簡化錯誤處理和併發問題，將幾個讀寫操作分組到一個邏輯單元中。 見第7章。



### 兩階段提交（2PC, two-phase commit）

一種確保多個數據庫節點全部提交或全部中止事務的演算法。 請參閱第354頁上的“原子提交和兩階段提交（2PC）”。



### 兩階段鎖定（2PL, two-phase locking）

一種用於實現可序列化隔離的演算法，該演算法透過事務獲取對其讀取或寫入的所有資料的鎖，直到事務結束。 請參閱第257頁上的“兩階段鎖定（2PL）”。



### 無邊界（unbounded）

沒有任何已知的上限或大小。 反義詞是邊界（bounded）。