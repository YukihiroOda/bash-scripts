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