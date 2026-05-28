# Forest Fire Detection System

An AI-powered forest fire detection system using deep learning and ONNX models. This project provides real-time forest fire detection from images using three different CNN architectures.

## Project Overview

Forest fires cause devastating environmental and economic damage each year. Early detection is critical for rapid response. This system uses computer vision and deep learning to automatically detect forest fires from images, enabling faster alert systems and potentially reducing response times.

## Models

The project includes three ONNX models with different architectures:

1. **Model 1: Baseline CNN** - A basic convolutional neural network serving as a performance baseline
2. **Model 2: Tuned CNN** - An optimized CNN with hyperparameter tuning for better accuracy
3. **Model 3: MobileNetV3** - A lightweight mobile-optimized architecture balancing speed and accuracy

All models are exported to ONNX format for cross-platform compatibility and efficient inference.

## Features

- Real-time forest fire detection from images
- Three model architectures for comparison
- Web interface for easy testing
- ONNX Runtime support for fast inference
- Jupyter notebook for model training and experimentation

----
## Project Structure
```
Forest_Fire_Detection/

├── index.html
├── model1_baseline_cnn.onnx 
├── model2_tuned_cnn.onnx 
├── model3_mobilenetv3.onnx # MobileNetV3 model
├── Forest Fire_Dataset/ 
└── [notebook files].ipynb 
```

## Requirements

To run this project locally, you need:

- Python 3.8 or higher
- ONNX Runtime
- A modern web browser with JavaScript enabled

For development and training:
- TensorFlow or PyTorch
- Jupyter Notebook or Jupyter Lab
- OpenCV
- NumPy

Deployment
The project is deployed to: https://surakshya.netlify.app 

Any static web hosting service

## Future Improvements
Add video stream support for continuous monitoring

Implement drone or CCTV camera integration

Add alert systems (email, SMS notifications)

Expand dataset for better generalization

Optimize models for edge device deployment

## 👤 Author

**SabinAdhikari**  
GitHub: [SabinAdhikarii](https://github.com/SabinAdhikarii)

---

## 📞 Support

For questions or issues, please contact me at sabinofficial99@gmail.com).

---

**Last Updated:** December 2025
