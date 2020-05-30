Example 4:

1. 先執行以下指令, 會將環境準備好

```
cd $HOME
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2020/ex4/scripts/ex4-pre.sh) GITHUB_ACCOUNT GITHUB_PROJECT
```

2. 切到GITHUB_PROJECT資料夾下之後,依序執行以下指令

```
git rebase -i [CommitID] #進入互動介面交換Example4.3與Example4.2之順序
git merge origin/ex4-3
vim [ConflictFile] #處理conflict
git add [ConflictFile]
```

3. 完成並commit後, 在GITHUB_PROJECT資料夾下, 執行以下指令

```
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2020/ex4/scripts/ex4-test.sh) GITHUB_ACCOUNT GITHUB_PROJECT
```
