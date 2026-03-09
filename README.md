# Project-LockedBot
LockedBot is designed for researchers, developers, and companies building robotic systems who want security-first middleware. It is modular, open-source, and designed to integrate seamlessly with existing robotic stacks.

Project LockedBot is an open-source security middleware designed to make robotic systems safe, resilient, and cyberattack-resistant. It provides a universal security layer that can integrate with ROS2, ROS1, or other robot middleware, enabling developers to secure communication, authenticate nodes, and enforce command authorization across distributed robotic networks.

# Key Features

- Node Authentication – Ensure only trusted nodes can join the robotic system
- Encrypted Communication – End-to-end message encryption using TLS/mTLS
- Command Authorization – Role-based policies to prevent unauthorized commands
- Anomaly Detection (Optional) – Detect abnormal sensor or motor commands and trigger safe mode
- Universal Middleware Support – Modular adapters for ROS2, ROS1, and custom frameworks
- Safe Mode Fallback – Automatically stop robot operations if a security threat is detected
  
# Why LockedBot?
Modern robotic systems — from drones and autonomous vehicles to industrial and healthcare robots — are increasingly connected and exposed to cyber threats. Most robots lack robust security by design. Project LockedBot provides a trusted layer between middleware and hardware, making robotics security practical, reliable, and accessible.
