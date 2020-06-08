Example 4:

1. 先執行以下指令, 會將環境準備好

```
cd $HOME
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2020/ex4/scripts/ex4-pre.sh) GITHUB_ACCOUNT GITHUB_PROJECT
```

2. 切到GITHUB_PROJECT資料夾下. 依照投影片描述做修改

3. 如果遇到問題或是衝突
```
git status 
git tig
```
上述兩行指令可以有效了解問題發生點

4. 完成並commit後, 在GITHUB_PROJECT資料夾下, 執行以下指令

```
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2020/ex4/scripts/ex4-test.sh) GITHUB_ACCOUNT GITHUB_PROJECT
```
