[toc]

## 前言
本文基于 Karabiner-Elements 软件实现 macOS 平台下的按键重映射。



## 实现导航键功能
本项目提供两种方案实现下述的功能：
1. 方案1：只需要使用 `NavigationKey.json` 即可
2. 方案2：
  - 使用 `Capslock2Hyper.json` 将CapsLock键映射为Hyper键
  - 使用 `NavigationKey4HyperCaps.json` 结合Hyper键实现导航键功能


### 1. CapsLock映射为Hyper键
文件 `Capslock2Hyper.json` 实现将 CapsLock 键映射为Hyper键,即：Ctrl+Options+Cmd。


### 2. CapsLock实现方向键
热键及对应功能如下：
- CapsLoLock+'I'：向上键
- CapsLoLock+'J'：向左键
- CapsLoLock+'K'：向下键
- CapsLoLock+'L'：向右键


### 3. CapsLock实现删除键
热键及对应功能如下：
- CapsLoLock+'E'：Backspace 键
- CapsLoLock+'R'：Delete 键


### 4. CapsLock实现导航键
热键及对应功能如下：
- CapsLoLock+'P'：Home 键
- CapsLoLock+';'：End 键


## 实现媒体控制功能
热键及对应功能如下：
- RightShift+向上键：调大音量
- RightShift+向下键：调小音量
- RightShift+向左键：上一首
- RightShift+向右键：下一首



## 参考链接
- https://github.com/tekezo/Karabiner
- https://karabiner-elements.pqrs.org/docs/

