# 跨摄像头指定行人跟踪：追踪（Tracking）

Created by Ya-Nan Chen at IAIR, Xi’an Jiaotong University.

### 介绍

多目标追踪 MDP_tracking ，对作者源码进行了大幅度的性能改进，运行速度和内存占用都有巨大的改善，算法的各种评测指标基本保持不变.在全国研究生智慧城市大赛的擂台赛阶段，排名第7，最终获得全国三等奖.

**Tracking算法**：**MDP_Tracking**

    @inproceedings{xiang2015learning,
        Author = {Xiang, Yu and Alahi, Alexandre and Savarese, Silvio},
        Title = {Learning to Track: Online Multi-Object Tracking by Decision Making},
        Booktitle = {International Conference on Computer Vision (ICCV)},
        Year = {2015}
    }

### 运行环境配置

1. 安装**opencv**.
2. 正确配置**compile.m**中opencv的相关路径，之后运行.

### 在新的数据集上运行

1. 正确设置**globals.m**中的相关变量（包括seq_format, det_dir, test_seqs_name, seq_dir_base, final_results).
	- **seq_format**: 图片名称格式.
	- **det_dir**: 检测结果目录.
	- **test_seqs_name**: 追踪视频的名字.
	- **seq_dir_base**: 追踪图片的存放目录.
	- **final_results**: 追踪结果的输出目录.
2. 运行**MDP_debug.m**.

### Contact
个人主页： https://chenyncv.github.io/
