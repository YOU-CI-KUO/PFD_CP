# DFF設計
D Flip-Flop採用Asynchronous Reset (非同步)，及不用等clock訊號及產生復位

下圖為Transistor level DFF 的Schematic以及layout view
<div align="center"><img width="320" alt="DFF" src="https://github.com/user-attachments/assets/916b9062-ecf1-45d8-a73e-e8a33b4e93ee">      <img width="300" alt="DFF1" src="https://github.com/user-attachments/assets/4cdb5ef4-781b-4435-8ab3-724bd2fc6a6f"></div>

# PFD設計
此次的鉴频鉴相器设计(Phase Frequency Detector，PFD）設計我使用D Flip-Flop組成的架構，包括1個NAND gate去觸發reset信號，如下圖所示
<div align="center"><img width="250" alt="PFD" src="https://github.com/user-attachments/assets/fdb3fe40-f475-4a23-938d-0700ed997681"></div>

Transistor level PFD 的Schematic以及layout view

利用之前製作的子電路去構成，因為之前設計的DFF reset為active low的關係，所以改為用NAND去觸發
<div align="center"><img width="450" alt="PFD" src="https://github.com/user-attachments/assets/d24c6f77-0053-41e9-9e16-bb0dfd5163a4"></div>     
<div align="center"><img width="300"  alt="PFD1" src="https://github.com/user-attachments/assets/cfaa5a44-ea9d-4022-8d4c-1917880b6924"></div>

