---
title: w6_to_w8_鹼性磷酸酶的酵素動力學

---

<style>
    .markdown-body {
        max-width: 1000px !important;
        margin: 0 auto;
    }
    table {
  margin-left: auto;
  margin-right: auto;
    }

img {
  display: block;
  margin-left: auto;
  margin-right: auto;
    }
</style>

<center>
    
# Enzyme Kinetics of Alkaline Phosphatase<br>鹼性磷酸酶的酵素動力學
    
</center>
<span style="color: #adadad">4113052130 生科二 徐詠智</span>

## introduction
### 鹼性磷酸酶是什麼
- 鹼性磷酸酶 (**alkaline phosphatase, ALP**) 是一種在肝臟、骨骼、腸道中常見的水解酵素，在pH值為8~10的環境下活性較佳，負責幫忙釋出磷酸基，在生理上有不同的功能: 

$$R-O-PO_3^{2-} + H_2O\xrightarrow[]{ALP}R-OH + PO_4^{3-}$$

| 位置 | 功能 |
| --- | --- |
| **骨骼** | 促進骨基質礦化，提供磷酸鹽給羥基磷灰石沉積。 |
| **肝臟** | 參與膽汁分泌與代謝，臨床上常用來檢測肝膽疾病 |
| **腸道** | 協助磷酸鹽的吸收與再利用 |

- 本次實驗利用**硝基苯基磷酸酯 (P-nitrophenyl phosphate, PNPP)** 來做為底物，其跟ALP作用後，PNPP被水解成**p-nitrophenol (PNP)**
- 該產物呈現黃色，而且在405 nm有強烈吸收峰 ( $\varepsilon_{405}=18.8\times 10^3\ M^{-1}cm^{-1}$ )。這三周實驗會透過**酵素濃度、底物濃度、抑制劑**三個因子，去思考ALP水解PNPP的影響因素

### Michaelis–Menten 方程式和 Lineweaver–Burk 方程式
- 在推導出 $K_m$ 跟 $V_{max}$ 時，需要用到**Michaelis–Menten方程式**，也就是: 

$$v = \frac{V_{max}[S]}{K_m + [S]}$$

- 其中 $v$ 為反應速率， $V_{max}$ 為酵素能夠反應的最大速率， $K_m$ 為米氏常數， $[S]$ 為底物濃度 
- 當我們對該公式取倒數，同時拆開分子，就能得到一條線性公式，**又稱為Lineweaver–Burk 方程式**，也就是雙倒數圖: 

$$
\begin{align}
& \frac{1}{v} = \frac{K_m + [S]}{V_{\max}[S]}\\
\Rightarrow &\frac{K_m}{V_{\max}[S]} + \frac{[S]}{V_{\max}[S]}\\
\Rightarrow & \frac{1}{v} = \frac{K_m}{V_{\max}} \cdot \frac{1}{[S]} + \frac{1}{V_{\max}}\\
\Rightarrow & \boxed{\frac{1}{v} = \frac{K_m}{V_{\max}} \cdot \frac{1}{[S]} + \frac{1}{V_{\max}}}
\end{align}
$$
- 其中: 
  - 此為一條二元一次方程式: $y = mx + b$
  - $y = \frac{1}{v}$
  - $x = \frac{1}{[S]}$ 
  - 斜率 $m = \frac{K_m}{V_{\max}}$
  - 截距 $b = \frac{1}{V_{\max}}$

### three types of inhibitor
#### competitive inhibition
- 抑制劑與底物 "搶同一個位子" —— 活性位點
- 增加 $K_m$ (需要更高底物濃度才能達到同樣速率)，但 $V_{max}$ 不變
> [!Tip]
> 在雙倒數圖上，所有直線在y軸交會，但斜率不同

#### noncompetitive inhibition
- 抑制劑不跟底物搶位子，而是結合在酵素的**非活性位點 (allosteric site)**，改變酵素構型
- $K_m$ 不變 (底物親和力一樣)，但 $V_{max}$ 降低
> [!Tip]
> 在雙倒數圖上，直線在x軸交會，但y截距不同

#### uncompetitive inhibition
- 抑制劑只結合在**酵素-底物複合體 (ES complex)** 上，阻止反應進行
- $K_m$ 降低 (因為抑制劑鎖住ES， "表面上看起來" 底物親和力增加)，同時 $V_{max}$ 也降低
> [!Tip]
> 在雙倒數圖上，直線彼此平行 (因為斜率相同)，但整體向上、向左平移

