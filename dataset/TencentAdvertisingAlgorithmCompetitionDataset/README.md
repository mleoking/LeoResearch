EN

The data of the 2020 is open for non-profit academic research

Demographic features like user age and gender are important input features for many kinds of recommendation systems, including online advertising systems. The assumption behind is that the preferences upon recommended items are different among people with different ages and genders. This has already been verified by practitioners who have access to both recommending scenarios and demographic data. However, the verifications so far were mostly done in the “forward” way, i.e., using demographic features to recommend items and comparing the offline and online performance with settings without these features. The problem of the competition this year is to verify the assumption in the “backward” way, i.e., using responsive behavior of users in the system to predict their demographic features.
The problem has practical significance. For those practitioners which have limited access to user information, the ability to infer demographic features based on data generated within their own systems is valuable. For example, it enables smart targeting and audience protection on more broad population, which will benefit the whole ecosystem. Participants might need to orchestrate various techniques from machine learning to achieve better performance.
The preliminary data of the 2020 Tencent Advertising Algorithm Contest is open for download and is only for non-profit academic research. It is strictly forbidden to sell, transfer or use the data for any commercial activities.


The data of the 2019 is open for non-profit academic research

Tencent performance advertising adopts the GSP (Generalized Second-Price) bidding mechanism, and the actual exposure of the advertisement depends on the traffic coverage of the advertisement and the relative competitiveness level in competing advertisements. The traffic coverage of the ad depends on the ad's population orientation (the number of users matching the corresponding characteristics), the size of the creative (the matching ad slot), and the delivery period, budget and other settings. The main factors affecting advertising competitiveness are bidding, advertising quality and other factors (such as pctr/pcvr, etc.), as well as control strategies for user experience. Generally speaking, the basic competitiveness can be used ecpm = 1000 * cpc_bid * pctr = 1000 * cpa_bid * pctr * pcvr (cpc, cpa stand for the pay-per-click model and the pay-per-conversion model, respectively). In summary, the former determines the number of times the advertisement can participate in the competition and the object of competition, while the latter determines the probability of winning in each competition. The two ultimately determine the daily exposure of the ad.
This competition will provide historical n-day data of exposed advertisements (up-sampling of specific traffic), including traffic characteristics corresponding to each exposure (temporal and spatial information such as user attributes and advertising positions) and the settings of exposed advertisements And the competitiveness score; the test set is a new batch of advertising settings (there are completely new advertising IDs, and there are also old advertising IDs modified settings), and it is required to estimate the daily exposure of this batch of advertisements. (For the sake of business data security, all data is desensitized.)
The preliminary data of the 2019 Tencent Advertising Algorithm Competition is open for download and is only for non-profit academic research. It is strictly prohibited Sell, transfer or use the data in any commercial activities.


The data of the 2018 is open for non-profit academic research

Lookalike is based on a seed group (also called a seed pack) provided by the advertiser, and automatically calculates a similar group of people (called an expanded group). This topic will provide contestants with hundreds of seed groups, user characteristics corresponding to massive candidate groups, and advertisement characteristics corresponding to seed groups. For the sake of business data security assurance, all data is desensitized data. The entire data set is divided into training set and test set. The training set calibrates the users who belong to the seed package and the users who do not belong to the seed package (that is, positive and negative samples) in the population. The test set will check whether the algorithm of the contestants can accurately calibrate whether the users in the test set belong to the corresponding seed package. The seed packets corresponding to the training set and the test set are exactly the same. The seed packs provided in the preliminary and semi-finals have the same settings except for the different magnitudes.
The competition is divided into two stages: preliminary and semi-finals. The difference between these two stages is that the magnitude of the seed package provided is different, and the other settings are the same.
The preliminary data of the 2018 Tencent Advertising Algorithm Contest is open for download and is only for non-profit academic research. It is strictly forbidden to sell, transfer or use the data for any commercial activities.

---

CN

2020年赛题供学习使用

本届算法大赛的题目来源于一个重要且有趣的问题。众所周知，像用户年龄和性别这样的人口统计学特征是各类推荐系统的重要输入特征，其中自然也包括了广告平台。这背后的假设是，用户对广告的偏好会随着其年龄和性别的不同而有所区别。许多行业的实践者已经多次验证了这一假设。然而，大多数验证所采用的方式都是以人口统计学属性作为输入来产生推荐结果，然后离线或者在线地对比用与不用这些输入的情况下的推荐性能。本届大赛的题目尝试从另一个方向来验证这个假设，即以用户在广告系统中的交互行为作为输入来预测用户的人口统计学属性。
我们认为这一赛题的“逆向思考”本身具有其研究价值和趣味性，此外也有实用价值和挑战性。例如，对于缺乏用户信息的实践者来说，基于其自有系统的数据来推断用户属性，可以帮助其在更广的人群上实现智能定向或者受众保护。与此同时，参赛者需要综合运用机器学习领域的各种技术来实现更准确的预估。
2020腾讯广告算法大赛初赛数据已开放下载，仅供非盈利性的学术研究，严禁对该数据进行出售、转让或用于任何商业活动。


2019年赛题供学习使用

腾讯效果广告采用的是GSP（Generalized Second-Price）竞价机制，广告的实际曝光取决于广告的流量覆盖大小和在竞争广告中的相对竞争力水平。其中广告的流量覆盖取决于广告的人群定向（匹配对应特征的用户数量）、广告素材尺寸（匹配的广告位）以及投放时段、预算等设置项。而影响广告竞争力的主要有出价、广告质量等因素（如pctr/pcvr等）， 以及对用户体验的控制策略。 通常来说， 基本竞争力可以用ecpm = 1000 * cpc_bid * pctr = 1000 * cpa_bid * pctr * pcvr (cpc, cpa分别代表按点击付费模式和按转化付费模式)。综上，前者决定广告能参与竞争的次数以及竞争对象，后者决定在每次竞争中的胜出概率。二者最终决定广告每天的曝光量。
本次竞赛将提供历史n天的曝光广告的数据（特定流量上采样）， 包括对应每次曝光的流量特征（用户属性和广告位等时空信息）以及曝光广告的设置和竞争力分数；测试集是新的一批广告设置（有完全新的广告id， 也有老的广告id修改了设置）， 要求预估这批广告的日曝光 。（出于业务数据安全保证的考虑，所有数据均为脱敏处理后的数据。）
2019腾讯广告算法大赛初赛数据已开放下载，仅供非盈利性的学术研究，严禁对该数据进行出售、转让或用于任何商业活动。


2018年赛题供学习使用
相似人群拓展（Lookalike）基于广告主提供的一个种子人群（又称为种子包），自动计算出与之相似的人群（称为扩展人群）。本题目将为参赛选手提供几百个种子人群、海量候选人群对应的用户特征，以及种子人群对应的广告特征。出于业务数据安全保证的考虑，所有数据均为脱敏处理后的数据。整个数据集分为训练集和测试集。训练集中标定了人群中属于种子包的用户与不属于种子包的用户（即正负样本）。测试集将检测参赛选手的算法能否准确标定测试集中的用户是否属于相应的种子包。训练集和测试集所对应的种子包完全一致。初赛和复赛所提供的种子包除量级有所不同外，其他的设置均相同。
此次比赛分为初赛和复赛两个阶段。这两个阶段的区别是所提供的种子包的量级有所不同，其他的设置均为相同。
2018腾讯广告算法大赛初赛数据已开放下载，仅供非盈利性的学术研究，严禁对该数据进行出售、转让或用于任何商业活动。