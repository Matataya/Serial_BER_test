# Serial_BER_test
串口通讯由于不稳定的外界因素，会存在误码。人工使用串口助手发送指定测试指令耗时且枯燥。可借用其他串口助手，实现简单统计的串口误码率
![20190622183843995](https://user-images.githubusercontent.com/55845745/226626920-2cd42c2c-8520-4165-9f71-b1bc8199f981.png)

Serial _loop.py用于数据的接收和发送；
Serial_BER_test.py用于读取发送文件和接收文件，并处理误码率。
