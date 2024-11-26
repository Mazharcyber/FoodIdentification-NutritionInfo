# FoodIdentification-NutritionInfo
 This project aims at detecting food from images and offering nutritional value data about these foods using a Vision Transformer (ViT) model. Using Python, PyTorch, Hugging Face, and Gradio it demonstrates how deep learning can be used for food classification and nutrition extraction from images.
# Food Identification and Nutrition Information

This project demonstrates food identification using a pre-trained Vision Transformer (ViT) model. The model is capable of classifying images of food items and outputting the name of the predicted food.

## Steps for Running the Project

### 1. **Set Up the Environment**

First, make sure to set up the environment. You can either use **Conda** or **pip** to install the necessary dependencies. 

**Using Conda:**
```bash
conda create -n foodpro python=3.10
conda activate foodpro
conda install pytorch torchvision torchaudio cpuonly -c pytorch
pip install -r requirements.txt
