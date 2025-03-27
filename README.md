# Personalized-Medical-Recommendation-System-with-Machine-Learning

Welcome to our cutting-edge **Personalized Medical Recommendation System**, a powerful platform designed to assist users in understanding and managing their health. Leveraging the capabilities of machine learning, our system analyzes user-input symptoms to predict potential diseases accurately. Here's what sets our system apart:

## Features

- **User-Friendly Interface:** Our intuitive interface allows users to input their symptoms effortlessly, creating a seamless user experience.
- **Advanced Machine Learning Models:** We've integrated state-of-the-art machine learning models that accurately predict diseases based on input symptoms, ensuring reliable and precise results.
- **Tailored Recommendations:** Receive personalized recommendations for the top 5 medicines, prescription details, and even workout routines based on the predicted disease.
- **Flask App Integration:** The entire system is powered by a Flask web application, making it easily accessible to users. Experience the convenience of accessing healthcare recommendations from anywhere.
- **Privacy and Security:** We prioritize user privacy and data security. Your health information is handled with the utmost confidentiality, adhering to the highest industry standards.
- **Continuous Improvement:** Our system is designed for continuous improvement. As we gather more data, the machine learning models evolve, providing increasingly accurate and relevant recommendations.

Take charge of your health with our **Personalized Medical Recommendation System**. Your well-being is our priority, and we're dedicated to providing you with the tools and insights you need for a healthier, happier life.

---

## Installation Guide

Follow these steps to set up and run the project:

### 1. Clone the Repository
```bash
git clone https://github.com/your-repository-url.git
cd your-repository-folder
```

### 2. Create a Virtual Environment
Ensure you create the virtual environment in the same hierarchy as `requirements.txt`.

```bash
python -m venv venv  # Create virtual environment
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate  # On Windows
```

### 3. Install Dependencies
First, try installing all dependencies at once:
```bash
pip install -r requirements.txt
```
If this does not work, install the dependencies manually:
```bash
pip install flask
pip install numpy
pip install pandas
pip install scikit-learn==1.3.2  # Required version for model compatibility
```
_**Note:** The model is trained on scikit-learn 1.3.2, so please use this version only._

### 4. Run the Application
```bash
python src/main.py
```

### 5. Deactivate Virtual Environment (Optional)
When you're done using the project:
```bash
deactivate
```

---

## Project Structure
```
project-folder/
│── src/
│   ├── main.py
│   ├── templates/
│   ├── models/
│   ├── datasets/
│── requirements.txt
│── README.md
│── venv/
```

Now, you're ready to use the **Personalized Medical Recommendation System**! 🚀

