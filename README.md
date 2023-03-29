# Stable Diffusion FastAPI Project
Welcome to the Stable Diffusion FastAPI Project, a Python-based API that leverages the stable diffusion deep learning model to generate images based on user prompt. This project is designed to work in conjunction with the <a href="https://github.com/ahmedbellaaj10/react-stable-diffusion-app">Stable Diffusion Image Generator React application</a>, allowing users to generate custom images with ease.

### Introduction
The Stable Diffusion FastAPI Project is an open-source project that provides the machine learning capabilities necessary to generate images based on user input. The project is built using Python and leverages the stable diffusion deep learning model to produce unique and visually appealing images. This API project is linked with the Stable Diffusion Image Generator React application, allowing users to generate images with ease.

### Usage
To use the Stable Diffusion FastAPI Project, follow these simple steps:

1. Clone this repository to your local machine.
```cmd
git clone https://github.com/ahmedbellaaj10/stable-diffusion-api.git
```

2. Install the necessary dependencies by running pip install -r requirements.txt.
```cmd
pip install -r requirements.txt
```

3. Register an account on the Hugging Face website and obtain an API token.

4. Set the AUTH_TOKEN environment variable to your Hugging Face API token.
AUTH_TOKEN=<your_hugging_face_api_token>

5. Start the application by running uvicorn main:app --reload.
```cmd
uvicorn main:app --reload
```

6. In your web browser, navigate to http://localhost:8000/docs.

7. Use the Swagger UI to interact with the API and generate images based on user input.

### Integration with Stable Diffusion Image Generator
Note that the Stable Diffusion FastAPI Project is designed to work in conjunction with the Stable Diffusion Image Generator React application. The React application provides an easy-to-use interface for users to generate custom images, while the FastAPI project provides the machine learning capabilities necessary to produce the images. You can find the link to the Stable Diffusion Image Generator React application <a href="https://github.com/ahmedbellaaj10/react-stable-diffusion-app">here</a>

### Conclusion
Thank you for your interest in the Stable Diffusion FastAPI Project. If you have any ideas to improve this work, you can contact me via mail on ```ahmed-bellaaj@outlook.com``` or via [linkedIn](https://www.linkedin.com/in/ahmed-bellaaj/).
Any feedback will be appreciated.