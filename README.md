cat > README.md <<'EOF'
# 云边端协同智能巡检与运维平台

## 1. 项目简介

本项目面向智慧机房、实验室和小型数据中心运维场景，构建一套云边端协同的智能巡检与运维平台。

系统通过设备数据采集、边缘网关接入、智能巡检任务管理、异常告警、知识库问答、ROS2机器人接入和AI视觉识别，帮助运维人员及时发现设备异常、定位故障原因并形成处理建议。

## 2. 项目目标

本项目不是单一 Demo，而是一个完整的平台型项目，目标是按照公司级项目流程完成从需求分析、架构设计、接口设计、数据库设计、开发、测试、部署、监控到复盘的完整过程。

## 3. 核心能力

- 用户与权限管理
- 设备管理
- 模拟设备数据上报
- 实时监控大屏
- 告警规则与告警记录
- 边缘网关接入
- MQTT 设备通信
- RAG 运维知识库问答
- ROS2 巡检机器人接入
- AI 视觉巡检
- 异常检测
- Docker / Kubernetes 部署
- Prometheus / Grafana 监控

## 4. 技术栈规划

### 后端

- FastAPI
- PostgreSQL
- Redis
- SQLAlchemy / SQLModel
- Alembic
- JWT
- WebSocket
- MQTT

### 前端

- React
- TypeScript
- Ant Design
- ECharts

### AI

- OpenCV
- YOLO
- scikit-learn
- RAG
- 向量数据库

### 云原生与运维

- Docker
- Docker Compose
- Kubernetes
- Nginx
- Prometheus
- Grafana
- CI/CD

### 边缘与机器人

- Python 设备模拟器
- MQTT Client
- ROS2
- Gazebo / RViz
- 传感器数据采集

## 5. 版本规划

| 版本   | 阶段           | 核心内容                               | 状态   |
| ------ | -------------- | -------------------------------------- | ------ |
| v1.0.0 | 项目初始化     | 项目目录、文档体系、Git规范            | 进行中 |
| v1.1.0 | 后端基础框架   | FastAPI、数据库、Redis、日志、异常处理 | 规划中 |
| v1.2.0 | 用户与权限     | 登录、JWT、角色权限                    | 规划中 |
| v1.3.0 | 设备管理       | 设备增删改查、设备状态                 | 规划中 |
| v1.4.0 | 数据上报       | 模拟设备、心跳、指标数据               | 规划中 |
| v1.5.0 | 监控大屏       | 设备统计、指标曲线、状态展示           | 规划中 |
| v1.6.0 | 告警管理       | 告警规则、告警记录、告警处理           | 规划中 |
| v1.7.0 | Docker部署     | Docker Compose 一键部署                | 规划中 |
| v2.0.0 | 云边端链路     | MQTT、边缘网关、任务下发               | 规划中 |
| v3.0.0 | 运维助手       | RAG、知识库、告警解释                  | 规划中 |
| v4.0.0 | ROS2接入       | 巡检机器人状态与任务接入               | 规划中 |
| v5.0.0 | AI视觉与工程化 | 视觉识别、监控、CI/CD、K8s             | 规划中 |

## 6. 项目目录

```text
cloud-edge-inspection-platform/
├── docs/
├── backend/
├── frontend/
├── edge-gateway/
├── ros2_ws/
├── ai-services/
├── deploy/
├── scripts/
├── README.md
├── CHANGELOG.md
├── .env.example
└── .gitignore
```
