Example 2:

1. 先執行以下指令, 會將環境準備好

```
cd $HOME
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2020/ex2/scripts/ex2-pre.sh) GITHUB_ACCOUNT GITHUB_PROJECT
```

2. 切到GITHUB_PROJECT資料夾下. 依據data/0001-ex2.patch做相對應的修改
3.執行git blame指令並指定印出2到8行的資訊
```
git blame -L 2,8 ex2.txt
```
4. 完成並commit後, 在GITHUB_PROJECT資料夾下, 執行以下指令

```
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2020/ex2/scripts/ex2-test.sh) GITHUB_ACCOUNT GITHUB_PROJECT
```
