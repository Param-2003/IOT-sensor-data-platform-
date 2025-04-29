# 📡 IoT Sensor Data Platform – Real-Time Data Lake Architecture

A real-time data engineering solution that simulates and processes high-volume IoT sensor data. This pipeline demonstrates the ingestion, validation, anomaly detection, and preparation of structured sensor data, ready for cloud-scale analytics via AWS Glue, Athena, and S3.

---

## 🚀 Project Overview

This project simulates 10,000+ IoT sensors streaming real-time temperature and humidity data. It includes a data cleaning pipeline, basic anomaly detection, and a foundation for building a real-time AWS-powered data lake architecture.

✅ Built for scale  
✅ Presented via Jupyter Notebook for demo  
✅ Designed to transition into a cloud-native pipeline

---

## 🛠️ Technologies Used

- Python (Pandas, NumPy)
- Jupyter Notebook (demo + visualization)
- Matplotlib, Seaborn (data visualization)
- AWS Glue (planned for scalable ETL)
- AWS S3 (data lake layer)
- AWS Athena (structured querying)
- AWS SNS (for real-time alerts in production)
- Kafka/Kinesis (for real-time ingestion - scalable version)

---

## 🧩 Architecture (Production Vision)

```
IoT Sensors ➝ Kafka/Kinesis ➝ AWS S3 (raw) ➝ AWS Glue (transform) ➝ Athena (query) ➝ Alerts (SNS) + Dashboards (Grafana)
```

> This notebook simulates the entire flow with local code blocks and is designed to scale on AWS cloud.

---

## 📂 Project Structure

```
iot-sensor-data-platform/
├── notebooks/
│   └── iot_sensor_data_pipeline.ipynb
├── visualization/
│   └── sensor_trend_charts.png
├── architecture_diagram.png
├── README.md
└── requirements.txt
```

---

## 📊 Key Features

- Simulates 10,000+ sensor records with random values
- Validates and cleans temperature/humidity readings
- Detects abnormal readings (e.g., temperature > 38°C)
- Plots temperature trends using Matplotlib & Seaborn
- Exports cleaned data for cloud ingestion (e.g., Athena or S3)
- Designed to scale with AWS-native tooling

---

## 📈 Sample Use Cases

- Smart city environmental monitoring  
- Predictive maintenance for IoT hardware  
- Live dashboards for environmental alerting  
- Cost-optimized serverless data pipeline for sensor platforms  

---

## ⚡ Scalability Notes

This Jupyter Notebook demonstrates the logic flow using in-memory processing.  
The production-grade pipeline would be implemented using:

- **AWS Kinesis / Kafka** for real-time stream ingestion  
- **AWS S3** for data lake storage  
- **AWS Glue** for Spark-based distributed ETL  
- **Athena or Redshift Spectrum** for low-latency querying  
- **SNS + Lambda** for alert automation  
- **Grafana or QuickSight** for live dashboards

---

## ✅ Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/iot-sensor-data-platform.git
   cd iot-sensor-data-platform
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   ```bash
   jupyter notebook notebooks/iot_sensor_data_pipeline.ipynb
   ```

---

## 🙌 Acknowledgements

Built as part of a real-world portfolio to demonstrate skills in scalable cloud-native data engineering, IoT data modeling, and anomaly detection systems.

---

## 📬 Contact

- **Name:** Paramveer Singh Shekhawat  
- **Email:** rahulshekhawat408@gmail.com  
- **LinkedIn:** [LinkedIn Profile](https://www.linkedin.com/in/paramveer-singh-shekhawat-376a1a244/)  
- **GitHub:** [GitHub Profile](https://github.com/Param-2003)

---