<div style="display: flex; gap: 20px">
    <img src="https://raw.githubusercontent.com/Jacklyn301/experiment_file_1142/main/lineweaver%E2%80%93burk_plot_0504.png" style="width: 80%; margin-right: 10%; margin-left: 10%;">
</div>

---

## 實驗a: 不同pH值下的數據影響
### preparation
- 一共有10管，每一管各為不同的pH值: 

|reagents| $H_2O$ ( $\mu l$ ) | 100mM Gly buffer | $100mM\ MgCl_2 + 1mM\ ZnCl_2$ | 5mM PNPP ( $\mu l$ ) | ALP ( $\mu l$ ) |
|---|---|---|---|---|---|
|tube 1|400|250 (**pH=7.5**)|200|50|100|
|tube 2|400|250 (**pH=8.0**)|200|50|100|
|tube 3|400|250 (**pH=8.5**)|200|50|100|
|tube 4|400|250 (**pH=9.0**)|200|50|100|
|tube 5|400|250 (**pH=9.4**)|200|50|100|
|tube 6|400|250 (**pH=9.8**)|200|50|100|
|tube 7|400|250 (**pH=10.2**)|200|50|100|
|tube 8|400|250 (**pH=10.6**)|200|50|100|
|tube 9|400|250 (**pH=11**)|200|50|100|
|tube 10|400|250 (**pH=11.4**)|200|50|100|


- 上述各管依序加入 $H_2O$ 、 $100mM$ 甘胺酸緩衝液 (glycine buffer)、 $100mM\ MgCl_2 + 1mM\ ZnCl_2$ 及 $5mM$ PNPP後，放入光度計中，在 $405nm$ 波長下作校正
- 校正完畢後立即加入 $100\mu l$ ALP 在 $405nm$ 波長下測量300秒 (每10秒測量一次吸光值)。根據不同pH值的吸光值計算PNP的反應速率
- 反應速率以 "每分鐘生成多少 $\mu$ mole的PNP" 表示。由於: 

$$A=\varepsilon\cdot C\cdot l$$

- 又因為PNP在405nm時之吸收係數 $\varepsilon$ 為 $18.8\ mM^{-1}\cdot cm^{-1}$ ，因此該物質在某時間 ( $t$ ) 的平均速率為: 

$$\Delta A_{405}/ \text{time} =\frac{\Delta A_{405}}{18.8} (\text{second}^{-1}) = \frac{\Delta A_{405}}{18.8} \times 60  (\text{minute}^{-1})$$

- 如果要算整體的平均速率，可以直接使用吸光度趨勢線的斜率，作為 $\Delta A$ 的值。**務必記得單位要一致 !!**

### 結果
#### 標準曲線
- 根據第六周得到的數據[^1]，依照吸光度的變化情形做圖，以不同顏色標示出酵素在不同的pH值下反應的狀態，整理出以下的標準曲線:


