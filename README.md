Example 4:

1. 先執行以下指令, 會將環境準備好

```
cd $HOME
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2020/ex4/scripts/ex4-pre.sh) GITHUB_ACCOUNT GITHUB_PROJECT
```

2. 切到GITHUB_PROJECT資料夾下. 依照投影片描述做修改
當合併出現衝突時，顯示CONFLICT: Merge conflict in xxx.txt
需先查看 xxx.txt的內容
在發生衝突的地方插入Git找到差異的部分，並修改它
衝突修改完成，再次提交
```
git add xxx.txt

git rebase --continue
```

3. 完成並commit後, 在GITHUB_PROJECT資料夾下, 執行以下指令

```
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2020/ex4/scripts/ex4-test.sh) GITHUB_ACCOUNT GITHUB_PROJECT
```
