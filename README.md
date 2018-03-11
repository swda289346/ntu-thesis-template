# 國立臺灣大學學位論文模板 ntu-thesis-template

## 依賴套件

- fontspec
- geometry
- ifthen
- xeCJK

## 參數

使用以下指令定義各項參數

例如 `\department{Department of Computer Science and Information Engineering}{資訊工程學系}`

- 學院 `\college`
- 系所 `\department`
- 碩士/博士論文 `\thesistype`
- 論文題目 `\thesistitle`
- 作者 `\thesisauthor`
- 指導老師 `\advisor`
- 畢業日期 `\thesisdate`

## 特殊頁面

### 封面

使用 `\makecover` 插日封面

### 摘要

使用abstract環境插入摘要

例如

```
\begin{abstract}[tw]
	中文摘要內容
\end{abstract}
\begin{abstract}
	The abstract in English
\end{abstract}
```

### 口試委員會審定書

使用 `\makeacceptance{檔名}` 插入口試委員會審定書
