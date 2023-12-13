# Object Detection and Removal Web App

This repository contains the source code for a web application built with Flask and Streamlit. The application allows users to upload images, automatically detects objects using a pre-trained YOLO model, labels the objects with numbers, and provides an option to remove selected objects.

## Features

- **Object Detection:** Utilizes a pre-trained YOLO model to detect and label objects in images.

- **Object Removal:** Allows users to remove selected objects from the labeled image.

- **Interactive Web Interface:** Provides a user-friendly interface for image uploading and object removal.

## Getting Started

### Prerequisites

- Python 3.6 or later
- Required Python packages (install using `pip install -r requirements.txt`)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/object-detection-removal.git
    cd object-detection-removal
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Download the YOLO model files (`yolov3.weights`, `yolov3.cfg`, `coco.names`) and place them in the project directory.

4. Run the Flask application:

    ```bash
    python app.py
    ```

5. In a separate terminal, run the Streamlit app:

    ```bash
    streamlit run streamlit_app.py
    ```

### Usage

1. Access the application by opening the provided Streamlit URL.

2. Upload an image using the provided form.

3. The application will automatically detect objects in the image, label them with numbers, and display the labeled image.

4. Optionally, enter the numbers of objects you want to remove and click the "Remove Selected Objects" button.

5. The application will display a success message if objects are removed. Choose to upload another image or continue with the current image.

## Documentation

For more details about the application, including challenges faced during development and code explanations, refer to the [documentation](documentation.md).

## Deployment

The application can be deployed to platforms such as [Streamlit Sharing](https://www.streamlit.io/sharing) or [Heroku](https://www.heroku.com/). Follow the platform-specific instructions for deployment.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
