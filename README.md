# Automated Football Match Event Detection
Project Title: Automated Football Match Event Detection

This project addresses the challenge of automating event detection in football (soccer) match videos. The solution utilizes advanced computer vision and machine learning techniques to process video footage and extract a structured summary of critical moments. This system is a submission for the ML Engineer Assessment, focusing on delivering accurate and reproducible results.

Core Functionality:
The pipeline is engineered to scan a given video file and identify the following key events:

Goals: Detection of goals scored, with a timestamp of the event. The system also includes an optional feature to identify the team that scored.

Yellow Cards: Identification and precise timestamping of instances where a yellow card is shown.

Red Cards: Identification and precise timestamping of red card events.

Methodology:
The approach involves a multi-stage process, starting with video frame extraction and followed by model-based classification. Pre-trained open-source models, such as YOLOv8 for object detection and a custom-trained classifier for event recognition, are leveraged to minimize the need for training from scratch. The system focuses on identifying visual cues like players celebrating (for goals), the referee's hand gestures, and specific card colors.

Output:
The final output is a summarized table (or CSV) containing event types, timestamps, and any additional information captured (e.g., team). Additionally, bonus tasks such as player tracking, substitution detection, and highlight reel generation have been considered and documented as potential future enhancements. The provided code is well-commented, and the accompanying documentation details the logic, libraries used, and a discussion of the project's limitations and areas for improvement.
