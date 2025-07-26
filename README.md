# 🔍 UIU Lost and Found System

**Smart Automated Lost Item Management with ML-Based Object Detection**

The UIU Lost and Found System is a comprehensive automated solution for managing lost items within university campus environments. This innovative system combines machine learning-based object detection, Arduino-powered hardware automation, and user-friendly interaction interfaces to create a seamless lost-and-found experience with 90% identification accuracy.

## 🎥 Demo Video

[![UIU Lost and Found System Demo](https://img.shields.io/badge/▶️-Watch%20Demo%20Video-red?style=for-the-badge&logo=youtube)](https://youtu.be/7L6bt5VlScU?si=gHwdVN1p5ZPHbyrU)

*Click the badge above to watch the complete demonstration of the automated Lost and Found System in action!*

## 🚀 Features

### 🤖 Machine Learning & Computer Vision

#### 📷 Intelligent Object Detection
- **Webcam Integration**: Real-time item analysis using OpenCV for image processing
- **Multi-Parameter Detection**: System identifies three key characteristics:
  - **Item Color**: Automated color recognition and classification
  - **Text Recognition**: OCR capabilities to read text written on items
  - **Item Classification**: ML model categorization of objects

#### 🎯 Smart Classification System
- **Handbag Category**: Specialized detection for bags and purses
- **Pendrive Category**: USB drives and small storage devices
- **Unknown Category**: Fallback classification for unrecognized items
- **90% Accuracy**: High-precision identification and matching system

### 🔧 Hardware Automation

#### 🏷️ RFID-Based User Identification
- **Secure Access**: RFID scanner integration for user verification
- **Identity Management**: Seamless user authentication system
- **Database Integration**: User profiles linked with lost item claims

#### 🚚 Automated Item Handling
- **Conveyor Belt System**: Automated item transportation mechanism
- **IR Sensors**: Precise item transfer detection and control
- **Servo Motors**: Accurate item placement in categorized storage boxes
- **Mechanical Precision**: Smooth item retrieval from category boxes to conveyor belt

### 💻 User Interaction Interface

#### 🖥️ LCD & Keypad System
- **Interactive Display**: LCD screen for user prompts and information
- **Keypad Input**: User-friendly keypad for answering verification questions
- **Question-Answer Verification**: Three-question validation system for item claims
- **Real-time Feedback**: Immediate response and system status updates

#### 🔐 Secure Item Retrieval Process
1. **User Authentication**: RFID-based identity verification
2. **Question Validation**: Three-answer verification system
3. **Automated Retrieval**: System activates conveyor belt upon successful validation
4. **Item Delivery**: Items delivered through secure receiving window

### 📥 Item Submission Process
- **Easy Deposit**: Users can submit found items directly into the system
- **Automatic Processing**: OpenCV-powered detection begins immediately upon item placement
- **Instant Categorization**: Real-time classification and storage assignment
- **Database Logging**: All submissions recorded with timestamps and characteristics

## 🛠️ Technical Stack

- **Programming Language**: Python
- **Computer Vision**: OpenCV for image processing and detection
- **Machine Learning**: TensorFlow for model training and classification
- **Development Environment**: Jupyter Notebook for ML model development
- **Hardware Platform**: Arduino for sensor and motor control
- **Database**: MySQL for user and item data management
- **Hardware Components**: RFID scanners, IR sensors, servo motors, conveyor belt system
- **User Interface**: LCD display and keypad integration

## 📋 System Requirements

### Software Requirements
- Python 3.8 or higher
- OpenCV library
- TensorFlow for ML model training and inference
- Jupyter Notebook for model development
- MySQL database
- Arduino IDE
- Required Python packages (opencv-python, mysql-connector-python, numpy, tensorflow, jupyter)

### Hardware Requirements
- Arduino microcontroller
- Webcam for image capture
- RFID scanner module
- IR sensors
- Servo motors
- Conveyor belt mechanism
- LCD display
- Keypad module
- Power supply units

## 🚀 Getting Started

### Software Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/rakib73520/Microprocessor-Project.git
   cd Microprocessor-Project
   ```

2. **Install Python dependencies**
   ```bash
   pip install opencv-python mysql-connector-python numpy tensorflow jupyter
   ```

3. **Database setup**
   ```sql
   CREATE DATABASE lost_found_system;
   -- Import database schema from provided SQL file
   ```

4. **Configure database connection**
   ```python
   # Update database credentials in config file
   DB_HOST = "localhost"
   DB_USER = "your_username"
   DB_PASSWORD = "your_password"
   DB_NAME = "lost_found_system"
   ```

### Hardware Setup

1. **Arduino Connections**
   - Connect RFID scanner to designated pins
   - Wire IR sensors for item detection
   - Set up servo motors for item placement
   - Configure LCD and keypad connections

2. **Upload Arduino Code**
   ```bash
   # Open Arduino IDE and upload the provided sketch
   # Ensure all pin configurations match your hardware setup
   ```

3. **Calibrate System**
   - Test webcam positioning for optimal detection
   - Calibrate conveyor belt speed and servo positions
   - Verify RFID scanner functionality

## 🔄 System Workflow

### Item Submission Process
1. **Item Placement**: User places found item in submission area
2. **Automatic Detection**: Webcam captures item using OpenCV
3. **ML Classification**: System analyzes color, text, and category
4. **Storage Assignment**: Item automatically sorted into appropriate category box
5. **Database Logging**: Item characteristics and timestamp recorded

### Item Retrieval Process
1. **User Authentication**: User scans RFID for identity verification
2. **Item Search**: System queries database for user's lost items
3. **Verification Questions**: LCD displays three validation questions
4. **Answer Validation**: User inputs answers via keypad
5. **Automated Retrieval**: Upon successful validation:
   - Servo motor places item on conveyor belt
   - Conveyor belt transports item to receiving window
   - User collects item securely

## 📊 Key Performance Metrics

- **90% Identification Accuracy**: High-precision ML-based object detection
- **Real-time Processing**: Instant item classification and storage
- **Automated Workflow**: Minimal human intervention required
- **Secure Verification**: Multi-layer authentication system
- **Efficient Storage**: Organized categorization system

## 🎯 Project Objectives

This system was developed to:
- **Automate Lost Item Management**: Reduce manual handling and processing time
- **Enhance Security**: Multi-layer verification for legitimate item claims
- **Improve Accuracy**: ML-based detection eliminates human error in classification
- **Streamline Process**: End-to-end automation from submission to retrieval
- **Ensure Reliability**: Robust hardware integration with software intelligence

## 🤝 Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for:
- ML model improvements and accuracy enhancements
- Hardware integration optimizations
- User interface enhancements
- Database schema improvements
- Documentation updates

## 👨‍💻 Developer

**Rakibul Hasan**
- 📧 Email: rakibulhasan38556@gmail.com
- 💼 LinkedIn: [Rakibul Hasan](https://www.linkedin.com/in/rakibul-hasan-5539891a3/)
- 🐙 GitHub: [@rakib73520](https://github.com/rakib73520)
- 🏆 Competitive Programming: [Codeforces](https://codeforces.com/profile/rakib73520) | [LeetCode](https://leetcode.com/rakib73520)

---

*Built with 🤖 combining Machine Learning, Computer Vision, and Hardware Automation for smart campus solutions*
