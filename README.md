# Vegetable Disease Classification

This project focuses on building a machine learning model to detect vegetable diseases using image classification techniques. The frontend is designed  to provide an interactive user interface for predictions and visualizations.

## Features
- **Deep Learning Model**: Built with TensorFlow for image classification.
- **Interactive Frontend**: Developed for an intuitive user experience.
- **Disease Detection**: Identifies common potato diseases based on image inputs.
- **Customizable Parameters**: Supports adjustments for batch size, image dimensions, and epochs.

## Project Structure
- **Backend**: Jupyter Notebook containing model training and evaluation.
- **Frontend**: Frontend for user interaction and visualization.
- **Data**: Image dataset of vegetable leaves labeled with corresponding disease categories.

## Technologies Used
### Backend
- TensorFlow: For building and training the image classification model.
- Matplotlib: For data visualization.
- tqdm: For progress tracking.

### Frontend
- HTML , CSS/Tailwind & JavaScript : For creating the user interface.

## Installation
### Backend Setup
1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```bash
   cd potato-disease
   ```
3. Install required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```
   Ensure TensorFlow is installed.

4. Run the Jupyter Notebook to train the model or use the pre-trained model provided.

### Frontend Setup
1. Navigate to the `frontend` directory:
   ```bash
   cd frontend
   ```
2. Install Node.js dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm start
   ```

## Usage
1. Train the model using the provided Jupyter Notebook or load the pre-trained model.
2. Launch the React frontend to upload images and view predictions.
3. Explore visualization features for better insights into disease classification.

## Dataset
The dataset contains images of potato leaves, categorized into healthy and diseased classes. Ensure the dataset is placed in the `data` directory for training and evaluation.

## Results
The model achieves high accuracy in identifying potato diseases. Visualizations of the results can be viewed in the notebook.

## Contributing
Contributions are welcome! Feel free to fork the repository and submit pull requests.

## License
This project is licensed under the MIT License.

## Acknowledgments
- TensorFlow documentation
- React.js community for their resources

---
Feel free to explore the project and provide feedback!
