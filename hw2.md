### hw2
```mermaid
gantt
    title 專案進度
    dateFormat X
    axisFormat  %d天
    section 研擬計畫
    1    :des1, 2024-01-01, 1d

    section 任務分配
    2    :des2, after des1, 4d

    section 取得硬體
    3    :des3, after des1, 17d

    section 程式開發
    4    :des4, after des2, 70d

    section 安裝硬體
    5    :des5, after des3, 10d

    section 程式測試
    6    :des6, after des4, 30d

    section 撰寫使用手冊
    7    :des7, after des5, 25d

    section 轉換檔案
    8    :des8, after des5, 20d

    section 系統測試
    9    :des9, after des6, 25d

    section 使用者訓練
    10   :des10, after des7 des8, 20d

    section 使用者測試
    11   :des11, after des9 des10, 25d
```


