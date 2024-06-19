# RandomForestPTSDPredict
基于随机森林模型的多模态PTSD风险预测模型（第七届MAS案例分析大赛参赛作品）  
预测模型分为两个部分，第一部分为问卷数据PTSD风险预测模型，第二部分为多模态数据PTSD风险预测模型  
在程序开始执行后，需要选择是否可以提供脑电波数据，如果能够提供脑电波数据将自动进入多模态数据PTSD风险预测模型，否则将使用问卷数据PTSD风险预测模型  
在两个预测模型中，都需要用户通过回答问题的方式来完成问卷数据的填写  
脑电波数据（eeg.csv）需将列名按原意更改为Focus Relaxion Alpha1 Alpha2 Beta1 Beta2 Gamma1 Gamma2  
  
问卷系统预览如下图所示
![问卷系统预览](https://github.com/Walterman0628/RandomForestPTSDPredict/blob/main/images/Questionnaire.png)
