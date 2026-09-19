# vocabuddy-group-2

## 小組名稱

Luca 好可愛

## 組員姓名

1. 楊岳蓁
2. 吳沛宸
3. 張語珊
4. 陳涓涓

## 組員的 GitHub 帳號

1. yyc000123
2. brAnChes1029
3. takooo3
4. juanjuan007

## 專案簡介

此專案為一單字庫，內容包含本組自己定義的單字，以及該單字之意思。此外，四個單字分別對應著四個組員，並且呈現了各個組員的特色。

## 組員分工

1. 楊岳蓁：參與討論、場外援助
2. 吳沛宸：新增隨機抽取單字的功能（第二次 commit）
3. 張語珊：建立 Repository 與邀請 Collaborators 並整理 README
4. 陳涓涓：新增單字及第一次 commit

## 本次新增的單字與功能

本組新增的單字
1. yyc : 歪歪西
2. wpc : 奇異果
3. tako : 張語珊
4. juanjuan : 水豚

本組新增的功能：隨機抽取單字並顯示中文解釋


## Google Colab 開啟連結

https://colab.research.google.com/github/takooo3/vocabuddy-group-2/blob/main/VocaBuddy.ipynb

## 程式執行方式

1. 載入 python 內建的隨機函式庫
2. 建立字典：定義四組單字與其解釋的對照表
3. 定義隨機抽取單字的函式：
   a. 將字典中所有單字轉為列表
   b. 使用 random.choice(...) 從列表中隨機挑選一個單字
   c. 存取字典中該單字對應的中文解釋
   d. 印出固定提示文字"Luca thinks the below word is cute." 、隨機挑選的單字、該單字之中文解釋
4. 呼叫函式：執行 3. 中的函式，觸發上述流程，每次執行都會隨機輸出其中一個單字及其對應解釋
