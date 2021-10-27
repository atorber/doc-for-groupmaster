# 活动管理

## 发布活动

**注意只有群主可以发布活动**
- 填写活动基本信息
活动基本信息包括:开始时间、活动时长、人数限制、活动地点、描述、联系人、联系人电话
如无特殊情况，选择和填写以上信息后，点击下方的【提交并发布】即可完成活动发布。
活动发布成功后机器人会同步在群内发布一条活动信息，成员即可开始报名。
- 从模板中选择活动描述
群组大师内置了几个常用的活动描述模板，在填写活动描述时，可直接选择使用，也可根据需要编辑修改
- 单人最多报名人数
可以设置当前活动中，每个成员最多可报名的人数，报名时系统会检验成员报名情况，超过最多报名人数将不允许报名
可选范围为0-9，默认为9，表示最多一人成员可以报9个名额
如只允许成员自己报名，不允许代报名或携带群成员以外的人员参加活动，请将单人最多报名人数设置为1
- 报退截止时间
要求成员报名后，如需退报名最晚在活动开始前几小时取消
设置后系统会检验此时间，成员将不能取消报名，但管理员可通过在群内回复  **代@张三取消** 格式的指令取消成员报名
- 定时开放报名
可以指定活动开放报名的时间，例如希望明天早上10点开放报名，把时间设置好之后，系统会在明早10点自动开启报名，并发布活动详情和报名通知到群内，提醒群成员
- 预定报名名单
发布活动时允许为群成员预定报名，适用于成员线下向管理员预定报名名额的场景，比如某些固定活动的成员不需要主动报名，而是由管理员直接帮助预定报名
预定报名后，成员可以主动取消报名，取消方法与主动报名时相同，在群内回复 **取消** 即可，管理员同样可以回复 **代@张三取消** 格式取消

## 活动列表
在小程序中进去群组主页，即可查看活动列表
群主可以管理活动（取消活动、停止报名等）
群成员只可以查看活动

## 活动报名

- 报名
成员群内回复 **报名** 或 **报名2人** 进行报名，一次回复最多报名2人，单人最多报名人数受活动规定限制
- 取消报名
成员群内回复 **取消** 或 **取消2人** 取消已报名，一次回复最多可取消自己已报名的全部名额
- 替补
报名已满时，成员群内回复 **替补** 或 **替补2人** 进行替补报名，一次回复最多替补2人
有成员取消报名时，替补会按报名时间增补转正，同时机器人会@转正成员
- 取消替补
群内回复 **取消替补** 或 **取消替补2人** 取消已报名的替补，一次回复最多可取消自己已报名的全部替补名额

## 代报名/取消
- 群主代报名
群主可在群内使用@的方式代替指定成员报名，例如回复 **代@张三 报名** 格式指令，替张三报名1个名额
- 群主代取消报名
群主可在群内使用@的方式取消指定成员报名，例如回复 **代@张三 取消** 格式指令，取消张三的1个报名名额

## 增加名额

群主在群内回复 **@大师 加6名额** 可为当前报名中的活动增加6个名额，增加名额后，如果有替补报名存在，替补自动转为正式报名

## 截止报名

管理员主动停止/截止活动报名，停止后成员不能再报名

## 开启报名

开启后会恢复报名，成员可继续正常报名

## 取消活动

活动取消时关闭活动，取消活动后群成员将无法报名
群主在详情页下方点击 **管理活动>取消活动** 完成操作，取消成功机器人会发消息到群内通知成员

## 恢复活动

恢复已经取消的活动，恢复后活动可继续报名

## 活动记录
