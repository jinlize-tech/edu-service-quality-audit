# G5/G9 产品修改记录

- 产品编号：$(@{number=92; product_id=JLZ-EDU-SK-074; chinese_name=服务质量检查; english_name=Service Quality Audit; repository_name=edu-service-quality-audit; repository_url=https://github.com/jinlize-tech/edu-service-quality-audit; product_type=Skill; category_code=08; category=08 校区标准化与多校区管理中心; description=服务质量检查。; target_users=System.Object[]; core_input=服务对象、服务标准、触点、样本、证据和投诉数据; main_output=服务质量评分表、证据记录、问题分级、根因假设和整改建议; product_risk=样本偏差、主观评价或暴露家长信息; dedup_label=存在部分功能交叉; dedup_note=与教学服务标准核查区别：本产品跨校区服务触点审计；后者聚焦教学服务交付。; development_status=Planned / 待研发; license=Apache-2.0; spec_version=1.0.0; workbuddy_status=PLANNED_FOR_WORKBUDDY}.product_id)
- 产品名称：服务质量检查
- 基线：EDUCATION_BASELINE_V1.0.0
- 基线提交：$BaselineCommit
- 原版本：1.0.0
- 新版本：1.0.1

## 本次修改

1. 强化产品专属执行流程、输入核对和输出验收规则。
2. 新增 scripts/validate_input.js，实际检查必填字段、冲突、未确认数据和敏感信息。
3. 新增正常、缺失、冲突、敏感信息和非法JSON场景输入。
4. 测试升级为 T1–T7 分层并保存逐项检查结果。
5. 安装包加入 Apache-2.0 LICENSE 和 THIRD_PARTY_NOTICES.md。
6. 安装包升级为 1.0.1，加入许可证、第三方声明和输入校验脚本，保留 1.0.0 ZIP。
7. 按本产品冻结规格补充专属处理规则、输入到成果的核对矩阵和去重边界。

## 产品专属增强

- 核心任务：服务质量检查。
- 主要风险：样本偏差、主观评价或暴露家长信息
- 去重边界：与教学服务标准核查区别：本产品跨校区服务触点审计；后者聚焦教学服务交付。

- 先明确标准版本、适用校区、检查范围、证据来源和例外条件。
- 按流程节点核对责任人、输入、完成标准、输出和升级机制。
- 区分现状证据、标准要求、差距、影响、整改动作和复验标准。
- 不代替机构作出处罚、人事、财务或行政批准决定。

## 运行边界

- 本地模型行为：NOT_RUNTIME_VERIFIED
- WorkBuddy平台验证：WORKBUDDY_VALIDATION_NOT_IN_SCOPE
- 本轮不执行上传、安装、审核或正式发布。
