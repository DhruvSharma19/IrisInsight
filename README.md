# 👁️ IrisInsight - Eye Tracker Using ResNet

This project is an eye-tracking system that uses a ResNet model for iris estimation. It involves collecting eye images, augmenting them, training a neural network to predict iris positions, and running a real-time eye tracker. The project is implemented in Python using TensorFlow, OpenCV, and Albumentations libraries.

## 🎥 Demo Video



## 🛠️ System Diagrams



## 🌟 Key Features

- 📹 Real-time eye tracking using a webcam
- 🔍 Iris position estimation with ResNet152V2 model
- 🌟 Data augmentation for robust training
- 🖼️ Interactive visualization of predictions
- ⚙️ Easy to set up and run

## 🛠 Technologies Used

- 🐍 **Python**
- 🔬 **TensorFlow**
- 👁️ **OpenCV**
- 🎨 **Albumentations**
- 📈 **Matplotlib**

## 📸 Screenshots



## 🚀 Getting Started

### Prerequisites

- 🐍 Python 3.x
- 📹 Webcam

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/DhruvSharma19/IrisInsight.git
    cd IrisInsight
    ```

### Data Collection

1. Run the `DataCollection.ipynb` notebook to capture images from your webcam:
    ```bash
    jupyter notebook DataCollection.ipynb
    ```

2. Follow the instructions in the notebook to capture images and save them to the `data` directory.

### Data Augmentation and Preparation

1. 📁 Organize the captured images and label files into `train`, `test`, and `val` folders under the `data` directory.

2. 🌟 Run the data augmentation code provided in the `DataCollection.ipynb` notebook to augment the data and save it to the `aug_data` directory.

### Model Training

1. Open the `IrisEstimation.ipynb` notebook and run all cells to train the ResNet model for iris estimation:
    ```bash
    jupyter notebook IrisEstimation.ipynb
    ```

2. The trained model will be saved as `eyetrackerresnet.h5`.

### Real-Time Eye Tracking

1. Run the real-time eye tracker using your webcam:
    ```bash
    python RealTimeEyeTracker.py
    ```

    *(Create a separate Python script named `RealTimeEyeTracker.py` that contains the real-time tracking code from the last cell of `IrisEstimation.ipynb`.)*

## 🤝 Contributions

We welcome contributions to IrisInsight! To contribute:

1. **Fork the Repository**:
   Click the "Fork" button at the top right corner of the repository page.

2. **Clone Your Fork**:
   ```bash
   git clone https://github.com/your-username/IrisInsight.git
   cd FlowLink
   ```

3. **Create a New Branch**:
   ```bash
   git checkout -b feature/your-feature-name
   ```

4. **Make Your Changes**:
   Implement your feature or fix the bug.

5. **Commit Your Changes**:
   ```bash
   git add .
   git commit -m "Add your commit message here"
   ```

6. **Push to Your Fork**:
   ```bash
   git push origin feature/your-feature-name
   ```

7. **Create a Pull Request**:
   Open a pull request from your forked repository's branch to the main branch of the original repository.

We appreciate your contributions and will review your pull request as soon as possible!

## 🙏 Acknowledgements

A big thank you to everyone who contributed to this project! We appreciate your support and feedback.

If you have any questions or need assistance, feel free to open an issue or reach out to the project maintainers. Enjoy using IrisInsight and happy coding! ✨
