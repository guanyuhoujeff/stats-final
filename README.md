# 投資組合分析 Python 入門教材

本專案為高科大財管系114學年統計學(一)期末報告程式碼，內容為初學者使用 Python 進行基本的股票數據分析與投資組合管理。


## 課程資訊

- **學校:** 國立高雄科技大學
- **系所:** 財務管理系
- **學年度:** 114學年上學期
- **課程:** 統計學(一)
- **授課老師:** 侯冠宇
- **聯絡方式:** jeff7522553@gmail.com

## 檔案結構

- `investment_analysis_tutorial.ipynb`：主要的 Jupyter Notebook 教學檔案。
- `tw-price.csv`：包含三支台股歷史股價的資料檔案。
- `requirements.txt`：執行此專案所需的 Python 相依套件。
- `README.md`：本說明檔案。

## 如何使用

您可以選擇在您的本機電腦上或使用 Google Colab 來執行此教學。

### 1. 本機端執行

**事前準備：**
請確認您的電腦已安裝 [Python](https://www.python.org/downloads/) 與 [Jupyter Notebook](https://jupyter.org/install)。

**步驟：**
1. 下載本專案的所有檔案。
2. 開啟終端機 (Terminal) 或命令提示字元 (Command Prompt)，移動到專案資料夾底下。
3. 執行以下指令安裝所需的 Python 套件：
   ```bash
   pip install -r requirements.txt
   ```
4. 安裝完成後，啟動 Jupyter Notebook：
   ```bash
   jupyter notebook
   ```
5. 在開啟的瀏覽器頁面中，點擊並開啟 `investment_analysis_tutorial.ipynb` 檔案即可開始學習。

### 2. 在 Google Colab 中開啟

您也可以使用免費的 Google Colab 雲端環境來執行此筆記本，無需在本機安裝任何軟體。

**步驟：**
1. 前往 [Google Colab](https://colab.research.google.com/)。
2. 在彈出視窗中選擇「上傳」分頁，或點擊左上角 `檔案 > 上傳筆記本`。
3. 將 `investment_analysis_tutorial.ipynb` 檔案拖曳或選擇上傳。
4. **上傳資料檔**：筆記本成功開啟後，點擊左側的「檔案」圖示打開檔案總管。點擊「上傳至工作階段儲存空間」圖示，並選擇 `tw-price.csv` 檔案上傳。
   > **注意：** 請確保 `tw-price.csv` 與筆記本在同一個目錄層級，否則筆記本中的讀取路徑會找不到檔案。

5. 現在您可以從頭開始執行每個儲存格，進行學習。

## 相依套件

本專案的程式碼依賴以下 Python 套件：

- `pandas`
- `numpy`
- `matplotlib`

您可以使用 `requirements.txt` 檔案來快速安裝它們。

## 著作權

© 2025 侯冠宇. All Rights Reserved.

本教材僅供「國立高雄科技大學 財務管理系 統計學(一)」課程教學使用，未經作者書面同意，不得以任何形式複製、轉載或散布。