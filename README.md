# 5G Network Slice Classification Using CNN  

This project demonstrates the use of Convolutional Neural Networks (CNNs) to classify 5G network slices based on simulated data. The slices represent three core 5G functionalities:  
- **eMBB (Enhanced Mobile Broadband)**  
- **mMTC (Massive Machine-Type Communications)**  
- **URLLC (Ultra-Reliable Low-Latency Communications)**  

The project provides end-to-end functionality, from synthetic data generation to visualizing model performance through multiple metrics and plots.  

---

## Features  
- **Synthetic Data Simulation**: Creates a dataset with key parameters such as latency, throughput, signal strength, and more, with corresponding slice labels.  
- **CNN Model**: Utilizes a deep learning-based CNN for accurate slice classification.  
- **Performance Visualizations**: Includes:  
  - Accuracy and Loss Curves  
  - Confusion Matrix  
  - ROC Curves for class-specific performance  
  - Pair Plots with KDE  
  - Simulated Resource Utilization Heatmap  

---

## Technologies Used  
- **Programming Language**: Python  
- **Libraries**:  
  - TensorFlow/Keras  
  - Matplotlib  
  - Seaborn  
  - Scikit-learn  

---

## File Structure  
- **Colab Notebook**: Contains all the code for synthetic data generation, model training, evaluation, and visualization, organized into modular blocks for clarity.  

---

## How to Run  
1. Download the Colab Notebook file.  
2. Open it in Google Colab ([Google Colab](https://colab.research.google.com/drive/1YXNBPb4X7P7UnYur0wBrKWtmH7uH2Yz_?usp=sharing)).  
3. Execute each block sequentially to:  
   - Generate the synthetic dataset  
   - Train the CNN model  
   - Visualize the outputs  

---

## Visual Outputs  
1. **Training Accuracy and Loss**:  
   - Tracks the progress of the model during training.  
2. **Confusion Matrix**:  
   - Visualizes classification performance across the three slice categories.  
3. **ROC Curves**:  
   - Provides AUC scores for eMBB, mMTC, and URLLC slices.  
4. **Pair Plot with KDE**:  
   - Displays feature relationships for different slice categories.  
5. **Simulated Heatmap**:  
   - Illustrates resource utilization trends for 5G slices.  

---

## Example Plots  
### Training Performance  
![Accuracy and Loss Example](https://github.com/pradyot29/Deep-Learning-Based-Framework-for-Network-Slice-Optimization-in-5G-Networks/blob/main/accuracy-loss.jpg)

### Confusion Matrix  
![Confusion Matrix Example](https://github.com/pradyot29/Deep-Learning-Based-Framework-for-Network-Slice-Optimization-in-5G-Networks/blob/main/confusion-matrix.jpg)

### Resource Utilization Heatmap  
![Heatmap Example](https://github.com/pradyot29/Deep-Learning-Based-Framework-for-Network-Slice-Optimization-in-5G-Networks/blob/main/heatmap.jpg)

---

## Acknowledgments  
This project explores the integration of 5G technologies and machine learning techniques, highlighting the potential for automated slice classification and resource optimization.
We would like to extend our heartfelt gratitude to **Bhupendra Sir** for his invaluable guidance and support throughout this project. His insights and expertise were instrumental in helping us understand and implement the concepts of 5G network slicing effectively. This project was part of our coursework in **5G Communication and Network**, and we are grateful for the opportunity to delve into this cutting-edge field.

---

## Author  
This project was collaboratively developed by:

- **Pradyot Soni**  
- **Ishita Agarwal**  
- **Harsh Sharma**  
- **Harsh Taunk**  
- **Ved Vekhande**

We worked as a team to conceptualize, develop, and present this project, combining our unique skills and perspectives to achieve our objectives.
