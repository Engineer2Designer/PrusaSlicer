這是定義E2D 3D 列印設備用來使用PrusaSlicer 切片軟體的設定.
---
E2D 3D 列印設備 編碼原則如:i310 第一碼為設備運作方式 i代表龍門架構 第二碼代表軸數的馬逹數量 第三碼代表擠出機的馬逹數量 第四碼代表硬體版次.
如有可擴建設備 可列擴充碼 如M 代表 MMU 或 I 代表SI 

MacOS 手動增加E2D 3D 列印設備方式
---
1.下載[E2D_config.zip](https://github.com/Engineer2Designer/PrusaSlicer/archive/refs/heads/E2D_Config.zip) 將目錄中的2.8.0-resources/profiles/ 下的資料包含 E2D目錄及E2D.idx 跟 E2D.ini 複製到從 [PrusaSlicer-2.8.0+MacOS-universal-202406270936.dmg](https://github.com/prusa3d/PrusaSlicer/releases/download/version_2.8.0/PrusaSlicer-2.8.0+MacOS-universal-202406270936.dmg)下載解壓縮後目錄底下的 PrusaSlicer-2.8.0+MacOS-universal-202406270936.dmg\PrusaSlicer\PrusaSlicer.app\Contents\Resources\profiles\ 目錄中

2.再重啟 PrusaSlicer-2.8.0 ,重新執行 增加/移除打印機
![螢幕擷取畫面 2024-08-23 114819](https://github.com/user-attachments/assets/30fd6a91-1fa6-4e1f-9db9-8ce423409e26)

3.就應該可以看到 E2D 的選項 
![Other FFF](https://github.com/user-attachments/assets/1def8df6-4b5a-4dd1-b84c-8b1431b35639)
