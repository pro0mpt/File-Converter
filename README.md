



## Table of Contents
1. [Overview](#overview)
2. [Features](#features)
   - [Document Format Converter](#document-format-converter)
3. [Requirements](#requirements)
4. [Installation and Setup](#installation-and-setup)
5. [How to Use](#how-to-use)
6. [How to Run in VS Code](#how-to-run-in-vs-code)


### Document Format Converter

1. **Launch the Application**:
   Run the Document Format Converter by executing the Python file:
   ```bash
   python document_format_converter.py
   ```

2. **Usage**:
   - **Upload a Document**: Select the document you want to convert by clicking the upload button.
   - **Choose Format**: Use the dropdown menu to select the format you want to convert to.
   - **Download Converted Document**: Once converted, click the "Download" button to save the file.

## How to Run in VS Code

1. **Open Project in VS Code**:
   - Open VS Code, and from the menu, select **File** > **Open Folder**.
   - Navigate to the cloned repository folder and open it.

2. **Set Up the Virtual Environment (Optional)**:
   It's a good practice to use a virtual environment for managing dependencies. In the terminal, run:
   ```bash
   python -m venv venv
   ```
   Then activate the virtual environment:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

3. **Install Dependencies**:
   With the virtual environment active, run:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Python Script**:
   Open the file you want to run (`qr_code_converter.py` or `document_format_converter.py`) and press `F5` to run the Python file in VS Code.
   
   Alternatively, you can run the files from the terminal in VS Code:
   ```bash
   python qr_code_converter.py
   ```
   or
   ```bash
   python document_format_converter.py
   ```
