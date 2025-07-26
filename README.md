# ResNet-101 for Wildlife Classification in Camera Trap Images 🦁📷

## Description  
This project utilizes the **ResNet-101** deep learning model for classifying wildlife species in camera trap images. The dataset consists of **20,978 images**, divided into:

- **13,078** for training  
- **3,466** for validation  
- **4,434** for testing  

The model is trained to classify images into **eight different classes**:
- Antelope Duker  
- Bird  
- Blank  
- Civet Genet  
- Hog  
- Leopard  
- Monkey Prosimian  

After training, the model is capable of predicting which category an image belongs to among these eight classes.

---

## Installation  

### **1. Clone the Repository**  
To download the project, use:  
```sh
git clone https://github.com/YOUR-USERNAME/ResNet101-Wildlife-Classification.git
cd ResNet101-Wildlife-Classification


# Navigate to your project directory
cd path/to/your/project

# Create a README.md file (if not already created)
touch README.md

# Open README.md in a text editor (you can manually paste content here)
nano README.md  # Or use "vim README.md" or open with a code editor like VS Code

# Save and close the file, then add it to Git
git add README.md

# Commit the README file
git commit -m "Added README file with project details"

# Push the changes to GitHub
git push origin main  # Change "main" to "master" if your default branch is named "master"


### **2. Install Dependencies**  
Make sure you have Python installed, then install the required packages: 
```sh
pip install -r requirements.txt

### **3. Run the Model**
You can test the model using the provided notebook and trained model file:
```sh
python test_model.py --image sample_image.jpg


```
## 🤝 Contributors  
- 👩‍💻 [Swathi M K](https://github.com/SwathiMK2004)
  ```
- 👩‍💻 [Piyu](https://github.com/piyu-123-106)
  ```
- 👨‍💻 [Supreet Gouda Hiregoudra](https://github.com/SupreetgoudaHiregoudra)
  ```
