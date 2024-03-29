# teochew-character

## 簡介

本項目收集潮汕漢字及其白話字，並生成同音字表，以便操持潮汕話者可以查閱學習潮汕漢字及白話字。

潮汕漢字是潮汕話中使用到的漢字集。 潮州白話字，簡稱 PUJ，是古早來華傳教士根據當時汕頭地區的話語使用羅馬字構造的潮州話文字系統。

理論上應該從現有的潮汕文本中提煉出常用的漢字。但這項工作困難重重，一方面潮汕話本身並沒有多少書寫材料留存，另一方面留存的材料跟現實的用語又頗有差距，再者存在數字化的難度。

本著敏捷迭代的精神，本人利用普通話中常用的3700餘個漢字，再從7000字的通用漢字表中看眼緣收錄了一些，並加上潮汕話中常用而普通話中不常見的漢字，整理成一個不成熟的同音字表。接下來，就依靠社區和時間的力量來完善了。

## 同音字表

* Markdown格式由腳本生成，見 [puj_table.md](puj_table.md)。 
* PDF格式採用 Obsidian插件生成，見 [潮汕話同音字表.pdf](潮汕話同音字表.pdf)。

## 輸入法詞典

本項目生成了兩個文件[teochew.han.dict.yaml](teochew.han.dict.yaml) 和 [teochew.puj.dict.yaml](teochew.puj.dict.yaml) 用作姊妹項目 [rime-teochew](https://github.com/tsunhua/rime-teochew) 中的潮州話拍字方案的詞典文件。

如想了解如何在各個平台上使用潮州話拍字方案，請訪問該[項目](https://github.com/tsunhua/rime-teochew)。

## 貢獻

修改 [han_list.txt](han_list.txt)，然後運行 `python3 main.py` 即可生成新的同音字表。

歡迎大家提交 PR，或者在 issue 中提出建議。
