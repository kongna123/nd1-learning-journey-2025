# 🌐 IoT Concepts & Architecture

สิ่งที่ได้เรียนรู้เกี่ยวกับแนวคิดหลักและสถาปัตยกรรมของ Internet of Things ผ่านโปรเจกต์นี้

## Core Architecture
เรียนรู้โครงสร้างระบบ IoT แบบครบวงจร (Full Stack IoT) ตั้งแต่ต้นน้ำยันปลายน้ำ:

1.  **Perception Layer (Device):** การจำลองอุปกรณ์ IoT (Sensors/Actuators) เพื่อกำเนิดข้อมูล
2.  **Network Layer (Transport):** การส่งข้อมูลผ่านโปรโตคอลมาตรฐาน (MQTT/HTTP)
3.  **Processing Layer (Backend):** การจัดการข้อมูลด้วย Python Flask และ Node-RED
4.  **Application Layer (UI/Data):** การแสดงผลผ่าน Grafana และ FlowFuse Dashboard

## Key Learning Points

### 🔹 Data Flow Integration
ความเข้าใจในการไหลของข้อมูล (Data Pipeline):
* **Source:** Device Simulator -> **Broker:** EMQX -> **Processor:** Python/Node-RED -> **Storage:** InfluxDB -> **Visualization:** Grafana

### 🔹 System Integration
การนำ Service ต่างๆ มาทำงานร่วมกัน (Orchestration) โดยใช้ Docker Compose เพื่อจำลองสภาพแวดล้อมจริงของ Server

### 🔹 Workshop References
* **Workshop 01:** Introduction to System Overview
* **Architecture Documentation:** Data Flow & Component Details