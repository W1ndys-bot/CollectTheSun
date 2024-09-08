# CollectTheSun

来为 24 级新生收集阳光吧！每次收集阳光或雨水，都会随机增加 0-50 阳光或雨水。阳光减去雨水为有效阳光。
本玩法为限时娱乐玩法，适度娱乐，切勿当真。
数据全服互通，你的数据将会基于所有群聊的数据结算，切勿频繁刷分喔，否则会被关进小黑屋，玩法将于 9 月 14 日 0 点军训结束准时关服。
排行榜也是全服实时结算，偷偷告诉你，这是 W1ndys 第一次写全服互通和奇遇、排行榜的玩法，快来测测他有没有写出愚蠢的 bug。

特殊玩法：奇遇事件，群里的每一条消息都有 5% 的概率触发奇遇事件并收集 0-20 阳光或雨水。
（作者脑子已经炸了）

## 指令

- `收集阳光|collectsun` 收集阳光，每次收集会给全服增加 0-50 点阳光
- `查看阳光|checksun` 查看阳光，查看全服阳光值、自己收集阳光值、本群收集阳光值
- `阳光排行榜|sunrankt` 查看排行榜，查看全服收集阳光排行榜
- `加入奇遇|join` 加入奇遇，加入奇遇后，群里每条消息都有 5% 的概率触发奇遇事件

## 更新日志

### 2024 年 9 月 9 日

- fix: 修复被偷阳光之后被偷者进入 CD 的 bug
- feat: 增加指令 `suninfo` 查看别人的信息
- feat: 简化偷资源的指令
- feat: 详情请看`sunmenu`

### 2024 年 9 月 7 日

- feat: 增加赠送阳光和雨水功能，增加指令 `赠送阳光|givesun` 和 `赠送雨水|givewater`

### 2024 年 9 月 6 日

- feat: 清理数据库
- feat: 重构收集阳光的算法
- feat: 重构抢夺阳光的算法
- feat: 增加抢夺阳光的冷却时间的提示
- fix: 修复抢夺阳光的冷却时间计算错误的 bug
- feat: 增加冷却时间提示

### 2024 年 9 月 5 日

- feat: 15% 概率大量收集，增加的阳光或雨水数量为当前数量的 50% 到 100% 之间，并额外增加 1000 到 5000 之间的随机数。
- feat: 85% 概率正常收集，增加的阳光或雨水数量为当前数量的 10% 到 30% 之间，并额外增加 500 到 2000 之间的随机数。
- feat: 增加指令 `抢夺阳光|stealsun` 抢夺阳光，抢夺阳光会抢夺成功或失败
- feat: 增加指令 `抢夺雨水|stealrain` 抢夺雨水，抢夺雨水会抢夺成功或失败

### 2024 年 9 月 4 日

- feat: 增加指令 `雨水排行榜|rainrank` 查看排行榜，查看全服收集雨水排行榜
- feat: 更新收集机制，有概率收集大大大大大大量阳光或雨水，有概率减少阳光或雨水

## 2024 年 9 月 1 日

- feat: 上调奇遇事件的阳光/雨水基数为 1-500
- feat: 下调奇遇触发概率为 0.05
- feat: 上调奇遇事件的阳光/雨水基数为 500-1000
- feat: 增加指令 `啦啦啦种太阳` 收集阳光

### 2024 年 8 月 31 日

- feat: 优化奇遇事件，调整为默认不参与，通过指令 `加入奇遇|join`选择加入
- feat: 上调奇遇事件的阳光/雨水基数为 50-100，上调触发概率为 0.1
- fix: 修复阳光排行榜传参错误的 bug
- feat: 增加内置 CD 机制，两次奇遇事件的间隔时间不得少于 30 秒，取消禁言的 CD 机制，sun、rain、奇遇共享 CD
- feat: 优化 suninfo

### 2024 年 8 月 30 日

- feat: 初始版本
