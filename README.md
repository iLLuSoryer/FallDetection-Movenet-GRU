整體流程：
1. 用 Movenet 取影片的節點資料
2. 訓練 GRU model
3. 將要預測的影片交給訓練好的 model 預測，並輸出影片的預測結果及 GIF （方便觀查）

注意：
* 要先將"DataVideos"內的"testVideos.7z"和"allVideos.7z"解壓縮
* "GRUkeypoints"內的"GRUdata.npy"和"GRUlabels.npy"是"allVideos"的節點資料，可以直接使用，這樣就可以跳過
  "#取所有影片節點資料"，直接跳到"#載入data和labels"
* 所有路徑記得要修改