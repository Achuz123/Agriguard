# AgriGuard - Smart Agricultural Rover

## 🚀 Project Overview
AgriGuard is an innovative agricultural rover designed to assist farmers in monitoring crop health, detecting soil conditions, and identifying anomalies through real-time imaging and AI-based analysis. This project integrates **IoT and AI** to provide a smart farming solution, reducing manual effort and improving productivity.

The rover is equipped with an **ESP32-CAM** module for capturing images and an **Arduino Uno** for controlling movement and sensor operations. The collected data is analyzed using AI models to detect potential diseases, soil deficiencies, or other agricultural concerns. A web-based interface, built with **React.js** and **Tailwind CSS**, allows users to remotely monitor and control the rover. The backend, powered by **Node.js, Express.js, and MongoDB**, manages communication between hardware and software components. The database used for this project is based on **Paddy Doctor**, providing valuable insights into crop health and diseases.

## 🌟 Key Features
- 📸 **Image Capture & Analysis**: Uses ESP32-CAM to capture real-time images for AI-based processing.
- 🏭 **Smart Farming**: Helps in crop health analysis and soil condition assessment.
- 📡 **Remote Rover Control**: Web-based interface to navigate and monitor the rover.
- 📊 **Data Logging**: Stores collected images and analysis results in MongoDB for historical tracking.
- 🖥️ **User-friendly Dashboard**: Provides real-time insights and control options via a web interface.
- 🔍 **AI-Based Crop Diagnosis**: Leverages AI models trained with Paddy Doctor’s dataset for accurate disease detection.

## 🚀 How It Works
1. The rover navigates the field, capturing images of crops.
2. Images are uploaded to Firebase for storage.
3. AI-based models analyze images to detect crop diseases or soil anomalies.
4. The analysis results are displayed on the web dashboard.
5. Farmers can use the dashboard to track crop conditions and send movement commands to the rover.

## 🤖 AI Models
AgriGuard uses powerful deep learning models for crop health analysis. These models include:

### **ResNet50**
- **Overview**: A 50-layer deep convolutional neural network (CNN) that uses residual connections to overcome the vanishing gradient problem.
- **Advantages**:
  - Residual connections allow for deeper networks and efficient training.
  - Pre-trained on ImageNet and fine-tuned for agricultural data to detect diseases in crops.
- **Use Case**: Detecting diseases such as fungal infections or blights.

### **Xception**
- **Overview**: A deep convolutional model that utilizes depthwise separable convolutions to reduce computational cost while maintaining performance.
- **Advantages**:
  - More efficient than traditional convolutions.
  - Performs well in fine-grained image classification tasks.
- **Use Case**: Classifying soil conditions or detecting pest damage.

### **DenseNet121**
- **Overview**: A deep neural network with dense connections that help improve gradient flow and feature reuse.
- **Advantages**:
  - Dense connections improve accuracy while keeping parameters low.
  - Well-suited for early-stage disease detection and subtle texture analysis in plant images.
- **Use Case**: Detecting early-stage diseases like powdery mildew.

## 📌 Contribution
We welcome contributions! If you're interested in enhancing AgriGuard, feel free to open issues and submit pull requests.

