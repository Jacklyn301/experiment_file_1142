---
title: w10 _to_w12  利用大腸桿菌生產及純化重組蛋白

---

# production and purification of recombinant protein using E.coli<br>利用大腸桿菌生產及純化重組蛋白
### group 3

---

## week 1: 大量表現蘋果酸脫氫酶
### 前製步驟
- 在含可誘導蛋白產生質體的平板培養基中挑取單一的大腸桿菌 (BL21 菌株) 菌落，培養在含 $50 mg/ml$ Kanamycin LB 中，在 37℃ 懸浮培養16 hours
- 取 $500 \mu l$ 的菌液加到 $50 ml$ LB 中 (加入菌液體積：放大後培養基體積 = **1：100**)，在 37℃ 懸浮培養到 $OD_{600} = 0.6$ ，加入 IPTG 至培養基中 (最終濃度為 $0.5 mM$ )，再繼續培養 1.0、1.5、2.0、2.5、3.0 小時後，將培養液離心(8000rpm, 4℃, 10 mins), 倒掉上清液，保留底層pellet
- 將pellet 以 $5ml$ 的 $0.01M$ **sodium-phosphate buffer** (pH7.4，內含 4M $NaCl$) 回溶，移至 $50ml$ 的塑膠離心管中，放在冰上以維持低溫
- 將超音波震盪機器的tip，伸入離心管內 sodium-phosphate buffer 的液面下

> [!Note]
> 建議 tip 盡量不要碰到離心管

- 功率調成 40%，震盪的時間設 10 mins，pulse on 設成 3s，pulse off 設成9s
- 4℃、3000rpm 的條件下離心 10 mins。將上清液取出，以 **protein dye** 測定上清液蛋白質含量
- 測完酵素的粗萃取液置於4℃冰箱中，保留到下週進行純化。離心剩下的沉澱物，置於-20℃保留至第三週蛋白質電泳使用

### 測定酵素活性

- 將分光光度計中測定酵素活性的波長定為 $340nm$ (此為NADH的吸收峰)
- 在 cuvatte 中加入 $900 \mu l$ 的 $0.01M$ sodium-phosphate buffer (pH7.4，內含有 4M $NaCl$) 後，放進分光光度計中歸零
- 加入 $25 \mu l$ OAA(oxaloacetate，草醯已酸，stock 濃度為 $5mg/ml$ )、 $25\mu l$ NADH (stock 濃度為 $10 mg/ml$ )，放入分光光度計中
- 待其吸光值趨於穩定後，加入 $50\mu l$ 的粗萃取液，混勻後放入分光光度計中 5 mins內測定吸光值的變化情形，紀錄並計算活性

> [!Important]
> 若吸光值一下下降過快，表示 MDH 活性太強，**需要稀釋後再重測 !!**

---

## week 2: 純化蘋果酸脫氫酶
### 前製步驟
- 將1ml BD TALON 樹脂 (resin) 加到5ml分離管柱中，關緊下方的開關，並以 $4ml\ 10mM$ sodium-phosphate buffer (pH7.4，內含4M $NaCl$ ) 為洗滌液(wash buffer)，輕搖離心管數次 

> [!Note]
> 這是為了讓樹脂充分浸潤在buffer

- 靜置至樹脂沉澱後，將管柱上層的洗滌液吸去，留下一薄水層，盡量避免樹脂乾掉
- 把上週破菌後的粗萃取液取出，先保留50μl 在-20℃的冰箱中，以備下週電泳實驗用剩下的粗萃取液加至含有樹脂的分離管柱中，輕輕搖晃 5 mins，使粗萃取液中帶有His-tagged的蘋果酸脫氫酶
- 靜置於冰上，等到樹脂沉澱後，打開下方的開關，並收取流出液 (即為**flow through**)，取一部分進行蘋果酸脫氫酶的活性及蛋白質含量測定

> [!Important]
> 接下來的步驟中，剩下的流出液請妥善保存至下週實驗用 !!

