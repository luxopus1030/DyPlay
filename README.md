# DyPlay
抖音刷播放量，查播放量
可刷播放量1300，查视频播放量
免费下单地址：

import requests
url = "http://185.241.40.169/free/orders/submit/"
payload = 'url=https%3A%2F%2Fv.douyin.com%2Fi5DVHBYJ%2F'
headers = {
  'Content-Type': 'application/x-www-form-urlencoded',
  'Cookie': 'PHPSESSID=4be709cf28a555e27d2febb0306c21d3'
}
response = requests.request("POST", url, headers=headers, data=payload)
print(response.text)

联系 TG:@LuxoPus5896
