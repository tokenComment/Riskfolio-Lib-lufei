量化战略资产配置，人人皆可轻松实现。



 


在 ko-fi.com 给我买杯咖啡

GitHub 星标 下载 下载 文档状态 GitHub 许可证 活页夹

星空历史图

描述
Riskfolio-Lib 是一个由秘鲁🇵🇪开发的 Python 库，用于进行量化战略资产配置或投资组合优化。其目标是帮助学生、学者和从业人员轻松构建基于数学复杂模型的投资组合。它基于 CVXPY构建，并与Pandas数据结构紧密集成。

Riskfolio-Lib 提供的一些主要功能：

平均风险和对数平均风险（凯利准则）投资组合优化，具有 4 个目标函数：

最低风险。
最大回報。
最大效用函数。
最大风险调整回报率。
具有 24 个凸风险度量的平均风险和对数平均风险（凯利准则）投资组合优化：

分散风险措施：

标准差。
平方根峰度。
平均绝对偏差（MAD）。
基尼均值差（GMD）。
条件风险价值范围。
尾部基尼范围。
风险范围内的熵值。
相对风险价值范围。
范围。  
下行风险衡量指标：

半标准差。
平方根半峰度。
第一下偏矩（欧米茄比率）。
第二下偏矩（索蒂诺比率）。
条件风险价值（CVaR）。
尾基尼。
熵风险价值（EVaR）。
相对风险价值（RLVaR）。
最坏情况实现（最小极大值）。  
回撤风险措施：

非复利累计收益的平均回撤。
溃疡指数为非复利累计收益。
非复利累积收益的条件风险回撤 (CDaR)。
非复利累积收益的风险熵回撤 (EDaR)。
非复利累积收益的相对风险回撤 (RLDaR)。
非复利累积收益的最大回撤（卡尔玛比率）。
具有 20 个凸风险度量的风险平价投资组合优化：

分散风险措施：

标准差。
平方根峰度。
平均绝对偏差（MAD）。
基尼均值差（GMD）。
条件风险价值范围。
尾部基尼范围。
风险范围内的熵值。
相对风险价值范围。  
下行风险衡量指标：

半标准差。
平方根半峰度。
一阶下偏矩（欧米茄比率）
二阶下偏矩（索蒂诺比率）
条件风险价值（CVaR）。
尾基尼。
熵风险价值（EVaR）。
相对风险价值（RLVaR）。  
回撤风险措施：

溃疡指数为非复利累计收益。
非复利累积收益的条件风险回撤 (CDaR)。
非复利累积收益的风险熵回撤 (EDaR)。
非复利累积收益的相对风险回撤 (RLDaR)。
层次聚类投资组合优化：采用朴素风险平价的层次风险平价 (HRP) 和层次平等风险贡献 (HERC)，包含 35 种风险度量：

分散风险措施：

标准差。
方差。
平方根峰度。
平均绝对偏差（MAD）。
基尼均值差（GMD）。
风险价值范围。
条件风险价值范围。
尾部基尼范围。
风险范围内的熵值。
相对风险价值范围。
范围。  
下行风险衡量指标：

半标准差。
四次根半峰度。
第一下偏矩（欧米茄比率）。
第二下偏矩（索蒂诺比率）。
风险价值（VaR）。
条件风险价值（CVaR）。
尾基尼。
熵风险价值（EVaR）。
相对风险价值（RLVaR）。
最坏情况实现（最小极大值）。  
回撤风险措施：

复合和非复合累计收益的平均回撤。
溃疡指数的复合和非复合累计收益。
复合和非复合累积收益的风险回撤 (DaR)。
复合和非复合累积收益的条件风险回撤 (CDaR)。
复合和非复合累积收益的风险熵回撤 (EDaR)。
复合和非复合累积收益的相对风险回撤 (RLDaR)。
复合和非复合累积收益的最大回撤（卡尔玛比率）。
嵌套聚类优化 (NCO) 具有四个目标函数以及针对每个目标的可用风险度量：

最低风险。
最大回報。
最大效用函数。
平等风险贡献。
最坏情况均值方差投资组合优化。

宽松风险平价投资组合优化。

有序加权平均（OWA）投资组合优化。

使用 Black Litterman 模型进行投资组合优化。

利用风险因素模型进行投资组合优化。

使用 Black Litterman 贝叶斯模型进行投资组合优化。

使用增强型黑利特曼模型进行投资组合优化。

具有跟踪误差和周转率约束的投资组合优化。

通过空头头寸和杠杆投资组合进行投资组合优化。

对资产数量和有效资产数量进行约束的投资组合优化。

基于图形信息的约束投资组合优化。

对方差风险贡献具有不等式约束的投资组合优化。

对方差的因子风险贡献进行不等式约束的投资组合优化。

为 24 个凸风险度量构建有效前沿的工具。

对资产、资产类别和风险因素建立线性约束的工具。

建立资产和资产类别观点的工具。

建立风险因素观点的工具。

用于为每个资产类别建立风险贡献约束的工具。

使用明确的风险因素和主要成分来构建每个风险因素的风险贡献约束的工具。

为层次聚类投资组合构建边界约束的工具。

计算风险度量的工具。

计算每项资产风险贡献的工具。

