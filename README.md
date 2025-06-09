# GeminiDecode – Multilanguage Document Extraction 🌍
**GeminiDecode** is a Streamlit-based web application powered by Google’s Gemini Pro API. It extracts content from multilingual document images, translates them into English, and provides insightful analysis, all within a user-friendly interface.


## **Table of Contents**
1. [Overview](#overview)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Setup Instructions](#setup-instructions)
5. [How to Use](#how-to-use)
6. [Environment Variables](#environment-variables)
7. [Directory Structure](#directory-structure)
8. [Troubleshooting](#troubleshooting)
9. [Contributing](#contributing)
10. [License](#license)
11. [Author](#author)
12. [Acknowledgments](acknowledgments)


## **Overview**
- GeminiDecode enables users to:       
- Upload scanned or photographed documents in various languages.      
- Extract text using OCR and translate it into English in real-time.            
- Generate insights from the extracted content based on predefined categories (e.g., coding, academic, business).         
- This tool is ideal for multilingual environments where seamless content understanding is vital.          

## **Features**
- 📄 Multilanguage OCR from scanned documents or images.
- 🌐 Real-time translation into English using Gemini Pro.
- 🧠 Insight generation tailored to business, academic, or technical contexts.
- 🗂️ Auto-categorization of documents for quick sorting and retrieval.
- 🧪 Built entirely with Streamlit for interactivity.

  ![Architecture](https://github.com/user-attachments/assets/f50c8932-569f-492d-97dc-2d575ad137cc)
  >Architecture 

## **Technologies Used**
- **Python**: Core backend logic and API integration
- **Streamlit**: Interactive UI framework
- **Google Gemini Pro API**: For text extraction and translation
- **Pillow (PIL)**: Image handling and formatting
- **dotenv**: Environment variable management

https://github.com/user-attachments/assets/05de7d67-b334-4ec1-951b-9ee0dbaab1b5
> Demo Video

## **Setup Instructions**
1. Clone the Repository
```
git clone https://github.com/Im-Mohammed/GeminiDecode.git

cd GeminiDecode
```
2. Create a Virtual Environment

```
python -m venv venv
venv\Scripts\activate       # On Windows
# OR
source venv/bin/activate    # On macOS/Linux
```

3. Install Dependencies
```
pip install -r requirements.txt
```
## **How to Use**
Run the Application     

```
streamlit run app.py
```
Open your browser and visit: http://localhost:8501

## **Environment Variables**
Create a .env file in the project root and add:

```
GOOGLE_API_KEY=your_google_api_key_here

```

## **Directory Structure**
```
GeminiDecode/
│
├── app.py               # Main Streamlit application
├── .env                 # Environment variables file
├── requirements.txt     # Python dependencies
├── README.md            # Documentation
└── assets/              # Images and architecture diagrams

```

## **Troubleshooting**
### Google API Error:        
- Ensure .env is correctly configured with a valid GOOGLE_API_KEY.         
           
### Streamlit Won’t Launch:       
- Double-check that all dependencies are installed using:         

```
pip install -r requirements.txt
```

### OCR/Translation Delays:

- Large image files or complex document layouts can increase processing time.

## Contributing
We welcome contributions!

1. Fork this repository    
2. Create a new branch:         

```
git checkout -b feature/your-feature-name
```
3. Commit your changes:
```
git commit -m "Added feature XYZ"
```
4. Push your branch:

```
git push origin feature/your-feature-name
```
5. Open a Pull Request

## License
This project is licensed under the Apache 2.0 License. See the LICENSE file for details.

## Author
- Developed by Mohammed Abdul Muqtadir
- 📧 abdulmuqtadir1027@gmail.com

## Acknowledgments
- 💡 Google for the Gemini Pro API
- 🛠️ Streamlit for simplifying frontend UI
- 📚 Open-source developers for tools and best practices
- 🎯 Inspiration from real-world document processing needs


