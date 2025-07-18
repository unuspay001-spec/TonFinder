# TonFinder
TonFinder is a Telegram miniapp that connects TON users with global merchants that support crypto payments, combining red envelope marketing and task fission to create a new entry point for Web3 merchant growth.


1 MVP功能：
🎯 1st产品核心价值：“发现全球支持加密货币支付的商家，建立可被信任的商家生态。”
 —— 汇聚真实用户评分、商家资料和加密支付支持币种，让Crypto消费更透明。

1.1 功能主线：(B端基础功能)
商家提交，平台管理商家提交信息，商家分类信息导航。

1.2 首页模块
- 搜索框（支持关键词、币种、国家搜索）
- 导航分类：
  - 最近新增商家
  - 支持最多币种
  - 热门行业（VPN、电商、线下零售）
  - 热门国家（按商家数量排序）
- 商家推荐区：
  - Promote商家Banner（$299/年，轮播展示）
  - 推荐商家列表（可后台置顶）
- 币价信息滚动区（实时同步主流币美金汇率）
  - BTC, ETH, LTC, BCH, DOGE, SOL, USDT, XRP, USDC, SHIB, BNB, TRX

1.3 商家目录页
- 商家卡片展示信息：
  - 名称 / Logo / 简介 / 国家 / 行业分类
  - 支持币种（图标展示）
  - 用户评分（平均分 + 评论数）
- 筛选功能：
  - 按国家 / 地区（下拉选择）
  - 按币种（多选）
  - 按行业（多选）
  - 排序规则（最新/评分/支持币种数）

1.4 商家详情页
- 商家名称 / Logo / 行业 / 国家
- 简介 & 官网链接 & 联系方式（如官网、Twitter）
- 支持币种图标
- 用户评分系统：
  - 星级打分（1-5）
  - 留言评价（带时间戳、TG用户ID或用户名）
- 【可选】收藏按钮 / 分享按钮（生成商家卡片，可分享至其他群组）

1.5 商家提交页（B端入口）
- 提交表单：
  - 名称、官网、国家、行业
  - 接受币种（多选）
  - 简介、联系方式
  - Email 验证（初期验证身份）
- 提交后机制：
  - 商家入库状态为“待审核”
  - 管理后台审核通过后才可展示
- 附加功能（商家端）：
  - 上传折扣活动（Discount 码）
    - 折扣图、使用说明、有效期、剩余名额
    - 支持下单链接
  - Promote your company
    - 上传首页Banner图（尺寸要求）
    - 自动进入首页轮播区，需支付 $299/年
    - 支持加密钱包支付（TON, USDT, ETH）
  
1.6 后台管理功能（平台运营端）
- 商家管理
  - 审核新提交商家 / 编辑资料 / 删除
  - 设置推荐商家（置顶排序）
  - 管理Promote Banner（到期提醒）
- 用户评价管理
  - 评论审核（防刷屏/广告）
  - 评论统计（商家口碑数据）
