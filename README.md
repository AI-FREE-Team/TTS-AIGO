# 語音合成(Speech Synthesis)

## 執行程式碼的必備條件
1. 取得 LJ Dataset
點此[連結](https://keithito.com/LJ-Speech-Dataset/)，取得 LJ Dataset。

2. 取得預訓練模型(Pretrained Models)
點此[連結](https://drive.google.com/drive/u/3/folders/1FhLjoT3FdTdo2b_sYziOcy59YURC4v59)，下載範例程式碼(`Text-to-Speech.ipynb`)會用到的預訓練模型

3. 取得本專案開源程式碼
```
git clone https://github.com/AI-FREE-Team/TTS-AIGO.git
```

## 緣起
民國110年，於AIGO媒合賽中與財團法人原住民族語言研究發展基金會合作，共同打造文字轉語音系統(Text-to-Speech, TTS)。

## 專案內容
針對 `Text_to_Speech_for_(Google Colab/ TWCC).ipynb`:
* 第一部分: 簡介 Nemo 與 TTS 任務
* 第二部分: 資料前處理
* 第三部分: 模型訓練
* 第四部份: 模型推論
* 第五部分: 模型推論(針對太魯閣族語音生成)
* 第六部分: 引用

# 補充內容
若使用 TWCC 作為執行環境(特別是用於模型訓練階段)，可參考 `slides/TWCC: 建立開發型容器.pptx` 與 `slides/TWCC: 將檔案上傳到指定目錄.pptx`，完成基本設置。並參考 `Text_to_Speech_for_TWCC.ipynb`。

# 參考資源
* [Nvidia NeMo](https://docs.nvidia.com/deeplearning/nemo/user-guide/docs/en/stable/tts/intro.html)
* [原語會族語樂園](https://web.klokah.tw/essay/)
* [LJ Dataset](https://keithito.com/LJ-Speech-Dataset/)