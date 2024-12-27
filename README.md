# fake-freshmen-message
Record QQ users who posts fake messages for freshmen

## 说明
为了避免大学新生被虚假校园墙或类似宣传欺骗，这里记录宣传虚假校园墙、群的账号，以及墙、群的信息。

本仓库的目的是建设一个公共的黑名单，QQ群管理员可以根据本仓库的数据自动执行踢人、封禁、撤回消息等操作。

若您被错误记录，请提issue。

## 技术细节
f文件夹下共有四个文件：
- [user.json](/f/user.json)记录发布虚假信息的QQ号
- [group.json](/f/group.json)记录发布的QQ群号
- [wall.json](/f/wall.json)记录发布的「校园墙」的号
- [wechat.json](/f/wechat.json)记录发布的微信号

## 建议的操作
如果您使用机器人管理群聊，建议您设置以下操作：

1. 遇到user.json记录的QQ号，立刻踢出并拉黑。
2. 发现有用户发布其他三个文件记录的关键字，立刻撤回并踢出发布者。
3. 为了项目更好地发展，希望您额外记录触发关键字的信息，以及发布者的QQ号码，并一起提报到此仓库的issue或者pr。

## 授权协议
本仓库的数据库依据[ODbL 1.0](LICENSE)授权，其它所有说明文本依据[CC BY-SA 4.0](LICENSE-text)授权。额外说明：除非经过所有贡献者的授权，本仓库及其衍生作品不允许镜像到Gitee、Gitcode等其它源代码托管平台。

为本仓库贡献即表明您同意以上授权协议。
