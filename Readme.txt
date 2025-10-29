# Spark Kafka Streaming

Implementación de procesamiento batch y en tiempo real con **Apache Spark** y **Apache Kafka**.  
Incluye limpieza de datos, análisis exploratorio (EDA) y procesamiento de flujo con Spark Streaming.

---

## 📦 Contenido
- `spark-kafka-demo.rar`: Proyecto completo con el código fuente y scripts de ejecución.
- `LICENSE`: Licencia MIT.
- `.gitignore`: Configuración para ignorar archivos temporales de Python y entorno.
- `README.md`: Documentación del proyecto.

---

## ⚙️ Requisitos
- Python 3.8+
- Apache Spark 3.x
- Apache Kafka
- Docker (opcional, para ejecutar Kafka y Zookeeper)
- Librerías principales:
  - pyspark  
  - kafka-python  
  - pandas

---

## 🚀 Ejecución
1. Descomprimir el archivo `spark-kafka-demo.rar`.
2. Iniciar Zookeeper y Kafka (puedes usar Docker o instalación local).
3. Crear un *topic* en Kafka:
   ```bash
   kafka-topics.sh --create --topic spark-demo --bootstrap-server localhost:9092


Daniel Velasquez
