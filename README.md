<h1 align="center">Ubuntu-Yunzai</h1>
<h6 align="center">快捷安装Yunzai-Bot</h6>
<hr/>
<ul>
<li>由于本人是萌新，很多东西才刚刚起步</li>
<li>如果你使用过程中发现报错或者问题，请麻烦您向我反馈</li>
<li>功能完善中……</li>
<img src="图片/星野爱.jpg" alt="爱" width = "400">
  </a><br>
</ul>
<hr/>

## 一.Ubuntu系统直接安装脚本<br>
>如果您是服务器或者自备了`ubuntu` 请直接使用下面的命令<br>

```
apt update
```
```
apt install curl -y
```
```
bash <(curl -sL https://gitee.com/Wind-is-so-strong/yz/raw/master/install.sh)
```

<li>首次启动脚本似乎会自动关闭，再执行一遍就好了喵<li>

<hr>

## 二、手机termux安装

>[☞Termux下载地址](https://github.com/termux/termux-app/releases)<br>
>选择下载`arm64`版 然后使用下面的命令
<li>如果你是32位的手机请下载｀arm32｀<li>
<li>随后自动查找Ubuntu18.04的安装教程
```
bash <(curl -sL https://gitee.com/haanxuan/yzai-pd/raw/master/GG.sh)
```

如果提示`No command curl found` 则使用下面的命令安装curl <br>

```
pkg update
```
```
pkg install -y curl
```
>安装完成后执行
```
bash <(curl -sL https://gitee.com/Wind-is-so-strong/yz/raw/master/install.sh)
```
<hr>

#### 作者列表
| 作者 | QQ |QQ群|
| --- | --- | --- |
|等风来|3139373986|797434884|


<hr/>

#### 特别鸣谢

1. [Yunzai](https://gitee.com/Le-niao/Yunzai-Bot)
2. [Yunzai插件库](https://gitee.com/yhArcadia/Yunzai-Bot-plugins-index)
3. 某个不愿意透露姓名的大佬
4. [白狐Ubuntu-Yunzai](https://gitee.com/baihu433/Ubuntu-Yunzai)
