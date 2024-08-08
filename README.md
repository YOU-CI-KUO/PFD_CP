# PFD with CP output
# 說明
此次期末專題為 2015 University/College IC Design Contest Full Custom IC Category for Undergraduate Students，但因為是第一次做競賽題目，所以教授只要求規格正確即可
# 題目描述
設計一個頻率為250MHz的相位/頻率偵測器(phase/frequency detector，以下簡稱為PFD)與電荷幫浦(charge pump，以下簡稱為CP)電路，電路方塊圖如圖一，主要可分為PFD及CP兩部份。此電路之I/O包含：輸入時脈訊號A, B、PFD之輸出訊號QA, QB、輸出訊號VOUT、電源VDD, GND、輸入電壓VB1, VB2

<div align="center"><img width="450" alt="PFD_CP" src="https://github.com/user-attachments/assets/7d9fad47-0481-40f5-b482-3118674d1382"></div>

# 波行期望結果
分為輸入訊號A, B相位不同以及頻率不同
<div align="center"><img width="390" alt="螢幕擷取畫面 2024-08-08 185346" src="https://github.com/user-attachments/assets/bf2d30ed-1c38-4619-84f8-fd56b6a007e9"></div>
<div align="center"><img width="390" alt="螢幕擷取畫面 2024-08-08 185357" src="https://github.com/user-attachments/assets/b4806f0a-d71c-44e5-bcc7-522993a86a48"></div>

# 規格要求
電路輸入與輸出波形如圖六、圖七所示。圖六為輸入訊號相位不同之情形，圖七為輸入訊號頻率不同之情形。電路之供應電壓(VDD)為1.8V、接地電壓(GND)為0V、VB1為0.7V、VB2為1.1V、輸入訊號A為250MHz之時脈訊號、圖六之輸入訊號B為比A訊號延遲0.5ns之時脈訊號、圖七之輸入訊號B為166.67MHz之時脈訊號。
<div align="center"><img width="410" alt="螢幕擷取畫面 2024-08-08 185918" src="https://github.com/user-attachments/assets/9fbebfaa-5c85-4f95-9caa-96f363a4a790"></div>
<div align="center"><img width="410" alt="螢幕擷取畫面 2024-08-08 190032" src="https://github.com/user-attachments/assets/9a3ec053-443d-41f8-9dd9-3b540cf54934">
</div>

參賽者必須完成電路設計、佈局(Layout)、DRC、LVS、PEX，電路模擬以post-layout simulation為準，並於溫度27°C與TT Corner下，通過規格要求。
其他相關細節請自行查閱網路上的題目


