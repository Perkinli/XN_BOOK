# 预约系统(管理员+学生)

如果是初次登录，提醒修改密码（弹窗），设置密码强度要求

（高级：绑定手机号后，使用手机号码登录，难！

支持第三方QQ、微信登录，难！）

## 首页

- **活动类型**：（据此设置分类栏）
  - 不同活动类型预约方式不同，有些活动预约需要时间限制。有些活动是以班级为单位报名的，如一个班报名三个人。有些活动不需要预约，直接参与即可。有些活动是强制的（参观科技公司、召开年级大会；这种活动不算在活动时间记录之列）
  - **学术**：学术讲座、学术竞赛、论文答辩、学术展览等
  - **文艺**：音乐会、美术展览、舞蹈演出、电影、摄影大赛
  - **体育**：运动会（校运动会、院运动会）、球类比赛（篮球、足球、羽毛球、乒乓球）、环湖跑
  - **志愿公益**：志愿者报名、公益活动
  - **招新活动**：校组织(社团招新、勤工俭学招新、沸点)、院组织招新（学生会）（预约键换成报名键）
  - **节日庆典**：狮山文化节、校庆、端午、毕业典礼
  - **其它**：新生活动、企业进校园、心理健康、（社团活动）

- **活动发布**：管理员登录后台，点击“发布活动”按钮，进入活动发布页面。填写各种信息后，点击“发布”按钮，活动预告即添加到数据库中。
- **活动查看**：
  - 按时间/热度排序：活动热度通过关注人数计算。学生可按时间顺序（从近到远）或热度（从高到低）查看活动预告，已结束的活动不参与热度排序。
  - 筛选:按学院、按类别
  - 活动链接分享
- **活动预约流程**：
  - 预约规则：
    - 每人可预约多个活动，但同一时间段只能预约一个
      - 判定预约冲突
    - 根据学生所在院校、年级、班级会产生限制
    - 预约，部分预约活动需上传附件（如报名表）
  - 学生在活动预告页面浏览活动，点击“预约”按钮，填写预约信息（如姓名、学号、联系方式等），提交后预约成功。也可以点击“关注”为活动增加热度。预约成功的活动会在学生端的日历中高亮显示，打开QQ群通道。
  - **取消预约**：活动开始前可取消预约，取消后名额释放。
- **活动参与：**未开放---预约----已预约----待开始----待签到----待签退
  - 怎么签到？对于线下的活动，获取地理位置，才能开启签到；线上直接点签到
- **违约惩罚**：管理员在活动结束后，通过后台系统检查学生是否按时参加活动。若学生违约，系统自动记录违约次数。违约三次以上的学生，账号将被限制3天内禁止预约活动，3天后自动解除限制。

#### 

## 消息

- **日历**：日程会显示在日历上

- **系统通知**：密码修改提醒、登录异常提醒、新功能上线通知、反馈处理通知、校园重要活动公告（放假安排.....）

- **活动提醒**：预约成功通知，活动开始通知（活动开始前30分钟发送签到提醒，一些强制性活动如分流大会、年级大会等也会发布在此）、变更通知、撤销通知

- **违约与申诉**：误判了？去申诉

## 我的

**活跃度**（预约次数、参与次数、违约次数----申诉处理、活动时长）（点击活跃度中的具体项会显示具体信息）

**成就**：根据学生的参与情况颁发虚拟徽章或称号（学术、文艺、志愿、体育）---->具体再迭代

**基本信息**（头像、姓名、性别、学号、出生、年级、院系班级）

**安全设置**（修改密码，绑定手机号码）

**提交反馈**

**帮助文档**

**个性化**：[深色系统、字体设置]





# 管理员

管理员账号（十三个学院、校团委）

**发布活动**

- **发布活动**（针对一些可以自由参加的活动）

  - 填写信息：活动封面，封面文字、基本信息（承办单位、活动类别、预约开放与截止时间（或者无预约）（如果需要预约，是否需要填写附件或其他信息），活动开始与结束时间，报名限制（院系、年级、人数限制（班级人数限制；总人数限制）），活动简介（活动海报），活动时间地点

  - 如果一些活动有限制，对不符合的学生账号将不显示活动信息

  - 活动时间地点冲突的处理方法（弹出提醒：与以下活动冲突，是否继续？）
  - 发布活动后，活动开始前，会自动提醒

- **发布提醒**(针对一些强制参加的活动，如年级大会、面向特定人群的强制会议等等，发布活动通知；或者针对一些重要校园事项如放假安排、教学楼，发布系统通知)

  - 活动提醒事项以及提醒人群，如某个年级的学生，学生会部门人群；支持批量导入名单

**活动管理**

- **预约名单导出**：支持导出活动的预约名单、签到名单、违约记录。
- **活动报告**：自动生成活动总结报告，包括参与人数、签到率等数据。
- **修改活动、活动撤销**

- **违约处理**，**申诉处理**

