# FD-SD
datasets in UP-SDCG

本仓库存储论文[**UP-SDCG: A Method of Sensitive Data Classification for Collaborative Edge Computing in Financial Cloud Environment**](https://www.mdpi.com/1999-5903/16/3/102)使用的仿真数据集。

参照银行机构数据特征，该仿真数据集涉及三大种类：员工信息、项目以及合同。实验数据概况如表 [1](#table-3-5) 所示：

### 表 1 仿真测试数据概况
| 数据集   | 行数    | 列数  | 敏感列 | 非敏感列 | 敏感类型                      |
|----------|---------|-------|---------|----------|-------------------------------|
| 员工信息 | 22,618  | 111   | 19      | 92       | 姓名, 性别, 手机号码, 电子邮箱等 |
| 项目信息 | 23,208  | 301   | 31      | 270      | 项目中涉及到的部门、个人信息    |
| 合同信息 | 6,351   | 37    | 15      | 22       | 合同协议信息                  |

### 数据集描述
1. **员工信息数据**:  
   员工信息数据集包含 111 列，共 22,618 条数据，包括员工姓名、性别、工号、手机号、邮箱、部门、职务等信息。

2. **项目数据**:  
   项目数据集是银行立项项目的基本信息，包含 301 列，共 23,208 条数据。其中包含项目涉及的人员及部门信息、项目预算等。此外，数据中存在大量缺失值。

3. **合同数据**:  
   合同数据集包含 37 列，共 6,351 条数据，涉及合同基本信息以及供应商信息。
