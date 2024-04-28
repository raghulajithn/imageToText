# Image Description using Gemini

This is a Streamlit web application that utilizes the Gemini model from Google's GenerativeAI to generate responses based on an input prompt and an uploaded image.

## Description

The application allows users to input a prompt and upload an image. The Gemini model then generates a response based on both the input prompt and the content of the uploaded image. This allows for interactive exploration and generation of content related to the provided image.

## Usage

1. Run the Streamlit app:

    ```
    streamlit run image.py
    ```

2. Input a prompt in the "Input Prompt" text input field.

3. Upload an image by clicking the "Choose an image..." button and selecting an image file (supported formats: jpg, jpeg, png).

4. Click the "Tell me about the image" button to generate a response based on the input prompt and the uploaded image.

5. The generated response will be displayed below the image.

## Installation

1. Clone this repository:

    ```
    git clone https://github.com/raghulajithn/imageToText.git
    ```

2. Navigate to the project directory:

    ```
    cd imageToText
    ```

3. Install the required dependencies:

    ```
    pip install -r requirements.txt
    ```

4. Set up your Google API key by creating a `.env` file and adding your API key:

    ```
    GOOGLE_API_KEY=your_api_key_here
    ```

## Example

![example](https://github.com/raghulajithn/imageToText/assets/96931716/6a2d5f01-5088-4364-8f61-eab605ccd1f5)
![response](https://github.com/raghulajithn/imageToText/assets/96931716/c0307f46-e161-4837-9d45-52b0c06095d2)



## Credits

- This application utilizes the Gemini model from Google's GenerativeAI.
- It also uses the Streamlit library for building interactive web apps.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
