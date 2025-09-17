SMART SDLC
:

🌱 Eco Assistant & Policy Analyzer

An AI-powered Gradio app that helps users generate eco-friendly living tips and summarize policy documents. Built with IBM Granite 3.2 2B Instruct
, PyTorch, and Transformers.

🚀 Features

Eco Tips Generator:
Enter environmental keywords (e.g., plastic waste, solar energy, water saving) to receive practical sustainability tips.

Policy Summarization:
Upload a policy PDF or paste raw text, and the app will generate a clear summary with key points and implications.

AI-Powered:
Uses IBM Granite 3.2 instruct-tuned language model.

🛠️ Installation

Clone the repo and install dependencies:

git clone https://github.com/your-username/eco-assistant.git
cd eco-assistant
pip install -r requirements.txt


requirements.txt should contain:

transformers
torch
gradio
PyPDF2

▶️ Usage

Run the app with:

python app.py


or inside Jupyter Notebook:

!pip install -q transformers torch gradio PyPDF2
!python app.py


Once launched, Gradio will show a local link and an optional shareable public link.

📂 Project Structure
eco-assistant/
│── app.py              # Main Gradio app
│── requirements.txt     # Dependencies
│── README.md            # Project documentation

🌍 Example Use Cases

Eco Tips Generator
Input: plastic waste, ocean pollution
Output: Sustainable living tips such as reusable bags, recycling hacks, eco-friendly alternatives.

Policy Summarization
Input: Upload a climate policy PDF
Output: Clear summary highlighting provisions, stakeholders, and key implications.

📌 Notes

Works with both CPU and GPU. GPU recommended for faster responses.

For PDF uploads in Gradio, the app extracts text using PyPDF2.

📜 License

MIT License – feel free to use and modify!
