# Elderly Care Monitoring System Using Computer Vision

This project is a real-time posture monitoring system designed to enhance the safety of elderly individuals using computer vision technologies. It uses MediaPipe and OpenCV to detect and classify body postures such as:

Standing
Sitting
Sleeping
Falling

By analyzing key body landmarks and calculating angles, the system can accurately recognize these postures through a connected camera feed.

# Activity Logging
The system also records the duration of each detected activity (e.g., how long a person is sitting, sleeping, or standing), along with the timestamp of when it started. This data can be used to monitor daily patterns, detect anomalies, or generate activity reports.

# Fall Detection & Notification
When a falling action is detected, the system triggers an instant WhatsApp alert to notify caregivers or family members, ensuring timely response and reducing risk from unattended falls.

# Technologies Used
Python

OpenCV

MediaPipe

Twilio API (for WhatsApp notifications)

This project is ideal for home care, elderly care centers, or remote health monitoring solutions.
