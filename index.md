# Since 2025 September 1sh
- test
- 

- [draft](draft) <-- *always* put this at first line for quick idea capturing and organizing
- [portal](portal)
- [resources](resources)

# mynote

1. [program](program)
2. [package](package)
3. [uni](uni)


# Draft

- Linh 37 15 22 24 34
- An 32 2 18 42 12
- A Le 17 17 14 15 33
- Huong 26 27 21 20 32
- NA 10 18 10 8 29

- data:
  - address
  - data 1-5
  - 
- future agenda:
  - develop questionaire
  - a week depends on the fieldsite
  - ask for hot to intiate contact

## climate data class:
- heatwave:
  - prolonged period of abnormally hot weather
    - relative to the local climate norms
    -  often lasting multiple days
  - vary by region and organization
    - but generally emphasize **exceeding temperature thresholds**
    - for a **minimum duration,**
      - sometimes incorporating humidity or nighttime minima.
  - The World Meteorological Organization (WMO)
    - describes a heatwave as a period
    - where the daily maximum temperature
      - using a 1961–1990 baseline.



- project 4: download 6 station so to cover the entire taiwan
- FOCUS ON THE DATA first, after understand where the data is missing, then load the data into the code, then edit the code with deepseek
- start from project 1 to 5, one at a time, to see progression
- try to describe the dat
- after got the file from antigravity: use this to compare with the orignal file, ask what changes have been made, how to explain the main differences i made compare to the original file to my professor
- workflow to do:
  - keep opening the google collab, also check the scoretable and final result picture
  - try to open which "one" part of the code in charge of generate the plot
  - understand that and put it to the python
  - edit the python -> may be the most important is the data
  - after get the data, generate the chart and see what missing
  - edit with AI -> finally run with nvim -> don't focus on nvim too early
  - capture and submit
  - che

- BTC:
  - what skills do you need questions:
    - Mixed-Methods Research: To integrate quantitative (farmer surveys, service metrics) and qualitative (interviews, stakeholder mapping) data.
      - Global Climate Change" - WEI-TING CHEN -> i found this course will give me more context at high level like the course climate change and issue i took in the fall semester. but this course expect this course will have a higher level concept on global scale, with more context and 
      - "Climate change and extreme events - machine learning hands-on" - YU-CHIAO LIANG and MIN-HUI LO -> mention something about statistical and machine learning skill
      - "Introductory Statistics for Geosciences" - Department of Geosciences i also consider this course to the machine learning course above, but this will also give me concepts of geosciences, this will be useful for me for comprehensive understanding of earth system
      - "Computer Intensive Statistics in Ecology" - Available to Earth System Science, Oceanography, and other departments - i hope to achive the cocmputer skill and statistics skill in relate to ecology or biodiversity,...




- thesis:
  - try to frame: i'm focusing more on communication side rather than modelling -> as the audience (professors) will have background in atmospheric science so when talking about research about climate service try to frame it i'm about social science so it's more about social or communication side rather than doing modeling
  - 3 core inquiries:
    - 
  - data
    - primary data: unique year panel survey data colletion
    - what are climate services, temperture, precipitation - climate information - what are climate **variable** you are looking at.
      - salinity data: ob tain from 27 salinity stations from 20.. to 20.. obtain from southern center for hydro-meteological forecast center in VN
      - precipitation data: obatain from AgERA5
- giong lua co thay doi qua nhieu nam khong?




- https://garc.ntu.edu.tw/%e7%8d%8e%e5%8a%a9%e9%87%91/%e8%be%a6%e6%b3%95/ NTU Social science scholarship


- different objects layers, then climate service how are they play a role in this cross level
- thoi tiet


- 
- https://us.humankinetics.com/blogs/excerpt/major-movements
  - Major Movements
  - Although thousands of movements occur in a single tennis match, a certain number of movements are common to the sport of tennis. Becoming proficient in these major movements will help you become a better mover on the tennis court and therefore a better overall player. Training for tennis requires that you repeat good quality movement patterns on a regular basis. Having a clear understanding of the correct movement patterns and how best to train to improve them will speed your improvement and make you more efficient on the court. Over time it can also reduce the chance of injury resulting from inefficient movements, poor loading patterns, and overuse as a result of inappropriate mechanics.



