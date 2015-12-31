## SublimeText配置文件

#### 序列号
注意：该序列号对3095版本适用。  
```
----- BEGIN LICENSE -----
Michael Barnes
Single User License
EA7E-821385
8A353C41 872A0D5C DF9B2950 AFF6F667
C458EA6D 8EA3C286 98D1D650 131A97AB
AA919AEC EF20E143 B361B1E7 4C8B7F04
B085E65E 2F5F5360 8489D422 FB8FC1AA
93F6323C FD7F7544 3F39C318 D95E6480
FCCC7561 8A4A1741 68FA4223 ADCEDE07
200C25BE DBBC4855 C4CFB774 C5EC138C
0FEC1CEF D9DCECEC D3A5DAD1 01316C36
------ END LICENSE ------
```

#### 具体步骤
- 官网下载SublimeText 3 Build最新版本（或者3095版本）。
- 安装启动，输入序列号。
- 打开终端并输入：
```
cd Library/Application\ Support/Sublime\ Text\ 3/Packages/User
git git@github.com:winux404/subl_config.git
mv subl_config/* .
rm -rf subl_config
```
- 在SublimeText中使用ctrl + `打开终端面板，安装Package Control。  
Package Control安装过程中根据User目录中的配置文件，将自动安装所有插件以及你自己的所有个性化设置。