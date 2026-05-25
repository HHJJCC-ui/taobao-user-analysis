# 淘宝用户行为分析项目

## 📌 项目简介
本项目基于淘宝公开用户行为数据，从用户活跃度、转化漏斗、品类表现和用户分群四个维度，完成了完整的数据分析，并提出了可落地的业务优化策略。

## 📊 关键分析图表

### 1. 用户活跃度与行为分布
![用户活跃度与行为分布](images/01_overview_and_activity_charts.png)

### 2. 大促预热 vs 周末的用户行为对比
![大促预热 vs 周末用户行为](images/02_promotion_vs_weekend_uv_and_depth.png)

### 3. 高意向行为占比与转化率
![高意向行为与转化率](images/03_promotion_intent_and_conversion_rate.png)

### 4. 每日新增用户趋势
![每日新增用户趋势](images/04_user_acquisition_new_users.png)

### 5. DAU vs 新增用户对比
![DAU vs 新增用户](images/05_dau_vs_new_users_daily.png)

### 6. 新增用户占比趋势
![新增用户占比趋势](images/06_daily_new_user_proportion_trend.png)

### 7. Top 10 品类转化率分析
![Top 10 品类转化率](images/10_top10_category_conversion_rate_chart.png)

### 8. Top 10 销量品类分析
![Top 10 销量品类](images/11_top10_category_sales_volume.png)

### 9. RFM 用户分群结果
![RFM 用户分群结果](images/12_rfm_feature_matrix.png)

### 10. 最优聚类数分析（肘部法）
![最优聚类数分析](images/13_elbow_method_optimal_k.png)

## 💡 核心结论与业务建议
1.  **用户活跃度**：用户日活在大促预热期显著提升，但新增用户占比持续下降，说明拉新成本上升，需重点优化拉新渠道。
2.  **转化漏斗**：从浏览到购买的整体转化率仅为 2.2%，流失严重，需优化商品详情页、加购转化路径和召回策略。
3.  **品类表现**：少数品类的转化率和购买量表现突出，可重点运营这些品类，同时优化低转化品类的运营策略。
4.  **用户分群**：通过 RFM 模型将用户分为流失用户、一般用户等，可针对不同群体制定差异化的运营和召回策略。
## 项目介绍

基于淘宝用户行为数据，对用户浏览、收藏、加购、购买行为进行分析，
完成用户留存分析、漏斗分析、商品分析以及用户分层。

---

## 技术栈

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- MySQL
- Tableau
- Scikit-learn

---

## 项目内容

### 用户活跃分析
- DAU
- PV
- 用户行为趋势

### 用户留存分析
- 次日留存率
- 用户粘性分析

### 用户转化漏斗
- 浏览 → 收藏/加购 → 购买

### 商品品类分析
- Top10 高销量品类
- Top10 高转化率品类

### 用户分层
- RFM 用户价值模型
- KMeans 用户聚类

---

## 项目成果

- 完成完整电商数据分析流程
- 提升数据分析与机器学习实战能力
- 输出用户运营与精准营销建议
