# trykernel_pico_disp_board


### 液晶のON/OFF回路
- MOSFETを使います
- 秋月で売っている30円のBSS138 Panjit製を使います
- Vthが1.5Vと使いやすいです
- 300mAしか引けませんが、液晶は100mA程度なので問題ないでしょう
- NチャネルのMOSFETです
- 
![image](https://github.com/user-attachments/assets/00e3a56c-f55f-409b-b892-214be2330bf9)


### MOSFETの基本回路通りに構成

![image](https://github.com/user-attachments/assets/02d8ef0a-17e2-4032-b4d3-842ae6cd06a3)

- 基本回路どおりに設計します
- マイコン側に電流が流れる可能性があるので、直接受けず、抵抗を介します
- オープンドレイン接続を想定し、ゲートはプルダウンしておきます



![image](https://github.com/user-attachments/assets/9aeece22-3885-4b49-99ee-fa5d8bbca554)



![image](https://github.com/user-attachments/assets/af2d48a5-9085-40e8-b74f-bf2fe51b8961)

![image](https://github.com/user-attachments/assets/4b0066f6-a3bd-477d-80aa-a59814d81076)

![image](https://github.com/user-attachments/assets/365809ca-22af-4cc3-9e33-5ea588506706)

![image](https://github.com/user-attachments/assets/04787444-f125-41e2-ad46-cdd52281c5df)

![image](https://github.com/user-attachments/assets/db542a91-2199-41fd-aed2-2f4e90907f27)






  