![image alt](https://raw.githubusercontent.com/Jacklyn301/experiment_file_1142/main/absorbance_of_PNP_under_different_pH_effect_0506.png)

#### 速率曲線
- 再根據Beer-Lambert定律，利用已知的趨勢線斜率，計算反應物PNP濃度跟酵素的速率，得到的結果如下: 

![image alt](https://raw.githubusercontent.com/Jacklyn301/experiment_file_1142/main/velocity_of_ALP_under_different_pH_effects_0506.png)

> [!Note]
> 註解: 速率計算為斜率 $\times \frac{60}{18.8}$， $\varepsilon$ 為405nm的吸光係數: $18.8\ mM^{-1} cm^{-1}$


### 討論
#### 鹼性磷酸酶的最佳活性範圍為何?
- ALP的名字上就已經代表它在鹼性環境 (約pH 8–10) 下活性最高，在這次的作圖中可以發現，過酸或是過鹼的環境都會導致活性下降，尤其是酸性環境，速率曲線圖上可以發現，**pH 9.5-10的酵素反應速率是最快的**
- 然而，在有些時候，ALP在pH 11–12仍能維持部分活性，並非完全失活。可能原因有幾個: 
  - 1. 實驗器材問題: 可能跟分光光度儀的檢測誤差有關係
  - 2. 實驗失誤: 在做較強鹼性時的溶液搭配可能有容量上的錯配或是誤差
  - 3. 產物PNP在強鹼下去質子化成p-nitrophenolate，可能導致顏色更強烈，吸光度不會完全下降。這會讓高 pH 區間的活性曲線看起來偏高，即使酵素本身已部分失活[^2]


#### 鹼性磷酸酶為何在人體中有活性? 
- 雖然人體平均pH值呈現中性 ( $\approx 7.4$ )，但在體內它仍能在接近中性或稍偏鹼的環境下工作
- 有些局部微環性，如骨骼、腸道、膽汁分泌區域，能夠提供相對偏鹼的環境，讓ALP發揮功能
  - osteoblasts在骨基質沉積時，局部環境會偏鹼性。此時ALP會在這裡去除磷酸基，釋放無機磷酸鹽，促進羥基磷灰石沉積
  - 小腸液體環境比胃液中性，甚至稍偏鹼，因為其富含碳酸氫鈉。ALP在腸道刷狀緣膜上 (也就是微絨毛，microvilli)，協助磷酸鹽的吸收與再利用

---

## 實驗b: 不同溫度下的數據影響
### preparation

|reagents|volume ( $\mu l$ )|
|---|---|
| $H_2O$ | 600 |
| **100mM Gly buffer** | 375 |
| $100mM\ MgCl_2 + 1mM\ ZnCl_2$ | 300 |
| **5mM PNPP** | 75 |

- 總共要做出7管，混和均勻後，將各管放置在不同溫度的water bath (15℃、25℃、35℃、45℃、55℃、65℃、75℃) 中，靜置5分鐘
- 從各管中取 $900\mu l$ 混和溶液至cuvette在 $405nm$ 波長下作校正
- 校正完畢後立即加入 $100\mu l$ ALP 在 $405nm$ 波長下測量300秒 (每10秒測量一次吸光值)。根據不同溫度的吸光值計算PNP 的反應速率
- 同以上步驟，做出 **"ALP一起控溫"** 的，跟 **"ALP沒有控溫"** 的，兩組情況做實驗，觀察吸光值是否有變化，再化出反應速率

### 結果
#### ALP有控溫的狀況下
- 根據第七周得到的數據[^3]，依照吸光度的變化情形做圖，以不同顏色標示出在不同的溫度 (攝氏) 反應下時的狀態，整理出以下的標準曲線: 


![image alt](https://raw.githubusercontent.com/Jacklyn301/experiment_file_1142/main/standard_curve_of_PNP_under_different_temperature_experimental_0506.png)

- 根據Beer-Lambert定律，利用已知的標準曲線斜率，計算反應物PNP濃度跟酵素的速率，得到7個數據點，做出圖形: 

![image alt](https://raw.githubusercontent.com/Jacklyn301/experiment_file_1142/main/velocity_of_ALP_under_different_temperature_experimental_0506.png)

#### ALP沒有控溫的狀況下
- 一樣依照吸光度的變化情形做圖，以不同顏色標示出不同的溫度 (攝氏)，整理出以下的標準曲線:

![image alt](https://raw.githubusercontent.com/Jacklyn301/experiment_file_1142/main/standard_curve_of_PNP_under_different_temperature_control_0506.png)

- 再根據Beer-Lambert定律，利用已知的標準曲線斜率，計算反應物PNP濃度跟酵素的速率，得到7個數據點，做出以下圖形: 

![image alt](https://raw.githubusercontent.com/Jacklyn301/experiment_file_1142/main/velocity_of_ALP_under_different_temperature_control_0506.png)

### 討論
#### 酵素的速率跟環境溫度的關係
- 實驗發現，在控溫良好情況下，酵素速率在15~45°C的區間上升，並且在45°C登到最高點。在過了45°C之後便速率開始慢慢下降，甚至到65°C之後開始急速下降，75°C的酵素幾乎失活，沒有反應
  - **溫度較低**: 在低於20°C的環境，分子運動減慢，底物與酵素的碰撞頻率下降，因此活性降低。然而，酵素在該溫度下，結構仍能保持穩定，只是反應速率慢
  - **溫度較高**: 超過50–60°C，ALP的蛋白質結構開始變性，活性迅速下降，這是因為氫鍵、疏水作用等維持酵素構型的力被破壞

> [!Note]
> 註解: 不同來源的ALP (例如來自真核生物的ALP，對比來自原核生物的ALP) ，可能最佳溫度不一樣

#### 非控溫情況下產生的問題
- 第二個未控溫的情況下，可以發現，當酵素並沒有在試管加熱時一起泡入水浴，做出來的實驗會非常不如預期，例如，在最高溫75°C的時候，酵素的反應速率依然很高，沒有劇烈下降的情形
- 原因可能為以下幾點: 
  - **熱傳導不均**: 水浴的溫度雖然固定，但如果試管沒有完全浸入，管壁和液體的溫度可能比水浴低，相對之下，酵素反應實際發生在試管內液體，溫度差會導致反應速率偏低或不穩定
  - **操作延遲**: 加入ALP的時間差會讓不同試管反應的起始溫度不一致，這種操作誤差就可能會讓結果看起來隨機或是不穩定
  - **溶液散熱速度太快**: 加入eppendorf並且拿去水浴的溶液不到1毫升，很容易就因為空氣接觸而迅速降溫，原本70°C以上的溶液在反應時早已低於預設的溫度
- 因此，如果把ALP溶液和反應底物溶液分開放在水浴裡預熱 (也就是我們做的 "ALP控溫組" 的情形)，等到兩者都達到設定溫度，再快速混合，比較能避免拿出來後冷卻造成的誤差

---

## 實驗c: $K_m$ 跟 $V_{max}$ 在不同濃度下的抑制劑的影響
### preparation
- 一共有五種濃度的抑制劑 (磷酸氫二鈉， $Na_2HPO_4$ )，分別為A、B、C、D、E
- 每一種濃度的搭配五種濃度的PNPP，一共25管，如下: 

<div style="text-align: center;">
<table border="1">
  <tr>
    <th rowspan="6">A. 10mM <br> Na₂HPO₄ <br> 0μl</th>
    <th>Component</th>
    <th colspan="5">Volume (μl)</th>
  </tr>

  <tr>
    <td>H₂O</td>
    <td>445</td><td>440</td><td>425</td><td>400</td><td>350</td>
  </tr>

  <tr>
    <td>100 mM Gly buffer (pH 9.4)</td>
    <td colspan="5">250</td>
  </tr>

  <tr>
    <td>100 mM MgCl₂ + 1 mM ZnCl₂</td>
    <td colspan="5">200</td>
  </tr>

  <tr>
    <td>5 mM PNPP</td>
    <td>5</td><td>10</td><td>25</td><td>50</td><td>100</td>
  </tr>

  <tr>
    <td>ALK</td>
    <td colspan="5">100</td>
  </tr>
</table>

<table border="1">
  <tr>
    <th rowspan="6">A. 10mM <br> Na₂HPO₄ <br> 5μl</th>
    <th>Component</th>
    <th colspan="5">Volume (μl)</th>
  </tr>

  <tr>
    <td>H₂O</td>
    <td>440</td><td>435</td><td>420</td><td>395</td><td>345</td>
  </tr>

  <tr>
    <td>100 mM Gly buffer (pH 9.4)</td>
    <td colspan="5">250</td>
  </tr>

  <tr>
    <td>100 mM MgCl₂ + 1 mM ZnCl₂</td>
    <td colspan="5">200</td>
  </tr>

  <tr>
    <td>5 mM PNPP</td>
    <td>5</td><td>10</td><td>25</td><td>50</td><td>100</td>
  </tr>

  <tr>
    <td>ALK</td>
    <td colspan="5">100</td>
  </tr>
</table>

<table border="1">
  <tr>
    <th rowspan="6">A. 10mM <br> Na₂HPO₄ <br> 20μl</th>
    <th>Component</th>
    <th colspan="5">Volume (μl)</th>
  </tr>

  <tr>
    <td>H₂O</td>
    <td>425</td><td>420</td><td>405</td><td>380</td><td>330</td>
  </tr>

  <tr>
    <td>100 mM Gly buffer (pH 9.4)</td>
    <td colspan="5">250</td>
  </tr>

  <tr>
    <td>100 mM MgCl₂ + 1 mM ZnCl₂</td>
    <td colspan="5">200</td>
  </tr>

  <tr>
    <td>5 mM PNPP</td>
    <td>5</td><td>10</td><td>25</td><td>50</td><td>100</td>
  </tr>

  <tr>
    <td>ALK</td>
    <td colspan="5">100</td>
  </tr>
</table>

<table border="1">
  <tr>
    <th rowspan="6">A. 10mM <br> Na₂HPO₄ <br> 50μl</th>
    <th>Component</th>
    <th colspan="5">Volume (μl)</th>
  </tr>

  <tr>
    <td>H₂O</td>
    <td>395</td><td>390</td><td>375</td><td>350</td><td>300</td>
  </tr>

  <tr>
    <td>100 mM Gly buffer (pH 9.4)</td>
    <td colspan="5">250</td>
  </tr>

  <tr>
    <td>100 mM MgCl₂ + 1 mM ZnCl₂</td>
    <td colspan="5">200</td>
  </tr>

  <tr>
    <td>5 mM PNPP</td>
    <td>5</td><td>10</td><td>25</td><td>50</td><td>100</td>
  </tr>

  <tr>
    <td>ALK</td>
    <td colspan="5">100</td>
  </tr>
</table>

<table border="1">
  <tr>
    <th rowspan="6">A. 10mM <br> Na₂HPO₄ <br> 100μl</th>
    <th>Component</th>
    <th colspan="5">Volume (μl)</th>
  </tr>

  <tr>
    <td>H₂O</td>
    <td>345</td><td>340</td><td>325</td><td>300</td><td>250</td>
  </tr>

  <tr>
    <td>100 mM Gly buffer (pH 9.4)</td>
    <td colspan="5">250</td>
  </tr>

  <tr>
    <td>100 mM MgCl₂ + 1 mM ZnCl₂</td>
    <td colspan="5">200</td>
  </tr>

  <tr>
    <td>5 mM PNPP</td>
    <td>5</td><td>10</td><td>25</td><td>50</td><td>100</td>
  </tr>

  <tr>
    <td>ALK</td>
    <td colspan="5">100</td>
  </tr>
</table>
</div>

- 根據A、B、C、D、E，添加不同濃度的酵素抑制劑所配製的混和溶液 (ALP先不添加) 混和均勻後在 $405nm$ 波長下作校正。校正完畢後立即加入 $100\mu l$ ALP 在405 nm 波長下測量300秒 (每10秒測量一次吸光值)
- 分別將 A~E 繪製標準濃度曲線
- 當你得到一組數據後 (例如你得到A的數據)，以PNPP的濃度( $\mu M$ )改變為x軸，以所計算的生成PNP濃度 ( $\mu$ mole/min) 反應速率為y軸，直接作圖，應可得到一條動力學曲線
- 接著，改以PNPP濃度 ( $\mu M$ ) 的**倒數**為x軸，而以所計算的生成PNP濃度 ( $\mu$ mole/min) 反應速率的**倒數**為y軸，得到雙倒數作圖，應該可得到一條直線。不同濃度的酵素抑制劑 (A~E) 共有五條直線
- 由雙倒數直線，應該可推得 $K_m$ 及 $V_{max}$ (請注意兩者的單位)
- 由所得到的數據，不同濃度的抑制劑為x軸，分別以 $K_m$ 及 $V_{max}$ 為y軸作圖，探討屬於何種型的酵素抑制劑

### 結果
#### 標準曲線
- 根據第八周得到的數據[^4]，依照吸光度的變化情形做圖，以不同顏色標示出在不同PNPP濃度下，加入抑制劑後的標準曲線，每一張圖都代表一種濃度的抑制劑環境下的狀態，共有五張圖，25條標準曲線: 

##### A: $10\ mM\ Na_2HPO_4\ 0\mu l$

<div style="display: flex; gap: 20px">
    <img src="https://raw.githubusercontent.com/Jacklyn301/experiment_file_1142/main/standard_curve_of_PNP_with_inhibitor_A.png" style="width: 80%; margin-right: 10%; margin-left: 10%;">
</div>

##### B: $10\ mM\ Na_2HPO_4\ 5\mu l$

<div style="display: flex; gap: 20px">
    <img src="https://raw.githubusercontent.com/Jacklyn301/experiment_file_1142/main/standard_curve_of_PNP_with_inhibitor_B.png" style="width: 80%; margin-right: 10%; margin-left: 10%;">
</div>

##### C: $10\ mM\ Na_2HPO_4\ 20\mu l$

<div style="display: flex; gap: 20px">
    <img src="https://raw.githubusercontent.com/Jacklyn301/experiment_file_1142/main/standard_curve_of_PNP_with_inhibitor_C.png" style="width: 80%; margin-right: 10%; margin-left: 10%;">
</div>

##### D: $10\ mM\ Na_2HPO_4\ 50\mu l$

<div style="display: flex; gap: 20px">
    <img src="https://raw.githubusercontent.com/Jacklyn301/experiment_file_1142/main/standard_curve_of_PNP_with_inhibitor_D.png" style="width: 80%; margin-right: 10%; margin-left: 10%;">
</div>

##### E: $10\ mM\ Na_2HPO_4\ 100\mu l$

<div style="display: flex; gap: 20px">
    <img src="https://raw.githubusercontent.com/Jacklyn301/experiment_file_1142/main/standard_curve_of_PNP_with_inhibitor_E.png" style="width: 80%; margin-right: 10%; margin-left: 10%;">
</div>

#### 動力學曲線
- 接下來再根據Beer-Lambert定律，利用已知的標準曲線斜率，計算反應物PNP濃度跟酵素的速率
- 得到25種狀況的速率後，以PNPP的濃度 ( $\mu M$ ) 改變為x軸，以所計算的反應速率(Velocity, $\mu$ mole/min) 為y軸直接作圖，得到五條動力學曲線:

![image alt](https://raw.githubusercontent.com/Jacklyn301/experiment_file_1142/main/kinetic_assay_of_ALP_with_inhibitor_0506.png)

#### 雙倒數圖
- 在經過調整後，我們去除了三個數據點: A1、B1、E1
- 在計算PNPP濃度時，以A1情形 ($5\ mM\ PNPP 5\mu l,\ 10\ mM\ Na_2HPO_4 0\mu l$) 為例，計算方式如下: 

$$\frac{0.005\times (5\times 10^{-6})}{(445+250+200+5+0+100)\times 10^{-6}} = 25\mu M$$

- 依此算出每個狀況下的PNPP濃度後，以PNPP濃度的倒數 ( $1/\mu M$ ) 為x軸，以速率的倒數 (min/ $\mu$ mol) 為y軸，繪出五種抑制劑環境下的Lineweaver-Burk plot:

![image alt](https://raw.githubusercontent.com/Jacklyn301/experiment_file_1142/main/Lineweaver-Burk_plot_of_ALP_and_inhibitor_0506.png)

#### 求出 $K_m$ 及 $V_{max}$
- 由於我們知道雙導數曲線對應到的公式為: 

$$\frac{1}{v} = \frac{K_m}{V_{\max}} \cdot \frac{1}{[S]} + \frac{1}{V_{\max}}$$

- 由此可以求出 $K_m = m\times V_{max}$ ，$V_{max}=\frac{1}{b}$ ，根據以上方式推導出了五種抑制劑環境下的 $K_m$ 值跟 $V_{max}$ 值:

|情形|抑制物濃度 ( $\mu M$ )|截距 (b)|斜率 (m) | $V_{max}$ | $K_m$ |
|---|---|---|---|---|---|
|**A**|0|102.75|6761.7|0.009732|65.8073|
|**B**|50|86.961|11384|0.011499|130.9093|
|**C**|200|104.69|17047|0.009552|162.8331|
|**D**|500|129|23283|0.007752|180.4884|
|**E**|1000|78.152|47923|0.012796|613.2025|

- 分別以抑制劑濃度為x軸， $K_m$ 及 $V_{max}$ 為y軸作圖，得到以下的分布: 

![image alt](https://raw.githubusercontent.com/Jacklyn301/experiment_file_1142/main/Km_and_Vmax_of_ALP_inhibitor_0506.png)

### 討論
#### 抑制劑的可能形式為何?
- 在調整數距之後得到的雙倒數圖，我們發現A、B、C、D、E五個情形得到的圖形截距大小差不多 (交錯於y軸上)，而且隨著抑制劑濃度增加，雙倒數圖的斜率也跟著增加
- 觀察以 $K_m$ 及 $V_{max}$ 為y軸的兩張圖，可以發現 $K_m$ 值的趨勢線隨著抑制劑濃度增加而增加，而 $V_{max}$ 的趨勢相對來說沒有這麼明顯，趨勢線接近水平
- 因此對應到截距 ( $b=\frac{1}{V_{max}}$ ) 以及斜率 ( $m=\frac{K_m}{V_{max}}$ )，可以推測其偏向競爭型抑制劑
- 由於在Michaelis–Menten方程式上，競爭型抑制劑與底物競爭同一活性位點，理論上 $V_{max}$ 在加了抑制劑後不變 (只要底物濃度夠高，仍能達到最大速率)，而 $K_m$ 增加 (需要更高的底物濃度才能達到一半的 $V_{max}$ )

#### $Na_2HPO_4$ 為何屬於競爭型抑制?
- 當ALP催化PNPP的反應進行到後期，溶液裡的無機磷酸鹽 (Pi) 濃度會逐漸升高，這時Pi會反過來和底物競爭活性位點，這造成了ALP的活性降低
- 這現象又被稱為**產物抑制 (product inhibition)** ，在身體裡面是一種常見的生化調控機制
- 磷酸氫二鈉 ( $Na_2HPO_4$ ) 之所以會呈現 "類似競爭型抑制" 的效果，是因為它本身就是屬於一種無機磷酸鹽，所以相當於環境裡面的Pi濃度變多了，ALP的活性也會因此降低
- 由於Pi結合的未點就是酵素的活性位點，所以它屬於競爭型抑制

#### 為什麼去除 "PNPP加得最少" 的那幾個點? 
- 我們在繪製雙倒數圖時去除了A1、B1、E1三個數據，這些數據如果放在圖上，會使趨勢線出現很大的誤差，至於為什麼是這幾個點誤差最大，可能原因如下: 
  - A1、B1、E1等情形都是屬於底物濃度很低，速率也很低的情況
  - 在公式上，x值 ( $x=\frac{1}{[S]}$ ) 較大，同時，y值 ( $y=\frac{1}{v}$ ) 也比較大。因此這些值在雙倒數圖上通常都在離y軸非常遠的地方
  - 一旦這些點在濃度或是速率有些微的誤差 (例如利用pipette時加入的量不準確)，這些誤差會因為倒數的關係而放大，不僅對整條線造成很大的影響，也會使 $K_m$ 與 $V_{max}$ 的估算不準。因此在這次實驗上就去除了這些造成回歸線偏移的點
 

---

## 整體結論
- **鹼性磷酸酶在在pH 8–10活性最高，但在pH 11–12仍有殘餘活性**。有可能是人為誤差、分光光度儀的偵測產生問題、或是與產物p-nitrophenol在鹼性環境下去質子化，導致吸光值增加有關係
- **鹼性磷酸酶在45攝氏度左右的活性最高**，當溫度降低時，酵素會因為分子動能不足而活性下降；反之，溫度過高會導致酵素不可逆變性。如果溫度控制不嚴謹 (例如操作速度過慢導致溶液溫度不理想)，會導致數據偏差
- 抑制劑 $Na_2HPO_4$ 在實驗中呈現出類似**競爭型抑制劑**的數據，當加入抑制劑時， $K_m$ 增加而 $V_{max}$ 不變。在製作雙倒數圖時，低PNPP濃度的數據點誤差容易被放大。

#### 以下為數據跟參考資料

[^1]: https://1drv.ms/x/c/0fc3b0b896285a9d/IQCG_t5XRG3EQYKHojqV1waRAR_ldhzxmYAgecif9lbwr4g?e=KLkVpE

[^2]: https://pdf.benchchem.com/1585/Application_Note_Protocol_Colorimetric_Determination_of_Phosphatase_Activity_Using_p_Nitrophenyl_Phosphate_pNPP.pdf

[^3]: https://1drv.ms/x/c/0fc3b0b896285a9d/IQAdY0ZbL0QBRpMKnXUO9SjnAdhH-5fnQyiea4L6Xuus_9Q?e=VoILRo

[^4]: https://1drv.ms/x/c/0fc3b0b896285a9d/IQDTeAjdks0vTZR0BsyD06KkAaaYmj16tTzrI1mK9xJZBtA?e=HvAgOJ