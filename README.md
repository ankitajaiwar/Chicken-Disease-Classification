# Chicken-Disease-Classification
Classify the chicken's images into 'Have the Coccidiosis Disease' and 'Doesn't have the Coccidiosis Disease' using Deep Learning


# Chicken Disease Classification

This project aims to automate the identification of diseases in chickens using Convolutional Neural Networks (CNNs). By leveraging deep learning techniques, it seeks to enhance disease detection in poultry populations.

Follow these steps to run the code:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/chicken-disease-classification.git

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt

3. **Run the app**
   ```
   python app.py

## Project Structure

### Data Preparation
- **Folder**: `artifacts/data_ingestion`
- **Purpose**: Contains scripts for data preprocessing tasks such as loading, cleaning, and augmenting the dataset.

### Model Development
- **Folder**: `src/cnnClassifier`
- **Purpose**: Implements CNN architectures for chicken disease classification using TensorFlow/Keras.

### Evaluation
- **Folder**: `research`
- **Purpose**: Includes modules or scripts for evaluating the trained model's performance.

### Deployment
- **Files**: `Dockerfile`, `app.py`
- **Purpose**: Utilizes Docker for containerizing the trained model and Flask for serving it as a web application.

### Configuration
- **Folder**: `config`
- **Purpose**: Contains configurations and settings for various project components.

### Version Control
- **Files**: `.gitignore`, `README.md`
- **Purpose**: `.gitignore` specifies files ignored by version control, `README.md` provides project documentation.

### Dependency Management
- **Files**: `requirements.txt`, `setup.py`
- **Purpose**: Lists project dependencies and manages package distribution.

### Continuous Integration/Continuous Deployment (CI/CD)
- **Folder**: `.github/workflows`
- **Purpose**: Contains CI/CD workflows for automating testing, building Docker images, and deploying the application.

### Data Versioning
- **File**: `dvc.yaml`
- **Purpose**: Used with Data Version Control (DVC) for versioning and managing datasets.

### Templates
- **Folder**: `templates`
- **Purpose**: Contains HTML templates for rendering web pages if the application includes a web interface.

## Technologies Used
- Python
- TensorFlow/Keras
- Docker
- Flask
- Git
- GitHub Actions
- Data Version Control (DVC)

## Contributors
- Ankita Jaiwar (@ankitajaiwar)


