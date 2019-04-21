Example 2:

1. 先執行ex2-pre.sh, 將環境準備好.

```
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2020/ex2/scripts/ex2-pre.sh) GITHUB_ACCOUNT GITHUB_PROJECT
```

2. 依據data/0001-ex2.patch做相對應的修改.

3. 完成並commit後, 執行以下指令.


```
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2020/ex2/scripts/ex2-test.sh) GITHUB_ACCOUNT GITHUB_PROJECT
```
