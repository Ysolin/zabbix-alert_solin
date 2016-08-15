# zabbix-alert_solin
# zabbix-agent端 邮件报警脚本

email:
  smtp_host: mail.example.com
  user: test@example.com
  alias: zabbix-alert
  password: mypassword

redmine:
  url: http://redmine.example.com
  user: solin
  key: 1f2u3c4k5g6f7w
  project: zabbix-alert

twilio_call:
  from: '+1234567'
  sid: 'Your twilio sid'
  token: 'Your twilio token'
  voice: alice
  language: zh-CN
