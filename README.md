# FPGA-project-8
### Authors: 107321005 107321041 107321042

#### Input/Output unit:<br>
* 8x8 LED 矩陣，用來顯示遊戲畫面。<br>
<img src="https://drive.google.com/a/mail1.ncnu.edu.tw/file/d/1MKj8BIGABArIRODM5YTZMMmrcIB31vae/view?usp=sharing" width="300"/><br>

#### 功能說明:<br>
玩家操控藍色移動，閃躲上面掉下來的紅色障礙物，碰到紅色扣血，綠色加血血量最高為三，時間撐越久越好。<br>

#### 程式模組說明:<br>
module LD_final_project(output reg [7:0] DATA_R//紅色燈, DATA_G//綠色燈, DATA_B//藍色燈,
								output reg [6:0] d7_1, 
								output reg [2:0] COMM, Life//血量,
								output reg [1:0] COMM_CLK//計時,
								output EN,
								input CLK, clear//clear, Left//左, Right//右,down//下,uu//上);<br><br>
module slide_game(output reg[3:0]S //控制亮燈排數,output reg [7:0]Red //紅色燈,output reg [7:0]Green //綠色燈,
output reg [7:0]Blue //藍色燈,output reg [4:0]A_count,B_count //計分,output [6:0]O //倒計時,output reg beep //叫聲,input [1:0]button //玩家一左右,input [1:0]button2 //玩家二左右,input CLk,Clear); <br><br>
*** 請說明各 I/O 變數接到哪個 FPGA I/O 裝置，例如: button, button2 -> 接到 4-bit SW <br>
*** 請加強說明程式邏輯 <br>

#### Demo video: (請將影片放到雲端空間)

<a href="https://drive.google.com/open?id=1MiB9dVKYmXJobLUtd_gAzs95X0-PXw3_" title="Demo Video">
