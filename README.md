## Prerequisite

### Environment Setup
* 下載 64-bit Git for Windows
[download link](https://github.com/git-for-windows/git/releases/downloa
d/v2.26.2.windows.1/Git-2.26.2-32-bit.exe)
* 下載 Github hub for Windows 64-bit
[download link](https://github.com/github/hub/releases/download/v2.14.
2/hub-windows-amd64-2.14.2.zip)
* 下載 Notepad++ (optional)
[download link](https://github.com/notepad-plus-plus/notepad-plus-plus/
releases/download/v7.8.6/npp.7.8.6.Installer.x64.exe)
* Setup hub token
[guideline](https://github.com/settings/tokens)
* Edit $HOME/.config/hub file
```
cat > $HOME/.config/hub <<EOF
github.com:
- user: [your github account]
  oauth_token: [generated from last step]
  protocol: https
EOF
```
### Git Setup
* Generate ssh key 
* Add to your github account
* Test connection
[https://help.github.com/en/articles/connecting-to
-github-with-ssh](https://)
```
ssh-keygen
cat ~/.ssh/id_rsa.pub
# copy and paste to github
ssh -T git@github.com
```
* Following statement means the connection is successful.
```
Hi YOUR_ACCOUNT! You've successfully authenticated, but GitHub does not provide shell 
access.
```
## Troubleshooting
### Hub command not found
* find the location of hub
```
which hub
export PATH=$PATH:[hub_location]
```
![](https://i.imgur.com/xXIdBUL.jpg)


## Example 0:

1. 設定git的使用者名稱和電子郵件. 使用者名稱是學號, 電子郵件是學校email

例如:

使用者名稱: 1043000

電子郵件: s1043000@mail.ncyu.edu.tw

2. 在Git Bash中執行以下指令

```
cd $HOME
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2020/ex0/scripts/ex0-test.sh) GITHUB_ACCOUNT GITHUB_PROJECT CHINESE_NAME
```

GITHUB_ACCOUNT: github帳號

GITHUB_PROJECT: github repository名稱 

CHINESE_NAME: 中文姓名
