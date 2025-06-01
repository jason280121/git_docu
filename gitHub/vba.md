
# 新增活頁薄excel檔
`Workbooks.Add`

# 作用新增活頁薄(2)
`Workbooks(2).Activate`


# 另存活頁薄檔名
`ActiveWorkbook.SaveAs "C:\Users\jason58.tsou\Desktop\vba-2025\test.xlsx"`


# 關閉活頁薄(2)excel檔
`Workbooks(2).Close`


# 新增工作表
`Worksheets.Add`


# 新增第工作表(4)之後
`Worksheets.Add after:=Worksheets(4)`


# 新增第工作表(4)之前
`Worksheets.Add before:=Worksheets(4)`

# 選擇作用中的工作表
`Worksheets(2).Select`

# 拷貝工作表(2)至工作表(4)之後
`Worksheets(2).Copy after:=Worksheets(4)`



# 更名工作表
`Worksheets(5).Name = "拷貝學生成績"`

# 拷貝工作表(3)至第一個工作表
`Worksheets(3).Copy before:=Worksheets(1)`


# 查詢工作表名稱(sheets)
指定工作表名稱=myNmae 變數
查詢第4個工作表名稱
`myName = Worksheets(4).Name`
`MsgBox myName`

# 更改工作表名稱
修改已存在工作表(5)名稱
Worksheets(5).Name = "new工作表"
`MsgBox myName`


# 統計目前活頁薄工作表數量
`myNo = Sheets.Count`
`MsgBox myNo`