- use AI to generate schematic AI figure, each  video file one figure
  - everything next friday
  - FIGURE => represent the content
  - represent the main concepts so the reader catch the main idea of the video
  - rearrange the excel later so look into the 5th video we just need to get the 10 second to 20 seconds
  - arrange video file


- A_0010D052H260410_訪問 羅敏輝教授-完整觀測資⋯.
- A_O010D051H260410_訪問 羅敏輝教授-完整觀測資..
- A_O010D050H260410_訪問 羅敏輝教授 陽明山測站⋯
- A_0010D047H260410_訪問 羅敏輝教授-雲霧對台灣⋯.
- A_0010D045H260410_1120315E_訪問 羅敏輝教授..
- A_0010D044H260410_111742J4_訪問 羅敏輝教授⋯
- A_0010D043H260410_111451E8_訪問 羅敏輝教授陽.⋯.
- A_0010D042H260410_111226FE_訪問 羅敏輝教授-⋯

- mermaid code
```mermaid
graph TD
    ROOT["📁 A206 專案資料夾"]

    ROOT --> F1["📁 20260422_Lama_CMIP7"]
    ROOT --> F2["📁 20260422_WL_present_discuss"]
    ROOT --> F3["📁 20260424_HHH_A206_interview"]
    ROOT --> F4["📁 20260424_MIPs_A206"]
    ROOT --> F5["📁 20260424_WL_A206_interview"]

    subgraph WL_present["📄 20260422_WL_present_discuss.docx — 約 10 支影片（039A5922–039A5931）"]
        direction TB

        subgraph 簡報主題["🟦 高解析度模式：颱風 vs. 聖音"]
            P1["🎬 039A5922 — 高解析度模式簡報\n報告者：李威良，中研院環境變遷中心"]
            P1 --> P1A["100km大氣＋100km海洋：颱風個數太少\n25km大氣＋10km海洋：颱風路徑模擬接近觀測"]
            P1 --> P1B["但高解析度海洋下，聖音訊號幾乎消失\n強度僅觀測值一半不到\n→ 聖音弱 → 極端天氣模擬連帶失真"]
        end

        subgraph 他國比較["🟩 國際比較與問題定位"]
            P2["🎬 039A5923–5924 — 他國模式是否有同問題？"]
            P2 --> P2A["各國模式也有高解析下聖音偏弱現象\n→ 他國認為「可接受」\n→ TaiESM 的弱化程度遠超他國，需列入改進"]
        end

        subgraph 原因推測["🟨 原因分析與診斷"]
            P3["🎬 039A5925–5928 — 可能原因討論"]
            P3 --> P3A["高解析海洋的 diffusivity（擴散率）過強\n→ 海溫熱點過於分散，ENSO 能量被耗散消散"]
            P3 --> P3B["25km＋10km 組合：聖音週期與強度均異常\n→ 需針對海洋 diffusivity 調整進行更多診斷研究"]
        end

        subgraph 總結討論["🟥 許晃雄討論（039A5931）"]
            P4["🎬 039A5931 — 問題確認與後續方向"]
            P4 --> P4A["過去少有人做高解析度海洋長期模擬\n→ 此問題從未被預期，目前仍在摸索調整方向"]
            P4 --> P4B["颱風模擬佳，但聖音太弱是重大氣候缺陷\n→ 列為後續重要改進項目"]
        end
    end

    subgraph MIPs["📄 20260424_MIPs_A206.docx — 1 支影片（約 8 分 47 秒）"]
        direction TB
        M1["🎬 A206_MIPs_討論會議\n00:00 – 08:47"]
        M1 --> M1A["00:00｜S1（威良）\nTaiESM 參與 CMIP7 耦合模式比對計畫\n目標：提供 IPCC AR7 科學證據"]
        M1 --> M1B["00:51｜S2\nCMIP6 回顧：HighResMIP、CFMIP、DAMIP\nControl Run / 4xCO2 / Historical 等模擬"]
        M1 --> M1C["02:30｜S2\nCMIP7 FastTrack 介紹\n截止：明年 3 月前繳交第一批資料\n採 Concentration Driven 方式"]
        M1 --> M1D["04:00｜S2\n計算資源費用估算\n全跑約 950 萬，優先 TaiESM2 PI Control Run\nTaiESM1=100元/年，TaiESM2=300元/年，HR=5500–6000元/年"]
        M1 --> M1E["06:13｜S3\n討論：TaiESM2 參與 MIPs 可讓國內學界更多人使用"]
        M1 --> M1F["06:44｜S5 提問\nFastTrack 是必跑的嗎？\n→ 必跑項目：DECK（含 1%CO2、4xCO2）＋ScenarioMIP"]
        M1 --> M1G["07:44｜S4\nGeoMIP / RFMIP 目前無人有興趣，不列入\n→ PMIP 待討論（康斯維有興趣）"]
        M1 --> M1H["08:14｜S3\n結語：第一段結束，第二段細討各 MIP 興趣"]
    end

    subgraph WL["📄 20260424_WL_A206_interview.docx — 12 支影片（C181–C192）"]
        direction TB

        subgraph 基礎概念["🟦 輻射基礎概念"]
            V1["🎬 C181 — 輻射是什麼？\n約 0:44\n問：輻射是什麼？太陽光進入大氣後怎麼了？"]
            V1 --> V1A["00:07｜黑體輻射：有溫度的物體就會放出輻射\n溫度越高，波長越短，越接近可見光"]
            V1 --> V1B["00:37｜太陽光的能量被雲、冰反射，大部分被地球系統吸收\n→ 地球溫度上升"]
            V2["🎬 C182 — 地表反照率與海冰\n約 1:12\n問：陽光打到陸地、冰、海有何不同？"]
            V2 --> V2A["00:17｜冰反照率約 90%；海洋反照率低於 10%\n→ 海冰量對地球升溫速率影響極大"]
            V2 --> V2B["00:57｜地球是太空中的孤立系統，對外交換能量只靠輻射\n→ 必須精確模擬輻射量才能知道地球增溫或降溫"]
            V2 --> V2C["01:38｜全球暖化主因：CO₂過多\nCO₂讓太陽光穿透，卻吸收地球放出的紅外線\n→ 像棉被，使地表持續升溫"]
        end

        subgraph TaiESM改進["🟩 TaiESM 輻射改進"]
            V3["🎬 C183 — TaiESM 地形輻射改進\n約 3:42\n問：你針對 TaiESM 輻射做了什麼改進？"]
            V3 --> V3A["00:16｜其他模式假設地表平坦，TaiESM 考慮山的向陽面/背陽面\n用蒙地卡羅模式計算地形間光子多次反射的影響"]
            V3 --> V3B["01:50｜反射次數越多，地表吸收能量越多（雪地低估增溫效果）\n→ TaiESM 可修正冷偏差約 25–30%"]
            V3 --> V3C["03:27｜一般模式的輻射計算方式\n大氣分多層，每層計算吸收率、反射率、穿透率\n依波段分別計算後加總"]
        end

        subgraph 模式開發["🟨 模式開發"]
            V4["🎬 C184 — 什麼是發展模式？（中途斷電）\n約 0:47\n問：什麼叫做「發展模式」？"]
            V4 --> V4A["00:17｜用物理化學方程式計算大氣如何隨時間演變\n→ 轉換成電腦程式讓電腦逐步積分計算（斷電中斷）"]
            V5["🎬 C185 — 模式開發：方程式→程式碼\n約 2:49\n重錄 C184 主題"]
            V5 --> V5A["00:14｜模式就像科學家的虛擬實驗室\n每人在方程式數位化時取捨不同，所以各國模式都不一樣"]
            V5 --> V5B["02:20｜建立模式是 60–70 年的累積\n從單層大氣 → 超過百萬個網格，加入雲、降水、化學、生物"]
            V5 --> V5C["02:20｜美國 NCAR 有超過 100 人開發模式\nTaiESM 成員不到 10 人，基於 CESM 做重要修改"]
        end

        subgraph 工作流程["🟧 跑模式的流程"]
            V6["🎬 C186 — 跑完模式後在做什麼？\n約 1:21\n問：程式送出去跑以後你在幹嘛？"]
            V6 --> V6A["00:08｜每次跑完調整設定（CO₂濃度、氣膠等）\n比對觀測：降水是否太多？溫度是否偏高偏低？"]
            V6 --> V6B["01:03｜壞掉時逐步檢查：程式有沒有寫錯？輸入設定是否正確？"]
        end

        subgraph 個人心路["🟥 個人心路歷程"]
            V7["🎬 C187 — 研究的意義（中途 NG）\n約 0:50\n問：有什麼讓你覺得得意的地方？"]
            V7 --> V7A["00:35｜被問到意義覺得難以回答，停下來思考（NG 片段）"]
            V8["🎬 C188 — 難忘的瞬間\n約 3:34\n問：有什麼讓你覺得很值得的瞬間？"]
            V8 --> V8A["00:15｜輻射改進 RUN 完後，向陽面果然收到更多陽光\n→ 理論在黑暗中摸索，結果出來是對的，很有成就感"]
            V8 --> V8B["01:43｜TaiESM 在東亞的極端降水與季風模擬比前人模式好\n→ 只是為了讓大氣層頂能量平衡，卻意外得到更好結果"]
            V8 --> V8C["03:08｜推測原因：印尼暖池的對流模擬做好\n→ 能量傳遞更接近真實，東亞模擬因此改善"]
        end

        subgraph 科學影響["🟪 科學影響與 IPCC"]
            V9["🎬 C189 — TaiESM 與未來氣候推估\n約 1:21\n問：TaiESM 模擬的未來是什麼樣子？"]
            V9 --> V9A["01:10｜TCCIP 等單位使用 TaiESM 資料做更高解析度模擬\n→ 初始條件越好，應用端結果越接近真實"]
            V10["🎬 C190 — 物理過程與對流觸發機制\n約 3:42\n問：TaiESM 做了什麼讓它表現得不錯？"]
            V10 --> V10A["00:39｜好的模式在能量從低緯傳送到高緯的細微差別中可見高下\nTaiESM 在這些細微地方表現不錯"]
            V10 --> V10B["02:31｜對流觸發機制（Convective trigger）\n原本只要地表夠熱就觸發對流，TaiESM 加入逆溫層條件\n→ 對流發生時間更符合真實，改善 TaiESM-1 前身 CSM-1 的問題"]
            V11["🎬 C191 — 模式是科學家的手工藝 ＋ IPCC\n約 3:29\n問：地球系統模式很像科學家的手工藝？"]
            V11 --> V11A["00:18｜每個國家/單位的模式就像手工藝，強調的重點不同\n→ 各有優勢，沒有絕對好壞"]
            V11 --> V11B["01:50｜IPCC Report = 氣候變遷評估報告\n量化計算未來氣候：CO₂加倍時地球升溫 1.5–3°C 的依據"]
            V12["🎬 C192 — 系集模擬\n約 2:49\n問：各虛擬實驗室結果不同，IPCC 怎麼看？"]
            V12 --> V12A["00:22｜系集方式①：改變初始條件跑多次後平均\n系集方式②：不同物理模式的結果平均（多模式系集）"]
            V12 --> V12B["00:22｜系集平均的確比單一模式好\n確切原因未知，推測：各模式考慮的物理面向不同\n→ 合起來才更完整"]
        end
    end

    subgraph HHH["📄 20260424_HHH_A206_interview.docx — 10 支影片（C171–C180）"]
        direction TB

        subgraph 地球系統["🟦 地球系統模式概念"]
            H1["🎬 C171 — 什麼是地球系統模式？\n問：地球系統模式是什麼？"]
            H1 --> H1A["五大圈：大氣、海洋、岩石、冰雪圈、生物圈\n＋人類圈（最邪惡的一圈，造成全球暖化）\n→ 像虛擬電腦遊戲，給不同情境就得不同氣候"]
            H2["🎬 C172 — 為何須耦合模擬？\n問：為何不能只模擬大氣？"]
            H2 --> H2A["聖音（ENSO）現象說明大氣⇌海洋⇌陸地必須耦合\n→ 植被、土壤蒸發、降水、海溫彼此環環相扣\n缺少任一圈，模擬就失真"]
            H3["🎬 C173 — 聖音的回饋機制\n問：回饋到大氣是怎麼回饋法？"]
            H3 --> H3A["東太平洋海溫暖→水蒸氣↑→對流旺盛→西風強度變化\n→ 引發海洋波動→聖音發生\n→ 大氣與海洋必須互相交換訊息（耦合）"]
        end

        subgraph 高解析挑戰["🟧 高解析度的挑戰"]
            H4["🎬 C174 — 高解析度下聖音消失\n問：高解析聖音不見的影響與原因？"]
            H4 --> H4A["100km → 10km 後，聖音由過強變極弱甚至消失\n→ 聖音是全球最重要海洋氣候現象，消失則年際降雨模擬錯誤"]
            H4 --> H4B["全世界模式團隊皆有此困擾，目前無好答案\n→ 擬召集國際知名氣候模式團隊定期研討，共同解決"]
            H5["🎬 C175 — 模式推估未來氣候\n問：模式推估未來與現實觀測有何關連？"]
            H5 --> H5A["目前趨勢朝 21 世紀末升溫 2.5–3°C\n模式過去趨勢與觀測接近，但無法捕捉聖音發生時間點"]
            H5 --> H5B["氣溫變化是量子化跳躍（非平滑）\n聖音後溫度跳上去就不易回落\n→ 現有模式可能低估暖化幅度；2026–2027 或有超強聖音"]
        end

        subgraph TaiESM發展["🟩 TaiESM 發展歷程"]
            H6["🎬 C176 — 為何發展 TaiESM？\n問：為什麼要發展 TaiESM？"]
            H6 --> H6A["台灣過去幾乎沒有氣候模式，落後日韓中更遑論歐美\n2011 年國科會提供契機，決定以 CESM 為基礎自行改造\n→ 不只是使用者，更要成為開發者，建立台灣品牌"]
    - regulation: standard method for unify differnt way, -> help compare differnt way..
    - cliame change specialist: consider scenarios in future projection for a project in addtion to current time consideration from different specialist


CHES PET
  Cultural

  Historical

  Environmental

  Social

  Technological

  Political

  Economic




- today:
  - monday class BTC
  - seminar thesis sharing
  - send report to professor every saturday
  - goo

- ideas sharing:
  - good starting point: https://www.perplexity.ai/search/i-need-to-do-research-about-cl-nVtr6gXkQ8.LruKrrtvuag#0

- learn about something, actively search for news, real case for example
- transcription model: TODO
  - improve accuracy
  - more detail(number, )
  - explain how did i come up with this results
    - so i 
  - focus on one dimension, dig deeper, focus on one or two
  - more paper
  - explain figure 1 more

- transcription:
  - check words, findlink

- interview with RTI:
  - potential market for carbon credit verification 3rd party man power: need to go to developing country to verify
- next week present

- what topic
- context
- issue, why important => research question
- theory
  - 1 concept should be enough
- don't explain method

* question from monday class could use for the thesis: Using a specific, real-world example, illustrate the social or historical mechanisms that systematically place certain groups at a disproportionately greater risk.



- 

---

## principles
[writing](riting)

---
```keep this part no more than 5 lines
- want to good at something? PRACTICE PRACTICE PRACTICE!!
- if you can't categorize, tag the ideas, you're not understanding it
- do project(program) along category(package) <- intermediate packets
workflow -> write lessons in vim -> move the most important points into ~/v 
write lessons in vim is a must do -> it's help me to think (think of days that i skip d:quickjkjoing this because of being lazy
the learning progress is becoming stagnant
```
