🩺Key Points Chatbot Purpose: A smart health-focused chatbot that responds only to health-related queries. 
Model Used: Built using IBM Granite’s granite-3.3-2b-instruct model via Hugging Face Transformers. 
Interface: Powered by a Gradio UI, making it simple and user-friendly. 
Keyword Filtering: Filters input using a comprehensive list of health, nutrition, and wellness-related keywords to ensure topic relevance. 
Authentication: Requires an API token (HF_TOKEN) from Hugging Face or IBM Cloud to load the model and tokenizer.
Functionality: Checks if the input is health-related. If valid, generates a response using the loaded Granite model.
Setup Instructions: Clone the repository. Install dependencies using: bash Copy Edit pip install transformers accelerate gradio Run the script or notebook.
Deployment: Create a new repository on GitHub. Upload the .py or .ipynb file. Optionally, include a README.md file.
Compatibility: Works with GPU (if available) or CPU fallback. Disclaimer: Intended only for informational purposes—not for medical diagnosis or treatment.
