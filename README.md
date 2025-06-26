# NYC-Live-Traffic-Dashboard-with-Real-Time-ML-Travel-Time-Prediction
This project provides a real-time, end-to-end data pipeline and dashboard for New York City traffic analysis, built as a group project by Anudeep, Piyali, and Avi.


# NYC Live Traffic Analytics Dashboard

A complete real-time traffic analytics and prediction platform for New York City, featuring:
- Data streaming via Kafka
- Live machine learning travel time predictions
- Interactive geospatial dashboards

## 🚦 Overview

This project simulates and analyzes NYC traffic data in real-time. It streams trip data, predicts travel times with ML, and visualizes the results on a live dashboard.

**Group Members:**  
- Anudeep Koneru  
- Piyali  
- Avi

---

## 📦 Project Structure

│
├── streamlit_heatmap_dashboard.py # Streamlit dashboard app
├── train_model.py # Trains ML travel time model
├── predict_live_travel_time.py # Runs ML predictions on live data
├── generate_training_data.py # Simulates/generates trip/training data
├── kafka_producer_nyc.py # Produces (streams) trip data to Kafka
├── kafka_consumer_nyc.py # Consumes streamed data from Kafka
├── save_segments.py # Creates and saves NYC street segment data
├── nyc_traffic_data.csv # (Simulated/streamed) current traffic data
├── training_data.csv # ML model training data
├── predictions.csv # Latest travel time predictions
├── travel_model.joblib # Saved scikit-learn ML model
├── segments.geojson # Geospatial data for Manhattan street segments
├── segment_lengths.csv # Segment lengths for features/model
├── FlowChart.jpg # Project workflow diagram
├── about_project.jpg # About/intro visual
└── cache/ # Dashboard cache (auto-generated)
