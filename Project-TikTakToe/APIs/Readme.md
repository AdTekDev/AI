
## Tải và chạy công cụ kết nối APIs
(sẽ update ngày 21/6 --> 26/6) 

### TikTokToe Client
- Windows:  https://drive.google.com/file/d/15bhgf8_Yw0S2wbLnEkpNOEvmugFwLR1F/view?usp=drive_link  
- Linux:  
- MacOS:  

## Mô tả các tình huống sử dụng

CLIENT-TicTacToe.exe  start ABC BaDoSa
--> thông báo cho Server biết là người chơi BaDoSa sẵn sàng chơi trận game ABC 

CLIENT-TicTacToe.exe  status ABC
--> kiểm tra trạng thái của trận game ABC và coi tới lượt chơi chưa 

CLIENT-TicTacToe.exe  play ABC BaDoSa 2 3
--> thông báo cho Server biết là người chơi BaDoSa đi nước cờ tại dòng 2 cột 2 trong trận game ABC 

### * Code gọi và parse dữ liệu từ python (chạy trên colab, notebook) [đã viết sẵn trong client] 

### Code gọi từ Python trên Colab hoặc Notebook
* (chú ý vị trí thư mục của tập tin thực thi CLIENT-TicTacYoe) 
- Cách 1  
import os   
stream = os.popen('CLIENT-TicTacToe  start ABC BaDoSa')   
output = stream.read()  
output  

- Cách 2
import subprocess  

xCaro = subprocess.Popen(["CLIENT-TicTacToe", "start",  "ABC",  "BaDoSa"],  
                        stdin =subprocess.PIPE,  
                        stdout=subprocess.PIPE,  
                        stderr=subprocess.PIPE,  
                        universal_newlines=True,  
                        bufsize=0)  

# Fetch output  
for line in xCaro.stdout:  
    print(line.strip())  


