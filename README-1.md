# NVIDIA-GPU
# README

## 项目定位

​	随着人工智能技术的不断发展，情感计算随之成为一个新兴研究领域，在当前表情识别研究中，可识别的表情基本分为高兴、悲 伤、生气、惊讶、恐惧、厌恶和中立七种表情。这些表情较为常见和明显，一定程度上能够反映出真实的心理情绪，从而使计算机理解人类的情感。其目的是通过赋予计算机类似于人一样的识别、理解、表达和适应情感的能力，来建立更加和谐便捷的人机环境，最终使计算机能和人进行自然、亲切和生动的交互，从而使 计算机具有更高、更全面的智能。

项目内容具体体现在以下两个方面：

​	1.基于深度学习的人脸表情识别算法的调研和改进。通过研究人脸表情识别所需的基本步骤及其实现方法，确定使用基于卷积神经网络的算法来实现人脸表情识别。接着对 CNN 的基本原理及其发展进行研究和学习，确定mini_Xception 算法可较好完成表情识别任务。并在此算法的基础上做出改进，使表情识别率在数据集上有所提升，并取得较好的实际识别效果。 

​	2.改进的人脸表情识别算法在智能机器人上实施和实现。本次研究通过 NAO 机器人官方网站 了解 NAO 机器人的基本信息和功能，并学习 NAO 机器人编程，最终实现 NAO 机器人应用本课题改进的算法进行人脸表情识别。

## 环境依赖

Pycharm

VS2015

Anaconda3.6

CUDA9.0

cudnn-9.0-windows10-x64-v7

## 部署步骤

1. 安装环境搭建


2. 模型训练

3. 模型算法测试

4. NAO机器人利用训练好的模型进行表情识别

├── Readme.md                   // help
├── config                      // 配置
│   ├── default.json
│   ├── dev.json                // 开发环境
│   ├── experiment.json         // 实验
│   ├── index.js                // 配置控制
│   ├── local.json              // 本地
│   ├── production.json         // 生产环境
│   └── test.json               // 测试环境
├── data
├── doc                         // 文档
├── environment
├── gulpfile.js
├── locales
├── logger-service.js           // 启动日志配置
├── node_modules
├── package.json
├── app-service.js              // 启动应用配置
├── static                      // web静态资源加载
│   └── initjson
│       └── config.js         // 提供给前端的配置
├── test
├── test-service.js
└── tools



## V1.0.0 版本内容更新

1. 注册GitHub账号
2. 建立GitHub代码仓库
3. 将项目代码发布到GitHub
4. 在仓库的主分支里创建一个 /docs/index.md 文件
5. 把内容以 Jekyll 格式添加进去，并提交修改
6. 上传REAMED\INSTALL\FAQ\CREDITS\HISTORY\LICENSE .md文档
