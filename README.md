## Article List

### 1. [DAS System Design Report](DAS.pdf)

**Distributed Acoustic Sensing (DAS) System Design Report** Author: Zehua Huang · Nov 2025

This report introduces the design and implementation of a Distributed Acoustic Sensing (DAS) system. The system utilizes C++ for high-throughput data acquisition and shared memory management, and Python for real-time visualization and the interactive interface. It supports waveform, spectrum, and waterfall displays, signal audio reconstruction, and anomaly detection alerts. It is well-suited for scenarios such as perimeter security, pipeline leakage monitoring, and traffic vibration monitoring.

### 2. [Fallert Fall Detection System](Fallert.pdf)

**Fallert: Cost-effective IoT Fall Detection System** Authors: Shalva Butkhuzi, Zehua Huang · Mar 2025

A low-cost IoT fall detection solution designed for elderly users. Built on the ESP32 and MPU6500 to collect motion data, the device transmits alerts to mobile phones via Wi-Fi/Bluetooth. Notifications are preferentially pushed to the family app via MQTT, with SMS serving as a backup channel. This system offers a more accessible alternative to existing commercial solutions in terms of cost, battery life, and wearability.

### 3. [Performance Analysis and Optimization of a gRPC-based Edge Gateway](Performance_Analysis_and_Optimization_of_a_gRPC_based_Edge_Gateway_for_High_Frequency_Railway_Telemetry.pdf)

**Performance Analysis and Optimization of a gRPC-based Edge Gateway for High-Frequency Railway Telemetry** Author: Zehua Huang · Mar 2026

This report evaluates and optimizes a Go-implemented gRPC edge gateway designed for a high-frequency telemetry scenario involving 16 edge devices across a 32-kilometer railway monitoring network. Through techniques such as traffic prioritization, compact Protobuf data structures, and `sync.Pool` object pooling, the throughput of the Optimized-Unary mode was increased by approximately 2.14x, while the average and P95 latencies were reduced by about 50% and 56%, respectively. This work provides a practical reference for large-scale, safety-critical railway IoT deployments.

### 4. [Hierarchical IPTC Topic Classification (internship report, draft)](Hierarchical_IPTC_Topic_Classification_with_EuroBERT_and_HGCLR.pdf)

**Hierarchical IPTC Topic Classification of French Press Articles with EuroBERT and Hierarchy-Guided Contrastive Learning** Author: Zehua Huang · Oct 2026 · draft

Internship report at Abstrakt. A EuroBERT encoder tags press articles with the topics of the three-level IPTC Media Topics tree. The model rebuilds HGCLR on EuroBERT, adds article-to-topic attention, attention pooling and the asymmetric loss, and keeps its predictions coherent with avg-max, a variant of the C-HMCNN max rule. Trained on LLM-generated articles and tested on real French press.


# report

本仓库收录四篇技术报告，涵盖分布式光纤传感、物联网跌倒检测与铁路边缘网关性能优化等方向。

## 文章列表

### 1. [DAS 系统设计报告](DAS.pdf)

**Distributed Acoustic Sensing (DAS) System Design Report**  
作者：Zehua Huang · 2025.11

介绍分布式声学传感（DAS）系统的设计与实现。系统采用 C++ 负责高吞吐数据采集与共享内存管理，Python 负责实时可视化与交互界面，支持波形/频谱/瀑布图展示、信号音频重建及异常检测告警，适用于周界安防、管道泄漏监测与交通振动监测等场景。

### 2. [Fallert 跌倒检测系统](Fallert.pdf)

**Fallert: Cost-effective IoT Fall Detection System**  
作者：Shalva Butkhuzi, Zehua Huang · 2025.03

面向老年用户的低成本 IoT 跌倒检测方案。设备基于 ESP32 与 MPU6500 采集运动数据，通过 Wi-Fi / 蓝牙将告警发送至手机端，优先经 MQTT 推送至家属端 App，并以 SMS 作为备用通道，在成本、续航与可穿戴性上提供比现有商业方案更易普及的替代选择。

### 3. [gRPC 边缘网关性能分析与优化](Performance_Analysis_and_Optimization_of_a_gRPC_based_Edge_Gateway_for_High_Frequency_Railway_Telemetry.pdf)

**Performance Analysis and Optimization of a gRPC-based Edge Gateway for High-Frequency Railway Telemetry**  
作者：Zehua Huang · 2026.03

针对 32 公里铁路监测网络中 16 台边缘设备的高频遥测场景，评估并优化 Go 实现的 gRPC 边缘网关。通过流量分级、紧凑 Protobuf 数据结构与 `sync.Pool` 对象池等手段，将 Optimized-Unary 模式吞吐量提升约 2.14 倍，平均与 P95 延迟各降低约 50% 与 56%，为大规模、安全关键的铁路 IoT 部署提供参考。

### 4. [层级 IPTC 主题分类（实习报告，草稿）](Hierarchical_IPTC_Topic_Classification_with_EuroBERT_and_HGCLR.pdf)

**Hierarchical IPTC Topic Classification of French Press Articles with EuroBERT and Hierarchy-Guided Contrastive Learning**  
作者：Zehua Huang · 2026.10 · 草稿

Abstrakt 实习报告。基于 EuroBERT 编码器，为新闻文章标注 IPTC Media Topics 三层主题树中的主题。在 EuroBERT 上重建 HGCLR，加入文章-主题注意力、注意力池化与非对称损失（ASL），并以 C-HMCNN 最大值规则的变体 avg-max 保证预测的层级一致性。模型在 LLM 生成的文章上训练，在真实法语新闻上测试。
