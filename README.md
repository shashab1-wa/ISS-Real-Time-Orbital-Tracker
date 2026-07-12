# ISS Real-Time Orbital Tracker

Tracked live ISS position every 5 seconds over 1 hour; visualized orbital path on an interactive world map. Built 3 pipeline versions: REST, Kafka producer-consumer, and PySpark streaming.

# Tech Stack
* Language: Python
* Streaming & Messaging:** Apache Kafka & Zookeeper
* Environment:** Google Colab
* APIs Used:** Open Notify ISS API

## 🔬 Research & Publications
This repository contains the real-time implementation alongside my academic research into satellite architectures:

* 📝 **[ISS Real-Time Data Streaming Architecture](./research/ISS_Streaming_Architecture_Paper.pdf)** - Focuses on the core pipeline latency, Kafka messaging, and PySpark micro-batch streaming used in this notebook.
* 📝 **[AI-Driven Optimization of Satellite Communication Networks](./research/AI_Driven_Optimization_Satellite_Networks.pdf)** - Establishes an integrated reference architecture combining Kafka, Flink, and Spark with LSTM-TCN models for data-driven constellation control.
