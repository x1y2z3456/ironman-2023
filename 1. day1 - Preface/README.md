# [Day1] 緣起

Author: Nick Zhuang
Type: AI & Data

![1694321355125](image/README/1694321355125.png)
這是一張利用Stable Diffusion生成的圖片，蒸氣龐克的風格，歡迎大家進入AIGC的世界。

## 提要

- [整體大綱](#整體大綱)
- [前情提要](#前情提要)
- [補充章節](#補充章節)
- [適用對象](#適用對象)

## 整體大綱

本次參賽，預計攻克篇幅如下，共計30篇，以下是進行的內容。

1. 緣起
2. 先來了解AIGC是什麼東東
   - AIGC的定義
   - AIGC的意義：PGC → UGC → AIGC
3. AIGC的特色與應用
   - AIGC的特色
   - AIGC的應用
4. AIGC的演進
   - VAE
   - GAN
   - PixelRNN
   - Flow
   - Diffusion
   - Transformer
   - Nerf
   - CLIP
5. VAE原理
   - 什麼是自編碼器
   - 自編碼器的種類
   - 自編碼器的各種用途
6. GAN原理
   - 什麼是GAN
   - GAN的種類
   - GAN的各種用途
7. PixelRNN原理
8. Diffusion原理
9. Flow原理
10. Transformer原理
    - 什麼是Transformer
    - Transformer的由來
    - 近年來Transformer的演進
11. Nerf原理
12. CLIP原理
13. 生成式圖像工具介紹
14. Stable Diffusion原理
15. Dreambooth原理
16. LORA原理
17. ControlNet原理
18. Super Resolution - SwinIR
19. SD的安裝教學，介面總覽
20. SD生成模式介紹與使用一（常見功能）
21. SD生成模式介紹與使用二（進階功能）
22. SD生成模式介紹與使用三（推薦插件之一）
23. SD生成模式介紹與使用三（推薦插件之二）
24. CivitAI介紹-模型來源
    1. 模型可以應用的常見種類
    2. 套用與下載位置
25. 訓練Checkpoint方式
26. 訓練Lora方式
27. Embedding
28. Hyper parameter network
29. SD XL介紹
30. 總結與完賽心得

## 前情提要

近年來，隨著生成式AI的崛起，基礎知識及其對應的應用方向也蔚成顯學，因應數位轉型的Side Project需求，筆者近期開始研究關於AIGC的內容，為了能夠幫助大家快速了解其中的內容，因此有了本次參賽的想法，能夠一次把AIGC的結構梳理清楚。
如上述所示，可以看到內容其實非常多，要看超級多的paper，我會帶大家把基礎知識重新走一遍，然後才會帶到主軸Stable Diffusion的內容，所以以下的文章會以能夠解釋Stable Diffusion原理及應用為主，其中也涵蓋該軟體的詳細操作。
有試過的朋友應該都可以理解，Stable Diffusion中能操作的項目非常之多，觀念細部探究也非常之深，希望能幫助到大家，這系列文不是給大神看的，我也不是大神，其中敘述不夠精確之處還請大家包涵，在每篇文章多少都會些有批判性思考的論述環節，這也是跟直接用ChatGPT生出的內容有極大不同之處，期許自己能順利完成，讓大家都能理解和喜歡AIGC相關的知識及奧妙之處。

## 補充章節

如果這系列文有得獎的話，會再加至少五篇的內容（為保障品質，不會每日更）
我會再嘗試探討幾個面向以補足既有方面的不足，簡述如下：

1. AIGC的道德倫理相關探討內容
2. AIGC與AGI的差異，及近期AGI的發展與演進
3. AIGC延伸內容；例如，LLM相關的(文字生成)

後續為保障內容易於理解，所以幾乎不會放公式那些，我會提到一些，但會著重在講解這些公式的用途與意義。
也不會放數學證明，這不是理論課，真有需要再另外開版，我是覺得沒人想看這種XD。
知識如果不能應用的話，那就只是知識而已，知識要能很好地應用，才能轉化成人的智慧，是謂智人。（不是名言，我說的XDD）

## 適用對象

如果你是AI小白，可以放心服用，不會講一堆囉哩八唆的。
如果你有點程度，這系列文已經把相關文章及論文整理好了，可以按照自己的進度服用。
如果你是大神，筆者也還在學習中，歡迎多交流，不吝分享您的知識。

如果你是工程師，你將會知道架設環境的方式及該如何使用。
如果你是PM（Project Manager），你將會知道哪些地方可以使用這個東西，減少跨部門的溝通成本。
如果你是技術主管，你將會知道近期生成式AI的發展，並將其想法研擬成研發計畫。
如果你是企業主，你將能了解生成式AI與你的企業願景是否契合，評估是否要導入AIGC等問題。

## 小結

本日介紹了預計30天的大綱內容，希望可以順利趕稿成功XD，帶給大家深入淺出的內容，明天見！

## 參考連結

- [Cyberpunk Street Scene - cyberpunk scene v1.0 by Tooimage](https://civitai.com/posts/214522)
- [Challenges and Applications of Large Language Models](https://arxiv.org/pdf/2307.10169.pdf)
