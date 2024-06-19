# RandomForestPTSDPredict
基于随机森林模型的多模态PTSD风险预测模型（第七届MAS案例分析大赛参赛作品）  
预测模型分为两个部分，第一部分为问卷数据PTSD风险预测模型，第二部分为多模态数据PTSD风险预测模型  
在程序开始执行后，需要选择是否可以提供脑电波数据，如果能够提供脑电波数据将自动进入多模态数据PTSD风险预测模型，否则将使用问卷数据PTSD风险预测模型  
在两个预测模型中，都需要用户通过回答问题的方式来完成问卷数据的填写  
脑电波数据（eeg.csv）需将列名按原意更改为Focus Relaxion Alpha1 Alpha2 Beta1 Beta2 Gamma1 Gamma2  

问卷预测系统可以通过下载Questionnaire.zip解压部署，多模态预测系统可以通过下载Multimodal.zip解压部署，运行app.py并按照错误提示安装需要的依赖包，正常运行后访问http://127.0.0.1:5000进行预测  
脑电波数据需要输入包括focus、relaxion、Alpha1、Alpha2、Beta1、Beta2、Gamma1、Gamma2列数据，如果数据不符合要求，无法输出预测结果  
问卷系统预览如下图所示  
![问卷系统预览](https://github.com/Walterman0628/RandomForestPTSDPredict/blob/main/images/Questionnaire.png)
