Example 4:

1. 先執行以下指令, 會將環境準備好

```
cd $HOME
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2020/ex4/scripts/ex4-pre.sh) GITHUB_ACCOUNT GITHUB_PROJECT
```

(Hint:
You should exchange Example 4: 3 and Example 4: 2 before merging, and it may have some conflicts when doing the operation.

While fixing conflicts, you shouldn't change the order when it gives you feeback the first time；however, you should change it the second time.  

You can use “git status” and "git log --graph --oneline" to help you fix the conflicts.
)

2. 切到GITHUB_PROJECT資料夾下. 依照投影片描述做修改

3. 完成並commit後, 在GITHUB_PROJECT資料夾下, 執行以下指令

```
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2020/ex4/scripts/ex4-test.sh) GITHUB_ACCOUNT GITHUB_PROJECT
```
