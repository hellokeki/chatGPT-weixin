# ChatGPT 微信小程序

新版本即将支持双模型，提供了两种非官方 `ChatGPT API` 方法

| 方式                               | 免费？ | 可靠性     | 质量 |
|----------------------------------| ------ | ---------- |----|
| `ChatGPTAPI(gpt-3.5-turbo-0301)` | 否     | 可靠       | 聪明 |
| `ChatGPTAPI(gpt-3.0)`            | 是     | 相对不可靠 | 较笨 |

对比：
1. `ChatGPTAPI` 使用 `gpt-3.5-turbo-0301` 通过官方`OpenAI`补全`API`模拟`ChatGPT`（最稳健的方法，但它不是免费的，并且没有使用针对聊天进行微调的模型，每个用户绑定一个Key,支持上下文，可设置头像昵称，有推广奖励入口，微信提现）
2. `ChatGPTAPI(gpt-3.0)` 使用非官方代理服务器访问 `ChatGPT` 的后端`API`（支持聊天，对话功能，有广告使用真实的的ChatGPT，非常轻量级，但依赖于第三方服务器，并且有速率限制）

某用户的定制版，欢迎咨询定制加V 'youjunqifei',备注来意
<a href="https://imgse.com/i/ppmlhIU"><img src="https://s1.ax1x.com/2023/03/08/ppmlhIU.png" alt="ppmlhIU.png" border="0" /></a>



```
/service/.env
```

## 正在实现功能

1.对代码等消息类型的格式化美化处理

2.数据导入、导出

3.保存消息到本地图片

4.界面多语言

5.语音输入

6.一键生成多文本

项目演示地址：vx小程序：智能AI聊天工具

<a href='https://postimg.cc/Z9mhW6VT' target='_blank'><img src='https://i.postimg.cc/Z9mhW6VT/Wechat-IMG548.jpg' border='0' alt='Wechat-IMG548'/></a>

技术爱好者交流群：满了加我拉进去

<a href='https://postimg.cc/nCskD5Pk' target='_blank'><img src='https://i.postimg.cc/nCskD5Pk/Wechat-IMG724.jpg' border='0' alt='Wechat-IMG724'/></a>


需求定制联系： 微信：youjunqifei

<a href='https://postimg.cc/6TPVtcpG' target='_blank'><img src='https://i.postimg.cc/6TPVtcpG/Wechat-IMG550.jpg' border='0' alt='Wechat-IMG550'/></a>







