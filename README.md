# 使用说明


## 前置

需要在ubuntu中安装Arduino 1.8.x版本，并配置好端口号，开发板工具库(选择AI-Thinker Esp32-Cam)，然后在项目/加载库中导入data中的pubsubclient压缩包，最后在加载库/管理库中搜索PubSubClient，并安装。
## 参数配置说明
//ssid为WIFI账户名称

const char* ssid = "***";

//password为WIFI密码

const char* password = "***";

//mqtt_server为emqx服务器地址

const char* mqtt_server = "***";

//mqtt_port为emqx服务器端口(默认1883)

const int mqtt_port = 1883;

//mqttUser为emqx用户名(默认admin)

const char* mqttUser = "admin"; 

//mqttPassword为emqx密码(默认public)

const char* mqttPassword = "public"; 

//mqtt_topic为订阅的主题

const char* mqtt_topic = "picture"; // 定义用于发布图像的 MQTT 主题

## 运行

一切配置就绪，点击上传，成功后即可运行