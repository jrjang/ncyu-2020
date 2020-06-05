Example 6:

1. 依照投影片描述做修改

```
git clone git@github.com:GITHUB_ACCOUNT/GITHUB_PROJECT
```

GITHUB_ACCOUNT: github帳號

GITHUB_PROJECT: github repository名稱 

```
git remote add official https://github.com/jrjang/ncyu-2020
```

```
git fetch official
```

```
git push origin HEAD:refs/head/ex6-2
```

2. 完成後, 在GITHUB_PROJECT資料夾下, 執行以下指令

```
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2020/ex6/scripts/ex6-test.sh) GITHUB_ACCOUNT GITHUB_PROJECT
```
