---
title: evolution_1st_homework

---

# Pokémon phylogeny homework
> Jacklyn Hsu 🐱

### Pokémon image searching
- 根據這次的作業，我要分配的角色長相如下: 

|走路草|角金魚|毽子棉|帝牙海獅|
|---|---|---|---|
|![image](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/Oddish_image_0919.webp)|![image](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/Goldeen_image_0919.webp)|![image](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/Jumpluff_image_0919.webp)|![image](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/Walrein_image_0919.webp)|

### Selecting the Outgroup and Rationale
- 在這次作業裡面，我嘗試選擇**角金魚當 outgroup**，是因為在假設的 character evolution 下，**其餘的Pokémon共享一些 synapomorphies (例如前肢、身體顏色深淺)**，而我判斷，角金魚缺乏這些 derived states

### Creating the Data Matrix
- 分析下四個Pokémon，得到的表格如下: 

|特徵|limbs present<br>🩷|blue body<br>💙|horn present<br>💛|Leaf present<br>💚|teeth present<br>🩶|tail present<br>🧡|red eye present<br>❤️|terrestrial<br>🤎|sphere body<br>💜|tail fin present<br>🩵|
|---|---|---|---|---|---|---|---|---|---|---|
|**角金魚**<br>**(外系群)**|0|0|1|0|0|0|0|0|0|1|
|**走路草**|1|1|0|1|0|0|1|1|1|0|
|**毽子棉**|1|1|0|1|0|1|1|1|1|0|
|**帝牙海獅**|1|1|0|0|1|0|0|1|0|0|

> [!Note]
> **以上的愛心顏色是為了區分character，以便分析時標記**

### Drawing Relationship Scenarios
- 如果以outgroup為角金魚的話，有三種可能的演化樹: 

![image alt](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/evolution_homework_fig1_0919.png)

### Marking Character Evolution
- 我嘗試將各種character用不同顏色標記在branches上面，標記方式如下: 

|特徵|limbs present|blue body|horn present|Leaf present|teeth present|tail present|red eye present|terrestrial|sphere body|tail fin present|
|---|---|---|---|---|---|---|---|---|---|---|
|**標記顏色**|粉色🩷|深藍💙|黃色💛|綠色💚|灰色🩶|橘色🧡|紅色❤️|棕色🤎|紫色💜|淺藍🩵|

- 將標記繪製於三種可能的phylogeny trees，**代表他們在branch上出現的evolutionary change**，如下: 

![image alt](https://raw.githubusercontent.com/Jacklyn301/2_image_bank/main/evolution_homework_fig2_0919.png)

### Identifying the Most Parsimonious Tree
> [!Important]
> - 計算三個演化樹中，evolutionary change 的數量如下: 
> 
> $$ \text{可能1} = 10\quad \text{可能2} = 13\quad \text{可能3} = 12$$
> 
> - 根據maximum parsimony的核心: 演化樹出現的evolutionary change要盡量最少
> - 可推測**最有可能的演化樹是 "可能1"**

### Evaluating Outgroup Selection
- 這一次畫出演化樹時，**我認為角金魚作為 outgroup 是合理的**
- 因為當我選擇它成為這一次分析的 ingroup 之外，確實**成功的幫我判定 character 的 ancestral 與 derived state**
- 而這次結果發現，在最大簡約法的分析中，將目前的 taxa 以這種方式排列時，**可能 1 所需的 character-state changes 最少**，因此是最簡約的演化樹，也得到我想要的結果分析。

#### 改善的可能
- 其實在我選擇outgroup時，**我曾有考慮另外選擇帝牙海獅作為 outgroup**
- 如果以分析來說，其實完全可以在拓撲上將牠作為外群，也有可能可以從最大簡約法得到演化樹結果
- 只是，由於這次作業中，並沒有額外的系統發育，證據支持帝牙海獅與 ingroup 的親緣關係比角金魚更接近，**如果只是僅僅更換 outgroup，並不能證明這會得到更準確的演化關係**

> [!Tip]
> 結論就是，在目前的 character data 下，**我依然會保留角金魚作為 outgroup，並將帝牙海獅視為一個可以進一步測試的 alternative outgroup**
