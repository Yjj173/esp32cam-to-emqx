# ʹ��˵��


## ǰ��

��Ҫ��ubuntu�а�װArduino 1.8.x�汾�������úö˿ںţ������幤�߿�(ѡ��AI-Thinker Esp32-Cam)��Ȼ������Ŀ/���ؿ��е���data�е�pubsubclientѹ����������ڼ��ؿ�/�����������PubSubClient������װ��
## ��������˵��
//ssidΪWIFI�˻�����

const char* ssid = "***";

//passwordΪWIFI����

const char* password = "***";

//mqtt_serverΪemqx��������ַ

const char* mqtt_server = "***";

//mqtt_portΪemqx�������˿�(Ĭ��1883)

const int mqtt_port = 1883;

//mqttUserΪemqx�û���(Ĭ��admin)

const char* mqttUser = "admin"; 

//mqttPasswordΪemqx����(Ĭ��public)

const char* mqttPassword = "public"; 

//mqtt_topicΪ���ĵ�����

const char* mqtt_topic = "picture"; // �������ڷ���ͼ��� MQTT ����

## ����

һ�����þ���������ϴ����ɹ��󼴿�����