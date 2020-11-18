# 说明
#md
1. 先把act.10010.com, m.client.10010.com加到[MITM]
2. 再配置重写规则:
	* Surge: 把两条远程脚本放到[Script]
	* QuanX: 把10010.cookie.js和10010.js传到On My iPhone - Quantumult X - Scripts (传到 iCloud 相同目录也可, 注意要打开 quanx 的 iCloud 开关)
3. 打开 APP , 进入签到页面, 系统提示: 获取刷新链接: 成功
4. 然后手动签到 1 次, 系统提示: 获取Cookie: 成功 (每日签到)
5. 首页>天天抽奖, 系统提示 2 次: 获取Cookie: 成功 (登录抽奖) 和 获取Cookie: 成功 (抽奖次数)
6. 把获取 Cookie 的脚本注释掉
7. 运行一次脚本, 如果提示重复签到, 那就算成功了!
第 1 条脚本是用来获取 cookie 的, 用浏览器访问一次获取 cookie 成功后就可以删掉或注释掉了, 但请确保在登录成功后再获取 cookie.
第 2 条脚本是签到脚本, 每天00:00:10执行一次.
