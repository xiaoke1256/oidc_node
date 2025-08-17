# 一 、安装启动 keycloak .
# 二 、执行 bin/standalone.bat 启动程序。
# 三 、创建 Test_realm ，配置其中的client。
## 1、  Access Type 设置为 confiedntial
## 2、  打开 Authorization Enabled 设置
## 3、  重新设置 resource 、Policies、Permissions
# 四 、创建用户。
# 五 、模拟登录：
http://127.0.0.1:8080/auth/realms/test_realm/protocol/openid-connect/auth?response_type=code&client_id=test_client
