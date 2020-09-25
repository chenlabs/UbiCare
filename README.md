# About UbiCare

![ubicare4](https://user-images.githubusercontent.com/7458755/94276326-0bae6a80-ff83-11ea-8c83-5f603447c08b.png)

UbiCareは、心拍、血圧、酸素など生体信号を測定するバイオセンサーと、室温、湿度、気圧、騒音など健康に影響する信号を測定する環境センサーでデータを収集し、ユーザの近くにあるエッジサーバ(edge Server)で一旦蓄積し、定期的にクラウドへ集約する。

センサーデータの収集はESP32, エッジはRaspberry Piを利用する。

# センサー(Sensor)

ピエゾセンサーを利用する

![ubicare2](https://user-images.githubusercontent.com/7458755/94277324-5f6d8380-ff84-11ea-9442-6141e1fb2dc9.jpg)

# IoTデバイス(IoT Device)

![ubicare3](https://user-images.githubusercontent.com/7458755/94277524-a6f40f80-ff84-11ea-99a9-60b9889d5cae.jpg)

センサーからのデータはIoTデバイスで収集し、近くにあるエッジサーバ(edge Server)

![ubicare5](https://user-images.githubusercontent.com/7458755/94276315-094c1080-ff83-11ea-8425-d1e4b2be7aa3.png)

通信プロトコル：MQTT、HTTP

# Raspberry PiでUPD構築

![raspberry-pi-b](https://user-images.githubusercontent.com/7458755/94277945-37caeb00-ff85-11ea-81fd-3f4d21f2dbcb.jpg)

# モニタリング アプリ開発

![ubicare24](https://user-images.githubusercontent.com/7458755/94277673-d73bae00-ff84-11ea-8a62-434c5e4de17f.png)

