# 🔍 YOLO Image Search System

An end-to-end computer vision application that enables searching and visualizing images based on detected objects using YOLO.
The system runs one-time inference, stores structured metadata, and supports interactive querying without re-running the model.

# Features

YOLO-based object detection with reusable metadata (JSON)

Boolean search over classes (AND / OR)

Optional per-class count thresholds

Interactive visualization with bounding boxes

Configurable grid layout and highlighting

Export filtered results as JSON

# Tech Stack

Python · PyTorch · YOLO · Streamlit · PIL · JSON

# Run the App
pip install -r requirements.txt
streamlit run app.py

# High-Level Flow

Run YOLO inference or load existing metadata

Filter images using class and count constraints

Visualize annotated results

Export search results
