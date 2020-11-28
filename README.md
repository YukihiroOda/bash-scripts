# bash-scripts

My using bash-scripts.

## argcheck

*argchek* is what checks how to evaluate arguments.
This is not my original code. This code is in "山森 丈範， '[改訂第3版] シェルスクリプト基本リファレンス', 技術評論者. 2017/1/20".
For example,
```
~$ argcheck "$HOME"  '$HOME' "`echo \"\$HOME\"`"
```
then
```
'/home/Username'
'$HOME'
'/home/Username'
```

## sftp_all_get

*sftp_all_get* is to get all files in a remote machine by sftp.
For example, 
```
~$ sftp_all_get hoge.com
```
then you "get" all files in the home directory of hoge.com.

## tex2svg

*tex2svg* make the svg file from a tex file.
For example, 
```
~$ tex2svg hoge.tex
```
then you get hoge.svg.
This script depends on *lualatex* and *pdf2svg*.
