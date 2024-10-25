---
title: 学术版GPT-Free
top: false
cover: false
password: 
author: NicholasX
date: 2024-09-17 16:09:51
summary: 学术版GPT获取途径以及详细的fofa扫描网站!
tags: 学术版GPT获取
categories:
---

# 学术版 gpt

## 部署 $$ 运行

attention:如果在配置的过程中遇到困难或者这个教程无法解决的问题，请登录wiki站进行查看，链接：[常见问题 · binary-husky/gpt_academic Wiki (github.com)](https://github.com/binary-husky/gpt_academic/wiki/常见问题)进行查看！

### 环境配置

Attention：下述教程中的 gptac_venv 只是一个名字而已，可以随便命名，只要方便记忆即可，方便我们下次打开。

1. 创建 anaconda 环境

   ```python
   conda create -n gptac_venv pyhton=3.11
   ```

2. 激活 anaconda 环境

   ```python
   conda activate gptac_venv
   ```

5. 安装依赖

   ```python
   python -m pip install -r requirements.txt
   ```

### 下载项目

项目地址：[binary-husky/gpt_academic: 为GPT/GLM等LLM大语言模型提供实用化交互接口，特别优化论文阅读/润色/写作体验，模块化设计，支持自定义快捷按钮&函数插件，支持Python和C++等项目剖析&自译解功能，PDF/LaTex论文翻译&总结功能，支持并行问询多种LLM模型，支持chatglm3等本地模型。接入通义千问, deepseekcoder, 讯飞星火, 文心一言, llama2, rwkv, claude2, moss等。 (github.com)](https://github.com/binary-husky/gpt_academic)

也可以通过以下的一键命令进行下载，但提前是要安装好git,这里就先不介绍如何安装git了，大家可以直接浏览器搜索git进行下载

如果你已经有了git，那么我们可以使用一键命令

```python
git clone --depth=1 https://github.com/binary-husky/gpt_academic.git
```

```python
cd gpt_academic
```

如果你没有这个git, 我们可以手动进行安装！

```python
点击链接进入--code--Download Zip
```

### 配置API_key等变量

#### 代理配置

找到我们使用的代理的端口号，进入下载的学术版gpt的config.py程序，在这个配置文件里我们看到STEP2

其中的描述是这样的：

> 代理网络的地址，打开你的代理软件查看代理协议(socks5h / http)、地址(localhost)和端口(11284)
> 填写格式是 [协议]://  [地址] :[端口]，填写之前不要忘记把USE_PROXY改成True，如果直接在海外服务器部署，此处不修改
> <配置教程&视频教程> https://github.com/binary-husky/gpt_academic/issues/1>
> [协议] 常见协议无非socks5h/http; 例如 v2**y 和 ss* 的默认本地协议是socks5h; 而cl**h 的默认本地协议是http
> [地址] 填localhost或者127.0.0.1（localhost意思是代理软件安装在本机上）
> [端口] 在代理软件的设置里找。虽然不同的代理软件界面不一样，但端口号都应该在最显眼的位置上

大家如果有时间的话可以看下这个教程的视频信息，要是没时间的的话就打开我们的代理软件，找到我们的端口，然后将端口填入proxies中即可

> "http":  "http://127.0.0.1:？"
>
> 这里的问号就是我们要填写的端口信息，填进去就可以了

配置完成后先不急着叉掉，我们接着就进行API_key的配置。

#### Api_KEY 配置

我们现在滚动我们鼠标，来到配置文件的顶部，这里我们看到step1的内容

如果我们使用的官方的秘钥，我们就可以直接将我们的api_key填入其中保存就可以了

如果我们使用的是第三方中转的API，这时候我们要进行重定向操作，具体的重定向操作在github上面有详细的解释，我们只需要按照上面的文档进行操作就可以了。

### 运行

部署好之后，我们下一步进入运行阶段：

1. 打开搜索，输入anaconda,进入anaconda的终端

2. 找到我们的学术版gpt所在的文件夹

   ``` 
   cd 文件位置信息
   ```

3. 输入指令，激活我们的环境

   ```python
   conda activate gptac_venv
   ```

4. 运行main.py文件

   ``` python
   python main.py
   ```

当输入上述的指令之后，我们就进入到了学术版gpt的界面当中。

## fofa扫描

在开始教程之前，首先感谢@donggua大佬自建的fofa站点，让我可以更加顺利地写这个教程

### fofa站点信息

1. **https://fofa.guagua.info/**

   > 说明：此站点已经接入linux.do，需要进行认证才可以使用

2. [网络空间测绘，网络空间安全搜索引擎，网络空间搜索引擎，安全态势感知 - FOFA网络空间测绘系统](https://fofa.info/)

   > 说明：这个是官方的网站，可以通过这个进行搜索不止学术gpt一种资源！！

### 扫描指令

这里不得不感谢一下@Dawn Li大佬提供的两个指令

``` 
"GPT 学术优化"
```

```
"GPT 学术优化" && "gpt-4o"
```

### 站点信息

这里贴出来一些可以使用的学术版gpt信息

> http:*//119.23.218.27:12345* 
>
> http:*//47.93.81.131:85* 
>
> http:*//88.214.22.60:9999* 
>
> http:*//88.214.22.60:8888* 
>
> http:*//47.116.16.145:10492* 
>
> http:*//38.55.203.218:8001* 
>
> https:*//nsgzsupr.bja.sealos.run* 
>
> http:*//nsgzsupr.bja.sealos.run* 
>
> http:*//159.138.241.106:443* 
>
> http:*//43.159.139.30:5555* 
>
> http:*//43.251.102.231:9002*
