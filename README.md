pytorch安裝GPU
====
一.先查看cuda版本

  1.桌面>右鍵>NVIDIA控制面板
  
  ![Untitled](https://user-images.githubusercontent.com/46515944/177498729-b64c86af-5095-4f55-b08e-8097e2b0825d.png)
  
  2.點擊"系統資訊”
  
  ![Untitled (1)](https://user-images.githubusercontent.com/46515944/177498798-32f48e9e-0611-4151-a502-07d808cb834c.png)

  3.點擊"元素”，並查看第三行：NVIDIA CUDA 11.6.127 driver
  
  ![image](https://user-images.githubusercontent.com/46515944/181897756-74db5f99-8cf9-4105-9cae-0ea3e89f16c1.png)

  
二、
  1.到[這裡](https://download.pytorch.org/whl/torch_stable.html)去下載對應的.whl(有兩個要下載!)，python的版本若為3.7.多少，那下面的whl檔，就選cp37
  
  ![Untitled (4)](https://user-images.githubusercontent.com/46515944/177499601-687df0b6-ae9d-4c7a-b727-62e18acb46a2.png)
  
  2.在到cmd執行一下(要記得切到activate pytorch)
  
    cd C:\Users\17394\Downloads   #下載的位置
    pip install torch-1.7.1+cu110-cp37-cp37m-win_amd64.whl
    pip install torchvision-0.8.2+cu110-cp37-cp37m-win_amd64.whl
  
  參考文獻：https://blog.csdn.net/m0_45696735/article/details/118253942
