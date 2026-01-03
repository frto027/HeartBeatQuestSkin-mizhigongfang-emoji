# Intro

This is a HeartBeatQuest skin.

Image from 蜜汁工坊.

# HeartBeatQuest蜜汁工坊表情包模组

此项目可作为给HeartBeatQuest自定义表情包UI的一个样板项目。

适用于HeartBeatQuest v0.2.6及以后版本。在[这里](https://github.com/frto027/HeartBeatQuestSkin-mizhigongfang-emoji/releases/)下载qmod文件。然后使用你的mod管理工具安装它，并在mod设置里切换。

注意需要在游戏内打开Advanced HUD（高级HUD），否则不会显示。因为UI挂在了immediateRankGo上面。

根据心率切换不同的表情显示。

![img](Assets/z0.png)  
↓超过50%  
![img](Assets/z1.png)→低于50% ![img](Assets/zako.png)  
↓超过60%  
![img](Assets/z2.png)→低于60% ![img](Assets/zako.png)  
↓超过70%  
![img](Assets/z3.png)  
↓超过80%  
![img](Assets/z4.png)  
↓超过90%  
![img](Assets/z5.png)  


# 定制方法

你可以直接替换z0.png等图片文件为自己喜欢的表情包。然后再使用unity调整。

使用Unity 2021.3.16f1打开此项目。调整emotes这个prefab。包括DefaultWidgets文件夹下的各个动画等。

如果要更换表情包，请务必修改info里面的name。

点击`Assets > BuildAssetBundles`生成文件`AssetsBundlesAndroid/defaultwidget`。

调整mod.json。

将mod.json和zako.png（这是封面），还有defaultwidget一起打包压缩，改后缀为qmod即可作为mod使用。

详细定制内容请参考[这里](https://github.com/frto027/HeartBeatQuest/blob/master/UnityUI/Readme.md)。

# 改进

欢迎提交pr.
