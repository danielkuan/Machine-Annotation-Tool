專案名稱（中文）：圖片標註工具.html
用途：設備佈局互動式標註系統

Project Name: MachineAnnotationTool.html
Purpose: Interactive Equipment Layout Annotation System

一、 操作程序 (Operating Procedures)
1. 載入底圖

從本地端選取設備、電控櫃或硬體配置的影像檔（JPG/PNG）作為背景。

1. Load Background Image

Select an image file (JPG/PNG) of the equipment, control cabinet, or hardware configuration from the local drive to serve as the base layout.

2. 插入標註框

新增標註元件，每個元件包含：自動編號 (Index)、抬頭 (Title) 以及 用途說明 (Description)。

2. Insert Annotation Boxes

Add new annotation elements. Each box includes: an Auto-incremented Index, a Title, and a Functional Description.

3. 自由拖曳標註位置

可使用滑鼠自由移動標註框與標示點的位置，系統會自動更新引線路徑。

3. Free Drag-and-Drop Positioning

Freely move the annotation boxes and marker points using the mouse; the system will automatically update the leader line paths.

4. 數據與影像導出

儲存為 JSON 檔：保存所有座標、文字內容與樣式參數，以便日後修改。

導出為 PNG 檔：將目前標註後的畫面轉存為高解析度圖檔。

4. Data and Image Export

Save as JSON: Store all coordinates, text content, and style parameters for future editing.

Export as PNG: Capture and save the current annotated layout as a high-resolution image file.

5. 載入 JSON 數據

匯入先前保存的 JSON 設定檔，快速恢復所有標註位置、文字與樣式設定。

5. Load JSON Data

Import previously saved JSON configuration files to instantly restore all annotation positions, text, and style settings.

二、 功能特色 (Key Features)
1. 高度樣式自定義

標註框、引線（連接線）及標示點的顏色與透明度（Alpha Channel）皆可獨立調整。

1. Highly Customizable Styles

Colors and opacity (Alpha Channel) for annotation boxes, leader lines, and marker points can be adjusted independently.

2. 整體比例縮放

支援標註框的整體比例調整，以適應不同解析度的底圖或顯示需求。

2. Global Scaling

Supports overall scale adjustment for annotation boxes to fit different background resolutions or display preferences.

3. 多樣化標示點樣式

標示點外觀可自由切換為「數字標號」或「標準紅點」。

3. Versatile Marker Styles

Marker point appearance can be toggled between "Indexed Numbers" or "Standard Red Dots."

4. 智慧引線路徑選項

引線路徑支援三種模式：直線 (Straight)、30度轉折垂線 (30° Angled) 或 90度直角垂線 (90° Orthogonal)。

4. Intelligent Leader Line Routing

Leader lines support three routing modes: Straight, 30° Angled, or 90° Orthogonal.

5. 動態序號調換

選取標註框後，可藉由鍵盤「上/下鍵」即時調換標註順序，系統將同步更新所有編號。

5. Dynamic Sequence Reordering

Once an annotation box is selected, its order can be swapped instantly using the Up/Down arrow keys, with all indices automatically updated by the system.
