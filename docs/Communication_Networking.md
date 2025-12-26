# 📡 Communication & Networking

สิ่งที่ได้เรียนรู้เกี่ยวกับการสื่อสารข้อมูลและเครือข่ายในระบบ IoT

## Protocols

### 1. MQTT (Message Queuing Telemetry Transport)
หัวใจหลักของการสื่อสาร IoT:
* **Broker:** ใช้ EMQX เป็นตัวกลาง
* **Pattern:** Publish / Subscribe Model
* **Topics:** การออกแบบ Topic Hierarchy (เช่น `home/livingroom/temp`)
* **QoS:** ระดับคุณภาพการส่งข้อมูล

### 2. HTTP / REST API
การสื่อสารแบบ Request-Response:
* การใช้ **Flask** สร้าง API Endpoints
* Methods: `GET` (ดึงข้อมูล), `POST` (ส่งคำสั่ง/ข้อมูล)

## Docker Networking
การจัดการเครือข่ายภายใน Container:
* **Service Discovery:** การเรียกหา Service อื่นผ่านชื่อ (เช่น `http://influxdb:8086`)
* **Port Mapping:** การ map port จาก container ออกมาสู่ host
* **Reverse Proxy:** การใช้ **Nginx** เพื่อจัดการ Routing ไปยัง Service ต่างๆ

## Workshop References
* **Workshop 02:** MQTT Basics
* **Workshop 04:** REST API with Flask
* **Network:** Docker Compose Configuration