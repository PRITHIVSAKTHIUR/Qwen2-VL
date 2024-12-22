---
title: QWEN2 VL
emoji: 🍍
colorFrom: blue
colorTo: yellow
sdk: gradio
sdk_version: 5.9.1
app_file: app.py
pinned: true
license: creativeml-openrail-m
short_description: Qwen VL 2B
---

Check out the configuration reference at https://huggingface.co/docs/hub/spaces-config-reference

# Qwen2-VL: Vision and Language Processing

Welcome to the **Qwen2-VL** repository, a powerful tool for vision and language processing tasks. This project leverages advanced models to analyze images and generate descriptive text, offering a seamless integration of computer vision and natural language processing.

## Overview

Qwen2-VL provides a user-friendly interface for processing images and generating text outputs. The application supports multiple models, each tailored for specific tasks such as OCR, math parsing, and text analogy. The generated outputs can be formatted and exported into various document formats, including PDF and DOCX.

## Features

- **Model Selection**: Choose from a variety of models optimized for different tasks, including OCR, math parsing, and text analogy.
- **Image Input**: Upload images for analysis and generate descriptive text.
- **Text Input**: Ask questions or provide instructions related to the image.
- **Output Formatting**: Customize the output text, including font choice, size, line spacing, and alignment.
- **Document Generation**: Export the processed image and text into PDF or DOCX formats.
- **Streamlined Interface**: A clean and intuitive Gradio interface for easy interaction.

## Installation

To run the Qwen2-VL application locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/PRITHIVSAKTHIUR/Qwen2-VL.git
   cd Qwen2-VL
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application**:
   ```bash
   python app.py
   ```

4. **Access the Interface**:
   Open your web browser and navigate to `http://127.0.0.1:7860` to access the Gradio interface.

## Usage

1. **Upload an Image**: Use the file uploader to select an image for analysis.
2. **Select a Model**: Choose the appropriate model from the dropdown menu based on your task.
3. **Ask a Question**: Enter a question or instruction related to the image in the textbox.
4. **Submit**: Click the "Submit" button to generate the output text.
5. **Customize Output**: Adjust the font, size, line spacing, and alignment of the output text.
6. **Generate Document**: Click the "Get Document" button to export the image and text into a PDF or DOCX file.

## Examples

The application includes several examples to help you get started. Click on any example to load the image and pre-fill the question and model selection.

## Models

The following models are available for use:

- **Qwen2VL Base**: General-purpose vision and language model.
- **Latex OCR**: Optimized for OCR tasks involving LaTeX content.
- **Math Prase**: Specialized for parsing and solving mathematical problems.
- **Text Analogy Ocrtest**: Designed for text analogy tasks with OCR.

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- **Hugging Face**: For providing the model collections and libraries.
- **Gradio**: For the easy-to-use interface framework.

## Contact

For any questions or feedback, please contact [Prithiv Sakthi](mailto:prithivsakthi@example.com).

## Links

- **GitHub Repository**: [Qwen2-VL](https://github.com/PRITHIVSAKTHIUR/Qwen2-VL)
- **Hugging Face Collection**: [Vision-Language Models](https://huggingface.co/collections/prithivMLmods/vision-language-models-67639f790e806e1f9799979f)

---
