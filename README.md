[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/yOwut1-r)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=21160807&assignment_repo_type=AssignmentRepo)
# 07
Neurosynth Frontend
Sprint Goal: Build an AJAX-based, pretty, & publicly available frontend using Tailwind/BootstrapLinks to an external site. (among other JS libraries) for Tren's backend @ https://mil.psy.ntu.edu.tw:5000 :

 

/terms : look up all available terms

/terms/<t1> : look up terms associated with t1

/query/<q_string>/studies: logical search

 

Query examples:

https://mil.psy.ntu.edu.tw:5000/terms

https://mil.psy.ntu.edu.tw:5000/terms/amygdala

https://mil.psy.ntu.edu.tw:5000/query/amygdala%20not%20emotion/studies


### 功能特色
1. 所有的 input 欄位, 皆採用 AJAX 自動補全技術, 確保使用者不會打錯字.
2. Term Query: 會依查詢結果, 使用者可以自行針對 related term, 依其條件,再查詢相關 Paper.
3. Query builder: 提供使用者 query builder 產生查詢的字串, 查詢相關 Paper.

### 心得 
1. 前端程式要用 vibe coding 的方式對話, 不是很容易.
2. 當瞭解每個 API call 回傳的內容及其含意的時候, 就比較容易有想法, 知道如何設計畫面, 讓使用者有較佳的操作及用戶體驗.