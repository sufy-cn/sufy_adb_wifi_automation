# sufy_adb_wifi_automation uniapp wifi调试 自动化
# 通过电脑热点自动连接 adb wifi

### 最近开发uniapp的时候用数据线连接太不方便了，用adb调试桥开WIFI调试还要打好几行代码，然后就写了个这么个小玩意，从获取IP开始都是自动化的

## 使用教程

### 两个exe文件都要放到 下面这个目录里面才可以使用

```
HBuilderX\plugins\launcher\tools\adbs
```



### 首先要确保笔记本电脑可以开热点，待热点打开后手机去连接，然后运行main.py等待提示成功。

### 如果控制台中一直没有输出东西，就检查一下手机有没有连接到电脑开的热点上(大概15s内就好了)

### 如果是手机第一次通过wifi进行连接，先用usb数据线把手机连上电脑，然后运行one.py，然后拔出数据线再运行main.py

