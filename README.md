# djangotest
自我練習&心得

使用環境win10 pro

1.安裝docker及git  
&nbsp;&nbsp;&nbsp;&nbsp;參考 https://www.maxlist.xyz/2018/11/02/git_tutorial/  
&nbsp;&nbsp;&nbsp;&nbsp;在工作區，點擊右鍵，開啟git bash here, 設定git  
```
git config --global user.name "usrer"  
git config --global user.email "email"  
```

2.git的操作  
&nbsp;&nbsp;&nbsp;&nbsp;在雲端的github建立專案(可使用同類型的服務)  
&nbsp;&nbsp;&nbsp;&nbsp;在工作區，點擊右鍵，開啟git bash here  
&nbsp;&nbsp;&nbsp;&nbsp;下載專案至本機  
```
git clone https://github.com/a12636/djangotest.git  
git clone https://github.com/a12636/djangotest.git <可設定下載資料夾名稱>  
git clone https://github.com/a12636/djangotest.git -b <指定分支>  
```
&nbsp;&nbsp;&nbsp;&nbsp;建立索引  
```
git add .  
```
&nbsp;&nbsp;&nbsp;&nbsp;提交異動說明  
```
git commit -m "update readme.md"  
```
&nbsp;&nbsp;&nbsp;&nbsp;上傳專案至雲端  
```
git push  
```