计算每个风险因素的风险贡献的工具。

计算均值向量和协方差矩阵的不确定性集的工具。

根据相互依赖指标计算资产集群的工具。

估计载荷矩阵的工具（逐步回归和主成分回归）。

可视化投资组合属性和风险衡量的工具。

在 Jupyter Notebook 和 Excel 上构建报告的工具。

对于大规模问题，可选择使用 MOSEK 或 GUROBI 等商业优化求解器。

文档
在线文档可在文档中找到。

该文档包含一个带有示例的教程 ，展示了 Riskfolio-Lib 的功能。

选择求解器
由于 Riskfolio-Lib 基于 CVXPY，因此 Riskfolio-Lib 可以使用与 CVXPY 相同的求解器。与 CVXPY 兼容的求解器列表可在CVXPY 文档的“选择求解器”部分找到。但是，为了为每个风险度量选择合适的求解器，我们可以使用下表，该表指定了用于建模每个风险度量的编程技术类型。

风险度量	LP	量子点	索科普	社会民主党	经验值	战俘
方差（MV）			十	X*		
平均绝对偏差（MAD）	十					
基尼均值差（GMD）						X**
半方差（MSV）			十			
峰度（KT）				十		
半峰度 (SKT)				十		
一阶低偏矩（FLPM）	十					
二阶低偏矩（SLPM）			十			
条件风险价值（CVaR）	十					
尾基尼系数 (TG)						X**
熵风险价值（EVaR）					十	
相对风险价值（RLVaR）						X**
最坏实现（WR）	十					
CVaR范围（CVRG）	十					
尾部基尼范围（TGRG）						X**
EVaR范围（EVRG）					十	
RLVaR 范围 (RVRG)						X**
射程（RG）	十					
平均回撤 (ADD)	十					
溃疡指数（UCI）			十			
有条件风险回撤 (CDaR)	十					
熵减风险（EDaR）					十	
相对风险回撤（RLDaR）						X**
最大回撤（MDD）	十					
（*）包含 SDP 图论约束。对于整数规划图论约束，模型假设 SOCP 公式。

(**) 对于这些模型，强烈建议使用 MOSEK 作为求解器，因为在某些情况下 CLARABEL 无法找到解决方案，而 SCS 需要花费太多时间来解决它们。

LP——线性规划是指具有线性目标函数和线性约束的问题。

QP - 二次规划是指具有二次目标函数和线性约束的问题。

SOCP - 二阶锥规划是指具有二阶锥约束的问题。

SDP——半定规划是指具有正半定约束的问题。

EXP——指具有指数锥约束的问题。

POW——指具有三维功率锥约束的问题。

依赖项
Riskfolio-Lib 支持 Python 3.9 或更高版本。

安装需要：

numpy >= 1.24.0
scipy >= 1.10.0
Pandas >= 2.0.0
matplotlib >= 3.8.0
克拉贝尔>= 0.6.0
cvxpy >= 1.5.2
scikit-learn >= 1.3.0
统计模型>=0.13.5
arch >= 7.0
xlsxwriter >= 3.1.2
networkx >= 3.0
天体学>= 5.1
pybind11 >= 2.10.1
安装
可以从 PyPI 安装最新的稳定版本（和旧版本）：

pip install riskfolio-lib
引用
如果您使用 Riskfolio-Lib 发表作品，请使用以下 BibTeX 条目：

@misc{riskfolio,
      author = {Dany Cajas},
      title = {Riskfolio-Lib (7.0.0)},
      year  = {2025},
      url   = {https://github.com/dcajasn/Riskfolio-Lib},
      }
发展
Riskfolio-Lib 的开发在 Github 上进行：https://github.com/dcajasn/Riskfolio-Lib

咨询费
Riskfolio-Lib 是一个开源项目，但由于该项目没有任何机构资助，因此我开始对与源代码错误无关的咨询服务收费。我们的收费标准如下：

每个不需要检查代码的问题收费 25 美元（美元）。
检查小型脚本或代码（少于 200 行）的费用为 50 美元。解决方案的费用取决于解决方案的复杂程度：
脚本中的简单错误（修改少于 10 行代码）收费 50 美元。
对于大多数复杂错误，费用取决于解决方案的复杂性，但费用为每小时 150 美元。
检查中等大小的脚本或代码（201 至 600 行代码）的费用为 100 美元。解决方案的费用取决于解决方案的复杂程度：
脚本中的简单错误（修改少于 10 行代码）收费 50 美元。
对于大多数复杂错误，费用取决于解决方案的复杂性，但费用为每小时 150 美元。
对于大型脚本或代码（超过 600 行），费用将根据代码大小而有所不同。解决方案的费用取决于解决方案的复杂程度：
脚本中的简单错误（修改少于 10 行代码）收费 50 美元。
对于大多数复杂错误，费用取决于解决方案的复杂性，但费用为每小时 150 美元。
所有咨询费用必须提前付款。

您可以通过以下方式联系我：

LinkedIn
Gmail
您可以使用以下任一渠道付款：

Github赞助

在 ko-fi.com 给我买杯咖啡

路线图
该模块的计划是添加更多对资产管理者非常有用的功能。

根据用户建议添加更多功能。