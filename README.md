
# AI PDF Parser into a Structured Data

This project is a Jupyter Notebook for parsing text from PDF files using Python. It utilizes the `PyMuPDF` library for extracting text and the `openai` library for any subsequent processing.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## Installation

To use this project, you need to have Python installed on your system. You can install the required libraries using `pip`.

```bash
pip install pymupdf openai python-dotenv
```

## Usage

1. **Clone the repository:**
    ```bash
    git clone <repository-url>
    cd <repository-directory>
    ```

2. **Set up your environment:**
    Create a `.env` file in the root directory of the project and add your OpenAI API key:
    ```
    OPENAI_KEY=your_openai_api_key
    ```

3. **Run the Jupyter Notebook:**
    ```bash
    jupyter notebook pdf_parser.ipynb
    ```

4. **Extract text from a PDF:**
    Follow the instructions in the notebook to load a PDF file and extract text from it.

## Features

- Extract text from PDF files.
- Simple and easy-to-use interface.
- Integration with OpenAI API for additional text processing (e.g., summarization, translation).

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b my-feature-branch`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin my-feature-branch`.
5. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
