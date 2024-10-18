# AI-code-translator
# Language Converter AI

## Overview

Welcome to the Language Converter AI project! This tool leverages the power of AI, specifically the OpenAI API, to convert code from one programming language to another. Whether you're a developer looking to migrate codebases or just curious about how different languages express the same logic, this project aims to make code translation easier and more efficient.

## Features

- **Multi-Language Support**: Convert code between various programming languages such as Python, Java, JavaScript, C++, Ruby, and more.
- **AI-Powered**: Utilizes OpenAI's advanced models for accurate and context-aware translations.
- **User-Friendly Interface**: Simple command-line interface for quick and easy conversions.
- **Customizable Settings**: Configure translation parameters to suit your needs.

## Getting Started

### Prerequisites

- Python 3.7 or later
- OpenAI API key (sign up at [OpenAI](https://openai.com))

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/language-converter-ai.git
   cd language-converter-ai
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set your OpenAI API key in an environment variable:
   ```bash
   export OPENAI_API_KEY='your_api_key_here'
   ```

### Usage

To convert code, run the following command:

```bash
python converter.py --source-lang <source_language> --target-lang <target_language> --code "<your_code_here>"
```

Replace `<source_language>` and `<target_language>` with the desired programming languages, and `<your_code_here>` with the code you want to convert.

### Example

```bash
python converter.py --source-lang python --target-lang javascript --code "print('Hello, World!')"
```

This command converts a simple Python print statement to JavaScript.

## Contributing

We welcome contributions to enhance the functionality and accuracy of this project. Please fork the repository and submit a pull request with your improvements. 

### Steps to Contribute

1. Fork the repository.
2. Create your feature branch:
   ```bash
   git checkout -b feature/YourFeature
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add some feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/YourFeature
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [OpenAI](https://openai.com) for providing the API that powers this project.
- The open-source community for their invaluable contributions and inspiration.

## Contact

For questions or feedback, please open an issue on GitHub or reach out via **rahul9271@outlook.com** .

---

Happy coding!