- 加入 $2ml$ 的洗滌液至管柱中，並由管柱下方收取流出液 (即為**wash 1**)，取一部分進行蘋果酸脫氫酶的活性及蛋白質含量測定
- 重複上一步驟，並收取流出液 (即為**wash 2**)，取一部分進行蘋果酸脫氫酶的活性及蛋白質含量測定
- 將 $1ml$ 含 $50mM$ imidazole 的洗滌液加到管柱中 (這時，樹脂會隨著洗滌液的沖提而逐漸變成紅色) ，收集管柱下方的流出液，取一部分進行蘋果酸脫氫酶的活性及蚤白質含量測定
- 重複上一步驟，改用 $1ml$ 含 $100$ 、 $150$ 、 $200mM$ imidazole 的洗滌液，依序收集管柱下方的流出液，並依序取一部分進行蘋果酸脫氫酶的活性及蛋白質含量測定

> [!Important]
> 此步驟中，剩下的流出液取 $50\mu l$ ，加入 4 倍體積 -20℃ 的 acetone ( $200\mu l$ )，置於 -20℃ 冰箱沉澱 !!


- 將 $5ml$ ， $20 mM$ MES buffer (pH5.0，含 0.1M $NaCl$ ) 加入管柱中

> [!Note]
> 此步驟是為了把與樹脂結合的 imidazole 置換出來

- 再加入 $5ml$ 的蒸餾水清洗樹脂
- 將樹脂保存在 20％ 的酒精溶液中 (其中裡面含有 0.1% azide)

#### 步驟跟代測物總結如下

|實驗步驟|對應代測物|
|---|---|
| $3.0ml$ crude extract stand 5 mins|flow through|
| $1.0ml$ Tris buffer|wash 1|
| $1.0ml$ Tris buffer|wash 2|
| $1.0ml$ 50mM imidazole|50 mM|
| $1.0ml$ 100mM imidazole|100 mM|
| $1.0ml$ 150mM imidazole|150 mM|
| $1.0ml$ 200mM imidazole|200 mM|
| $1.0ml$ 250mM imidazole|250 mM|
| $5.0ml$ 20mM MES buffer|製換 (release)|
| $5.0ml$ $ddH_2O$ |清洗 (release)|
| $5.0ml$ 20% ethanol|releasing $3.0ml$ |

### 測定 Protein 含量
- 取 $20\mu l$ **tris buffer** +  $1.0ml$ **protein dye** ，混和均勻後，以波長 $A_{595}$ 校正
- 取 $20\mu l$ 待測物 (**crude extract、flow through、wash 1、wash 2、50mM、100mM、150mM、200mM、250mM**) + $1.0ml$ **protein dye** 混和均勻後，以波長 $A_{595}$ 測量，並估算 protein 含量

### 測定蘋果酸脫氫酶的活性
- 蘋果酸脫氫酶的反應式如下: 

$$\boxed{oxaloacetate + NADH \xrightarrow[]{MDH} NAD^+ + malate}$$

- 取 $900\mu l$ tris buffer + $25 \mu l$ OAA ( $5mg/ml$ ) + $25\mu l$ NADH ( $10 mg/ml$ )，混和均勻後，以波長 $A_{360}$ (由於機器故障，將340改為測量360) 校正
- 加入 $50\mu l$ 待測物 (**crude extract、flow through、wash 1、wash 2、50mM、100mM、150mM、200mM、250mM**) 後，以波長 $A_{360}$ 測量 5 mins

> [!Important]
> 若吸光值一下下降過快，表示 MDH 活性太強，**需要稀釋後再重測 !!**

### 備註: 何謂 "親和性管柱層析法" ?
- 假如說 A 與 B 兩分子之間，有專一性的親和力，如果想在樣本混合物中，將所含的 B 分子分離出來，則最方便的方法，是先**把 A 固定在一固定相 (solid phase) 上**
- 當樣本混合物通過此固定相時，其中的 B 分子即被 A 吸附到固定相。俟洗去混合物中其它雜質後，破壞 A-B 之間的吸引力，溶離下B，即可得到純質B
#### 其中有幾個因素會影響: 
- **固相擔体 (solid support)**
    - 要有良好多孔性，通透性佳，構成的分子骨架本身穩定，無太大的非專一性吸附，還要具有相當活性的官能基，以便與其它分子鍵結
    - 常用的有agarose、幾丁質 (chitin)、聚丙烯醯胺 (polyacrylamide)、聚苯乙烯 (polystyrene) 等等
- **Ligand 及其專一性結合分子**
    - 配體 (ligand) 與目標分子之間，要有相當強的親和力
    - 例如抗原-抗體、酵素-基質、荷爾蒙-受體、酵素-抑制因子
