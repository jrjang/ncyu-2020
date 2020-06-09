# Example 0:

顯示成功安裝hub後，卻無hub產生，請先確認Windows使用者名稱是否有空格

設定git的使用者名稱和電子郵件. 使用者名稱是學號, 電子郵件是學校email
例如:

使用者名稱: 1043000

電子郵件: s1043000@mail.ncyu.edu.tw

在Git Bash中執行以下指令
```
cd $HOME
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2020/ex0/scripts/ex0-test.sh) GITHUB_ACCOUNT GITHUB_PROJECT CHINESE_NAME
```
GITHUB_ACCOUNT: github帳號

GITHUB_PROJECT: github repository名稱

CHINESE_NAME: 中文姓名
