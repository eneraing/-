# -
用于江南大学计算机科学与技术2302班 计算机网络课程设计报告链接 可在此查看报告附件A：思科模拟器配置文件
---

# 📡 Cisco Network Simulator Configuration

## 项目简介
本项目是基于江南大学的计算机网络课程设计相关题目的思科配置文件分享，用于课程设计大作业备案以及调查。

本项目是基于 **Cisco 网络设备配置** 的学习与实验示例，使用思科模拟器（如 Packet Tracer 或 GNS3）完成了一个典型的多区域企业/校园网络的规划与配置，主要包括：

* 静态与动态路由（静态路由、OSPF）
* VLAN 划分与 Trunk 配置
* ACL 安全策略控制
* NAT 转换（源地址与静态映射）
* DHCP 中继 / DNS / Web 服务简单搭建

本项目可用于：

* 计算机网络课程实验
* 思科 CCNA/CCNP 认证学习
* 网络工程实践模拟

---

## 📂 目录结构

```
.
├── configs/
│   ├── routers/       # 各路由器配置脚本
│   ├── switches/      # 各交换机配置脚本
│   └── servers/       # 服务器配置简档
├── diagrams/
│   └── topology.png   # 网络拓扑示意图
├── packet-tracer/
│   └── project.pkt    # Packet Tracer 原文件
├── docs/
│   └── report.md      # 项目报告与分析
└── README.md
```

---

## 🚀 快速开始

1. **克隆仓库**

   ```bash
   git clone https://github.com/yourusername/cisco-network-sim.git
   cd cisco-network-sim
   ```

2. **打开 Packet Tracer 文件**
   使用 Cisco Packet Tracer 或 GNS3 打开 `packet-tracer/project.pkt`，可以看到完整的网络拓扑与预配置设备。

3. **查看配置文件**
   所有路由器、交换机配置都在 `configs/` 下，可以手动逐行输入到设备，也可用于学习备份。

---

## ⚙️ 核心特性

* 基于 VLAN 的办公区与教学区隔离
* 使用 OSPF 实现运营商与信息中心互联
* ACL 在出入口过滤教学区网络访问互联网
* NAT 动态地址池 + 静态映射实现公网访问
* DHCP 中继在不同 VLAN 分配 IP 地址
* 简单 DNS/WWW 服务部署

---


## 🤝 贡献

欢迎提交 Issues 或 Pull Requests，分享改进的网络设计或配置优化。本课程设计主要用于江南大学课程设计相关事宜

---

## 📜 许可

本项目采用 MIT License，可自由使用、修改与分享，不得涉及到对本校课程设计课程成绩相关的权力侵犯。

---

