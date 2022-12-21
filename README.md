# PL-Repo
### (2022) Learning programing language in NTNU

### 111-1 師大科技系程式語言  
授課教師：蔡芸琤   
姓名：蔡昱宏  
系級：校外選讀生

## 課程筆記區
#### W2 class
* Solve Code Problems Like an Engineer(most important): [GeekforGeeks](https://www.geeksforgeeks.org/), [StackOverflow](https://stackoverflow.com/)
* Sync files between local and GitHub: use [GitHub Desktop](https://desktop.github.com/)
* Python's code: data type(int, float, str, bool), if and else, input, print, **while and break**, **datetime(module)**
* Exercise: [0915 W2 class](https://github.com/AndersonTsaiTW/PL-Repo/tree/main/01_Notes/exercise_0915_02of16)
* 其他練習: [遲繳罰金計算機(可輸入金額、繳納時間，利率錯誤防呆機制)](https://github.com/AndersonTsaiTW/PL-Repo/blob/main/01_Notes/exercise_0915_02of16/fee_calaulator.ipynb)
#### W3 class
* Find a scene for database operations: intersection, union, difference, symmetric_differen
* Python's code:pandas(different, load_csv)
#### W4 class
* Python's code:enumerate(將給定序號成為配對結構), sorted(x1, key = lambda s: s[1])(x1為配對數列，lambda為虛擬表示法，透過s[1]表達“依每個配對數列的第2個(因為第一個是0)數列資訊來排序”)
* dictionary應用：[點菜計算機(可自動計算等餐時間、卡洛里、總價)](https://github.com/AndersonTsaiTW/PL-Repo/blob/main/01_Notes/exercise_0929_04of16/EX1_dictionary.ipynb)、[交通違規練習(單一字典及多功函數架構)](https://github.com/AndersonTsaiTW/PL-Repo/blob/main/01_Notes/exercise_0929_04of16/EX2_PairPrograming.ipynb)
#### w5 class
* use "peer assessment" to read otherone's code
* csv to dataframe, json to dictionary
* new datatype:json("import json" and use "json.load") 
#### w6 class
* regular expression: [introduce](http://perso.ens-lyon.fr/lise.vaudor/strings-et-expressions-regulieres/?fbclid=IwAR0IHvNKp43Qrfo0TqpolYPpMUfViSrCBDY8SmBveKm01yZ6PzHPxspVaNI), [tools](https://regexr.com/)
* [json data structure visualizer](https://jsoncrack.com/editor)
* Python's code: .get(import json), re("import re", search, group, findall, sub, split, compile)
#### w7 class
* [nbviewer](https://nbviewer.org/): when your can't open your jupyter doc, try this
* [大數軟體_爬蟲教學](https://www.youtube.com/playlist?list=PLohb4k71XnPaQRTvKW4Uii1oq-JPGpwWF)
* [VS Code](https://code.visualstudio.com/)
#### w8 class
* Python's code: dataframe(eval, append, loc, linc, str.contains)
* [Plotly](https://plotly.com/python/)
#### w9 class
* text mining: [LDA ref](https://medium.com/%E5%B0%8F%E8%94%A3%E7%9A%84%E8%B3%87%E6%96%99%E7%A7%91%E5%AD%B8%E5%B0%8F%E5%A4%A9%E5%9C%B0/%E6%96%87%E5%AD%97%E6%8E%A2%E5%8B%98-lda-latent-dirichlet-allocation-topic-model-a5001afdca34), [TextRank](https://danjtchen.medium.com/textrank-%E6%96%87%E5%AD%97%E6%8E%A2%E5%8B%98-%E6%89%BE%E5%87%BA%E9%97%9C%E9%8D%B5%E5%AD%97-%E4%BB%A5-%E5%85%AB%E5%8D%A6%E7%89%88%E6%A8%99%E9%A1%8C%E7%82%BA%E4%BE%8B-b16620370872), [hyphenation](https://peilee-98185.medium.com/python-%E5%A5%97%E4%BB%B6%E6%AF%94%E8%BC%83-%E7%B9%81%E9%AB%94%E4%B8%AD%E6%96%87%E6%96%B7%E5%AD%97-4e7a452138f8), [other ref](https://github.com/lining0806/TextMining), [Jieba說明](https://github.com/fxsjy/jieba)
#### w10 class
* Speech of Bass: 矽谷職場生存三部曲：愛拚不會贏，愛說才會！[(簡易筆記)](https://medium.com/@andersontsaitw/bass-anthropological-observations-in-silicon-valley-90a440186714)
#### w12 class
* UI/UX and full stake
* golden rule: Why, How, What
## 作業連結區
* [HW1-台鐵各車站使用分析](https://github.com/AndersonTsaiTW/PL-Repo/blob/main/02_Homework/HW1/stations_analysis.ipynb)：演示交集、聯擊、差集及對稱差集
  1. 找出一段時間內無人使用的車站
  2. 衍生應用：讓使用者可自行輸入日期區間及日使用人次標準，找出不合標準的車站，以考慮是否汰除
* [HW2-休閒農場_行程建議產生器](https://github.com/AndersonTsaiTW/PL-Repo/blob/main/02_Homework/HW2/FarmStay.ipynb)：演示查詢及排序
  1. 應用一：使用者可依照區域查詢休閒農場，將協助依預定費用排序，協助挑選農場
  2. 應用二：若已經確定想去的第一個農場，將依據直線距離遠近，額外推薦5家鄰近農場，協助規劃休閒農場系列之旅
* [HW3-ptt movie版爬蟲(基本版)](https://github.com/AndersonTsaiTW/PL-Repo/blob/main/02_Homework/HW3/ptt_movie.ipynb)、[小李飛刀爬蟲(進階版：user-agent使用、自動換頁、章節對照)](https://github.com/AndersonTsaiTW/PL-Repo/blob/main/02_Homework/HW3/GuLong_crawler.ipynb)
* [HW4-多情劍客無情劍_探勘古龍文字寫作](https://medium.com/@andersontsaitw/%E5%A4%9A%E6%83%85%E5%8A%8D%E5%AE%A2%E7%84%A1%E6%83%85%E5%8A%8D-%E6%8E%A2%E5%8B%98%E5%8F%A4%E9%BE%8D%E6%96%87%E5%AD%97%E5%AF%AB%E4%BD%9C-ad976a7760ef)：[程式碼參照](https://github.com/AndersonTsaiTW/PL-Repo/blob/main/02_Homework/HW4%265/GLandJY.ipynb)
* [HW5-多情劍客無情劍_探勘古龍文字寫作_part2](https://medium.com/@andersontsaitw/aa91d8bd289b)：[程式碼參照](https://github.com/AndersonTsaiTW/PL-Repo/blob/main/02_Homework/HW4%265/GLandJY_up.ipynb)
## 專題連結區
#### 『那個鐵達尼號乘客』(Dragon、EK、Anderson)
  1. [GitHub專案位置](https://github.com/BonBa2K/PL_project_tatanic)
  2. [資料分析程式碼](https://github.com/AndersonTsaiTW/PL-Repo/blob/main/03_topic/Titanic_data_analysis_v1.ipynb)
  3. [預測建模程式碼](https://github.com/AndersonTsaiTW/PL-Repo/blob/main/03_topic/Titanic_model_v1.ipynb)  
  2022/12/22的成績
  <img width="1506" alt="image" src="https://user-images.githubusercontent.com/113076298/208964322-4e6a2fdb-c7bd-456f-83f9-67b6705dbb66.png">

## 其他補充
[Classmates List](https://docs.google.com/spreadsheets/d/1hRIOovstwJst0SXgM_bogjYsrHLVZv4uVOkmYrgbql0/edit#gid=948403574)
