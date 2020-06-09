Example 2:

1. 先執行以下指令, 會將環境準備好

```
cd $HOME
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2020/ex2/scripts/ex2-pre.sh) GITHUB_ACCOUNT GITHUB_PROJECT
```

2. 切到GITHUB_PROJECT資料夾下. 查看data/0001-ex2.patch內容
```
cd ncyu-2020/
cat data/0001-ex2.patch
```
3. 按照0001-ex2.patch內容對ex2.txt進行修改
```
vi ex2.txt
```
4. 完成並commit後, 在GITHUB_PROJECT資料夾下, 執行以下指令

```
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2020/ex2/scripts/ex2-test.sh) GITHUB_ACCOUNT GITHUB_PROJECT
```
