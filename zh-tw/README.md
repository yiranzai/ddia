<!--ts-->
   * [設計資料密集型應用 - 中文翻譯](./zh-tw/README.md#設計資料密集型應用---中文翻譯)
      * [譯序](./zh-tw/README.md#譯序)
      * [前言](./zh-tw/README.md#前言)
      * [目錄](./zh-tw/README.md#目錄)
         * [<a href="preface.md">序言</a>](./zh-tw/README.md#序言)
         * [<a href="part-i.md">第一部分：資料系統的基石</a>](./zh-tw/README.md#第一部分資料系統的基石)
         * [<a href="part-ii.md">第二部分：分散式資料</a>](./zh-tw/README.md#第二部分分散式資料)
         * [<a href="part-iii.md">第三部分：衍生資料</a>](./zh-tw/README.md#第三部分衍生資料)
         * [<a href="glossary.md">術語表</a>](./zh-tw/README.md#術語表)
         * [<a href="colophon.md">後記</a>](./zh-tw/README.md#後記)
      * [法律宣告](./zh-tw/README.md#法律宣告)
      * [CONTRIBUTION](./zh-tw/README.md#contribution)
      * [LICENSE](./zh-tw/README.md#license)

<!-- Added by: runner, at: Tue Apr 20 03:41:42 UTC 2021 -->

<!--te-->
# 設計資料密集型應用 - 中文翻譯 

- 作者： [Martin Kleppmann](https://martin.kleppmann.com)
- 原書名稱：[《Designing Data-Intensive Application》](http://shop.oreilly.com/product/0636920032175.do)
- 譯者：[馮若航]( http://vonng.com/about) （fengruohang@outlook.com ）
- Gitbook地址：[ddia-cn](https://www.gitbook.com/book/vonng/ddia-cn)
- 使用[Typora](https://www.typora.io)或Gitbook以獲取最佳閱讀體驗。




## 譯序

> 不懂資料庫的全棧工程師不是好架構師
>
> —— Vonng

​	現今，尤其是在網際網路領域，大多數應用都屬於資料密集型應用。本書從底層資料結構到頂層架構設計，將資料系統設計中的精髓娓娓道來。其中的寶貴經驗無論是對架構師，DBA、還是後端工程師、甚至產品經理都會有幫助。

​	這是一本理論結合實踐的書，書中很多問題，譯者在實際場景中都曾遇到過，讀來讓人擊節扼腕。如果能早點讀到這本書，該少走多少彎路啊！

​	這也是一本深入淺出的書，講述概念的來龍去脈而不是賣弄定義，介紹事物發展演化歷程而不是事實堆砌，將複雜的概念講述的淺顯易懂，但又直擊本質不失深度。每章最後的引用質量非常好，是深入學習各個主題的絕佳索引。

​	本書為資料系統的設計、實現、與評價提供了很好的概念框架。讀完並理解本書內容後，讀者可以輕鬆看破大多數的技術忽悠，與技術磚家撕起來虎虎生風🤣。

​	這是2017年譯者讀過最好的一本技術類書籍，這麼好的書沒有中文翻譯，實在是遺憾。某不才，願為先進技術文化的傳播貢獻一分力量。既可以深入學習有趣的技術主題，又可以鍛鍊中英文語言文字功底，何樂而不為？



## 前言

> 在我們的社會中，技術是一種強大的力量。資料、軟體、通訊可以用於壞的方面：不公平的階級固化，損害公民權利，保護既得利益集團。但也可以用於好的方面：讓底層人民發出自己的聲音，讓每個人都擁有機會，避免災難。本書獻給所有將技術用於善途的人們。

---------

> 計算是一種流行文化，流行文化鄙視歷史。 流行文化關乎個體身份和參與感，但與合作無關。流行文化活在當下，也與過去和未來無關。 我認為大部分（為了錢）編寫程式碼的人就是這樣的， 他們不知道自己的文化來自哪裡。                         
>
>  ——阿蘭·凱接受Dobb博士的雜誌採訪時（2012年）



## 目錄

### [序言](preface.md)

### [第一部分：資料系統的基石](part-i.md)

* [第一章：可靠性、可擴充套件性、可維護性](ch1.md) 
* [第二章：資料模型與查詢語言](ch2.md)
* [第三章：儲存與檢索](ch3.md) 
* [第四章：編碼與演化](ch4.md)

### [第二部分：分散式資料](part-ii.md)

* [第五章：複製](ch5.md) 
* [第六章：分割槽](ch6.md) 
* [第七章：事務](ch7.md) 
* [第八章：分散式系統的麻煩](ch8.md) 
* [第九章：一致性與共識](ch9.md) 

### [第三部分：衍生資料](part-iii.md)

* [第十章：批處理](ch10.md) 
* [第十一章：流處理](ch11.md) 
* [第十二章：資料系統的未來](ch12.md) 

### [術語表](glossary.md)

### [後記](colophon.md)



## 法律宣告

從原作者處得知，已經有簡體中文的翻譯計劃，將於2018年末完成。

譯者純粹出於**學習目的**與**個人興趣**翻譯本書，不追求任何經濟利益。

譯者保留對此版本譯文的署名權，其他權利以原作者和出版社的主張為準。

本譯文只供學習研究參考之用，不得公開傳播發行或用於商業用途。有能力閱讀英文書籍者請購買正版支援。



## CONTRIBUTION

1. [序言初翻修正](https://github.com/Vonng/ddia/commit/afb5edab55c62ed23474149f229677e3b42dfc2c) by [@seagullbird](https://github.com/Vonng/ddia/commits?author=seagullbird)
2. [第一章語法標點校正](https://github.com/Vonng/ddia/commit/973b12cd8f8fcdf4852f1eb1649ddd9d187e3644) by [@nevertiree](https://github.com/Vonng/ddia/commits?author=nevertiree)
3. [第六章部分校正](https://github.com/Vonng/ddia/commit/d4eb0852c0ec1e93c8aacc496c80b915bb1e6d48) 與[第10章的初翻](https://github.com/Vonng/ddia/commit/9de8dbd1bfe6fbb03b3bf6c1a1aa2291aed2490e) by @[MuAlex](https://github.com/Vonng/ddia/commits?author=MuAlex) 
4. 第一部分前言，ch2校正 by @jiajiadebug
5. 詞彙表、後記關於野豬的部分 by @[Chowss](https://github.com/Vonng/ddia/commits?author=Chowss)
6. 簡體與繁體中文轉換工具 by [@afunTW](https://github.com/afunTW) using [OpenCC](https://github.com/BYVoid/OpenCC)

感謝所有作出貢獻，提出意見的朋友們：[Issues](https://github.com/Vonng/ddia/issues)，[Pull Requests](https://github.com/Vonng/ddia/pulls)



## LICENSE

CC-BY 4.0
