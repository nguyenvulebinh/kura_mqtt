# Hướng dẫn cách publish/subcribe Raspberry Pi tới Brocker

## Yêu cầu trước khi tiến hành kết nối 
+ **Raspberry Pi được cài đặt theo [hướng dẫn](https://github.com/nguyenvulebinh/kura_experience/blob/master/Ket_noi_i2c.md)**
+ **THiết đặt brocker đơn giản theo [hướng dẫn](http://iotalliance.vn/categories/tutorial/articles/huong-dan-lap-trinh-esp8266-phan-3-lap-trinh-giao-tiep-mqtt.html) bước 1.4**
+ **Đọc [tài liệu](http://www.indigoo.com/dox/wsmw/1_Middleware/MQTT.pdf) tổng quan về kết nối mqtt**
+ **Tham khảo [tài liệu](https://developer.ibm.com/recipes/tutorials/connect-eclipse-kura-to-ibm-watson-iot/) hướng dẫn kết nối kura tới IBM Watson IoT**

## Các bước tiến hành kết nối
**Ta tận dụng lại project demo của kura để làm ví dụ cho việc kết nối này. Đọc [tài liệu](http://eclipse.github.io/kura/doc/heater_demo.html) trước khi thực hiện các bước dưới đây**

+ Bước 1: Đăng nhập vào giao diện kura trên web, cấu hình MqttDataTransport như hình dưới đây.
![alt tag](https://github.com/nguyenvulebinh/kura_mqtt/blob/master/Screenshot%20from%202016-07-23%2010-27-41.png)
