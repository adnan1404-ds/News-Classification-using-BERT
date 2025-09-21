# News Topic Classifier using BERT
This project demonstrates how to build and deploy a news topic classifier by fine-tuning a pre-trained **BERT (Bidirectional Encoder Representations from Transformers)** model. The model is trained to classify news headlines into one of four categories: World, Sports, Business, and Sci/Tech.

## 🚀 Key Features
**Model Fine-tuning:** Fine-tunes the bert-base-uncased model on the AG News Dataset from the Hugging Face datasets library.

**Evaluation:** Evaluates the model's performance using standard metrics like accuracy and F1-score.

**Interactive UI:** Deploys the trained model with a user-friendly interface built using Gradio, allowing for real-time topic prediction.

**Reproducible Code:** Provides a clear, step-by-step guide to replicate the entire project pipeline.

## 🛠️ Requirements
To run this project, you need to install the following libraries:

Bash

pip install transformers datasets accelerate evaluate scikit-learn gradio
## 📂 Project Structure
The main script (news_classifier.py or a Jupyter Notebook) will follow these steps:

**Data Preparation:** Load and tokenize the AG News dataset using the BertTokenizer.

**Model Training:** Use the Trainer API from Hugging Face to fine-tune the AutoModelForSequenceClassification model.

**Evaluation:** Define a compute_metrics function to evaluate the model on the test set.

**Deployment:** Create a Gradio interface to host the model for live predictions.

## 🖥️ How to Run
Clone this repository (if applicable) or copy the code into a new Python file or a Colab notebook.

Install the dependencies listed in the Requirements section.

Run the script or notebook. The script will automatically download the dataset, fine-tune the model, and launch the Gradio UI.

Once the Gradio app is running, you will get a public URL (in Colab) or a local URL in your terminal. Open this URL in your browser to interact with the classifier.

## 📄 License
This project is open-source and available under the MIT License.
