# SnowFlake  
  
# 分布式雪花算法 SnowFlake 每秒自增生成26个万个可排序的ID

datacenterId（分布式）（服务ID 1，2，3.....） 每个服务中写死  
machineId（用于集群） 机器ID 读取机器的环境变量MACHINEID 部署时每台服务器ID  
