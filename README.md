关闭进程：ps -ef | grep node | awk '{print $2}'|xargs kill -9

curl -H "Content-Type:application/json" -X POST -d '{"version":"v1.0","componentName":"qcact-logic","eventId":1074043742,"timestamp":1654758205371,"user":"auto","interface":{"interfaceName":"lottery_api.prize.list","para":{"task_id":29}}}' http://30.42.74.33:50020/lottery_api/prize/list

Chrome 忽略本地请求跨域open -n /Applications/Google\ Chrome.app/ --args --disable-web-security --user-data-dir=/Users/yuan/MyChromeDevSet/
