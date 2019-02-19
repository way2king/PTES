
<ul>
<li class="toclevel-1 tocsection-1"><a href="#Overview"><span class="tocnumber"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1 </font></font></span> <span class="toctext"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">概述</font></font></span></a></li>
<li class="toclevel-1 tocsection-2"><a href="#Report_Structure"><span class="tocnumber"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2 </font></font></span> <span class="toctext"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">报告结构</font></font></span></a></li>
<li class="toclevel-1 tocsection-3"><a href="#The_Executive_Summary"><span class="tocnumber"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">3 </font></font></span> <span class="toctext"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">执行摘要</font></font></span></a></li>
<li class="toclevel-1 tocsection-4"><a href="#Technical_Report"><span class="tocnumber"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4 </font></font></span> <span class="toctext"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">技术报告</font></font></span></a></li>
</ul>
</div>

<h2><span class="mw-headline" id="Overview"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">概观</font></font></span></h2>
<p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本文档旨在定义渗透测试报告的基本标准。</font><font style="vertical-align: inherit;">虽然强烈建议您使用自己的自定义和品牌格式，但以下内容应能够高度理解报告中所需的项目以及报告的结构，以便为读者提供价值。 
</font></font></p>
<h2><span class="mw-headline" id="Report_Structure"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">报告结构</font></font></span></h2>
<p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该报告分为两（2）个主要部分，以便向各种受众传达测试的目标，方法和结果。 
</font></font></p>
<h2><span class="mw-headline" id="The_Executive_Summary"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">执行摘要</font></font></span></h2>
<p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本节将向读者传达渗透测试的具体目标和测试练习的高级结果。</font><font style="vertical-align: inherit;">目标受众将是那些负责安全计划的监督和战略愿景的人员，以及可能受到已识别/确认的威胁影响的组织的任何成员。</font><font style="vertical-align: inherit;">执行摘要应包含大部分（如果不是全部）以下部分：
</font></font></p><p><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">背景：</font></font></b>
</p><p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">背景部分应向读者解释测试的总体目的。</font><font style="vertical-align: inherit;">应提供有关风险，对策和测试目标的预参与部分中确定的条款的详细信息，以便将读者与整体测试目标和相关结果联系起来。
</font></font></p><p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（示例：（CLIENT）任务&lt;Pentester&gt;执行内部/外部漏洞评估和位于（逻辑区域或物理位置）的特定系统的渗透测试。这些系统已被识别为（风险等级）并包含（数据分类级别） ）如果访问不当，可能会对（客户端）造成重大损害。为了测试（CLIENT）抵御直接和间接攻击的能力，&lt;Pentester&gt;执行了全面的网络漏洞扫描，漏洞构造（&lt;-insert商定的攻击类型 - &gt;）利用弱化服务，客户端攻击，浏览器端攻击（等）此评估的目的是验证（CLIENT）为保护关键业务信息而实施的安全控制的有效性。本报告代表评估结果和相关的补救建议，以帮助客户加强其安全态势。
</font></font></p>
<ul><li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果在测试过程中更改了目标，则必须在报告的此部分中列出所有更改。</font><font style="vertical-align: inherit;">此外，修正函应包括在报告的附录中，并与本节相关联。</font></font></li></ul>
<p><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">整体姿势：</font></font></b>
</p><p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该领域将描述测试的整体有效性以及测试者在预约课程中实现目标的能力。</font><font style="vertical-align: inherit;">通过测试过程确定的Systemic（例如系统性问题=缺乏有效补丁管理流程与Symptomatic =发现MS08-067缺少xyz框）的简要描述以及实现对目标信息的访问和识别的能力对业务的潜在影响。
</font></font></p><p><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">风险排名/简介：</font></font></b>
</p><p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将在该领域中识别和解释总体风险等级/概况/分数。</font><font style="vertical-align: inherit;">在预接合部分，Pentester将确定评分机制和跟踪/评级风险的个人机制。</font><font style="vertical-align: inherit;">来自FAIR，DREAD和其他自定义排名的各种方法将合并到环境评分中并进行定义。
</font></font></p><p><a href="/index.php/File:Reporting-risk-scale.png" class="image"><img alt="报告 - 风险scale.png" src="/images/8/82/Reporting-risk-scale.png" width="690" height="547"></a>
</p><p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（CLIENT）的“总体风险评分”目前为七（7）。</font><font style="vertical-align: inherit;">该评级意味着安全控制的高风险可能会受到重大财务损失的影响。</font><font style="vertical-align: inherit;">顾问根据一个高风险和几个中等风险漏洞以及定向攻击的成功确定了这一风险评分。</font><font style="vertical-align: inherit;">确定的最严重漏洞是公司面向公众网站中存在默认密码，允许访问许多敏感文档以及控制设备上内容的能力。</font><font style="vertical-align: inherit;">此漏洞可能导致用户帐户被盗，敏感信息泄漏或完全系统受损。</font><font style="vertical-align: inherit;">几个较小的严重漏洞可能导致有效帐户凭据被盗和信息泄露。
</font></font></p><p><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一般调查结果：</font></font></b>
</p><p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一般性调查结果将以基本和统计格式提供渗透测试期间发现的问题的概要。</font><font style="vertical-align: inherit;">应该存在所测试目标的图形表示，测试结果，过程，攻击情景，成功率以及在预约定会议中定义的其他可趋势指标。</font><font style="vertical-align: inherit;">此外，问题的原因应以易于阅读的格式呈现。</font><font style="vertical-align: inherit;">（例如，显示被利用问题的根本原因的图表）
</font></font></p><p><a href="/index.php/File:Risk-origin.png" class="image"><img alt="风险origin.png" src="/images/4/43/Risk-origin.png" width="754" height="452"></a>
</p><p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果在预先参与活动中定义，该区域还应包括描述环境中对策的有效性的指标。</font><font style="vertical-align: inherit;">（例如，我们运行x攻击和IPS阻止y。其他对策也应该具有类似的设计与效果指标。）
</font></font></p><p><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">建议摘要：</font></font></b>
</p><p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">报告的建议部分应使读者高度了解解决所识别风险所需的任务以及实施建议的解决途径所需的一般工作量。</font><font style="vertical-align: inherit;">本节还将确定用于确定以下路线图顺序优先顺序的加权机制。
</font></font></p><p><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">战略路线图：</font></font></b>
</p><p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">路线图应包括一个优先计划，用于修复发现的不安全项目，并应根据业务目标/潜在影响程度进行权衡。</font><font style="vertical-align: inherit;">此部分应直接映射到已识别的目标以及在PTES-Threat建模部分中创建的威胁矩阵。</font><font style="vertical-align: inherit;">通过分解为预定义的基于时间/目标的目标，本节将创建一个以不同增量遵循的操作路径。</font><font style="vertical-align: inherit;">例：
</font></font></p><p><a href="/index.php/File:Roadmap1.png" class="image"><img alt="Roadmap1.png" src="/images/9/92/Roadmap1.png" width="549" height="190"></a>
</p><p><a href="/index.php/File:Roadmap2.png" class="image"><img alt="Roadmap2.png" src="/images/6/6f/Roadmap2.png" width="550" height="419"></a>
</p><p><a href="/index.php/File:Roadmap3.png" class="image"><img alt="Roadmap3.png" src="/images/8/8a/Roadmap3.png" width="547" height="283"></a>
</p>
<h2><span class="mw-headline" id="Technical_Report"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">技术报告</font></font></span></h2>
<p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本节将向读者传达测试的技术细节以及在参与前练习中作为关键成功指标达成一致的所有方面/组件。</font><font style="vertical-align: inherit;">技术报告部分将详细描述测试的范围，信息，攻击路径，影响和补救建议。
</font></font></p><p><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">介绍：</font></font></b>
</p><p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">技术报告的引言部分旨在作为以下的初始清单：
</font></font></p>
<ul><li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">客户和渗透测试团队参与测试的人员</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">联系信息</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">参与测试的资产</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测试目标 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测试范围 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测试强度 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">途径 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">威胁/评分结构 </font></font></li></ul>
<p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本节应作为测试所涉及的具体资源和测试的整体技术范围的参考。
</font></font></p><p><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">信息收集：</font></font></b>
</p><p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">情报收集和信息评估是良好渗透测试的基础。</font><font style="vertical-align: inherit;">测试人员对环境的了解越多，测试结果就越好。</font><font style="vertical-align: inherit;">在本节中，应编写许多项目，以向客户显示通过执行PTES的情报收集阶段可获得的公共和私人信息的范围。</font><font style="vertical-align: inherit;">至少，确定的结果应以4个基本类别列出：
</font></font></p><p><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">被动智力：</font></font></b>
</p><p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过间接分析收集情报，例如DNS，Google支持IP /基础设施相关信息。</font><font style="vertical-align: inherit;">本节将重点介绍用于在CLIENT环境中分析技术的技术，而不会直接向资产发送任何流量。
</font></font></p><p><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">主动情报：</font></font></b>
</p><p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本节将介绍基础架构映射，端口扫描，架构评估和其他脚印活动等任务的方法和结果。</font><font style="vertical-align: inherit;">本节将重点介绍通过直接向资产发送流量来在CLIENT环境中分析技术的技术。
</font></font></p><p><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">企业情报：</font></font></b>
</p><p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关组织结构，业务单位，市场份额，垂直和其他公司职能的信息应映射到业务流程和先前确定的被测物理资产。
</font></font></p><p><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">人事情报：</font></font></b> 
</p><p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在情报收集阶段发现的任何和所有信息，用户将用户映射到CLIENT组织。</font><font style="vertical-align: inherit;">本节应显示用于收集情报的技术，例如公共/私人员工仓库，邮件存储库，组织结构图和其他导致员工/公司连接的项目。
</font></font></p><p><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">漏洞评估：</font></font></b>
</p><p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">漏洞评估是识别TEST中存在的潜在漏洞以及每种威胁的威胁分类的行为。</font><font style="vertical-align: inherit;">在本节中，应该提供用于识别漏洞的方法的定义以及漏洞的证据/分类。</font><font style="vertical-align: inherit;">此外，本节还应包括：
</font></font></p>
<ul><li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">漏洞分类级别 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">技术漏洞 
</font></font><ul><li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OSI Layer Vulns </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">扫描仪找到了 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">手动识别 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">整体曝光 </font></font></li></ul></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">逻辑漏洞 
</font></font><ul><li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">NON OSI Vuln </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型的vuln </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何/在哪里找到它 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">曝光 </font></font></li></ul></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">结果摘要</font></font></li></ul>
<p><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">漏洞利用/漏洞确认：</font></font></b>
</p><p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">漏洞利用或漏洞确认是触发前面部分中识别的漏洞以获得对目标资产的指定访问级别的行为。</font><font style="vertical-align: inherit;">本节应详细审查确认已定义漏洞所采取的所有步骤以及以下内容：
</font></font></p>
<ul><li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开发时间表 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">选择用于利用的目标 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开发活动 
</font></font><ul><li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">定向攻击 
</font></font><ul><li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目标主机无法被利用 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目标主机可以被利用 
</font></font><ul><li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">个人主机信息 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">进行了攻击 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">攻击成功 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">访问级别授予+升级路径 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">整治 
</font></font><ul><li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">链接到Vuln部分参考 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">额外的缓解技术 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">补偿控制建议 </font></font></li></ul></li></ul></li></ul></li></ul></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">间接攻击 
</font></font><ul><li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">网络钓鱼 
</font></font><ul><li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">时间表/攻击细节 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">确定了目标 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">成功/失败率 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">授予的访问级别</font></font></li></ul></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">客户端 
</font></font><ul><li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">时间表/攻击细节 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">确定了目标 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">成功/失败率 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">授予的访问级别 </font></font></li></ul></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">浏览器方面 
</font></font><ul><li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">时间表/攻击细节 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">确定了目标 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">成功/失败率 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">授予的访问级别</font></font></li></ul></li></ul></li></ul>
<p><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">后利用：</font></font></b>
</p><p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">所有测试中最关键的项目之一是与正在测试的客户端的ACTUAL影响的连接。</font><font style="vertical-align: inherit;">虽然上面的部分介绍了漏洞的技术性质以及成功利用漏洞的能力，但是后开发部分应该将利用的能力与企业的实际风险联系起来。</font><font style="vertical-align: inherit;">在此区域中，应通过使用屏幕截图，丰富的内容检索以及真实世界特权用户访问的示例来证明以下项目：
</font></font></p>
<ul><li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">权限提升路径 
</font></font><ul><li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用的技术 </font></font></li></ul></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获取客户定义的关键信息 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">信息的价值</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">访问核心业务系统</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">访问受合规性保护的数据集</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">访问的附加信息/系统 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">持久的能力</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">渗透能力</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对策有效性 
</font></font><dl><dd><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本节应涵盖对范围内系统采取的反措施的有效性。</font><font style="vertical-align: inherit;">它应包括有关主动（主动）和被动（反应）对策的部分，以及在测试阶段触发的任何事件响应活动的详细信息。</font><font style="vertical-align: inherit;">有效抵制评估活动的对策列表将有助于客户更好地调整检测系统和流程，以处理未来的入侵企图。</font></font></dd></dl>
<ul><li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">检测能力 
</font></font><ul><li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FW / WAF / IDS / IPS </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">人的 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DLP </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">日志 </font></font></li></ul></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">反应和有效性</font></font></li></ul></li></ul>
<p><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">风险：</font></font></b>
</p><p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一旦通过脆弱性，开发和后期开发部分中存在的证据确定对业务的直接影响，就可以进行风险量化。</font><font style="vertical-align: inherit;">在本节中，上述结果与风险值，信息关键性，公司评估以及预参与部分的衍生业务影响相结合。</font><font style="vertical-align: inherit;">这将使CLIENT能够识别，可视化和货币化整个测试中发现的漏洞，并根据CLIENTS业务目标有效地权衡其解决方案。</font><font style="vertical-align: inherit;">本节将介绍以下小节中的业务风险：
</font></font></p>
<ul><li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">评估事件频率 
</font></font><ul><li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可能的事件频率 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">估计威胁能力（来自3  - 威胁建模） </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">估计控制力（6） </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">复合漏洞（5） </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">所需技能水平 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">需要访问级别 </font></font></li></ul></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">估算每次事故的损失程度 
</font></font><ul><li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">主要损失 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">二次损失 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">确定风险根本原因分析 
</font></font><ul><li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">根本原因永远不是一个补丁 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">识别失败的进程 </font></font></li></ul></li></ul></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">衍生风险 
</font></font><ul><li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">威胁 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">漏洞 </font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">交叠</font></font></li></ul></li></ul>
<p><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">结论：</font></font></b>
</p><p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">最终的测试概述。</font><font style="vertical-align: inherit;">建议本节回应整体测试的部分内容，并支持CLIENT安全态势的增长。</font><font style="vertical-align: inherit;">它应以积极的方式结束，并提供支持和指导，以便在未来的安全计划和测试/安全活动方面取得进展。
</font></font></p>
<!-- 
NewPP limit report
Cached time: 20190218070721
Cache expiry: 86400
Dynamic content: false
CPU time usage: 0.036 seconds
Real time usage: 0.048 seconds
Preprocessor visited node count: 14/1000000
Preprocessor generated node count: 20/1000000
Post‐expand include size: 0/2097152 bytes
Template argument size: 0/2097152 bytes
Highest expansion depth: 2/40
Expensive parser function count: 0/100
-->
<!--
Transclusion expansion time report (%,ms,calls,template)
100.00%    0.000      1 -total
-->

<!-- Saved in parser cache with key pentestmediawiki:pcache:idhash:13-0!*!*!!en!5!* and timestamp 20190218070721 and revision id 948
 -->
</div><div class="printfooter"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
来自“ </font></font><a dir="ltr" href="http://www.pentest-standard.org/index.php?title=Reporting&amp;oldid=948"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://www.pentest-standard.org/index.php?title=Reporting&amp;oldid=948</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ”</font></font></div>
		
