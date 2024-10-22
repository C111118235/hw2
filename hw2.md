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
    subgraph "研擬計畫"
        direction TB
        T1["<table border='1' cellspacing='0' cellpadding='10' style='width: 100%;'>
            <tr>
                <td style='text-align: center;'>2024-01-01|</td>
                <td style='text-align: center;'>1</td>
            </tr>
            <tr>
                <td style='text-align: center;'>2024-01-02|</td>
                <td style='text-align: center;'>1天</td>
            </tr>
        </table>"]
    end

    subgraph "任務分配"
        direction TB
        T2["<table border='1' cellspacing='0' cellpadding='10' style='width: 100%;'>
            <tr>
                <td style='text-align: center;'>2024-01-02|</td>
                <td style='text-align: center;'>2</td>
            </tr>
            <tr>
                <td style='text-align: center;'>2024-01-06|</td>
                <td style='text-align: center;'>4天</td>
            </tr>
        </table>"]
    end

    subgraph "取得硬體"
        direction TB
        T3["<table border='1' cellspacing='0' cellpadding='10' style='width: 100%;'>
            <tr>
                <td style='text-align: center;'>2024-01-02|</td>
                <td style='text-align: center;'>3</td>
            </tr>
            <tr>
                <td style='text-align: center;'>2024-01-19|</td>
                <td style='text-align: center;'>17天</td>
            </tr>
        </table>"]
    end

    subgraph "程式開發"
        direction TB
        T4["<table border='1' cellspacing='0' cellpadding='10' style='width: 100%;'>
            <tr>
                <td style='text-align: center;'>2024-01-06|</td>
                <td style='text-align: center;'>4</td>
            </tr>
            <tr>
                <td style='text-align: center;'>2024-03-15|</td>
                <td style='text-align: center;'>70天</td>
            </tr>
        </table>"]
    end

    subgraph "安裝硬體"
        direction TB
        T5["<table border='1' cellspacing='0' cellpadding='10' style='width: 100%;'>
            <tr>
                <td style='text-align: center;'>2024-01-19|</td>
                <td style='text-align: center;'>5</td>
            </tr>
            <tr>
                <td style='text-align: center;'>2024-01-29|</td>
                <td style='text-align: center;'>10天</td>
            </tr>
        </table>"]
    end

    subgraph "程式測試"
        direction TB
        T6["<table border='1' cellspacing='0' cellpadding='10' style='width: 100%;'>
            <tr>
                <td style='text-align: center;'>2024-03-15|</td>
                <td style='text-align: center;'>6</td>
            </tr>
            <tr>
                <td style='text-align: center;'>2024-04-14|</td>
                <td style='text-align: center;'>30天</td>
            </tr>
        </table>"]
    end

    subgraph "撰寫使用手冊"
        direction TB
        T7["<table border='1' cellspacing='0' cellpadding='10' style='width: 100%;'>
            <tr>
                <td style='text-align: center;'>2024-01-29|</td>
                <td style='text-align: center;'>7</td>
            </tr>
            <tr>
                <td style='text-align: center;'>2024-02-23|</td>
                <td style='text-align: center;'>25天</td>
            </tr>
        </table>"]
    end

    subgraph "轉換檔案"
        direction TB
        T8["<table border='1' cellspacing='0' cellpadding='10' style='width: 100%;'>
            <tr>
                <td style='text-align: center;'>2024-01-29|</td>
                <td style='text-align: center;'>8</td>
            </tr>
            <tr>
                <td style='text-align: center;'>2024-02-18|</td>
                <td style='text-align: center;'>20天</td>
            </tr>
        </table>"]
    end

    subgraph "系統測試"
        direction TB
        T9["<table border='1' cellspacing='0' cellpadding='10' style='width: 100%;'>
            <tr>
                <td style='text-align: center;'>2024-04-14|</td>
                <td style='text-align: center;'>9</td>
            </tr>
            <tr>
                <td style='text-align: center;'>2024-05-09|</td>
                <td style='text-align: center;'>25天</td>
            </tr>
        </table>"]
    end

    subgraph "使用者訓練"
        direction TB
        T10["<table border='1' cellspacing='0' cellpadding='10' style='width: 100%;'>
            <tr>
                <td style='text-align: center;'>2024-02-23|</td>
                <td style='text-align: center;'>10</td>
            </tr>
            <tr>
                <td style='text-align: center;'>2024-03-13|</td>
                <td style='text-align: center;'>20天</td>
            </tr>
        </table>"]
    end

    subgraph "使用者測試"
        direction TB
        T11["<table border='1' cellspacing='0' cellpadding='10' style='width: 100%;'>
            <tr>
                <td style='text-align: center;'>2024-05-09|</td>
                <td style='text-align: center;'>11</td>
            </tr>
            <tr>
                <td style='text-align: center;'>2024-06-03|</td>
                <td style='text-align: center;'>25天</td>
            </tr>
        </table>"]
    end



    T1 --> T2 --> T4 --> T6 --> T9 --> T11;
    T1 --> T3 --> T5 --> T7 --> T10 --> T11;
    T5 --> T8 --> T10;


```
##關鍵路徑：1 -> 2 -> 4 -> 6 -> 9 -> 11
