# Scientific Image Analyst with GPT-4 Visionary 🌟

## Overview

The "Scientific Image Analyst" is a Streamlit application powered by OpenAI's GPT-4 Visionary model. It allows users to upload scientific images and receive detailed, scientifically accurate explanations of the images' content. The application can also display additional user-provided details and context if needed.

## Getting Started

To use this application, follow these steps:

1. **Clone the Repository**:
   - Clone this repository to your local machine:
     ```
     git clone <repository-url>
     ```

2. **Create a Virtual Environment**:
   - It's recommended to create a virtual environment to isolate the project's dependencies. You can do this using Python's `venv` module. Navigate to the project directory and run:
     ```
     python -m venv venv
     ```
   - Activate the virtual environment:
     - On Windows:
       ```
       venv\Scripts\activate
       ```
     - On macOS and Linux:
       ```
       source venv/bin/activate
       ```

3. **Install Dependencies**:
   - Install the required Python packages by running:
     ```
     pip install -r requirements.txt
     ```

4. **Obtain OpenAI API Key**:
   - You need to have an OpenAI API key to use this application. You can obtain one by signing up on the [OpenAI website](https://beta.openai.com/signup/).
   - Once you have the API key, enter it in the "Enter your OpenAI API Key" field in the Streamlit sidebar.

5. **Run the Application**:
   - Start the Streamlit application by running the following command in your terminal:
     ```
     streamlit run GPTVision.py
     ```

6. **Usage**:
   - In the Streamlit web interface, you can use the sidebar to upload a scientific image (in JPG, PNG, or JPEG format).
   - You can also choose to add additional details about the image if needed.
   - Click the "Analyze the Scientific Image" button to initiate the image analysis.

7. **Results**:
   - After analysis, the application will display a comprehensive, scientifically accurate explanation of the image's content.
   - If you provided additional context, it will be included in the analysis.

## Example

Here's an example of how to use the application:

1. Enter your OpenAI API key in the sidebar.
2. Upload a scientific image, for instance, an image of a biological specimen.
3. If necessary, add more context or details about the image in the text area.
4. Click the "Analyze the Scientific Image" button.
5. The application will provide you with a detailed analysis of the image's content, highlighting key elements and their significance.

## Dependencies

The application relies on the following Python libraries:

- Streamlit
- OpenAI Python SDK

You can find the complete list of dependencies in the `requirements.txt` file.

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please feel free to open an issue or create a pull request in this repository.

## License

This application is licensed under the MIT License. You can find the full license text in the `LICENSE` file.

## Acknowledgments

- OpenAI for providing the GPT-4 Visionary model and the API key.
- Streamlit for the wonderful framework that makes building interactive web applications with Python a breeze.

## Contact
Enjoy using the Scientific Image Analyst with GPT-4 Visionary! 🚀
