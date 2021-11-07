## terminal 指令
下載vscode -> terminal -> new terminal
dir (看資料夾有什麼)
cd （切換資料夾）
mkdir （新增資料夾）
善用tab
- root
  - desktop
  - pictures
   - 2021

root -> desktop : cd ./desktop
root -> 2021 : cd ./pictures/2021
desktop -> picture : cd ../pictures
desktop -> 2021 : cd ../pictures/2021

## 什麼是git
版本控制
就像雲端硬碟：
複製 -> git clone (連結本地資料夾跟雲端資料夾)
上傳資料夾 -> git push
下載 -> git pull
存檔 -> git commit -m "message" 存檔(ex 打魔王前存擋， 去賭場錢存擋)
參數: 做這件事情 搭配什麼條件
教學： git -h or git --help
看紀錄: git log
加入存擋範圍：git add 
HEAD: 游標 現在在哪個版本
branch: 分支 平行時空
## 複製專案
git clone https://github.com/xnlyu/frontend-tutorial.git
1. git remote add willy https://github.com/WillyLi/frontend-tutorial.git （只要一次）
2. git fetch willy (更新存擋紀錄)
3. git merge willy/main

https://gitbook.tw/chapters/github/syncing-a-fork.html