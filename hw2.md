### hw2
```mermaid


gantt
    title 專案進度
    dateFormat YYYY-MM-DD

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

```mermaid
graph LR;
    subgraph "需求分析"
        direction TB
        B1["<table border='1' cellspacing='0' cellpadding='10' style='width: 100%;'>
            <tr>
                <td style='text-align: center;'>2024-01-01</td>
                <td style='text-align: center;'>1</td>
            </tr>
            <tr>
                <td style='text-align: center;'>2024-01-05</td>
                <td style='text-align: center;'>5天</td>
            </tr>
        </table>"]
    end

    subgraph "系統設計"
        direction TB
        C1["<table border='1' cellspacing='0' cellpadding='10' style='width: 100%;'>
            <tr>
                <td style='text-align: center;'>2024-01-06</td>
                <td style='text-align: center;'>2</td>
            </tr>
            <tr>
                <td style='text-align: center;'>2024-01-09</td>
                <td style='text-align: center;'>3天</td>
            </tr>
        </table>"]
    end

    subgraph "撰寫程式碼"
        direction TB
        D1["<table border='1' cellspacing='0' cellpadding='10' style='width: 100%;'>
            <tr>
                <td style='text-align: center;'>2024-01-10</td>
                <td style='text-align: center;'>3</td>
            </tr>
            <tr>
                <td style='text-align: center;'>2024-01-20</td>
                <td style='text-align: center;'>10天</td>
            </tr>
        </table>"]
    end

    subgraph "單元測試"
        direction TB
        E1["<table border='1' cellspacing='0' cellpadding='10' style='width: 100%;'>
            <tr>
                <td style='text-align: center;'>2024-01-10</td>
                <td style='text-align: center;'>4</td>
            </tr>
            <tr>
                <td style='text-align: center;'>2024-01-14</td>
                <td style='text-align: center;'>4天</td>
            </tr>
        </table>"]
    end

    subgraph "整合測試"
        direction TB
        F1["<table border='1' cellspacing='0' cellpadding='10' style='width: 100%;'>
            <tr>
                <td style='text-align: center;'>2024-01-21</td>
                <td style='text-align: center;'>5</td>
            </tr>
            <tr>
                <td style='text-align: center;'>2024-01-23</td>
                <td style='text-align: center;'>2天</td>
            </tr>
        </table>"]
    end

    subgraph "部署"
        direction TB
        G1["<table border='1' cellspacing='0' cellpadding='10' style='width: 100%;'>
            <tr>
                <td style='text-align: center;'>2024-01-24</td>
                <td style='text-align: center;'>6</td>
            </tr>
            <tr>
                <td style='text-align: center;'>2024-01-27</td>
                <td style='text-align: center;'>3天</td>
            </tr>
        </table>"]
    end

    subgraph "完成"
    end

    A --> B1 --> C1 --> D1 --> F1 --> G1 --> H;
    C1 --> E1 --> F1;


```
<div style="display: flex; align-items: center; justify-content: center; flex-direction: column;">
    <div style="text-align: center; font-size: 20px; margin-bottom: 10px;">任務名稱 1</div>
    <table border="1" cellspacing="0" cellpadding="10" style="width: auto; display: inline-table;">
        <tr>
            <td style="text-align: center;">開始時間: 2024-01-01</td>
            <td style="text-align: center;">任務編號: 1</td>
        </tr>
        <tr>
            <td style="text-align: center;">結束時間: 2024-01-05</td>
            <td style="text-align: center;">需求時間: 5天</td>
        </tr>
    </table>
    <span style="font-size: 24px;">&#8594;</span>
</div>

<div style="display: flex; align-items: center; justify-content: center; flex-direction: column;">
    <div style="text-align: center; font-size: 20px; margin-bottom: 10px;">任務名稱 2</div>
    <table border="1" cellspacing="0" cellpadding="10" style="width: auto; display: inline-table;">
        <tr>
            <td style="text-align: center;">開始時間: 2024-01-06</td>
            <td style="text-align: center;">任務編號: 2</td>
        </tr>
        <tr>
            <td style="text-align: center;">結束時間: 2024-01-10</td>
            <td style="text-align: center;">需求時間: 4天</td>
        </tr>
    </table>
    <span style="font-size: 24px;">&#8594;</span>
</div>

<div style="display: flex; align-items: center; justify-content: center; flex-direction: column;">
    <div style="text-align: center; font-size: 20px; margin-bottom: 10px;">任務名稱 3</div>
    <table border="1" cellspacing="0" cellpadding="10" style="width: auto; display: inline-table;">
        <tr>
            <td style="text-align: center;">開始時間: 2024-01-11</td>
            <td style="text-align: center;">任務編號: 3</td>
        </tr>
        <tr>
            <td style="text-align: center;">結束時間: 2024-01-15</td>
            <td style="text-align: center;">需求時間: 4天</td>
        </tr>
    </table>
    <span style="font-size: 24px;">&#8594;</span>
</div>

<div style="display: flex; align-items: center; justify-content: center; flex-direction: column;">
    <div style="text-align: center; font-size: 20px; margin-bottom: 10px;">任務名稱 4</div>
    <table border="1" cellspacing="0" cellpadding="10" style="width: auto; display: inline-table;">
        <tr>
            <td style="text-align: center;">開始時間: 2024-01-16</td>
            <td style="text-align: center;">任務編號: 4</td>
        </tr>
        <tr>
            <td style="text-align: center;">結束時間: 2024-01-20</td>
            <td style="text-align: center;">需求時間: 5天</td>
        </tr>
    </table>
    <span style="font-size: 24px;">&#8594;</span>
</div>

<div style="display: flex; align-items: center; justify-content: center; flex-direction: column;">
    <div style="text-align: center; font-size: 20px; margin-bottom: 10px;">任務名稱 5</div>
    <table border="1" cellspacing="0" cellpadding="10" style="width: auto; display: inline-table;">
        <tr>
            <td style="text-align: center;">開始時間: 2024-01-21</td>
            <td style="text-align: center;">任務編號: 5</td>
        </tr>
        <tr>
            <td style="text-align: center;">結束時間: 2024-01-25</td>
            <td style="text-align: center;">需求時間: 5天</td>
        </tr>
    </table>
</div>

<table border="1" cellspacing="0" cellpadding="10" style="width: 100%;">
    <tr>
        <td colspan="2" style="text-align: center; font-size: 20px;">大方格</td>
    </tr>
    <tr>
        <td style="text-align: center;">1</td>
        <td style="text-align: center;">2</td>
    </tr>
    <tr>
        <td style="text-align: center;">3</td>
        <td style="text-align: center;">4</td>
    </tr>
</table>
