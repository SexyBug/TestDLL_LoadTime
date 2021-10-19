# TestDLL_LoadTime
调用DLL（静态链接）  
# 步骤  
## 1.将MyDll.dll放在与.exe相同目录  
## 2.在如下选项引入DLL头文件目录  
![image](https://user-images.githubusercontent.com/34029554/137863290-ce926eb3-2673-417e-b3b6-14ecfe9377f5.png)  
## 3.在如下选项引入.lib所在目录  
![image](https://user-images.githubusercontent.com/34029554/137864230-1fa1edd0-19b8-4827-b3ed-6486fedcfa02.png)
## 4.在如下选项添加MyDll.lib  
![image](https://user-images.githubusercontent.com/34029554/137864197-402ceb03-6354-4676-a9b5-af3b1d94e2b4.png)  
## 5.写测试代码，运行
