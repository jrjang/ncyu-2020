Example 5:

1. 先執行以下指令, 會將環境準備好

```
cd $HOME
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2020/ex5/scripts/ex5-pre.sh) GITHUB_ACCOUNT GITHUB_PROJECT
```

2. 切到GITHUB_PROJECT資料夾下.

3. reset to "Example 5: 2" commit with unstaging everything

```
git reset --mixed HEAD^
```

4. clean all untracked files

```
git clean -x -f -d
```

5. 完成後(不用commit), 在GITHUB_PROJECT資料夾下, 執行以下指令

```
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2020/ex5/scripts/ex5-test.sh) GITHUB_ACCOUNT GITHUB_PROJECT
```
