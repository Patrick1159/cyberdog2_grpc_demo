# cyberdog2_grpc_demo
ssh连接mi@xxx.xxx.xx.xx后，cd grpc_demo，运行：  
```python3 -m grpc_tools.protoc -I. --python_out=. --grpc_python_out=. ./cyberdog_app.proto```生成依赖库   
```python3 grpc_teleop.py 172.18.21.183 cert/ca-cert.pem cert/client-key.pem cert/client-cert.pem```
