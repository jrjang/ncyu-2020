Example 3:

1. 先執行以下指令, 會將環境準備好

```
cd $HOME
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2020/ex3/scripts/ex3-pre.sh) GITHUB_ACCOUNT GITHUB_PROJECT
```

2. 切到GITHUB_PROJECT資料夾下,將ex3.txt裡的"return 1"修改為"return -1",接著使用stash這個指令保存目前的狀態,隨後切換分支到origin/ex3下,建立一個分支ex3,修改ex3.txt的內容,使其在執行時能顯示"Hello World"

3. 完成並commit後, 在GITHUB_PROJECT資料夾下, 執行以下指令

```
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2020/ex3/scripts/ex3-test.sh) GITHUB_ACCOUNT GITHUB_PROJECT
```