- **Ligand 與固相擔體間之的耦合反應**
- **可溶離下所要分離之目標分子**
    - 可改變溶離的pH、離子強度或其它方法
    - 某些方法可能會使ligand 或所欲純化之分子，受到不同程度的破壞


![image alt](https://www.neuromics.com/site/images/A8x105c6x71x1.jpg)

---


## week 3: 以 SDS-PAGE 分析純化蛋白質的程度
### 前製步驟
- 上週沉澱物以 4℃、12000 rpm 離心10 mins，倒掉上清液後，以 -20℃ 的 75% 酒精，清洗沉澱物，再以 4℃、12000 rpm 離心 10 mins
- 倒掉上清液後將沉澱物晾乾，再以 $20\mu l$ lx sample buffer 回溶後，進行SDS-PAGE分析 

### 實驗說明
- 將電泳玻片及氧化鋁片清洗淨後擦乾，再以玻璃清潔劑擦拭乾淨，選擇所需厚度的間隔條 (spacer) ，組裝於鑄膠套件
- 配置 Running Gel (12.5%) 膠體溶液，然後以微量吸管小心注入鑄膠套件

> [!Note]
> - 其中 APS 溶液必須最後加入
> - 盡量避免氣泡產生

- 注入膠體 (約佔玻片 2/3 至3/4 高) ，加完膠後，儘快在膠體液面上方小心加入 $100\mu l$ 異丙醇 (or $ddH_2O$ )，以壓平膠體液面
- 約靜製 30 mins 至 1 hour 後，凝膠已經固化，倒出上層的異丙醇
配製 Stacking Gel (4%) 焦集膠體溶液，在配置前先準備好適合的樣本梳，加入溶液後立刻插入，產生裝載樣本的孔洞

> [!Note]
> 整個過程必須在 5min 完成，因為其膠體凝固速度極快

- 膠體完成後，拆下膠片並清理，將多餘的凝膠去除

> [!Note]
> 鑄好的膠片可置封口袋中於 4℃ 保存，保存時要加入少量蒸餾水，以防止膠片乾裂

- 在確保膠片是在室溫下的情況下，將稀釋成一倍的通用電泳緩衝液，倒入電泳槽底部

> [!Warning]
> 如果用的是保存在低溫的膠片，務必等到其回復室溫再來做實驗，**否則玻片會因為溫度升高而破裂 !**

- 把膠片架到電泳槽上。當電泳夾夾妥後，在電泳玻片組合的上方槽內，加入電泳緩衝液
- 取出樣本 $20\mu l$ ，加 $10\mu l$ 追蹤染料，混合均勻後，以微量針管小心注入樣本 (務必記錄注入體積)，每個樣本槽最多容納20μl 樣本 
- 蓋上電泳槽的蓋子，確認正負電極裝置正確 (從負到正)，接上電源供應器，定電壓以 **100~150V**  進行電泳
- 待追蹤染料跑到底部後，關掉電源，取出膠片，以解剖刀截去膠片的右上角，以做記號
- 電泳膠片浸入 CBB stain 染色液中，置於平台，在震盪器上搖盪 30 mins

> [!Note]
> 染色液用量只要覆蓋過膠片即可，務必要蓋上蓋子

- 倒出染色液回收，膠片用自來水沖洗後加入脫色液 (一樣蓋過膠片即可)，約 10 mins 換第一次脫色液，然後一直定時換新到背景清澈透明為止

---

## 實驗結果
### 數據計算

- 由過去蛋白質定量測量實驗所得標準曲線為: 

![image alt](https://raw.githubusercontent.com/Jacklyn301/image_bank/main/protein_dye_method_curve_0325.png)

- 將測量之吸光值代入 $y = 0.4653x + 0.0937$ 中的  $y$
- 在未有加入IPTG的情況下，得出各樣本濃度為:

|樣本| $A_{595}$ | 濃度 ( $mg/ml$ )  |
|---|---|---|
|crude extract|0.920|1.776|
|flow through|0.636|1.165|
|wash 1|0.618|1.127|
|wash 2|0.120|0.057|
|50 mM|0.152|0.125|
|100 mM|0.300|0.443|
|150 mM|0.107|0.029|
|200 mM|0.057|-0.079|
|250 mM|0.100|0.014|

- 最終整理出的MDH數據表如下: 

<table class="mdh-table">
  <thead>
    <tr>
      <th>組別</th><th>項目</th><th>crude extract</th><th>flow through</th><th>wash1</th><th>wash2</th><th>50mM</th><th>100mM</th><th>150mM</th><th>200mM</th><th>250mM</th>
    </tr>
  </thead>
  <tbody>
    <tr><td rowspan="3">control (其他組)</td><td>蛋白質量 (mg)</td><td>0.083</td><td>0.078</td><td>0.070</td><td>0.024</td><td>0.028</td><td>0.019</td><td>0.011</td><td>0.005</td><td>0.006</td></tr>
    <tr><td>MDH 活性 (μmole/min)</td><td>0.039</td><td>0.026</td><td>0.006</td><td>0.005</td><td>0.058</td><td>0.018</td><td>0.001</td><td>0.001</td><td>0.002</td></tr>
    <tr><td>比活性 (μmole/min/mg)</td><td>0.466</td><td>0.331</td><td>0.080</td><td>0.223</td><td>2.079</td><td>0.909</td><td>0.088</td><td>0.100</td><td>0.312</td></tr>
    <tr><td rowspan="3">IPTG (本組)</td><td>蛋白質量 (mg)</td><td>1.176</td><td>1.165</td><td>1.127</td><td>0.057</td><td>0.125</td><td>0.443</td><td>0.029</td><td>-0.079</td><td>0.014</td></tr>
    <tr><td>MDH 活性 (μmole/min)</td><td>0.02545</td><td>0.0146</td><td>0.0087</td><td>0.00145</td><td>0.0066</td><td>0.01335</td><td>0.0014</td><td>0.0003</td><td>0.0004</td></tr>
    <tr><td>比活性 (μmole/min/mg)</td><td>0.02164</td><td>0.01253</td><td>0.00771</td><td>0.02544</td><td>0.0528</td><td>0.03014</td><td>0.04828</td><td>-0.0038</td><td>0.02857</td></tr>
  </tbody>
</table>

### 電泳分析
#### 有加IPTG
- 加入了IPTG的電泳情形如下: 

<div style="display: flex; gap: 20px">
    <img src="https://raw.githubusercontent.com/Jacklyn301/experiment_file_1142/main/gel_electrophoresis-with_IPTG.jpg" style="width: 70%; margin-right: 15%; margin-left: 15%;">
</div>

- 其中: 
    - 由左到右溶液依序是 **crude extract stand、flow through、wash1、wash2、50mM、100mM、150mM、200mM、250mM**
    - 在100mM條帶最為明顯
    - 粗萃取的雜蛋白最多，隨著萃取越多次雜蛋白越少
    - 粗萃取的條帶裡包括細胞被打破後的所有蛋白質
    - 圖中間以右的泳道皆有一條顏色較深，較明顯的條帶，即為MDH
    - 200及250mM的泳道幾乎看不到條帶，可能是MDH與管住的結合力不夠，導致wash過於乾淨造成

#### 分析
- MDH 活性最高峰落於 100mM 處，結果與電泳條帶符合，且比活性最高的是50mM及100mM，MDH純度最高
- 150mM 至 250mM 洗脫液，蛋白質定量已趨近於零，亦對應電泳膠體右側條帶訊號微弱之現象
- 比活性最高的是50mM及100mM，MDH純度最高
- 200mM時算出來的濃度有負值，代表偵測到蛋白質的量太少，甚至沒有蛋白質 (偵測到的可能是Imidazole)，150mM 之後管柱上幾乎已經完全沒有蛋白質
- 在crude extract stand中，吸光值預期會逐漸下降，但此次的數據發現在0-30秒的時間，吸光直從0.951 跌到 0.551 ，其中原因可能包含蛋白質濃度太高，反應速度太快，導致基質 (NADH/OAA) 在 30 秒內消耗殆盡
- flow through、wash1皆有測到明顯的MDH，其中原因可能包含 IPTG 誘導出來的 MDH 量過多，因此將樹脂能和MDH結合的位點幾乎全部結合，導致之後的 MDH 黏不上去，隨著 Flow Through 和 Wash 1 一起洗出。或是液體流過管柱的速度太快，導致 His-tag 尚未跟樹酯結合便掉了下來。


#### 未加IPTG
- 未加入IPTG的電泳情形如下: 


<div style="display: flex; gap: 20px">
    <img src="https://raw.githubusercontent.com/Jacklyn301/experiment_file_1142/main/gel_electrophoresis-no_IPTG%20.jpg" style="width: 70%; margin-right: 15%; margin-left: 15%;">
</div>


- 其中: 
    - 由左到右溶液依序是 **crude extract stand、flow through、wash1、wash2、50mM、100mM、150mM、200mM、250mM**
    - 在50mM條帶最為明顯，MDH活性、純度應最高
    - crude extract stand、flow through、wash1的雜蛋白很多，但尚有一點MDH的條帶，代表MDH可能吸附不完全，或流速太快，導致MDH一起被wash出來
    - 從100mM以後的條帶不太明顯，在200-250mM，已經幾乎看不到條帶

#### 分析
- 比活性最高的是50mM洗脫液，MDH純度最高，電泳圖上也顯示在50mM洗脫液有最明顯且乾淨的MDH條帶

### 兩者比較
- 加了 IPTG 誘導，Crude 的總蛋白質比沒加的高很多，但MDH 總活性反而比沒加的還要低
   - 原因可能包含: IPTG 誘導雖然成功讓蛋白質產量遽增 (分母極大)，但因合成過快而形成了大量沒有活性的包含體，加上高濃度酵素液未充分稀釋，導致活性測量被低估
- 有加IPTG的MDH比活性 (0.0528) 比沒加IPTG (2.079) 明顯的還低
   - 原因可能包含: 加了IPTG，可能因為製造MDH的速度太快，導致大量生產的MDH蛋白質沒有正確折疊，聚集形成沒有活性的包涵，或者是受到受質抑制

---


## 討論
### IPTG的效果
- 本實驗利用 IPTG (Isopropyl $\beta$ -D-1-thiogalactopyranoside) ，誘導大腸桿菌大量表現MDH
- IPTG 是一種乳糖類似物 (lactose analog)，能與 Lac repressor (LacI) 結合，使其脫離 lac operator，進而啟動下游基因的轉錄，大量轉錄目標基因，因此能提高目標蛋白的產量
- 若未加入 IPTG，LacI 會抑制目標基因的表現，使細胞僅產生少量甚至幾乎不產生目標蛋白。因此，理論上添加 IPTG 的菌株在粗萃取液中應具有較高的目標蛋白含量及較高的酵素活性，而未添加 IPTG 的樣品則應呈現較低的酵素活性。若實驗結果符合此趨勢，表示 IPTG 成功誘導目標蛋白表現
- 此外，由於親和性管柱層析純化的對象為帶有特定標籤的重組蛋白，因此 IPTG 誘導後產生較多目標蛋白，也有助於提高後續純化的回收量
- 在 SDS-PAGE 分析中，加入 IPTG 的樣品理論上應在目標蛋白分子量位置出現較明顯的蛋白質條帶，而未誘導組則可能僅出現微弱條帶或無法觀察。若兩組差異不明顯，則可能與誘導條件不佳、蛋白質降解等因素有關
- 若 IPTG 誘導組之 MDH 比活性顯著高於未誘導組，表示目標蛋白成功大量表現且維持酵素活性。反之，若蛋白質產量增加但比活性未同步提升，則可能代表部分重組蛋白未正確摺疊而失去活性

### 純化效果 
- 在親和性管柱層析過程中，crude extract 含有大量宿主蛋白與目標蛋白，因此總蛋白質濃度最高。flow through 與 wash 1 仍具有較高蛋白質濃度
- 此結果表示部分未與樹脂結合之雜蛋白被沖洗出去。Wash 2 的蛋白質濃度大幅下降，顯示大部分非專一性結合蛋白已被移除

### 最佳洗脫條件 
- 在不同濃度 imidazole 洗脫液中，100 mM fraction 具有最高蛋白質濃度及最高 MDH 活性，且 SDS-PAGE 顯示其目標蛋白條帶最明顯，表示大部分 MDH 於此濃度下被有效洗脫
- 由於 imidazole 可與 His-tag 競爭 $Ni^{2+}$ 結合位點，因此適當濃度的 imidazole 能使目標蛋白自管柱脫附。實驗結果顯示 100 mM 已足以有效洗脫 MDH，而更高濃度的 imidazole 幾乎未增加蛋白回收量。 

---


## 總結
- 本次實驗發現，蛋白質定量、MDH 活性分析及 SDS-PAGE 結果均顯示，100 mM imidazole 為最佳洗脫條件，具有最高的蛋白質含量、最高的酵素活性及最明顯的目標蛋白條帶











