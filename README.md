# 开放平台概述
欢迎使用炼金台助贷风控服务。炼金台与平台方合作，帮助核心企业实施上下游贷款业务。通过风险清洗筛掉不良客户，并将合格客户的不规则数据“冶炼” 成标准的**风控半成品**，批量推送给金融机构。

· 万能插头，平台方、金融机构无需IT开发，快速对接。

· 在线融资，数据无缝推入金融机构，节省大量人工，风险预处理，流水线式“信贷工厂”。


## 发布历史
V1.0 2016年8月12日
推贷接口初始版本

V1.1 2016年8月22日
修正文档错误，为符合银行端要求，增加身份证有效期

V1.2 2016年11月2日
增加测试环境介绍

V1.3 2017年1月5日
为适应资产端要求，减少必需字段

V1.4 2017年2月9日
融资申请创建接口优化：
- 到期日改为非必须
- 业务期限字段 长度缩短为6位整数
- 增加 mtTimeCd 业务期限类型字段
- cust_id 字段改为驼峰命名规则 custId

V1.5 2017年4月18日
融资申请创建接口优化：
- 担保方式类型字段 优化为：mtCollStyleCd，避免与担保类型混淆

V1.6 2017年5月12日
新增接口：
- 申请材料上传
- 企业财报上传
- 放款信息反馈
- 交易流水查询
- 还款计划查询
- 对账文件下载

V1.7 2018年1月17日
增加授信状态变更回调接口
融资申请创建接口优化：
- 增加还款卡号和回调URL

V1.8 2018年9月6日
增加企业财务报表保存接口
