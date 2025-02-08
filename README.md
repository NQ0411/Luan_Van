# Hệ thống vệ sinh cửa kính cho nhà cao tầng
## 🚗 **MODEL**
### 3D Model
![alt text](3D.png)
### Model 
![alt text](model.png)
## **Đặc tả hệ thống**
![alt text](Block_Diagram/dactahethong.png)
### Hệ thống được chia làm 4 mạch chính: 
- Mạch điều khiển động cơ di chuyển
- Mạch điều khiển động cơ quạt
- Mạch điều khiển hệ thống hoạt động (Rx)
- Mạch cho bộ điều khiển từ xa (Tx) 
- Mạch nguồn cho toàn bộ hệ thống
### Mạch điều khiển động cơ di chuyển (H Bridge Circuit) 
#### - Block Diagram cho mạch điều khiển động cơ di chuyển
![alt text](Block_Diagram/blockmotor.png)
#### - Mô hình 3D từ Altium
![alt text](Model/Motor.png)
### Mạch điều khiển động cơ quạt
#### - Block Diagram cho mạch điều khiển động cơ quạt
![alt text](Block_Diagram/blockmotorfan.png)
#### - Mô hình 3D từ Altium 
![alt text](Model/Motorfan.png)
### Mạch điều khiển hệ thống hoạt động (Rx)
#### - Block Diagram cho mạch điều khiển hệ thống hoạt động 
![alt text](Block_Diagram/blockRx.png)
#### - Mô hình 3D từ Altium
![alt text](Model/Rx.png)
### Mạch cho bộ điều khiển từ xa (Tx)
#### - Block Diagram cho mạch
![alt text](Block_Diagram/BlockTx.png)
#### - Mô hình 3D từ Altium 
![alt text](Model/Tx.png)
### Mạch nguồn hệ thống 
#### - Block Diagram cho mạch 
![alt text](Block_Diagram/Blockpower.png)
#### - Mô hình 3D từ Altium 
![alt text](Model/power.png)
## **Giải thuật của hệ thống)
### **MẠCH RX** 
### - Giải thuật tổng quát cho mạch Rx 
![alt text](Block_code/Rx.png)
### - Giải thuật chi tiết và frame truyền nhận data cho mạch Rx 
![alt text](Block_code/Rx_detailed.png)
![alt text](Block_code/Rx_data.png)
### **MẠCH TX** 
### - Giải thuật tổng quát cho mạch Tx 
![alt text](Block_code/Tx.png)
### - Giải thuật chi tiết và frame truyền nhận data cho mạch Tx 
![alt text](Block_code/Tx_detailed.png)
![alt text](Block_code/Tx_data.png)
