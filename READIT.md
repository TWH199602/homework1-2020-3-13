omework 1 将笔记上传至github前篇

## 1. 新建一个终端 
command + n

## 2.在命令行处输入命令
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

### 2.1注
（"your_email@example.com"）改为 （homework1)

## 3.在终端命令行内输入
cat ~/.ssh/id_rsa.pub

## 4.在github首页，在右上角倒三角处点开下拉菜单，点击Settings进入

### 4.1.在进入Settings页面后选择左侧SSH and GPG keys

## 5.进入新页面后点击右上角"New SSH Key"

## 6.补充一个标题"homework-one"

## 7.点击 Add SHH Key

## 8.验证设置：
输入ssh -T git@github.com