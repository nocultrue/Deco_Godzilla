**解密哥斯拉所有类型数据:**
![image](https://github.com/nocultrue/Deco_Godzilla/assets/84069457/59f73ab5-098f-489b-b0db-492584b87106)

php_raw 、csharp_raw 、asp_raw、 jsp_raw 格式传输的数据，使用16进值做为输入：

**1.举例-php_raw**：
raw格式的都这样
通过获取上传的webshell可以获取key(php_raw这里没有pass,知道就都填上)

![image](https://github.com/nocultrue/Deco_Godzilla/assets/84069457/7d300c94-06cf-4073-97c7-a58d6428fb3d)
请求解密:
![image](https://github.com/nocultrue/Deco_Godzilla/assets/84069457/e3ae983b-4409-4345-9c20-f7d0a858b364)
响应解密：
![image](https://github.com/nocultrue/Deco_Godzilla/assets/84069457/117361fc-4335-4432-9813-ff18f72b5705)


**2.举例-php_eval**
eval类型都这样

通过传输的流量获取key和pass

![image](https://github.com/nocultrue/Deco_Godzilla/assets/84069457/61206290-959c-47a2-a918-1bf24463e454)
请求解密（key 后面的值）：

![image](https://github.com/nocultrue/Deco_Godzilla/assets/84069457/849bc387-c800-44f2-86b4-e38e24d4a1a9)

响应解密（响应所有的值）：

![image](https://github.com/nocultrue/Deco_Godzilla/assets/84069457/686962a5-442f-4d86-9913-1ae677ce9470)
**3.举例-php_xor_base64**
不输入前面的pass

获取pass和key

![image](https://github.com/nocultrue/Deco_Godzilla/assets/84069457/db03bee0-9d41-45fb-a0a7-9497bb6f3210)


请求解密（pass 后面的值）

![image](https://github.com/nocultrue/Deco_Godzilla/assets/84069457/a89960f1-ef86-4886-ac41-04b25545fc47)


响应解密（响应全部部分）：

![image](https://github.com/nocultrue/Deco_Godzilla/assets/84069457/40532703-2895-474d-8261-85174146b122)


**有问题的话提issue或者加群交流**
qq:

![image](https://github.com/nocultrue/Deco_Godzilla/assets/84069457/be27bfa1-7283-4217-bd95-38d6139cd1df)

免责声明：根据我国《计算机软件保护条例》第十七条规定：“为了学习和研究软件内含的设计思想和原理，通过安装、显示、传输或者存储软件等方式使用软件的，可以不经软件著作权人许可，不向其支付报酬。”您需知晓本站所有内容资源均来源于网络，仅供用户交流学习与研究使用，版权归属原版权方所有，版权争议与本站无关，用户本人下载后不能用作商业或非法用途，需在24小时之内删除，否则后果均由用户承担责任
