# Computer-Network

请使用Packet_Tracer 8.1以上版本进行查看

## 实验内容
1. 单交换机实现基于端口的 VLAN 设计
2. 跨交换机实现 VLAN 设计
3. 静态路由设计
4. 动态路由 (RIP 协议) 设计
5. 动态路由 (OSPF 协议) 设计
6. DNS 服务器设计
7. WWW 服务器设计
8. FTP 服务器设计
9. 综合实验（园区网）

## 创新点
相较于实验指导书,基本上每个实验都做了一定程度的创新与修改

### RIP协议与OSPF协议对比

通过采用同一个拓扑图,RIP协议与OSPF协议选择了不同的路径,将RIP协议与OSPF协议进行了对比.

![E1](https://user-images.githubusercontent.com/58097859/162116744-5698de3f-d4d7-41f2-9a65-5ed7ad9474d9.png)

对于上图主机$PC0$与主机$PC1$之间的路径有两条

1.PC0 → 路由器0 → 路由器2 → PC1.

2.PC0 → 路由器0 → 路由器1 → 路由器2 → PC1.

RIP协议考虑的是最少的跳数，RIP协议选择路径1

OSPF基于链路状态，OSPF协议选择路径2

### 园区网设计

![T13](https://user-images.githubusercontent.com/58097859/162153499-3cebb0c0-c24a-466e-88d4-f16f0487f204.png)


按照接入层、汇聚层和核心层进行设计

实现了静态路由，动态路由，路由聚合，ACL，NAT等，详细内容请看实验报告
