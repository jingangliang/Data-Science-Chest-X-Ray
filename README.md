# 【跟我学】三步创建可复用的肺炎检测模型

*声明：本示例仅用于演示产品功能，肺炎检测算法仅供学习、研究使用，请谨慎用于实际生产环境。所用算法源于Github和Kaggle的开源项目，项目地址见文末附录。*
***
Oracle Data Science可以让数据科学家快速在Oracle公有云上搭建数据科学平台，在Oracle Data Science当中集成了数据分析和机器学习经常使用的工具包和插件。除了提供稳定、灵活的数据科学开发环境之外，Oracle Data Science还配备了独有的模型目录（Model Catalog）和Oracle Accelerated Data Science SDK（加速数据科学包，简称ADS），能让数据科学团队的工作更加高效和便捷。

## 模型目录简介 
在Oracle Data Science平台，模型指的是定义数据和处理流程的数学表示。模型目录是存储、跟踪、共享和管理模型的地方，可以直接在OCI页面访问。
数据科学团队通过模型目录实现了模型的可审计性和再现性。其功能包括：

跟踪模型元数据（创建者、创建日期、名称、出处）；

在服务托管对象存储中保存模型构件；

将模型加载到notebook session中等等。 

## ADS简介 
Oracle Accelerated Data Science（ADS）SDK是一个Python库，已预置在Data Science服务当中。ADS提供一系列工具，使数据科学任务更快、更容易、更不易出错。
ADS设计了友好的用户交互，可自动化或简化数据科学工作流程中的许多步骤，包括：连接数据；浏览和可视化数据；使用AutoML同时训练多个模型；评估模型；解释模型等等。

此外，用户可以通过ADS来访问模型目录和其他Oracle Cloud Infrastructure服务（包括对象存储）。

