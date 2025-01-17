
## 🍽 **Image Classification with GoogLeNet**

This project focuses on **image recognition** using a deep learning approach with the **GoogLeNet** architecture. The task involves classifying food images from a reduced version of the popular **[Food-101](https://data.vision.ee.ethz.ch/cvl/datasets_extra/food-101/)** dataset.

---

### 📂 **Dataset Overview**  
- **Source:** A reduced version of the **Food-101** dataset.  
- **Classes:** 12 distinct food categories, carefully selected to represent a variety of food types, with 200 items each class.  
- **Objective:** Accurately classify images into one of these 12 food categories using the **GoogLeNet** model.  

---

### 🧠 **Model Architecture**  
- **GoogLeNet (Inception v1):**  
  GoogLeNet is a deep convolutional neural network (CNN) that introduces **Inception modules** to optimize performance and computational efficiency.  
  - It enables **multi-scale feature extraction** through parallel convolution operations.  
  - Its compact architecture allows effective image classification with reduced computational cost.  

This makes GoogLeNet an excellent choice for the **multi-class classification** problem posed by the Food-101 dataset.

---

### 🛠 **Tools and Libraries**  
- **Deep Learning Frameworks**: Pytorch 
- **Data Handling**: Pandas, NumPy  
- **Visualization**: Matplotlib, Seaborn  
- **Dataset Management**: Scikit-learn for preprocessing, splitting and evaluating  

---

### 🔍 **Methodology**  
1. **Data Preparation**:  
   - Load the reduced Food-101 dataset with 12 classes.  
   - Perform image preprocessing (e.g., resizing, normalization, augmentation).  
2. **Model Training**:  
   - Implement the GoogLeNet architecture for image classification.  
   - Fine-tune hyperparameters to optimize model performance.  
3. **Evaluation**:  
   - Measure accuracy, precision, and recall on the validation and test sets.  
   - Analyze model performance across the 12 food classes.  

---

### 📚 **How to Run the Project**  
1. Clone the repository:  
   ```bash
   git clone <repository-url>
   cd <project-directory>
   ```  
3. Run the script:  
   ```bash
   Food12.ipynb
   ```  

---

### 🤝 **Collaborators**  
The project was developed as a team effort for the final assessment of the Deep Learning course. I would like to thank my teammates for their contribution and dedication. Below are the team members with links to their respective GitHub profiles:   
- [Tommaso Biganzoli](https://github.com/biguz-commits)
- [Matteo Delle Cave](https://github.com/matdcp)
- [Michele Giambelli](https://github.com/MicheleGiambelli)

Thank you all for the excellent teamwork! 🚀  

---

### 🔗 **References**  
- Food-101 Dataset: [https://data.vision.ee.ethz.ch/cvl/datasets_extra/food-101/](https://data.vision.ee.ethz.ch/cvl/datasets_extra/food-101/)  
- GoogLeNet Paper: *"Going Deeper with Convolutions"* by Szegedy et al.


