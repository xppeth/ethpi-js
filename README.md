# ethpi 官网挖矿教程

## 第一步 下载node.js 脚本环境 
```
https://www.nodejs.com.cn/
```

### 第二步 安装node.js

#### 一直下一步就可以 注意设置安装路径

#### 查看是否安装成功
```
键盘按键 win + R 
输入 cmd
终端打开后
输入 npm -v

出现版本号及安装成功
```

## 第三步 下载脚本
```
https://github.com/IErcOrg/ierc-miner-js
```

### 第四步 安装依赖

```
npm i -g yarn

yarn install
```

### 第五步 创建钱包或者导入私钥

```
创建钱包
yarn cli wallet --create

或者导入私钥
yarn cli wallet --set <privateKey>

```

### 第六步 开启挖矿
```
yarn run cli mine 难度 --account 当前导入地址
```

### 难度 选择
```
m4: 0x0000
m5: 0x00000
m6: 0x000000
m6: 0x0000000
m7: 0x00000000
m8: 0x000000000

难度越高获取的奖励就越多，当然需要相对于的算力。
```

### 查看挖矿奖励
```
https://www.ierc20.com/PoW-DPoS?tab=DPoS-PoW&type=PoW
```

### 小提示
```
官网脚本只是单进程的那么高算力的机器发挥不出来效果，如果想要发挥出高算力的机器，可以找我购买多进程脚本

多进程脚本地址：https://github.com/xppeth/ethpi
```