# 114-1 電腦視覺與深度學習 (Computer Vision and Deep Learning)

本 Repository 用於存放 **114 學年度第 1 學期**「電腦視覺與深度學習」課程的相關內容，主要包含課程作業與專案的實作檔案。

---

## 📚 課程資訊 (Course Information)

* **課程名稱 (Course Name):** 電腦視覺與深度學習 (Computer Vision and Deep Learning)
* **學期 (Semester):** 114 學年度第 1 學期

---

## 📂 檔案結構說明 (Repository Structure)

本 Repository 的檔案結構主要依照作業或專案進行分類。

```

.
├── HW01/                   \# 第一次作業 (Homework 01)
│   ├── HW01\_YourStudentID.ipynb  \# 作業主要的 Colab Notebook 檔案
│   └── requirements.txt        \# 該作業所需的套件需求檔案
├── HW02/                   \# 第二次作業 (Homework 02)
│   ├── HW02\_YourStudentID.ipynb
│   └── requirements.txt
├── FinalProject/           \# 期末專案 (Optional)
│   ├── FinalProject\_Report.ipynb
│   └── requirements.txt
└── README.md

````

### 核心內容說明：

1.  **作業資料夾 (`HWXX/` 或 `Project/`):** 每個資料夾代表一個獨立的作業或專案。
2.  **Colab Notebook 檔案 (`.ipynb`):**
    * 主要為在 Google Colaboratory 上完成的實作程式碼。
    * 通常包含實驗步驟、模型訓練、結果分析等。
    * **命名慣例建議:** `HWXX_YourStudentID.ipynb` (例如: `HW01_B11499001.ipynb`)
3.  **需求檔案 (`requirements.txt`):**
    * 記錄該作業 Notebook 執行所需的所有 Python 套件及其版本。
    * 方便在本地端或不同環境中重現實驗結果。
    * 您可以使用以下指令來安裝所需的環境：
        ```bash
        pip install -r HWXX/requirements.txt
        ```

---

## 🚀 環境與執行 (Environment and Execution)

大部分的作業都是設計在 **Google Colaboratory** 環境下執行，以利用其提供的免費 GPU/TPU 資源。

### 使用步驟：

1.  **開啟 Colab:** 登入 Google 帳號並將對應的 `.ipynb` 檔案上傳至 Colab 環境。
2.  **安裝套件:** 在 Notebook 的開頭通常會有安裝必要套件的儲存格。若有 `requirements.txt`，請確保 Notebook 內部的安裝指令與之對應，或者手動確認所有依賴項已安裝。
3.  **執行:** 依序執行 Notebook 中的儲存格，完成作業要求。

---

*最後更新日期: 2025 年 10 月 15 日*
