# Paraphrasing Automation Project

## Overview
### This project is intentionally wrote in a single file (HTML + CSS + JS)
This project aims to eliminate the repetitive task of splitting text into smaller parts for paraphrasing, This action ta. It automates the process using JavaScript, primarily relying on regular expressions for text manipulation and an API call to **Deepseek**. The API prompt is customizable directly in the code.

The project follows a **one-page, vertical development** structure, keeping everything streamlined and efficient.

## Features
- 🚀 **Automated text splitting** using powerful regex patterns
- 🔧 **Customizable API prompt** for tailored paraphrasing
- 🔗 **Deepseek API integration** to handle paraphrased output
- 🎯 **One-page vertical structure** — simple setup, clean workflow

## Technologies Used
- JavaScript (Vanilla)
- Regex for text processing
- Deepseek API
- HTML/CSS (optional for UI)

## Setup and Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/ahmeee-dev/paraphAI.git
   cd paraphrasing-automation
   ```

2. Install dependencies (if needed):
   ```bash
   npm install
   ```

3. Configure your Deepseek API key:
   - Open the script file and find the `API_KEY` variable.
   - Replace it with your personal API key from Deepseek.

4. Customize the prompt inside the script for tailored paraphrasing results.

5. Open `index.html` in your browser and start automating!

## Usage
1. Paste the text you want to paraphrase.
2. The script will split the text into manageable chunks.
3. The processed text is sent to Deepseek for paraphrasing.
4. The paraphrased output is displayed directly on the page.

## Example Prompt Configuration
Inside the script:
```javascript
const prompt = "Paraphrase this text clearly and concisely eliminating any plagiarism: ";
```
Modify the prompt string to guide the API's behavior for more creative or professional outputs.

## Future Improvements
- **Enhanced UI** for better user experience
- **Support for multiple languages**

## License
This project is licensed under the MIT License.

## Contributions
Feel free to fork, improve, or report issues. Pull requests are welcome!

---
Happy automating! 🚀

