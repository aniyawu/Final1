# Final1
## 项目简介
本项目旨在通过 ARIMA 和 LSTM 两种时间序列分析模型对微软公司的历史股价数据进行预测。该研究通过比较这两种模型在不同市场条件下的表现，探讨了它们在股价预测方面的优势和局限性。ARIMA 模型适用于处理线性关系和稳定的时间序列，而 LSTM 模型则能处理更复杂的非线性模式和长期依赖关系。本项目提供了完整的代码实现，用于实现和验证这两种模型在股价预测中的应用。
## 复现说明
### 运行环境
Python 版本：3.7 或更高    
主要依赖包：     
pandas：用于数据处理     
numpy：用于数值计算     
matplotlib：用于绘图     
sklearn：提供数据预处理工具     
tensorflow / keras：用于构建和训练 LSTM 模型     
statsmodels：用于构建 ARIMA 模型     
### 安装依赖包
在复现代码前，请确保安装了所有必要的依赖包。可以使用以下命令进行安装：pip install pandas numpy matplotlib sklearn tensorflow statsmodels
### 数据集
本报告所使用的数据来源于Kaggle 网站，该数据集包含了微软股票2015.04.01到2021.03.31价格变化的具体信息，用于对金融市场分析和时间序列预测研究。     
来源网站：Kaggle (www.kaggle.com)     
数据集名称：Microsoft Stock- Time Series Analysis     
发布者：VIJAY V VENKITESH     
数据集链接：Microsoft Stock- Time Series Analysis (kaggle.com)     
### 复现步骤
跟随文档中的文字指引，在 Python 环境中逐个运行提供的代码单元格即可成功复现。     
1.数据预处理：使用 pandas 加载股价数据，对数据进行必要的清洗和格式转换。     
2.数据可视化：直观查看数据的多项信息。     
3.ARIMA 模型：使用 statsmodels 库构建 ARIMA 模型，根据 ACF 和 PACF 确定 ARIMA 模型的参数，训练模型并进行预测。     
4.LSTM 模型：使用 sklearn 进行数据归一化处理，构建 LSTM 网络模型，训练模型并进行预测。     
5.结果评估和可视化：使用 matplotlib 绘制真实值与预测值的对比图，计算并比较两种模型的性能指标。     
## 注意事项
股价预测可能受多种因素影响，包括市场波动、经济状况等，因此建议将本项目作为学术研究或模型学习的参考，而非实际投资决策依据。
##### 如遇到任何问题，请通过邮箱与我联系。
