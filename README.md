# MSc-Project

Real-Time Driver Distraction Detection System

Overview

This project focuses on developing a real-time driver distraction detection system as part of an MSc final project, addressing the critical issue of road safety. By leveraging advanced machine learning techniques, the system integrates YOLOv8 and EfficientNet CNN models to identify and classify distracted driving behaviors.

Designed for affordability and scalability, the system operates on a Raspberry Pi equipped with a camera module, enabling real-time monitoring in vehicle environments.

Features

Data Preparation and Preprocessing:

Utilized a publicly available dataset for model training.

Advanced preprocessing techniques, including:

Face detection

Image augmentation

Image resizing using OpenCV.

Model Design and Implementation:

YOLOv8 for object detection.

EfficientNet CNN for feature extraction.

High accuracy and computational efficiency achieved through model optimization.

Hardware Integration:

Configured a Raspberry Pi with a camera module to process real-time video streams.

Designed to operate under hardware constraints for practical deployment.

Testing and Evaluation:

Extensive testing conducted under varying environmental conditions, including:

Lighting changes.

Motion variations.

Obstructions.

Evaluated key metrics such as accuracy, latency, and computational efficiency.

Results and Impact:

Delivered a cost-effective and scalable solution for real-time distracted behavior detection.

Potential applications in personal vehicles, fleet management, and road safety systems.

Key Achievements

Designed and implemented a low-cost, resource-efficient solution for real-world in-vehicle environments.

Addressed the research gap in live detection systems by creating a system capable of real-time operation on hardware-constrained platforms.

Gained expertise in:

Machine learning frameworks: YOLOv8, EfficientNet, and OpenCV.

Hardware-software integration using Raspberry Pi.

Technologies Used

Programming Languages: Python

Libraries and Frameworks:

YOLOv8

EfficientNet

OpenCV

Hardware: Raspberry Pi with Camera Module

How It Works

Data Preprocessing: Input data undergoes preprocessing (face detection, augmentation, resizing).

Model Prediction:

YOLOv8 detects objects in the video stream.

EfficientNet classifies behaviors based on extracted features.

Real-Time Monitoring:

The Raspberry Pi processes video streams and displays the detected behaviors.

Alert System (optional): Can be configured to alert the driver in case of distracted behavior.

Installation and Usage

Prerequisites

Hardware:

Raspberry Pi (Model 4 or higher recommended)

Camera Module

Software:

Python 3.8+

Git

Steps to Run

Clone the repository:

git clone <repository-url>
cd <repository-folder>

Install dependencies:

pip install -r requirements.txt

Connect the Raspberry Pi camera module and ensure it is enabled in raspi-config.

Run the system:

python driver_distraction_detection.py

Testing and Evaluation

Tested under diverse environmental conditions:

Lighting: Daytime, nighttime, shadows.

Motion: Different driving speeds.

Obstructions: Partial occlusion of the driver's face.

Achieved:

High accuracy in detecting and classifying distracted behaviors.

Low latency for real-time operation.

Future Improvements

Integration with cloud services for centralized monitoring.

Implementation of additional behavioral classes (e.g., drowsiness detection).

Deployment on more powerful embedded systems for enhanced performance.

Contributing

Contributions are welcome! If you have suggestions for improvements, please create a pull request or open an issue.

License

This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments

Public dataset used for training.

Inspiration from advancements in driver monitoring systems.

Feel free to adapt this README to your repository by adding links and specific commands as needed!

