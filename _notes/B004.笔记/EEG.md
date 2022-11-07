---
cssclass: dashboard
banner: "![[截屏2022-07-19 14.27.20.png]]"
banner_y: 0.29143
---
# 一、理论知识

- #### 一、脑电的底层逻辑
	- 1.为什么能够记录到脑电信号？
		- [[首先，你得知道先什么是脑电信号]]
		- [[其次，你得知道脑电是怎么样被记录到]]
	- 2.[[如何从记录到的脑电信号中分析人类的大脑活动？]]
	- 3.[[脑电的本质，其实也是认知神经科学的本质]]
- #### 二、脑电的一般知识
	-  1.[[脑电信号采集设备]]
	-  2.[[脑电的参考电极]]
	-  3.[[脑电实验中常用的刺激呈现软件]]
	-  4.[[脑电分析中常用的工具包]]
	-  5.[[脑电技术的优缺点]]
	-  6.[[脑电技术的发展历程和趋势]]
	-  7[[脑电信号特征]]
	-  8[[脑电技术的应用]]
	-  9.[[脑电研究的一般流程]]
	-  10.[[别人的研究过程和思路]]

# 二、实战，两步走

- #### 首先，数据采集
	- [[脑电数据采集的整个流程]]
	- [[ 脑电数据采集的注意事项]]
- #### 然后，数据分析（脑电信号的分析；特征提取）
	- 1.记住脑电数据分析的核心
		- 脑电的分析方法一定要有针对性，针对特定的研究问题
			- 不同的分析方法适用的场景是不同的
		- 服务于你的研究目的（你想要回答什么问题）而选择最合适的信号提取方法
	- 2.脑电信号特征提取方式分类
		- [[01.静息态和任务态（根据被试所处状态）]]
		- 02.时间/频率/空间（根据关注的脑电信息划分）
			- ![[截屏2022-07-19 14.45.54.png]]
				- [[01.Event-related potentials]] ——只考察时间信息
				- [[02.Spectral Analysis]]  ——只考察时间信息
				- [[03.Time-Frequency Analysis]]  ——考察时间和频率信息
				- 04.Blind source separation ——时间和空间信息
				- 05.Microstate analysis  ——时间和空间信息
				- [[06.Source analysis]]       ——时间、频率和空间信息
				- 07.Sigle-trial analysis   ——  时间、频率和空间信息
				- 08.Nolinear neural dynamics ——时间信息
				- 09.Connectivity analysis  ——时间、频率和空间信息
				- 10.Spital complex network analysis  ——空间信息
				- 11.Temporal complext network analysis ——时间信息
				- 12.Machine Learning & deep learning   ——时间、频率和空间信息
	- 3.可以拿一些[[EEG 公开数据集整理]]去跑，来练手
	- 4.[[脑电信号特征提取-参考资料]]
# 三、学习资料与方案
- #### 脑电学习思路与规划
	- 1.继续学习基础知识，对脑电的底层逻辑了解深入
	- 2.针对特定的分析方法进行学习
		- 一个是阅读文献，看看在实验中的如何研究的
		- 一个是下载一些原始数据，然后进行分析
- #### 学习资料
	- 书籍
		- [[2019_Hu_EEG Signal Processin_KEY-ZJXFQ8GS]]
			- 也有中文版
	- 互联网散文/视频/讲座：
		- [悦影科技的个人空间_哔哩哔哩_bilibili](https://space.bilibili.com/506419394/channel/series)
		- 雷旭教授——[静息态EEG与静息态fMRI](https://www.bilibili.com/video/BV1zi4y147eu?spm_id_from=333.337.search-card.all.click&vd_source=025a435f75f64171dd9cd96896be80a4)
		- 系列讲座：
			- [脑电信号处理与特征提取](https://www.bilibili.com/video/BV1Sg411775g?vd_source=025a435f75f64171dd9cd96896be80a4)
				- [x] P1 胡理 
					- [x] 真的牛逼，听完对脑电非常通透
				- [ ] P2
				- [ ] P3
	- 文献
	- Onenote笔记
		- [【EEG信号分析笔记】——时频域分析 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/401681076)
		- [01.时域分析——叠加平均 ERP](onenote:https://d.docs.live.net/a129753ae8c2511f/Onenote%20文件/A2%20学术与科研/链接到Obsidian/01.时域分析——叠加平均%20ERP.one#section-id={8FA0B045-4CBE-6F4D-ABC8-F3F5C775B8F4}&end)  
		- [00.EEG整体](onenote:https://d.docs.live.net/a129753ae8c2511f/Onenote%20文件/A2%20学术与科研/链接到Obsidian/00.EEG整体.one#section-id={9C6B2330-DDA8-614D-9E93-C048818B1C86}&end)  