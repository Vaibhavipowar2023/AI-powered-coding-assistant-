# AI Code Assistant 

## 📌 Overview
This AI-powered coding assistant leverages the **Gemini API** to help with various programming tasks. It can:
- Detect the programming language of a given code snippet.
- Generate code based on natural language prompts.
- Review code for best practices and efficiency improvements.
- Fix errors in code and provide debugging hints.

## 🚀 Features
✅ **Language Detection** – Identifies the programming language of any given code snippet.  
✅ **Code Generation** – Generates code based on user prompts.  
✅ **Code Review** – Analyzes code for best practices and optimization.  
✅ **Bug Detection & Fixing** – Identifies and corrects errors in the provided code.  

## 🛠️ Setup Instructions
1. Clone the repository or download the script.
2. Install the required dependencies:
   ```bash
   pip install google-generativeai
   ```
3. Set up the **Gemini API key** in your script:
   ```python
   import google.generativeai as genai
   genai.configure(api_key="YOUR_API_KEY")
   ```
4. Run the script in **Google Colab** or a Python environment.

## 📝 Usage
1. Run the script and enter your request when prompted.
2. Choose an option:
   - Enter a prompt to generate code.
   - Paste your code to review or fix it.
3. The AI will process your request and return results instantly!

## 🔗 Supported Languages
This assistant supports multiple programming languages, including:
- Python, JavaScript, Java, C++, C, C#, Go, Rust, Swift, Kotlin
- TypeScript, PHP, Ruby, R, Dart, Perl, Scala, Objective-C, SQL, Shell, Bash

## 📌 Example Usage
- **Generate Code:**
  ```plaintext
  Enter your request: Generate a Python function to check prime numbers.
  ```
- **Fix Code Errors:**
  ```plaintext
  Enter your request: Fix this code:
  (Paste buggy code here)
  ```
- **Review Code:**
  ```plaintext
  Enter your request: Review this Python script for best practices.
  ```


## 🤝 Contributing
Feel free to open issues or submit pull requests to enhance the functionality of this assistant.


