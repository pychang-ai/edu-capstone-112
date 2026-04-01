# 112 屆大學部專題

## 基本資訊

| 項目 | 說明 |
|------|------|
| 屆別 | 112 屆（112 學年度入學） |
| 指導教授 | 張珀銀 助理教授 |
| 實驗室 | 海事 AI 實驗室（Maritime AI Lab） |
| 專題期間 | 113-2 學期 ~ 114-2 學期 |
| 本 Repo 用途 | 進度追蹤、共用資源、培訓補強 |

## 使用方式

本 Repo 採用 **Fork + PR** 流程：

1. **Fork** 本 Repo 到你的 GitHub 帳號
2. 在你的 Fork 中建立 `members/你的學號/` 資料夾
3. 每月進度報告 → 發 PR 回主 Repo
4. 老師審閱 PR → 合併或回饋

## 成員

| 姓名 | 學號 | 督導 | 專題方向 | 備註 |
|------|------|------|---------|------|
| | | | | 待 PY 填入 |

## 現況

112 屆專題生已在進行中，本 Repo 追補建立。重點：

1. **進度追蹤**：每月進度報告（PR 繳交）
2. **培訓補強**：如有基礎能力缺口，可參考 `training/` 教材自主補強
3. **共用資源**：論文清單、工具連結

## 進度報告

每月 1 號前，在你的 Fork 中建立進度報告，發 PR 繳交：

```
progress/
├── 04-進度報告.md
├── 05-進度報告.md
└── ...
```

格式見 `progress/template.md`。

## 培訓教材（自主補強用）

如果覺得某方面基礎不夠，可以自行參考以下教材練習：

| 主題 | 教材位置 | 說明 |
|------|---------|------|
| Git/GitHub | training/git-basics.md | 版本控制和協作 |
| Linux | training/linux-basics.md | 指令操作和權限 |
| Python + Pandas | training/python-basics.md | 資料分析基礎 |
| 論文閱讀 | training/paper-reading.md | 怎麼讀一篇論文 |
| 實驗室工具 | training/lab-tools.md | SSH、Docker、GPU |

培訓教材不要求繳交，但建議趁暑假前把不熟的部分補起來。

## 評量方式

| 項目 | 比例 | 說明 |
|------|------|------|
| 專題進度 | 40% | 是否按計畫推進 |
| 每月進度報告 | 20% | 是否按時繳交、內容品質 |
| 態度與出席 | 20% | 週會出席、主動性 |
| 成果展示 | 20% | 期末發表品質 |

## Repo 結構

```
edu-capstone-112/
├── README.md              ← 本檔案
├── training/              ← 培訓教材（自主補強用）
│   ├── git-basics.md
│   ├── linux-basics.md
│   ├── python-basics.md
│   ├── paper-reading.md
│   └── lab-tools.md
├── progress/              ← 進度報告
│   └── template.md
├── resources/             ← 共用資源
│   └── reading-list.md
└── members/               ← 學生個人資料夾（Fork 後建立）
    └── （學號）/
        ├── profile.md
        └── weekly-log.md
```
