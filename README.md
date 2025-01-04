# Gauge Reader: End-to-End Solution for Analog Gauge Interpretation

This project provides an end-to-end solution for detecting and interpreting analog gauges. It leverages two TensorFlow Lite models:

* **Object Detection Model (best.tflite):** Detects key features like min/max values, needle base, and needle tip positions.
* **Angle Regression Model (final_angle_regression_model.tflite):** Predicts the angle of the needle and maps it to the gauge value.
