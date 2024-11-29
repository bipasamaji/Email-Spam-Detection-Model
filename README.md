# Email-Spam-Detection-Model
📋 **Overview**

This project is a **Machine Learning** model designed to detect whether an email is **Spam** or **Ham**. It provides two main functionalities:

**Manual Email Input**:

A GUI-based message box where users can paste or type an email, and the model predicts if the email is spam or ham.

**API Integration (Commented Out)**:

An **API** call to fetch emails directly from a mail service (e.g., Gmail).
This feature is commented out, and users need to configure it with their **own API credentials** for fetching email data.

🚀 **Features**

**Manual Email Classification**

Simple GUI where users can input an email manually.
The model returns the classification result (Spam or Ham).

**API-Based Email Classification (Commented Out)**

Allows fetching emails via an API (e.g., Gmail API).
This feature is optional and requires user configuration.

🛠️ **Tech Stack**

**Programming Language**: Python

**Libraries**:

**tkinter** (for GUI)

**pandas**, **numpy** (Data manipulation)

**scikit-learn** (Machine Learning)

**nltk** (Natural Language Processing)

**google-auth**, **google-api-python-client** (for Gmail API integration)

📈 **Model Workflow**

**Manual Email Input**:

User inputs an email through a GUI.
The model preprocesses and classifies the email.
Displays the result as Spam or Ham.

**API-Based Classification (Optional)**:

Fetches emails from the **user's inbox**.
Preprocesses the email content.
Classifies each email as Spam or Ham.

