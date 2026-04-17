# -我的自用

I love :coffee: :beer:,and:dancer:.

1.硬件连接

模块1: TX>GPIO20,RX->GPI021,EN->GPI05

模块2:TX->GPI016,RX->GPI017,。EN->GPI06

两个模块独立5V/2A供电，与ESP32-C3共地。

2.首次启动

若未配置wiFi,ESP32会创建开放热点ESP32-SMS-Manager，手机连接后访问192.168.4.1进入配置页面。
。默认管理员账号: admin/admin。

3.功能验证

登录后配置wiFi、邮箱SMTP、企业微信Webhook等。保存重启后即可自动接收短信并转发
可在Web页面主动发送短信(支持中文)
。
