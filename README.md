# Arduino-Micro-NANO 迷你Micro開發板
方便大家做開發使用，要做商業用途請告知，請不要移除板子上的QR-CODE & 背面的"立新電腦科技"，其他就隨便大家修改來玩囉WWW  
<div align="center">
<img src="https://user-images.githubusercontent.com/53372547/130380643-a72c6a33-72a3-4295-aeed-836fbcb793a7.jpg" width="400">
<img src="https://user-images.githubusercontent.com/53372547/130380654-1b4a3586-e742-4da2-bc54-018e16314aac.jpg" width="400">  
  
### 開發板尺寸為 1.8CM X 2CM
</div>  

## 元件表
- ATMega32U4 X1  
- 0603 22Ω X2 [位置在USB口下方兩個電阻位]  
- 0603 330Ω X2 [位置在RX/TX LED 下方兩個電阻位]  
- 0603 1uF X1 [C1]  
- 0603 LED X2 [位置在USB口左方RX/TX位，靠近電阻為正極，靠近USB口為負極]  
- 16Mhz 晶震 X1 [規格為 3215]  
- SMD Micro-USB 母座 X1  
- 7P 針腳 X2  
## Bootloader 引導程序燒錄
燒錄 Bootloader 時，請選擇燒錄 Arduino Micro 的 Bootloader  
板子背面有ICSP的腳位(雖然不是標準排列就是了)  
可以使用ArduinoISP(UNO或其他開發板模擬)來燒錄，使用Arduino AS ISP標準接法  
- UNO(等...開發板) > Micro-NANO  
- D13(SCK) > SCK  
- D12(MISO) > MI  
- D11(MOSI) > MO  
- D10 > RES  
- 5V > 5V+  
- GND > G  
## 注意事項
RX 腳位是 D0  
TX 腳位是 D1  
RX/TX 腳位使用不影響燒錄，請放心(反正它貌似不能用TTL燒程式來著)
