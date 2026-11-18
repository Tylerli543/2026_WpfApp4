# WPF小作家
2026/11/11

1. 新增一個DocutmentViewer視窗，用來顯示和瀏覽文檔內容。
1. 在主視窗MainWindow中新增一個按鈕，點擊後可以打開DocutmentViewer視窗。
1. 在DocutmentViewer視窗中新增一個RichTextBox，用來顯示文檔內容，並且可以進行編輯。
1. 使用CommandBinding來實現RichTextBox的基本編輯功能，例如複製、剪下、貼上等。
1. 在EditingToolBar中新增文字格式的按鈕，包含加粗、斜體、下劃線、字體顏色等功能。
1. 使用第三方元件ColorPicker來實現字體顏色的選擇功能。
1. 新增變更文字字型的ComboBox，讓使用者可以選擇不同的字型。
1. 新增變更文字大小的Com# WPF 小作家

本專案是一個使用 C# 與 WPF 開發的桌面文字編輯器，支援 RichTextBox 文字編輯與 RTF 文件管理。

## 開發環境

- .NET 8
- WPF（net8.0-windows）
- Visual Studio 2022 或更新版本
- Extended WPF Toolkit 5.1.2

## 功能

- 從主視窗開啟新的文件編輯視窗
- 新增文件視窗
- 開啟與儲存 RTF 文件
- 使用 RichTextBox 編輯多段文字與格式
- 設定粗體、斜體、底線文字格式
- 選擇文字顏色
- 選擇系統字型與字型大小
- 清除目前文件內容
- 使用圖示工具列執行文件與編輯操作
- 顯示文件編輯狀態列區域

## 執行方式

```powershell
dotnet run --project .\2026_WpfApp4\2026_WpfApp4.csprojboBox，讓使用者可以選擇不同的字體大小。